Enterprise_Network_OSPF
Project Overview
This project demonstrates the configuration of OSPF (Open Shortest Path First) routing protocol across multiple areas in Cisco Packet Tracer. The network includes multiple VLANs and uses DHCP for dynamic IP addressing. The design simulates an enterprise network with inter-VLAN routing to ensure connectivity between different segments.

Topology Overview
4 Routers: Configured for OSPF with multiple areas, including a backbone area (Area 0).
4 Switches: Interconnected to routers and used for VLAN segmentation.
24 PCs: Distributed across VLAN 10, VLAN 20, and VLAN 30, configured with dynamic IP addresses via DHCP.
VLANs:
VLAN 10: IT Department
VLAN 20: HR Department
VLAN 30: Marketing and Cloud
OSPF Configuration: OSPF configured to route between the VLANs using multiple areas, ensuring proper route propagation between devices.
Features
OSPF Multi-Area routing protocol setup across multiple areas.
VLAN Configuration: VLANs 10, 20, and 30 with inter-VLAN routing.
DHCP Setup: Dynamic IP assignment for all connected PCs.
Connectivity Testing: PCs are able to communicate across VLANs with ping and traceroute tests.
Getting Started
Download and open the 6_Enterprise_Network_OSPF.pkt file in Cisco Packet Tracer.
Ensure you have Cisco Packet Tracer installed on your system (version 8.2.2 or later recommended).
Explore the topology to see how OSPF is configured across multiple areas and how VLANs are segmented.
You can modify and expand the topology as needed to fit your project requirements.
Prerequisites
Cisco Packet Tracer (version 8.2.2 or later).
Basic understanding of OSPF, VLANs, and DHCP.
Familiarity with routing protocols and networking concepts.
License
This project is for educational use only. Feel free to use and modify the repository under the MIT License.