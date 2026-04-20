Cisco Packet Tracer – Switch Security Configuration
This project demonstrates secure Layer 2 switch configuration using Cisco IOS. The lab includes VLAN segmentation, trunk hardening, port security, DHCP snooping, and STP protections across two access‑layer switches.

🔧 Technologies Used
Cisco Packet Tracer

VLANs & Trunking

Port Security

DHCP Snooping

Rapid PVST+

BPDU Guard / PortFast

📁 VLAN Table
Switch	VLAN	Name	Ports	Network
SW‑1	10	Admin	F0/1, F0/2	192.168.10.0/24
SW‑1	20	Sales	F0/10	192.168.20.0/24
SW‑1	99	Management	F0/24	192.168.99.0/24
SW‑1	100	Native	G0/1, G0/2	—
SW‑1	999	BlackHole	Unused	—
SW‑2	10	Admin	F0/1, F0/22	192.168.10.0/24
SW‑2	20	Sales	F0/10	192.168.20.0/24
SW‑2	99	Management	F0/24	192.168.99.0/24
SW‑2	100	Native	—	—
SW‑2	999	BlackHole	Unused	—

📝 Objectives
Create secure trunk links

Lock down unused ports

Implement port security

Enable DHCP snooping

Configure PortFast & BPDU Guard

📌 Summary of What I Configured
Static 802.1Q trunks with DTP disabled

Native VLAN 100 on all trunk ports

All unused ports shut down and assigned to VLAN 999

Port security with sticky MACs and violation mode restrict

DHCP snooping with trusted trunk ports and rate limiting

Rapid PVST+ with PortFast and BPDU Guard on access ports
