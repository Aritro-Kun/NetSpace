Developing the logic to ARP.
-

As we must have already known by now, it's necessary for the communicating device to know the MAC Address of the device with which it wants to communicate. How does it do so, that's what we discuss here.

- Creating an ARP Request Packet. Oh and btw, we just can't be sending a random ARP Request out of nowhere and developing this whole thing from scratch would take a lot of time, and is basically senseless. There are already a few libraries rather packages which are available. Here, we will be using one such, Scapy.
- Making the ARP Request Packet: 
