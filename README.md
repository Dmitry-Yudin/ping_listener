# ping_listener

Python 3 script that will listen for ping requests and print the IP address of the host that is pinging your machine

This script will create a raw socket and bind it to the IP address of the local machine. 
It will then use the recvfrom() method to receive packets from the socket. If a packet is received, the script will extract the IP address of the pinging host from the packet using the struct module, and print the IP address.
