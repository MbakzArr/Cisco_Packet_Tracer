# Cisco_Packet_Tracer

I have configured DHCPv6 server on each router for the PC network connected to it. R1 is
the DHCPv6 Server for the PC1 network, R2 for the PC2 network, R3 for the PC3, etc.
All routers have been configured with IPv6 addresses on their Gig 0/0/0 interfaces for network
2001:12:34::/64.
R1, R2, R3 and R4 have been partially configured so PC1 and PC2 can obtain IPv6 address settings,
ping each other, and PC1 can ping the Gig 0/0/0 interfaces on R3 and R4.

All routers are statically configured with the first address on the network as shown.
I've also added configurations to all routers so all PCs can obtain correct IPv6 address settings
and can all ping the Gig 0/0/1 interface on every other router.

Note: You will need to run this on Cisco Packet tracer software.
