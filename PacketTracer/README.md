 Accounts & Delivery Network

Project Overview
This project involves designing and simulating a small enterprise network using **Cisco Packet Tracer**.  
The network connects two departments — **ACCOUNTS** and **DELIVERY** — while ensuring proper IP addressing, device configuration, and successful end-to-end connectivity.

---

Objectives
- Design a functional network connecting two departments
- Use appropriate **routers and switches**
- Apply **subnetting** on the given network address
- Configure IP addresses, subnet masks, and default gateways
- Verify connectivity using **ICMP (ping)**

---

Network Requirements
- Two departments: **ACCOUNTS** and **DELIVERY**
- Each department contains **at least 2 PCs**
- Network address used: **192.168.40.0**
- Proper cabling between all devices
- PCs in DELIVERY must be able to **ping** PCs in ACCOUNTS

---
Subnetting Details

 Given:
- Network Address: `192.168.40.0`
- Number of Subnets Required: `2`


### Subnet Mask:
- Binary: `11111111.11111111.11111111.10000000`
- Decimal: **255.255.255.128 (/25)**

---

Subnet 1 – ACCOUNTS Department
- Network ID: `192.168.40.0`
- Subnet Mask: `255.255.255.128`
- Valid Host Range: `192.168.40.1 – 192.168.40.126`
- Broadcast Address: `192.168.40.127`


Subnet 2 – DELIVERY Department
- Network ID: `192.168.40.128`
- Subnet Mask: `255.255.255.128`
- Valid Host Range: `192.168.40.129 – 192.168.40.254`
- Broadcast Address: `192.168.40.255`

 Devices Used
- PCs (End devices)
- Cisco Switches
- Cisco Router
- Ethernet straight-through cables

Connectivity Testing
- Connectivity tested using "ping"
- PCs in the DELIVERY department successfully ping PCs in the ACCOUNTS department
- Confirms correct:
  - IP addressing
  - Routing
  - Physical connections

 How to Run the Project
1. Open the `.pkt` file using "Cisco Packet Tracer"
2. Power on all devices
3. Open any PC → Desktop → Command Prompt
4. Use `ping` to test connectivity between departments



### Calculation:

