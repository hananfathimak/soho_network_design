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

### IPv4 Addressing (Static & Dynamic)
- Static IP addresses assigned to selected PCs (e.g., 192.168.10.10)
- DHCP used to dynamically assign IPs to other end devices
- **Subnet Mask**: 255.255.255.0
- **Default Gateway**: Corresponding router interface IP


### Router Configuration
- Assigned IP addresses to router interfaces
- Configured DHCP pools for dynamic IP assignment
- Enabled interfaces using the `no shutdown` command
- Verified connectivity using `ping`, `tracert`, and command-line tools


---

## ✅ Results
- Successful communication between devices in the same and different departments.
- Packets routed correctly using configured IP addresses and gateways.
- DHCP successfully assigned IPs to 50+ PCs.
- Wireless and wired devices accessed the network and internet correctly.


---
## 📦 Files Included

- `.pkt` file with the full Packet Tracer simulation

 ---
  
## 🔒 Skills Demonstrated

- Designed basic LAN and inter-departmental network topology.
- Configured IP addressing using both Static and DHCP methods.
- Implemented subnetting and logical network segmentation.
- Configured routers and switches for department-level communication.
- Simulated network behavior using Cisco Packet Tracer.
- Diagnosed and resolved basic network connectivity issues.


---

## 📝 Notes

- IP addresses like `192.168.x.x` are **private IPs**, used within local networks and not routable on the internet.
- The subnet mask `255.255.255.0` allows up to 254 usable IP addresses per subnet.
- The **default gateway** is the router’s IP address that forwards traffic to external or other subnets.


---

