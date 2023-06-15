# SimpleWire



SimpleWire is a code snippet and CLI utility for network analysis and security assessment. It includes simplified python implementation of [Wireshark](https://github.com/wireshark/wireshark) , a widely-used tool in the field of network exploration and packet analysis, using raw sockets.

The code captures each packet and shows the analyzed packet in the output and saving the packet information in a pcap file as well.

This repository serves as a learning resource and a starting point for developers and enthusiasts interested in understanding the inner workings of network protocols and conducting network scanning and analysis. The code provides a basic packet capturing and analysis functionality, allowing users to inspect network traffic and dissect packets.

By exploring and studying the code in this repository, you can gain insights into the fundamental concepts of network analysis, network security, and protocol handling.



# Promiscuous Mode

Promiscuous mode is a feature that makes the ethernet card pass all traffic it received to the kernel. It is usually used by a packet sniffing programs like Wireshark, and tcpdump.  So you must first enable promiscuous mode on your NIC card.



To set an interface to promiscuous mode you can use either of these commands:

```shell
ifconfig [interface] promisc
ip link set [interface] promisc on
```



To see your interfaces run the command below:

```shell
ifconfig
```



# How To Run

Just simply run the command below:

```shell
python3 wireshark.py
```



# Outputs

An example of output of a captured packet is shown below:

![Example](/home/h/Desktop/network-projects/wireshark/SimpleWire/images/example.png)



# References



[Wireshark](https://github.com/wireshark/wireshark)

