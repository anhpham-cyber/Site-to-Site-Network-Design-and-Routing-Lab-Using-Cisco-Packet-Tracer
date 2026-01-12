# Site-to-Site Network Lab (Calgary–Edmonton) – Cisco Packet Tracer

## Overview
This repository contains a series of Cisco Packet Tracer labs demonstrating the design and configuration of a **two-site network** between Calgary and Edmonton. The labs cover fundamental networking concepts including **IP addressing, Layer 2 switching, Layer 3 routing, static routing, and dynamic routing protocols (RIPv2, OSPF, and EIGRP).**

Each routing method is configured and verified **independently** to demonstrate connectivity and protocol functionality.

---

## Lab Objectives
By completing these labs, the following objectives are achieved:

- Design and implement a two-site network topology using Cisco Packet Tracer  
- Configure PCs, switches, and routers to enable connectivity  
- Assign IPv4 addresses and default gateways  
- Implement **static routing** for basic connectivity  
- Deploy **dynamic routing protocols**: RIPv2, OSPF, and EIGRP  
- Verify end-to-end connectivity between devices  
- Understand routing concepts such as distance-vector vs link-state 

---

## Repository Contents
| File / Folder | Description |
|---------------|-------------|
| `Step1_DevicePlacement.pkt` | Packet Tracer file showing PC, switch, and router placement |
| `Step2_ConnectDevices.pkt` | Connections between PCs, switches, and routers |
| `Step3_IPConfiguration.pkt` | IP addressing for PCs and default gateways |
| `Step4_RouterInterfaces.pkt` | Router interface configuration for LANs and inter-router links |
| `Step5.1_StaticRouting.pkt` | Static routing configuration |
| `Step5.2_RIPv2.pkt` | RIPv2 configuration and verification |
| `Step5.3_OSPF.pkt` | OSPF configuration and verification |
| `Step5.4_EIGRP.pkt` | EIGRP configuration and verification |

---

## Network Topology
- **Calgary Site:** PC1 → Switch1 → Router_Calgary  
- **Edmonton Site:** PC2 → Switch2 → Router_Edmonton  
- **Router-to-Router Link:** Routers are connected to enable inter-site communication  

---

## Usage
1. Open the `.pkt` file in **Cisco Packet Tracer**.  
2. Follow the step-by-step configuration instructions for each routing method.  
3. Use `ping` and `show ip route` commands to verify connectivity.  
4. Screenshots in the `Screenshots/` folder show expected results for reference.  

---

## Key Concepts Demonstrated
- IP addressing and subnetting  
- Layer 2 switching  
- Layer 3 routing  
- **Static routing**  
- Dynamic routing protocols: **RIPv2, OSPF, EIGRP**  
- Administrative Distance and path selection  
- End-to-end connectivity verification  

---

## Author
Duc Anh Pham 


