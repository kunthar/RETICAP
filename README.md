## RETICAP

### DESCRIPTION
In neuroscience research, observing and recording peripheral nerve action potentials has important applications. RETICAP stands for "Real-time Compound Action Potential" (recorder), which has been/is being developed for externally triggered and online-averaged recording of Compound Action Potentials (CAPs). It makes use of an RTAI (http://www.rtai.org/) module depending on DAQ hardware drivers from COMEDI project (http://www.comedi.org/) -a driver customly written only for some Advantech DAQ cards is included-, which provides microsecond-level jitter-. The associated backend daemon and the GUI front-end written in Qt, communicate with the backend for timely acquisition of data sync'd with the triggering of an external stimulator, and other non-realtime features such as averaging and disk-recording, besides the fancy visualization. Depending on a hard real-time loop rather than DMA makes it possible in RETICAP context, to design complex feed-back protocols possibly modified by the features of actual signal being acquired.


### INSTALLATION

### CITATION 


