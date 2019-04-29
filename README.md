![bitcoin mesh network](https://i.imgur.com/p1BPto4.png)
# bitcoin-mesh
A cheap to join mesh network to transmit and receive bitcoin transactions.

The cost of Bluetooth/wifi-embedded microcontrollers and the amount of power they consume has dramatically dropped, which has made it entirely plausible to embedded them into pre-existing infrastructure, ie streets lights.

Mesh-networks are an organic self-healing structure, with incomparable anti-fragile qualities. Some experimentation utilising mesh networks with bitcoin exist, but they have used expensive platforms such as GoTenna, and have very limited bandwidth.

The goal of bitcoin-mesh is to create an ultra-low cost, publically accessible, free and open-source mesh-network to send and receive bitcoin transactions. The project will create software that can be flashed to a microcontroller, then have that microcontroller automatically connect and support the bitcoin-mesh. The mesh network will route transaction data directly through the network, or via contact points such as blockstream satellite connections or internet enabled bitcoin full nodes.

Initially this project will focus on developing software for the ESP32 microcontroller, which is both cheap, reliable and easily auditable. Esspressif, the company that develops the microcontroller, has recently relased a keychain for developing mesh [solutions](https://www.espressif.com/en/products/software/esp-mesh/overview). 

Benefits to using the ESP32 include:

* Supports Wifi and BLE
* Low cost - $2-$6
* 200-meter range (although with additional hardware this can be extended to 1-2k)
* 10Mbps data transfer rate

![ESP32 Espressif](https://i.imgur.com/B64eBE7.jpg)

Network bandwidth will be separated into two layers, 1/3 broadcast, 2/3 unicast. The broadcast layer will transmit current bitcoin transaction data and is free to access, the unicast layer will transport transactions to the bitcoin network. In order to avoid spam, use of the unicast layer will incur a small scalable fee that will be distributed to the a point of contact used, ie someone running a satellite connection/full-node.

![transport layers](https://i.imgur.com/jxwNDRx.png)

# BTCIOT - bitcoin-mesh diaries, part 1

[![BTCIOT](https://i.imgur.com/MFQwEzz.jpg)](https://www.youtube.com/watch?v=3DN4L_vdwA4)
