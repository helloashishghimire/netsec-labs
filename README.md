# 🛡️ NetSec Labs — Enterprise Networking & Network Security Projects

> **Hands-on labs for mastering enterprise computer networking, network security, VPNs, firewalling, routing, and automation.**
>
> Real networks. Real configs. Real troubleshooting.

---

## 📌 Overview

This repository documents my journey in building **production-style network architectures** using:

- **Routing protocols:** OSPF, EIGRP, BGP, RIP v2
- **Network security:** IPsec VPN, ACLs, Firewalls, Segmentation
- **Switching:** VLANs, trunking, EtherChannel, STP
- **Automation:** Python, Ansible, Bash, Netmiko/Paramiko/Nornir
- **Tools:** EVE-NG, GNS3, VMware, Wireshark

Each lab contains:

✅ Network topology diagram  
✅ Step-by-step configuration  
✅ Troubleshooting + verification commands  
✅ Final working config files  

Goal: Build real-world engineer muscle memory.

---

## 📂 Repository Structure

netsec-labs/
│
├── routing/
│ ├── ospf/
│ ├── eigrp/
│ ├── bgp/
│ └── redistribution/
│
├── switching/
│ ├── vlans/
│ ├── trunking/
│ ├── etherchannel/
│ └── spanning-tree/
│
├── security/
│ ├── ipsec-site-to-site/
│ ├── zone-based-firewall/
│ ├── acl-control/
│ └── segmentation/
│
├── automation/
│ ├── ansible/
│ ├── python-netmiko/
│ ├── python-nornir/
│ └── terraform/
│
└── docs/
├── diagrams/
└── runbooks/


---

## 🔥 Featured Labs (Coming Soon)

| Lab Name | Category | Tools Used |
|----------|----------|------------|
| **Site-to-Site IPsec VPN** | Security | Cisco IOS, EVE-NG |
| **Multi-Area OSPF + BGP Redistribution** | Routing | EVE-NG, Wireshark |
| **DMZ / Server Segmentation with ACL + ZBF** | Firewall | Cisco IOS |
| **Ansible Network Automation** | Automation | Ansible, Python |
| **WAN + Datacenter Design with High Availability** | Architecture | EVE-NG |

---

## ✨ What You Will Learn

- Build complex routing topologies (enterprise-grade)
- Secure networks with firewalls, zone policies & ACLs
- Automate router/switch configs using Ansible + Python
- Troubleshoot routing/security issues like a real engineer

> **Every lab ends with:**
> - *"What broke?"*
> - *"How I fixed it."*

Because troubleshooting skills = job security.

---

## 🛠 Tools & Technologies

| Category | Tools |
|----------|------|
| Network Simulators | EVE-NG, GNS3 |
| Security | IPsec, ACLs, Zone-Based Firewall, AAA |
| Routing & Switching | BGP, OSPF, EIGRP, VLANs, STP |
| Automation | Python, Ansible, Netmiko, Nornir |
| Monitoring & Verification | Wireshark, SNMP |

---

## 🧠 Goals of This Repository

- Become a **Network Security Engineer**
- Build projects to showcase on **GitHub + LinkedIn**
- Develop muscle memory through **repetition + troubleshooting**
- Create labs that are **resume and interview ready**

---

## 🚀 Roadmap

- [ ] IPsec Site-to-Site VPN Lab
- [ ] Multi-Protocol Redistribution (OSPF + BGP + EIGRP)
- [ ] Zone-Based Stateful Firewall Deployment
- [ ] Device Hardening (SSH, AAA, RSA)
- [ ] Full automation of router configs (Ansible + Python)



## ⭐ How to Use

1. Clone the repo  
2. Import topology file (`.unl` / `.gns3`) into EVE-NG or GNS3  
3. Follow the lab guide in the directory  
4. Try to solve troubleshooting scenarios  
5. Commit your own configs — **learn by breaking things**

---

## 📬 Feedback / Suggestions

If you have ideas for improvements or want to collaborate:

📫 Open an **issue** or **Pull Request**

---

### 🧑‍💻 Author

Ashish Ghimire 
*Network + Cybersecurity + DevOps Enthusiast*

---

### ⭐ Support

If this repo helps you, consider giving it a ⭐ on GitHub — it motivates me to build more labs.

---

> “You don’t learn networking by watching videos —  
> **you learn by breaking networks and fixing them again.**”
