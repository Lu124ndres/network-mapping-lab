# network-mapping-lab
Network Mapping &amp; Scanning Lab A personal cybersecurity project focused on host discovery, port scanning, and traffic analysis using Nmap and Wireshark. The goal is to understand how devices communicate in a local network and how network mapping can support defensive cybersecurity analysis.

# 🧠 Network Mapping & Scanning Lab

This project focuses on **network discovery, port scanning, and traffic analysis** using **Nmap** and **Wireshark**.  
It was created as part of my cybersecurity learning path to understand how hosts, ports, and services operate within a local network and how network mapping supports threat detection and defensive analysis.

---

## 🎯 Objectives

- Identify all active devices within a local network.  
- Perform port and service scanning using **Nmap**.  
- Analyze generated traffic with **Wireshark**.  
- Document discovered hosts, open ports, and communication patterns.  
- Strengthen foundational knowledge in network security and ethical hacking.

---

## ⚙️ Environment Setup

### 🖥️ Option A — Virtual Lab (Recommended)
- **Attacker machine:** Kali Linux (includes Nmap preinstalled).  
- **Target machine:** Ubuntu or Metasploitable 2 (with open services).  
- Connect both to a **Host-Only** or **Internal Network** in VirtualBox/VMware.  

### 🖥️ Option B — Home Network
- Run Nmap from your main PC on your home router’s IP range.  
- Example:
  ```bash
  nmap -sn 192.168.0.0/24
