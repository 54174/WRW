# WRW
WebRTCWeb - A serverless network with native WebRTC support in browser

You can add new nodes to WRW by transmitting message from A to B and then from B to A. This is a point for development, as the message from B to A before the actual connection, should not be necessary and would allow easier addition of new nodes.

Currently a STUN server is required, however, various public STUN servers exist so it is not a big issue.

Vision:

A massive network exists and a new node wants to join in. New node finds the required information for connection making from some website/forum/tweet/post this "message" can be ran in browser console to open a necessary connection using mainly WebRTC.

Once a new node is part of the network, it will be provided with content to store, information about other nodes and content in the network and it creates additional connections to avoid single point of failure in the connections.

