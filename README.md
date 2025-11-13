# Secure Campus Area Network System

The Secure Campus Area Network System is a Cisco Packet Tracer-based project 
that connects multiple departments in a campus using VLANs, routers, core switches, 
and firewall configurations. The goal is to build a secure, efficient, and scalable 
network for communication and data sharing between different departments.

- To design a secure and structured network for a campus environment.
- To implement VLANs for logical segmentation of departments.
- To configure static routing and inter-VLAN communication.
- To provide firewall protection for network security.
- To ensure efficient connectivity between all departments and servers.

🔍 Objective:
To design and implement a Campus Area Network (CAN) that connects diverse departments, servers, and end devices through efficient routing, VLAN segmentation, and security controls — ensuring data integrity, performance, and scalability.

💻 Project Overview:
The SCANS project connects departments such as Computer Science, Engineering, Business Management, Healthcare, and Commerce & Arts under a single, integrated network. Each department operates within a dedicated VLAN, managed through a multilayer switch and secured by a Cisco ASA 5506-X Firewall. The system allows smooth inter-department communication while maintaining isolation, security, and administrative control.
⚙️ Technical Implementation:

Core Layer: Cisco Catalyst 3650-24PS Multilayer Switch for inter-VLAN routing and backbone management.

Distribution & Access Layers: Cisco 2960-24TT switches for departmental access.

Firewall Security: Cisco ASA 5506-X configured with NAT, PAT, and Access Control Lists (ACLs) for internal and external traffic filtering.

Routing: Cisco 2911 Routers providing WAN connectivity and static routing for internet access.

Server Room: Web, FTP, DNS, and Email servers configured under VLAN 101 with both local and cloud access.

Wireless Infrastructure: Cisco WLC-2504 Wireless LAN Controller managing APs for campus-wide mobility support.

VLAN Segmentation: Separate VLANs (10–101) for each department to ensure logical separation, security, and performance optimization.

🔒 Security Features:

ASA Firewall policies to filter inbound/outbound traffic.

Access Control Lists (ACLs) to restrict unauthorized inter-VLAN communication.

NAT/PAT configurations for secure Internet access.

Layer 3 switch routing to enable controlled inter-VLAN communication.

🧩 Tools & Technologies Used:
Cisco Packet Tracer | Cisco Routers (2911) | Cisco ASA Firewall | Cisco Switches (3650, 2960) | WLC-2504 | FTP, DNS, Web & Email Servers | VLAN & ACL Configurations

📈 Outcome:
The final network achieved:
✅ Centralized management across departments.
✅ High-speed, reliable communication within and outside the campus.
✅ Enhanced data security using firewall and ACL policies.
✅ Scalable infrastructure ready for future expansion.
