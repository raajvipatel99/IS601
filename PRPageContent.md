## Packets, Routing and Reliability

How is it possible for every piece of astonishing amount of data to be delivered to you reliably ?\
Information when transferred through network, does not follow a dedicated path. It is broken down into pieces, called packets. Each packet has a source and destination address in its header and depending on the traffic congestion, it takes a different path in the network. This method of breaking down of information into packets and sending them independently though the optimum path is known as packet switching.\
Router acts like a traffic manager. It keeps track of multiple paths and chooses the cheapest (in terms of time, company relationships and politics) path for a packet to travel. More options for path makes network fault tolerant. Router systems, TCP are designed to be scalable.\
Reliability is the key principle for internet. TCP (Transmission Control Protocol) guarantees that all the data is delivered by sending acknowledgements for each packet received. If acknowledgement for a packet isn’t received after some time, that packet is resent.\
Principles of Fault Tolerance and Redundancy state that more routers lead to more reliability.
