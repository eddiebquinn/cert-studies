Tags: #network-plus 

---
The first layer of the [[Overview|OSI model]] is the physical layer. This is where bits are physically transported across the network, and includes the physical and network characteristics of the network. This is going to tell us if were using an [[Ethernet]] network, what type of cable were using, if were using RF, etc. Regardless of the specific [[Network topology|topology]] we're using, at this layer data is always transferred in [[Bits]] (for more information on how these bits are represented on different network topologies, see the page).

## Connectors
The way the wires connect into different sockets under different [[Network topology|topologies]] is another thing that falls under Layer 1. The relevant pages are linked below

- [[RJ45 connector|Copper wire]]

## Physical topology
In the [[Network topology]] section, the distinction was made between a 'logical topology' and a 'physical' topology. The physical layer of the topology falls into the scope of this layer. We need to ask how are actually running the cables: is it s [[Bus Topology|bus]], [[Ring Topology|ring]], [[Hub-and-spoke Topology|hub-and-spoke]]?

##  Synchronizing communication
Another issue we need to consider at layer one of how are communications being synchronized across the devices - how does the receiving node know if it's read to accept the bits being sent. There are two things that can happen, the data is either transferred

### Asynchronous communication
The best real world example of this would be you call a friend, and he doesn't answer; you therefore leave a message. The communication happens out of sync - You do it, and he listens later.

The manifests in network communication in a similarity way. The sending node will send a `start bit` and a `stop bit` to indicate when transmissions occur between the sender and receiver

### Synchronous communication
A real world example of this would be if you called your friend, and he picked up the phone, and you have a back and forth conversation. This is synchronous. When you talk about this from a network perspective, in order to sync up communications you would need to use a common time source i.e. a real time clock. Then you would be able to send receive every second, on the cadence of the beat. 

## Bandwidth