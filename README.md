# Cisco-Packet-Tracer-project-12-Multi-Switch-Campus-Network-7-Switches-2911-Router-Multiple-Subnets

I’m happy to share my latest Cisco Packet Tracer project – a multi‑switch campus network featuring a Cisco 2911 router, seven 2960 switches, and multiple PCs spread across different subnets (192.168.20.100 and 192.168.30.100).

![image alt](https://github.com/Sameera54321/Cisco-Packet-Tracer-project-12-Multi-Switch-Campus-Network-7-Switches-2911-Router-Multiple-Subnets/blob/main/17.jpg?raw=true)

## 📌 Summary

### Multi‑Switch Campus Network is a Cisco Packet Tracer simulation that models a medium‑sized campus or building distribution network. The topology includes:

    1 router – Cisco 2911 (acts as the gateway for inter‑VLAN routing)

    7 switches – Cisco 2960‑24TT (access layer switches connecting end devices)

    3+ PCs – PC0, PC1, PC3 with IPs in 192.168.20.0/24 and 192.168.30.0/24 (more PCs can be added)

### The project focuses on:

    Router‑on‑a‑stick – configuring subinterfaces on the router for each VLAN

    VLAN creation – e.g., VLAN 20 for 192.168.20.0/24, VLAN 30 for 192.168.30.0/24

    Trunk configuration – between router and first switch, and between switches

    Access port assignment – each PC connected to a switch port in the correct VLAN

    Inter‑VLAN routing verification – pinging from 192.168.20.100 to 192.168.30.100

    Spanning‑Tree Protocol (STP) – to prevent loops in the multi‑switch topology

## ✨ Features

    ✅ 1 router (2911) – inter‑VLAN routing via subinterfaces

    ✅ 7 switches (2960) – access layer with trunking and STP

    ✅ Multiple subnets – 192.168.20.0/24 and 192.168.30.0/24 (expandable)

    ✅ VLANs – e.g., VLAN 20, VLAN 30 (or as configured)

    ✅ Trunking (802.1Q) – between router and switches, and switch‑to‑switch

    ✅ End devices – PCs with static IPs (or DHCP possible)

    ✅ Full Packet Tracer file (.pkt) – ready to open and practice

    ✅ Documentation – VLAN mapping, trunk ports, router subinterface configs, switch configs

### Suggested VLAN & IP Assignment :

| VLAN | Subnet | Gateway (Router subinterface) | Example PC IP |
| :--- | :--- | :--- | :--- |
| 10 | 192.168.10.0/24 | 192.168.10.1 | 192.168.10.100 |
| 20 | 192.168.20.0/24 | 192.168.20.1 | 192.168.20.100 |
| 30 | 192.168.30.0/24 | 192.168.30.1 | 192.168.30.100 |
| 40 | 192.168.40.0/24 | 192.168.40.1 | 192.168.40.100 |
| 99 | 192.168.99.0/24 | 192.168.99.1 | 192.168.99.100 |

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – router and switch configurations

## 🤝 Contributing

### Contributions are welcome! To extend this lab:

    Fork the repository.

    Add more VLANs (e.g., VLAN 10 for HR, VLAN 40 for servers).

    Implement VTP (VLAN Trunking Protocol) to manage VLANs across all seven switches.

    Add EtherChannel (port aggregation) between switches for higher bandwidth.

    Configure DHCP server on the router to assign IPs to all PCs.

    Introduce access control lists (ACLs) to restrict traffic between VLANs.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
