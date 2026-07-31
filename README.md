# Enterprise Multi-Site Network Infrastructure

A production-inspired Cisco Packet Tracer project that simulates a real-world enterprise network connecting a Headquarters (HQ) with two geographically distributed branch offices.

The project demonstrates how enterprise routing, switching, WAN redundancy, and centralized network services work together to build a highly available, scalable, and resilient network infrastructure using Cisco technologies.

---

## Network Topology



---

## Project Overview

The objective of this project was to design and implement a production-inspired enterprise network that reflects the architecture commonly used in modern corporate environments.

The Headquarters (HQ) serves as the central hub, hosting essential enterprise services such as DNS, DHCP, Web, Mail, File Server, IP-PBX, Wireless LAN Controller (WLC), CCTV, and NVR. Two branch offices are connected to the HQ through redundant ISP links and GRE tunnels, ensuring reliable and uninterrupted communication across all locations.

The core focus of this project was to build a resilient enterprise infrastructure using OSPF, eBGP, GRE tunnels, HSRP, VLAN segmentation, Inter-VLAN routing, and EtherChannel. These technologies work together to provide dynamic routing, gateway redundancy, link redundancy, and high availability throughout the network.

Cisco ASA firewalls are included in the topology as part of the overall enterprise architecture. However, advanced firewall policy configuration was not the primary focus of this project, allowing greater emphasis on enterprise routing, switching, WAN connectivity, redundancy, and centralized network services.

Overall, this project demonstrates practical enterprise network design by applying industry-standard technologies and best practices to build a scalable, reliable, and highly available multi-site infrastructure.


# Enterprise Architecture

* Headquarters (HQ)
* Branch Office 1
* Branch Office 2
* Dual ISP Connectivity
* Dual Cisco ASA Firewall Integration
* Core Layer
* Distribution Layer
* Access Layer
* Dedicated DMZ
* Server Farm
* Wireless Infrastructure
* CCTV & NVR Network
* Enterprise Voice Network

---

# Key Features

### High Availability

* HSRP Gateway Redundancy
* HSRP Preemption
* HSRP Priority Control
* Interface Tracking
* Dual Core Switch Architecture
* Dual Firewall Architecture

### WAN Infrastructure

* Dual ISP Connectivity
* WAN Redundancy
* GRE Site-to-Site Tunnels
* Multiple Tunnel Interfaces
* eBGP WAN Routing

### Routing

* OSPF Area 0
* OSPF MD5 Authentication
* Dynamic Route Advertisement
* Inter-VLAN Routing
* Layer 3 Switching

### Switching

* VLAN Segmentation
* 802.1Q Trunking
* EtherChannel (LACP) for Link Aggregation
* PVST+
* STP Root Priority
* Native VLAN
* PortFast

### Security

* Cisco ASA Firewall Integration
* Basic ACL Configuration
* Basic NAT Configuration
* Dedicated DMZ Connectivity
* OSPF MD5 Authentication
* Enterprise Network Segmentation

### Enterprise Services

* DHCP Server
* DNS Server
* Web Server
* Mail Server
* File Server
* DHCP Relay (IP Helper)
* Wireless LAN Controller (WLC)
* Corporate Wi-Fi
* Guest Wi-Fi
* IP-PBX
* VoIP
* CCTV
* Network Video Recorder (NVR)

---

# Technologies Used

| Category          | Technologies                                                                 |
| ----------------- | ---------------------------------------------------------------------------- |
| Routing           | OSPF, eBGP, GRE Tunnel,HSRP                                                  |
| Switching         | VLAN, Inter-VLAN Routing, Layer 3 Switching, EtherChannel (LACP), STP, PVST+ |
| High Availability | HSRP, Interface Tracking                                                     |
| Security          | Cisco ASA (Basic Integration), ACL, NAT, DMZ                                 |
| Network Services  | DHCP, DNS, Web, Mail, File Server                                            |
| Wireless          | Wireless LAN Controller (WLC), Corporate WLAN, Guest WLAN                    |
| Voice             | Cisco IP-PBX, VoIP                                                           |
| Monitoring        | CCTV, NVR                                                                    |
| Platform          | Cisco IOS, Cisco Packet Tracer                                               |

---

# Skills Demonstrated

This project allowed me to gain practical experience in:

* Enterprise Network Design
* Campus Network Architecture
* Routing & Switching
* WAN Design
* Dynamic Routing (OSPF & eBGP)
* GRE Tunnel Deployment
* High Availability with HSRP
* Layer 3 Switching
* VLAN Planning & Segmentation
* Link Aggregation using EtherChannel
* Firewall Integration
* Enterprise Security Fundamentals
* Enterprise Wireless Deployment
* IP Telephony
* Enterprise Network Services
* Network Troubleshooting
* Infrastructure Documentation

---

# Enterprise Services

The HQ Data Center hosts multiple centralized services that are shared across all branch locations.

* DNS Server
* DHCP Server
* Web Server
* Mail Server
* File Server
* Wireless LAN Controller
* IP-PBX
* CCTV Server
* NVR

---

# Design Goals

The network was designed with the following objectives:

* High Availability
* Redundant WAN Connectivity
* Scalable Enterprise Architecture
* Secure Site-to-Site Communication
* Centralized Network Services
* Fault Tolerance
* Gateway Redundancy
* Easy Maintenance
* Simplified Network Management

---

# Project Verification

The deployment was validated using several Cisco verification commands, including:

* show ip route
* show ip ospf neighbor
* show ip ospf interface
* show ip bgp
* show standby brief
* show etherchannel summary
* show interfaces trunk
* show spanning-tree
* show vlan brief
* show ip interface brief
* ping
* traceroute

---

# Repository Structure

```text
Enterprise-Multi-Site-Network/
│
├── configs/
│   ├── HQ/
│   ├── Branch-1/
│   ├── Branch-2/
│   ├── Core/
│   ├── Distribution/
│   ├── Access/
│   └── Firewalls/
│
├── packet-tracer/
│   └── Enterprise-Network.pkt
│
├── diagrams/
│   ├── topology.drawio
│   ├── topology.png
│   └── architecture.pdf
│
├── screenshots/
│   ├── Routing/
│   ├── HSRP/
│   ├── OSPF/
│   ├── BGP/
│   ├── Firewall/
│   ├── VLAN/
│   ├── WLC/
│   ├── Servers/
│   └── Verification/
│
├── documentation/
│   ├── Network-Design.pdf
│   ├── IP-Plan.pdf
│   ├── VLAN-Plan.pdf
│   ├── Routing-Design.pdf
│   └── Configuration-Guide.pdf
│
├── README.md
└── LICENSE
```

---

# About This Project

This project was created as part of my hands-on learning journey in enterprise networking. My goal was not only to configure Cisco devices but also to understand how enterprise networks are planned, secured, and made highly available.

Throughout the implementation, I focused on applying practical design principles such as redundancy, scalability, centralized services, and resilient routing to build a network that closely resembles a production environment.

---

# Future Enhancements
* Advanced Cisco ASA Security Policies
* IPsec Site-to-Site VPN
* AAA (RADIUS/TACACS+)
* SNMP Monitoring
* Syslog Server
* QoS for Voice Traffic
* IPv6 Support
* Network Automation using Python & Ansible

---

# Author

**Md. Delowar Hossain**
Network Engineer(NOC)
Walton Hi-Tech Industries PLC

---
⭐ If you found this project helpful, consider giving the repository a star.
--- 
