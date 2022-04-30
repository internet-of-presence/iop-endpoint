# iop-endpoint
The Final usage of this is simple we create entrypoints (edges) programatical and translate the traffic 

This Repo bundels translation logic for standard protocols like HTTP all versions TCP and turns it into a valid IoP Multicast aka iopp internet of presence protocol iopp://

It is also the first world wide known Implementation of Web 4.0 exposing the iopp v1 the first iopp implementation is a WebRTC like implementation using a ieee802 standard like signaling protocol. The clients are signaling to each other that they are offering services and consumers can filter all services that are in reach or they can even shrink that more down via endpoints that share already filtered services.

so to keep it relative simple iopp is a layer2 protocol while it can be implemented in hardware layer 1 but it is not done at present
it combines all 3 major interface types broadcast, multicast, point to point it can also be implemented via tcp/ip while 802.11 or 802.1 or 2 are prefered 

List: https://www.ieee802.org/

see: 
- https://en.wikipedia.org/wiki/Multicast - High Level Concept Overview similar to IoPP v1
- https://en.wikipedia.org/wiki/Multiple_Registration_Protocol - Details about Group Algos similar to IoPP v1
  - https://www.ieee802.org/1/pages/802.1ak.html
 
