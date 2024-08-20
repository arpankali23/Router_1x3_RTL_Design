# Router_1x3_RTL_Design
Router is a device that forwards data packets between computer networks. It is an OSI layer 3 (TCP/IP Protocol) routing device. It drives an incoming packet to an output channel based on the address field contained in the packet header.
Router 1x3 design follows packet based protocol and it receives the network packet from a source LAN uning data on a byte by byte basis on active poedge of the clock.

Router top block level architecture consist 4 sub blocks
1. FSM Controller
2. Synchronizer
3. Register
4. FIFOs
