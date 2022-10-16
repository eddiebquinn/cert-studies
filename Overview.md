Tags: #network-plus 

---
OSI stands for `Open Systems Interconnction`, and was developed in 1977 by the ISO. Its ISO number is 7498. This is mainly referred to as the OSI model, but can also be called the OSI stack. It is a major part in modern networking.

The exact purpose of the OSI model from a meta perspective is to serve as a standard set of protocols manufacturers can follow to ensure that networking remains consistent. This allows inter-operability between vendors. It does also offer another benefit from a troubleshooting perspective, when you understand the 7 layers you are able to narrow down the scope of a problem when it occurs, allowing you to better identify the root cause. 

## Layers of OSI
It is made up of 7 different layers of communication

| Layer name | Data-Type |
|------------|-----------|
|[[Layer 1 - Physical]]| [[Bits]] |
|[[Layer 2 - Data-Link]]| Frame |
|[[Layer 3 - Network]]| Packet |
|[[Layer 4 - Transport]]| Segment |
|[[Layer 5 - Session]]|Data|
|[[Layer 6 - Presentation]]| Data|
|[[Layer 7 - Application]]| Data |

## Relationship to [[TCP/IP]]
One of the big drawbacks of the OSI model is that in the modern day it is used more as a reference guide, as opposed to law. Many things we encounter d not fit neatly into a single layer. The reason for this is that most modern networks actually follow the [[TCP/IP|TCP/IP Model]], however it is important to understand the following

> The OSI model was meant to refer to how **ALL** networks should operate, rather than just TCP/IP networks

