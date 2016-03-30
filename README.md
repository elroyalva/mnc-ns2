MNC NS2

This repo is a project for writing a custom MAC protocol for sensor networks. 

Part of CSE 589 MNC at the University at Buffalo

We have written a custom MAC protocol called 'ESMAC' that can be used by sensors to transmit data reliably with minimal packet loss. It retransmits packets after random time intervals to make sure packets are delivered. An important thing to note is that the sensors cannot check if a packet has been delivered or not. Hence the repeated retransmissions. 

We ran tests for 100 nodes and a sink node, and then for 10 nodes and a sink node.

Number of copies sent ranged from 1 to 10

Analysis of these results have been discussed in the report attached
