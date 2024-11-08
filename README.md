# VoIP and Secure SSH Configuration Lab
This lab project simulates a network environment in Cisco Packet Tracer, focusing on VLAN segmentation, inter-VLAN routing via Router-on-a-Stick, and VoIP with IP phones across VLANs. Key configurations include VTP for VLAN management, DHCPv4 for IP assignment, DTP for trunk negotiation, and SSH for secure remote access.
# Key protocols and technologies
- **VTP:** Used to manage VLAN information across multiple switches, ensuring consistent VLAN IDs throughout the network.
- **VLANs:** Implemented for logical network segmentation, providing separate broadcast domains for different device groups. 
- **Trunk and Access Ports:** Configured to manage VLAN traffic; trunk ports carry multiple VLANs, while access ports link end devices to specific VLANs.
- **DTP:** Employed for automatic trunk negotiation between switches. 
- **Router-on-a-Stick Configuration:** A single router interface is used for inter-VLAN routing, allowing devices on separate VLANs to communicate.  
- **DHCPv4:** Provides dynamic IP address allocation to devices within the VLANs, simplifying network management and configuration.
- **VoIP Configuration:** Cisco IP phones are connected and assigned to designated VLANs to simulate Voice over IP capabilities in the network.
- **SSH Setup:** Secure Shell is set up for encrypted remote access to network devices, enhancing security for network management.
