🌍 SAFARICOM ENTERPRISE NETWORK TOPOLOGY 

## Project Summary

This project is a **simulation of Safaricom’s enterprise-wide network infrastructure** built in Cisco Packet Tracer. It represents a **multi-branch corporate topology** interconnecting **Call Centers and Data Centers across Kisumu, Nairobi, and Mombasa**.  

The design showcases my ability to apply **industry-standard practices** in enterprise networking, including secure dynamic routing, VLAN segmentation, subnetting, and device hardening.  


Design Objectives

- Build a **scalable, secure, and resilient enterprise network**.
- Demonstrate **pragmatic engineering choices** through OSPF, VLANs, and authentication.  
- Simulate **real-world ISP/corporate practices** suitable for a production-grade environment.  
- Maintain clear documentation to reflect professionalism and real workplace deliverables.  


 Features Implemented

### Routing & Addressing 
- **OSPFv2 (Open Shortest Path First)**  
  - Configured across all routers for dynamic route advertisement.  
  - **MD5 authentication** enabled for secure adjacencies.  
  - Loopback interfaces used as **stable router IDs**.  
  - Passive interfaces applied to LAN-facing ports.  

- **IP Addressing Scheme**  
  - Backbone WAN links: `10.0.0.0/24`, `10.0.12.0/24`.  
  - Data Centers, Call Centers, and branch LANs: custom `/24` subnets.  
  - Addressing designed for **clarity, non-overlap, and scalability**.  

---

### Switching & VLANs
- **VLAN segmentation** for Call Centers (Voice/Data separation).  
- Trunking configured between distribution switches and routers.  
- Access ports mapped to VLANs for end devices.  
- Multilayer switching at Nairobi Data Center for inter-VLAN routing.  

---

### Security
- **OSPF MD5 Authentication** (routing plane security).  
- **SSH-only remote access**, Telnet disabled.  
- **VTY & console password protection** with login authentication.  
- **MOTD banners** for legal/security compliance.  
- Passive interfaces to **eliminate unnecessary routing advertisements**.  

---

### Documentation & Pragmatism
- Clean, modular CLI configuration files (`command.txt`).  
- Clear hostname and VLAN naming conventions.  
- Logical addressing aligned with real enterprise ISP deployments.  
- Design principles inspired by **Cisco CCNA/CCNP best practices**.  

---


## 🌟 Why This Project Stands Out

Unlike a basic Packet Tracer lab, this project integrates **advanced enterprise features**:  

- Secure OSPF with MD5 (rarely seen in student labs).  
- Proper VLAN segmentation with trunking and access ports.  
- Passive interfaces for noise reduction and routing efficiency.  
- Device hardening (SSH, banners, passwords).  


> ⚡ The goal was not just to “make it work” — but to **mirror how a real ISP like "Safaricom" would deploy, document, and secure their network**. This reflects my **pragmatism, attention to detail, and readiness for real-world roles**.

---

 Future Improvements
- Redundancy with **HSRP/VRRP** for gateway failover.  
- QoS for **voice/video prioritization** in Call Centers.  
- **Access Control Lists (ACLs)** for traffic filtering.  
- Integration with a **DHCP server** for dynamic host IP assignment.  
- Migration plan to **IPv6 dual-stack**.  

---

## 🧑‍💻 Author - **BRADLEY GOVANNI**    

 Network Engineer | CCNA-Level Projects | Passionate About ISP & Enterprise Infrastructure 

 EMAIL : giovanniibradley@gmail.com

 [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/bradley-giovanniii293) 

