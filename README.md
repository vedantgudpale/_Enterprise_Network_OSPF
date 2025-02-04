<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enterprise Network OSPF - README</title>
</head>
<body>
    <h1>Enterprise Network OSPF</h1>
    
    <h2>Project Overview</h2>
    <p>This project demonstrates the configuration of OSPF (Open Shortest Path First) routing protocol in Cisco Packet Tracer, using a multi-area setup. It incorporates 4 VLANs and DHCP configuration for dynamic IP addressing. The topology simulates a corporate network design with inter-VLAN routing, ensuring proper communication between different departments.</p>
    
    <h2>Topology Overview</h2>
    <ul>
        <li><strong>4 Routers:</strong> Configured to implement OSPF across multiple areas for routing between VLANs.</li>
        <li><strong>4 Switches:</strong> Used for VLAN segmentation and interconnectivity between routers and PCs.</li>
        <li><strong>24 PCs:</strong> Assigned to different VLANs, configured with DHCP for dynamic IP allocation.</li>
    </ul>
    
    <h2>VLAN Configuration</h2>
    <ul>
        <li><strong>VLAN 10:</strong> IT Department</li>
        <li><strong>VLAN 20:</strong> HR Department</li>
        <li><strong>VLAN 30:</strong> Finance Department</li>
        <li><strong>VLAN 40:</strong> Marketing Department</li>
    </ul>
    
    <h2>OSPF Configuration</h2>
    <p>OSPF routing protocol is configured in multiple areas with a backbone area, ensuring route propagation between VLANs.</p>
    
    <h2>Features</h2>
    <ul>
        <li><strong>OSPF Routing Protocol:</strong> Implementation of OSPF across multiple areas (including the backbone area).</li>
        <li><strong>VLAN Setup:</strong> VLANs configured to segment the network for different departments.</li>
        <li><strong>Dynamic IP Addressing:</strong> DHCP configured to provide dynamic IP addresses to all devices.</li>
        <li><strong>Inter-VLAN Routing:</strong> Enabled routing between VLANs to ensure communication across departments.</li>
        <li><strong>Connectivity Testing:</strong> Connectivity tested using ping and traceroute.</li>
    </ul>
    
    <h2>Getting Started</h2>
    <ol>
        <li>Download and open the <code>6_Enterprise_Network_OSPF.pkt</code> file in Cisco Packet Tracer.</li>
        <li>Make sure you have Cisco Packet Tracer installed on your system (version 8.2.2 or later recommended).</li>
        <li>Explore the topology and understand the configurations for OSPF and VLANs.</li>
        <li>You can modify and extend the network as per your requirements.</li>
    </ol>
    
    <h2>Prerequisites</h2>
    <ul>
        <li>Cisco Packet Tracer installed on your computer.</li>
        <li>Basic understanding of OSPF routing protocol, VLANs, and DHCP.</li>
    </ul>
    
    <h2>License</h2>
    <p>This project is for educational purposes and is shared under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</p>
</body>
</html>
