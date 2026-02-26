# SVNET v1 — Basic Network Topology Design

## 📌 Overview
SVNET v1 is a basic enterprise network simulation built using Cisco Packet Tracer.  
This project demonstrates foundational networking concepts including IP addressing, routing, and core network services.

The topology is divided into internal and external networks, connected via routers, and includes essential services such as DHCP, DNS, and a Web Server.

---

## 🎯 Objectives
- Build a functional network topology
- Understand IP addressing and subnetting
- Configure basic routing between networks
- Deploy core network services (DHCP, DNS, Web Server)
- Test connectivity between internal and external systems

---

## 🏗️ Network Architecture

### Internal Network (192.168.1.0/24)
- PCs (Clients)
- DHCP Server (IP allocation)
- DNS Server (Name resolution)
- Web Server (SVNET service)
- Printer
- Network Sniffer (traffic monitoring)
- Switch (Layer 2)

### External Network (192.168.2.0/24)
- PCs (External users)
- Switch

### Network Devices
- 2 Routers (Inter-network communication)
- 2 Switches

---

## 🌐 IP Addressing

| Device | IP Address |
|--------|----------|
| DHCP Server | 192.168.1.1 |
| DNS Server | 192.168.1.15 |
| Web Server | 192.168.1.20 |
| Internal PCs | 192.168.1.x |
| External PCs | 192.168.2.x |
| Router Interfaces | 192.168.1.4 / 192.168.2.4 / 192.168.3.x |

---

## ⚙️ Technologies Used
- Cisco Packet Tracer
- TCP/IP Protocol Suite
- Basic Routing
- DHCP Configuration
- DNS Configuration

---

## 🧪 Key Features

### DHCP Configuration
- Automatically assigns IP addresses to internal clients

### DNS Server
- Resolves domain names for internal services

### Web Server
- Hosts a simple web service (SVNET)

### Routing
- Enables communication between internal and external networks

### Network Monitoring
- Sniffer used to observe packet flow in the network

---

## 🔍 Testing & Validation

The following tests were performed:

- Successful ping between internal devices
- Communication between internal and external networks
- Access to web server from external PC
- DNS resolution testing
- Packet capture using sniffer

---

## 📊 Project Files

- `SVNET_v1.pkt` — Cisco Packet Tracer file
- `topology.png` — Network diagram
- `README.md` — Project documentation

---

## ⚠️ Limitations

This is a basic network design and does not include advanced security features:

- No VLAN segmentation
- No Access Control Lists (ACL)
- No NAT configuration
- No firewall implementation
- Limited security controls

---

## 🚀 Future Improvements (SVNET v2)

Planned upgrades to enhance security and scalability:

- Implement VLAN segmentation for network isolation
- Configure ACLs for traffic filtering
- Add NAT (Network Address Translation)
- Integrate firewall rules
- Deploy IDS/IPS (Snort / Suricata)
- Implement dynamic routing (OSPF)
- SIEM integration for monitoring

---

## 👨‍💻 Author

Sanskar Vijay Dahatre  
Cybersecurity Enthusiast | Networking Learner  

---

## 📬 Contact

- Email: dahatresanskar@gmail.com  
- LinkedIn: linkedin.com/in/sanskar-dahatre-284405330  

---

## ⚠️ Disclaimer
This project is created for educational purposes and demonstrates basic networking concepts.