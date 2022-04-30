# iop-endpoint
The Final usage of this is simple we create entrypoints (edges) programatical and translate the traffic 

This Repo bundels translation logic for standard protocols like HTTP all versions TCP and turns it into a valid IoP Multicast aka iopp internet of presence protocol iopp://

It is also the first world wide known Implementation of Web 4.0 exposing the iopp v1 the first iopp implementation is a WebRTC like implementation using a ieee802 standard like signaling protocol. The clients are signaling to each other that they are offering services and consumers can filter all services that are in reach or they can even shrink that more down via endpoints that share already filtered services. iopp is a http/3 quic and webrtc compatible protocol as long as your client is able to recive iopp http3 or quic you can connect it via any IEEE 802.2+ standard 

so to keep it relative simple iopp is a layer2 protocol while it can be implemented in hardware layer 1 but it is not done at present
it combines all 3 major interface types broadcast, multicast, point to point it can also be implemented via tcp/ip while 802.11 or 802.1 or 2 are prefered 

List: https://www.ieee802.org/

see: 
- https://en.wikipedia.org/wiki/Multicast - High Level Concept Overview similar to IoPP v1
- https://en.wikipedia.org/wiki/Multiple_Registration_Protocol - Details about Group Algos similar to IoPP v1
  - https://www.ieee802.org/1/pages/802.1ak.html
 
 ## Why?
 This Protocol is mainly designed to offer a decentralised free internet that is able to get build with cheep electrical components that can even be found 
 after a lets say world wide fallout scenario. It is also designed to be only physical censor able so communication can only be blocked via physical attacking all systems else the network is able to heal and work as it is supposed to be. It is also designed to Eleminate the need for a Permernent Internet Provider thats why it is 802.1 only if you where courios as this reads a bit like it would be simple a other Implementation of Secure UDP but that is only for compatability reasons. The Full Potential of iopp will be released with v2 when it is ready to get used with none IEEE Standard hardware! 
