# ns3dvrp
A distance vector routing protocl (DVRP) for ns-3 simulator.

Distance Vector Routing Protocol (DVRP) Integration for ns3
-----------------------------------------------------------
As IPv4 proactive table driven routing protocol, the DVRP is implemented to the ns-3.
This routing protocol ebables a good platform for testing and experimenting with
different network typologies.

The DVRP is a IPv4 unicast only routing protocol, which is developed based on the Bellman-Ford algorithm.
In particular, DVRP is developed based on RIPv2 (RFCs : rfc: `2453`) and thus, DVRP supports some additional features that are not defined in both RPIv2 and RIPng. Among those additional features, use sequence numbering for route updates, and maintain a neighbor table for fast reactions for topology changes are major.

The protocol is very simple, and it is normally suitable for flat, simple network typologies.
