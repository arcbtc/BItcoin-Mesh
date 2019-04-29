![bitcoin mesh network](https://i.imgur.com/p1BPto4.png)
# BItcoin Mesh Network
A cheap to join mesh network to transmit and recieve bitcoin transactions.

The cost of bluetooth/wifi-embedded microcontrollers and the amount of power they consume has dramatically dropped, which has made it entirely plausable to embedded them into pre-existing infrastructure, ie streets lilghts. 

The goal of bitcoin-mesh is to create a publicallly accessible, free and open-source mesh-network to send and recieve bitcoin transactions. The project will create software that can be flashed to a microcontroller, then have that microcontroller automatically connect and support the bitcoin-mesh. The mesh network will route transaction data directly through the network, or via contact points such as blockstream satalite conections or internet enabled bitcoin full nodes.
The network bandwidth will have two layers, 1/3 broadcast, 2/3 unicast. The broadcast layer will transmit crrent bitcoin transaction data, the unicast layer will transport transactions to the bitcoin network. In order to avoid spam, use of the unicast layer will cost a small scable fee that will be distributed randomely to a point of contact, ie someone runing a satalite conection/full-node. 



