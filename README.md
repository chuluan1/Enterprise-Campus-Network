# Enterprise Campus Network Design using Cisco IOS & EVE-NG
## Overview
This project simulates a small enterprise network using Cisco IOS in EVE-NG.
The network is designed with security, scalability and maintainability in mind. It includes VLAN segmentation, dynamic routing, network address translation, remote management and Layer 2 redundancy technologies.
## Objectives
- Design an enterprise network
- Implement VLAN segmentation
- Configure Inter-VLAN Routing
- Deploy OSPF Multi-Area
- Provide Internet access using NAT/PAT
- Secure the network with ACL and Port Security
- Enable remote management using SSH
## Topology
<img width="1342" height="702" alt="image" src="https://github.com/user-attachments/assets/2809cf5b-8616-49a7-a494-14686317cc42" />
## IP Addressing Plan
| VLAN | Department | Network         | Gateway      |
| ---- | ---------- | --------------- | ------------ |
| 10   | Sales      | 192.168.10.0/24 | 192.168.10.1 |
| 20   | HR         | 192.168.20.0/24 | 192.168.20.1 |
| 30   | IT         | 192.168.30.0/24 | 192.168.30.1 |
| 40   | Guest      | 192.168.40.0/24 | 192.168.40.1 |
## Devices
| Device  | Role                 |
| ------- | -------------------- |
| R1      | Internet Edge Router |
| R2      | Core Router          |
| SW1     | Access Switch        |
| SW2     | Access Switch        |
## Technologies
VLAN
802.1Q Trunk
Router-on-a-Stick
Static IP Addressing
OSPF Multi-Area
NAT/PAT
SSH
Standard ACL
Extended ACL
STP
EtherChannel (LACP)
Port Security
## Verification
| Feature            | Status |
| ------------------ | ------ |
| Inter-VLAN Routing | Đ      |
| Internet Access    | Đ      |
| OSPF Neighbor      | Đ      |
| SSH Login          | Đ      |
| ACL Filtering      | Đ      |
| Port Security      | Đ      |
| EtherChannel       | Đ      |
| STP                | Đ      |
## Common Issues
| Issue              | Solution              |
| ------------------ | --------------------- |
| OSPF Neighbor Down | Check Area & Wildcard |
| Internet Failed    | Check NAT             |
| Ping Failed        | Check VLAN & Trunk    |
| SSH Failed         | Check VTY & ACL       |
## Result
Successfully implemented a secure enterprise network using Cisco IOS and EVE-NG.
