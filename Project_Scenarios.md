# Scenario 1: AMIGO Ltd
## Assessment & Planning

 

You are a network administrator at AMIGO Ltd, a medium-sized company that has recently migrated several business-critical applications, including VoIP, video conferencing, and cloud-based CRM tools, to a centralized corporate network. Employees have started complaining about laggy voice calls, buffering during meetings, and slow CRM performance, especially during peak business hours. The executive team has asked you to improve network performance without upgrading bandwidth.

 

## After conducting your investigations you took note of the following issues:

1. IPv4 Limitations

o   The organisation is still running on an IPv4-based network, resulting in limited address space and inefficient Routing.

o   Network Address Translation (NAT) is used extensively, adding complexity to network management.

2. Quality of Service (QoS) Deficiencies

o   Business-critical applications experience latency and jitter due to inadequate QoS policies.

o   Video conferencing and VoIP services suffer from inconsistent performance.

o   Network congestion during peak hours leads to reduced productivity.

3. Wireless Network Coverage and Performance Issues

o   Weak wireless signals in some regions of the office cause connectivity disruptions.

o   Increased network traffic from employees, IoT devices, and guests overwhelms the wireless network.

o   Security vulnerabilities in the wireless infrastructure expose the company to cyber threats.

4. Lack of Centralized Network Control

o   The absence of a centralised network management system makes troubleshooting and monitoring difficult.

o   Configuration inconsistencies across devices result in security loopholes.

o   Manual configuration changes lead to frequent downtime and human errors.

## Proposed solutions:

1.  Migration to IPv6

o   Implement IPv6 to overcome address limitations and improve network efficiency.

o   Optimise routing with IPv6 to reduce latency and enhance network scalability.

2.  Quality of Service (QoS) Implementation

o   Prioritise critical business applications by configuring QoS policies at the network edge.

o   Use Differentiated Services Code Point (DSCP) for traffic classification.

o   Implement traffic shaping and bandwidth allocation to prevent network congestion.

3.  Enhancing Wireless Network Performance

o   Deploy additional access points (APs) and optimise their placement using heatmaps.

o   Upgrade to Wi-Fi 6 technology for improved speed, efficiency, and capacity.

o   Implement robust encryption (WPA3) and network segmentation to enhance security.

# Scenario 2: Amigo Te Bchite Corporation Network Upgrade Case Study:

As part of Amigo Corporation’s network upgrade initiative, you have been assigned to transition one of the branch office LANs from IPv4 to IPv6. You aim to configure IPv6 addresses, enable Routing, and verify connectivity using Cisco Packet Tracer.

# Scenario 3: GlobeTech Inc.
Project Title: Enterprise Multisite Network Infrastructure with High Availability, Security, and Wireless Management

## Scenario Overview

You are the senior network engineer for GlobeTech Inc., a multinational corporation with headquarters in Johannesburg, regional offices in Cape Town, and a remote branch office in Potchefstroom. You are required to design and implement a secured, reliable, scalable, and robust network system that is paramount to safeguarding the Confidentiality, Integrity, and Availability of data.  The company places a strong emphasis on achieving top-tier performance, redundancy, scalability, and availability within its network infrastructure.

Each site needs to be securely connected with high availability, internal segmentation, controlled internet access, and wireless infrastructure.

## Project Objectives

The following design considerations and configurations are to be implemented:

Implement a hierarchical IP addressing scheme
·        The organisation relies on 2 routers, 2 layer 3 switches connected for redundancy and multiple layer 2 switches as deemed necessary.

The two routers connect to the internet (ISP), which houses the organisation’s web server.
Potchefstroom Router (R3_POT) is connected to the R2_CPT
One Layer 3 Switch is located at the Johannesburg offices, and the other one is located at the Cape Town office.
The wireless LAN Controller is located at the HQ and is connected to the L3 Switch, which then connects to multiple access switches and the lightweight APS..
There is another router (3) which connects the remote site (Potchefstroom) to the main network.
The DHCP Server is also located in the HQ offices and is responsible for allocating IP addresses to the rest of the network.
The network uses OSPF for intra-network dynamic routing
Implements ACLs for traffic control between departments
Applies NAT for Internet access
Uses FHRP (e.g., HSRP) for gateway redundancy
·        For traffic control and congestion control between departments, implement strategies to limit broadcast storms

·        While implementing networking segmentation strategies, devices in all the departments are required to communicate with each other.

· The organisation uses a web server provided by the two ISPS.

·        All devices in the network are expected to obtain an IP address dynamically from the dedicated DHCP servers located at the server room.

·        Each site is required to have a wireless network and a printer for the users.

Set up Wireless LAN Controllers (WLC) for managing APs
·        The organization has a website (www. GlobeTech.co.za) which is hosted by the ISP and should be accessible by all computers.
