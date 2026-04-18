# Enterprise Network Design with Centralized Services (Cisco Packet Tracer)

## 🌐 Project Overview
This project presents a robust, simulated enterprise network architecture connecting a Headquarters (HQ) and two remote branch offices. The design focuses on **centralized network management**, utilizing a single hub-and-spoke topology to provide essential services (DHCP, DNS, HTTP) across the entire infrastructure.

## 👥 Author
* **Mustafa Aydın** - Computer Engineering Student at Muğla Sıtkı Koçman University

## 🛠️ Technical Specifications & Implementation
The network is built with professional-grade Cisco hardware and protocols:

* **Topology:** Hub-and-Spoke (Star) using Serial WAN links.
* **Routing:** End-to-end connectivity established via **Static Routing** for precise traffic control.
* **Centralized Services (HQ Server):**
    * **DHCP:** Automated IP management for all clients in Branch A, Branch B, and HQ.
    * **DNS & Web (HTTP):** Internal domain name resolution and hosted web services.
* **Network Monitoring:** Implementation of **SNMPv2** for remote device monitoring and management via MIB Browser.
* **Hardware:** Cisco ISR4321 (HQ), 2911, and 2901 Routers with 2960-24TT Switches.

## 🗺️ Network Architecture
The network consists of three main segments:
1.  **Headquarters (HQ):** The core of the network, hosting the primary server and centralized services.
2.  **Branch A:** Remote site connected via Point-to-Point Serial link.
3.  **Branch B:** Remote site connected via Point-to-Point Serial link.

## 📊 Documentation
A detailed technical report is included in the repository:
* `Branch Network Design with Centralized Routing.pdf`: Contains full configuration steps, IP addressing schemes, and SNMP verification results.

## 📁 Files
* `project.pkt`: The original Cisco Packet Tracer simulation file.
* `Full_Report.pdf`: Detailed project documentation and verification.

---
*This project was developed for the CENG 3007 Computer Networks course at MSKU.*
