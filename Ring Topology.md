Tags: #network-plus 

---
A ring topology runs similarly to a [[Bus Topology]] in that it uses a single cable, but it runs in a big circle. Each device in the ring can then talk on that cable in a single direction. 

This topology still experienced being a single collision domain, however it was addressed using something called a token ring. This was essentially a token that was passed from device to device, and essentially gave the different devices' permission to talk.

## FIDDI ring
These rings were similar to the Bus topology in that there was no redundancy - if the wire was damaged in any way, this would take down the whole network. These are something called an FDDI ring, which is two rings where one line of data runs clock wise while the other runs counterclockwise. This adds in redundancy that does not exist in a traditional ring topology.

***EXAM TIP*** ([[Network+]]): In the exam whenever you see ring, think FDDI ring, because that is the only type of ring topology that is in use in the modern day. Given this and what a FIDDI ring does remember *ring = redundancy*