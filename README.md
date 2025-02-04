# Enterprise Network OSPF

## Project Overview
This project demonstrates the configuration of OSPF (Open Shortest Path First) routing protocol in Cisco Packet Tracer, using a multi-area setup. It incorporates 4 VLANs and DHCP configuration for dynamic IP addressing. The topology simulates a corporate network design with inter-VLAN routing, ensuring proper communication between different departments.

## Topology Overview
- **4 Routers:** Configured to implement OSPF across multiple areas for routing between VLANs.
- **4 Switches:** Used for VLAN segmentation and interconnectivity between routers and PCs.
- **24 PCs:** Assigned to different VLANs, configured with DHCP for dynamic IP allocation.

## VLAN Configuration
- **VLAN 10** - IT Department  
- **VLAN 20** - HR Department  
- **VLAN 30** - Finance Department  
- **VLAN 40** - Marketing Department  

## OSPF Configuration
OSPF routing protocol is configured in multiple areas with a backbone area, ensuring route propagation between VLANs.

## Features
- **OSPF Routing Protocol:** Implementation of OSPF across multiple areas (including the backbone area).
- **VLAN Setup:** VLANs configured to segment the network for different departments:
  - VLAN 10: IT  
  - VLAN 20: HR  
  - VLAN 30: Finance  
  - VLAN 40: Marketing  
- **Dynamic IP Addressing:** DHCP configured to provide dynamic IP addresses to all devices.
- **Inter-VLAN Routing:** Enabled routing between VLANs to ensure communication across departments.
- **Connectivity Testing:** Connectivity tested using ping and traceroute.

## Getting Started
1. Download and open the `6_Enterprise_Network_OSPF.pkt` file in Cisco Packet Tracer.
2. Make sure you have Cisco Packet Tracer installed on your system (version 8.2.2 or later recommended).
3. Explore the topology and understand the configurations for OSPF and VLANs.
4. You can modify and extend the network as per your requirements.

## Prerequisites
- Cisco Packet Tracer installed on your computer.
- Basic understanding of OSPF routing protocol, VLANs, and DHCP.

## License
This project is for educational purposes and is shared under the [MIT License](https://opensource.org/licenses/MIT).
