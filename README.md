# dmp
A decentralized mega platform, it's called a mega platform, because it does everything.



## need to do
### Design flow chart
### Figure out what is needed for rest of system
### Write software
### write more software
### more software


## The basics

Data is required to flow between one client, and another client. So what do you do? You add nodes. One node will talk to another node via the client computer, and the one node could talk to clients, just using basic tcp/ip stacks. Multiple nodes, and their clients using the process of going from node1-client-node2 allowing all of the nodes to communicate. There will eventually be node-node communication, but that will notg be coming for a long time, im guessing. After two nodes peer, the clients from each node will be able to communicate with the other nodes clients.

## Example of peering with multiple nodes.
### This only applies if you are peering with a client from another node, if thats not what you're interested in, look elsewhere.
Client1 is asking node1 to ask member of its node if it has file named sword.stl, that node asks all of its members, (clients of its node) if its clients don't have the file, the node tells the client to try and ask another node (node2) if it has the file, the client will then try that node, finds a client that does have the file, we will call that client client2. Client 2 uploads to its node (node2) and allows client1 to download from node2 directly.


