![bitcoin mesh network](https://i.imgur.com/p1BPto4.png)
# The Bitcoin Mesh Project
A cheap to join mesh network to transmit and receive bitcoin transactions.

The cost of Bluetooth/wifi-embedded microcontrollers and the amount of power they consume has dramatically dropped, which has made it entirely plausible to embedded them into pre-existing infrastructure, ie streets lights.

Mesh-networks are an organic self-healing structure, with incomparable anti-fragile qualities. Some experimentation utilising mesh networks with bitcoin exist, but they have used expensive, closed sourced platforms such as GoTenna.

The goal of bitcoin-mesh is to create an ultra-low cost, publically accessible, free and open-source mesh-network to send and receive bitcoin transactions. The project will create software that can be flashed to a microcontroller, then have that microcontroller automatically connect and support the bitcoin-mesh. The mesh network will route transaction data directly through the network, or via contact points such as blockstream satellite connections or internet enabled bitcoin full nodes.

Network bandwidth will be separated into two layers, 1/3 broadcast, 2/3 unicast. The broadcast layer will transmit current bitcoin transaction data and is free to access, the unicast layer will transport transactions to the bitcoin network. In order to avoid spam, use of the unicast layer will incur a small scalable fee that will be distributed randomly to a point of contact, ie someone running a satellite connection/full-node.

![bitcoin mesh network](https://i.imgur.com/jxwNDRx.png)



