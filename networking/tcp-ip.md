# TCP/IP

TCP/IP is a set of communication protocols used by devices to communicate across IP networks such as the Internet.

## IP Address

An IP address is a numerical address used to identify a network interface and allow devices to communicate across an IP network.

## TCP

TCP stands for Transmission Control Protocol. It is a core communication protocol used by devices on the Internet to send and receive data reliably.

## Ports

Ports identify a specific service or application running on a host.

For example:

* Port 80 → HTTP
* Port 443 → HTTPS
* Port 22 → SSH
* Port 53 → DNS

An IP address identifies the host, while a port identifies the service or application on that host.

## TCP Three-Way Handshake

Before exchanging data, TCP establishes a connection using a three-way handshake:

Client → SYN → Server
Server → SYN-ACK → Client
Client → ACK → Server

After these three steps, the TCP connection is established.

## TCP vs UDP

TCP is connection-oriented and reliable. It manages:

* Connection establishment
* Data ordering
* Retransmission of lost packets
* Flow control
* Acknowledgements

UDP, on the other hand, is connectionless and does not guarantee:

* Delivery
* Ordering
* Retransmission
* Acknowledgements

## What I Learned

* An IP address identifies a network interface.
* Ports identify specific services or applications running on a host.
* TCP establishes a connection using a three-way handshake.
* TCP provides reliable and ordered data delivery, while UDP does not guarantee delivery or ordering.
