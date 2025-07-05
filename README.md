# 🌐 CCNA Network Project: VLANs & Routing 🚀

A clean Cisco Packet Tracer lab covering VLANs, Inter-VLAN Routing, and ACLs — perfect for hands-on CCNA practice! 🖥️

---

## 🎯 Features

- 🏢 **VLAN Setup**: Two VLANs (Sales - VLAN 10, IT - VLAN 20)  
- 🔄 **Inter-VLAN Routing**: Router-on-a-stick configuration  
- 🔒 **Access Control**: ACL to restrict VLAN-to-VLAN communication  
- ✅ **Testing**: Ping tests & simulation in Packet Tracer  

---

## 🖼️ Photos
<p align="center">
  <img src="images/scale-lan.jpg" width="500" alt="Diagram" />
  
## Devices:
- 1 Router (Cisco 2811) 🖧
- 1 Switch (Cisco 2950-24) 🔌
- 4 PCs (2 per VLAN) 💻

Connections: Trunk link between switch and router 🌉

---

## 🧱 Devices & Connections

- 🖧 1 Router (Cisco 2811)  
- 🔌 1 Switch (Cisco 2950-24)  
- 💻 4 PCs (2 in each VLAN)  
- 🌉 Trunk connection between Switch & Router 

## 📶 IP Addressing

- **VLAN 10 (Sales)**: `192.168.10.0/24`  
- **VLAN 20 (IT)**: `192.168.20.0/24`

---

## 📋 Requirements

- 🛠️ Cisco Packet Tracer (v8.2 or later)  
- 📥 Git (to clone the repo)  
- 📝 A Markdown editor like VS Code  

---

## 🚀 Quick Start

git clone [https://github.com/HeidarAli83h/LAN-Simulation-with-VLANs-Routing-Sample-ACL]

# Open the project file
Open `network.pkt` in Packet Tracer

# Check configurations
View `router_config.txt` and `switch_config.txt` for CLI configs

---

## ⚙️ Configuration Files

- network.pkt: Packet Tracer file 📂
- photo.jpg: Topology diagram 🖼️
- switch_config.txt: Switch configs 📜
- router_config.txt: Router configs 📜

---

## 🧪 Testing

Ping:
- PC1 (VLAN 10) → PC2 (VLAN 10): ✅ Success
- PC1 → PC3 (VLAN 20): 🚫 Blocked by ACL
- PC3 → PC1: ✅ Success

---

## Verify:
- Switch: show vlan brief 📋
- Router: show ip route 🗺️
- Router: show access-lists 🔒


Use Packet Tracer’s Simulation Mode to trace packets. 🔍


## 💡 Motivation
"Take the leap and build your skills—your network, your rules!" 🌟

## 👨‍💻 Author
Created by **HeidarAli** – Future CCNP & DevNet Pro! 🌐

## 📜 License
[MIT License 📄]

🌟 Thanks for checking out this project! Questions? Open an issue! 😊
