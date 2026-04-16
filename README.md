## Enterprise Network Design & IPv6 Transition Portfolio.
## Project Overview:
This repository contains a dual-phase network engineering project focusing on infrastructure modernization, multi-site scalability, and secure traffic management. It showcases the design and implementation of complex network solutions for two distinct organizations: Amigo Ltd and GlobeTech Inc.
## Technical Case Studies
### 🏢 Amigo Ltd: IPv6 Transition & Performance Optimization
Objective: Modernize a legacy star topology to support high-bandwidth, real-time applications and transition to IPv6.
- Traffic Prioritization (QoS): Implemented DSCP classification and traffic shaping to ensure stability for VoIP and Video Conferencing, preventing congestion from cloud-based CRM traffic.
- Transition Strategy: Deployed a three-stage migration plan using Dual-Stack for simultaneous protocol support, Tunneling to bridge IPv4 gaps, and NAT-PT for legacy system communication.
- Advanced Routing: Evaluated OSPFv3 and EIGRP for IPv6 to provide robust path determination and rapid fault recovery.
### 🌍 GlobeTech Inc: Multi-Site Enterprise Infrastructure 
Objective: Design a fault-tolerant, redundant network architecture spanning three geographical locations: Johannesburg, Cape Town, and Potchefstroom.
- Addressing & Subnetting: Engineered a complex addressing scheme using Variable Length Subnet Masking (VLSM) for the 172.16.0.0/16 and 10.0.0.0/8 ranges.
- Secure Logical Segmentation: Defined and configured VLANs to isolate Guest Wi-Fi, Corporate Wi-Fi, Management, and Print services.
- Centralized Wireless Management: Deployed a Wireless LAN Controller (WLC) to manage Lightweight Access Points across sites, secured with WPA2-PSK.
- Hardened Security: Configured Extended Access Control Lists (ACLs) to restrict guest traffic and protect administrative interfaces on interconnectivity devices.
## Technical Skills Demonstrated:
- Simulations:Cisco Packet Tracer.
- Routing & Switching: OSPF, VLAN Trunking (802.1Q), Inter-VLAN routing, and HSRP concepts.
- Security: Extended ACLs, NAT/PAT, and WPA2 wireless security.
- Network Services: DHCP Server configuration and WLC management.
