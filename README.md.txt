# Enterprise Network Topology using Cisco Packet Tracer

## Overview

This project demonstrates a scalable enterprise WAN/LAN network topology designed in Cisco Packet Tracer.
It simulates a multi-branch enterprise network with dynamic routing, DHCP, NAT/PAT, WAN/ISP connectivity, and centralized email services.

---

## Network Architecture

* **1 ISP Router**
* **1 Edge Router (R1)**
* **9 Branch Routers (R2–R10)**
* **10 LANs**
* **10 Switches**
* **100 PCs**
* **1 Centralized Mail Server**
* **WAN Cloud Simulation**

---

## Implemented Technologies

* **OSPFv2 Dynamic Routing**
* **DHCP on All LAN Gateways**
* **NAT/PAT on Edge Router**
* **Default Route Propagation**
* **WAN/ISP Simulation**
* **Centralized Mail Server**
* **Inter-LAN Routing**
* **Internet Reachability Simulation**

---

## IP Addressing Scheme

| Segment      | Network         |
| ------------ | --------------- |
| ISP Uplink   | 10.0.0.0/30     |
| Internal WAN | 203.0.113.0/24  |
| LAN1         | 192.168.1.0/24  |
| LAN2         | 192.168.2.0/24  |
| LAN3         | 192.168.3.0/24  |
| LAN4         | 192.168.4.0/24  |
| LAN5         | 192.168.5.0/24  |
| LAN6         | 192.168.6.0/24  |
| LAN7         | 192.168.7.0/24  |
| LAN8         | 192.168.8.0/24  |
| LAN9         | 192.168.9.0/24  |
| LAN10        | 192.168.10.0/24 |

---

## Topology Diagram

![Network Topology](Diagrams/network-topology-diagram.png)

---

## Verification Screenshots

### OSPF Neighbor Adjacency

![OSPF](Screenshots/ospf-neighbors.png)

### Default Route Propagation

![Default Route](Screenshots/routing-table-default-route.png)

### NAT/PAT Translation

![NAT](Screenshots/nat-translations.png)

### DHCP Address Assignment

![DHCP](Screenshots/dhcp-binding.png)

### Internet Connectivity Test

![Ping](Screenshots/internet-ping.png)

### Email Service Verification

![Email](Screenshots/email-verification.png)

---

## Project Features

* Dynamic route learning across all branch routers
* Internet simulation via ISP loopback interfaces
* NAT/PAT translation for all internal LANs
* Automated DHCP address allocation
* Centralized enterprise email server
* Full inter-LAN communication
* Scalable enterprise-ready topology design

---

## Testing Performed

* OSPF Neighbor Verification
* Default Route Advertisement Verification
* NAT Translation Verification
* DHCP Binding Verification
* Inter-LAN Ping Testing
* Internet Ping Testing
* Email Send/Receive Testing

---

## Files Included

* `.pkt` Packet Tracer topology file
* Configuration documentation
* Architecture diagram
* Verification screenshots
* Demo video walkthrough

---

## Author

**Aniket Patil**

---

## License

This project is for educational and portfolio purposes.
