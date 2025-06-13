# SOHO Network Design and Implementation using Cisco Packet Tracer

This project is a part of my **Networking Basics** course and demonstrates the design and implementation of a small office/home office (SOHO) network using **Cisco Packet Tracer**. It includes IPv4 and IPv6 configuration, dynamic IP addressing with DHCP, inter-VLAN routing, and wireless connectivity.

---

## 🧠 Objective

To design and simulate a real-world network for a growing company (**XYZ LLC**) that improves communication efficiency and scalability by:
- Segmenting the network for each department.
- Routing between departments.
- Assigning IP addresses (static and dynamic).
- Integrating wireless and internet access.

---

## 🏢 Scenario: XYZ LLC Network Upgrade

XYZ LLC is expanding and currently operates all devices under a single IP network. This causes inefficiencies and network delays. The proposed solution:
- Separates networks by department (Admin, Sales, etc.).
- Implements routing for inter-department communication.
- Uses a combination of wired and wireless devices.
- Simulates real-world connectivity and traffic flow.
- Adds DHCP configuration to automate IP address assignment.

---

## 🧱 Devices Used

| Device             | Purpose                         |
|--------------------|----------------------------------|
| PCs (Admin/Sales)  | Department end-devices           |
| Switches           | Connect PCs within each department |
| Router             | Enable communication between departments |
| Wireless Router    | Provide wireless access to mobile devices |
| Laptop & Smartphone| Wireless end devices                 |
| ISP Cloud          | Simulated internet connection    |

---

## 🔌 Connections Used

- Copper Straight-Through: PC to Switch, Switch to Router
- Wireless connections:Laptop and Smartphone automatically connect to the Wireless Router
- Configuration:All physical and wireless connections were manually configured in Cisco Packet Tracer workspace

---

## 🔧 Configuration Overview

### IPv4 Addressing (Static)
Each PC is manually assigned:
- **IP Address**: e.g., `192.168.10.10`
- **Subnet Mask**: `255.255.255.0`
- **Default Gateway**: Router interface IP

### Router Configuration
- Assigned IP addresses to router ports
- Enabled interfaces using `no shutdown` command
- Verified routing using `ping` and command-line tools

---

## ✅ Results

- Successful communication between devices in the same and different departments.
- Packets routed correctly using configured IP addresses and gateways.
- Default gateway used to forward traffic to other networks.

---
## 📦 Files Included

- `.pkt` file with the full Packet Tracer simulation

 ---
  
## 🧑‍💻 Skills Demonstrated

- Basic network design
- IP addressing (static and DHCP)
- Subnetting and network segmentation
- Router and switch configuration
- Use of Cisco Packet Tracer for simulation
- Troubleshooting network issues

---

## 📝 Notes

- IP addresses like `192.168.x.x` are **private IPs** used within local networks.
- The subnet mask `255.255.255.0` defines how many IPs are available in each subnet.
- The default gateway is the router IP that sends traffic to other networks.

---

