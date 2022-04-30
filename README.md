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


## History Inspiration
the iopp is highly inspired by Human Interaction and is designed in a 1:1 Relation ship to that. It is for example not natural for all Humans to be awake
all at the same time. This will save Energie Costs and Eleminate the Cloud Market and raise the empowerment of data sovereignty.

The conclusion is simple and even military knows that for example there are one way network cards on the market to protect data silos from getting hacked via simply physical blocking outgoing traffic. This Tech needs to be useable for Private Persons also iopp enables that by default. It is not possible that you leak data that is simply not reachable.

but we want to be able to reach data from the usa even in east asia how can we do that? Via Topics as soon as we defined a network of topics we can keep the package reproduction multiplexing on topic level iopp introduces topics as term for filtered iopp multicast groups. In general iopp starts with broadcasting or multicasting depending on if it is a private or a public connection. Public connections simply broadcast via 802.1 and get multiplexed
while private connections contain a list of multicast topics that they can use to get a path. a topic is like a iopp://address in web2.0 or in web3.0 speach it is like a content address / token / coin / nfc no matter how you call that hash :). But Topic sounds more familar for most humans as they are interrested in topics in general may it be video content or anything else even chatting with a women is a own topic :)

Sorry for the smilys will remove that funny stuff later but it keeps me working and they see me rolin the hating .....
