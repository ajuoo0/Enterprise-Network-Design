# MAGIC Technologies – Enterprise Network Design

## 1. Project Overview

This project demonstrates the design and implementation of a multi-site enterprise network for a fictional company named **MAGIC Technologies**, using Cisco Packet Tracer.

The network connects a Head Office (HQ) and two branch offices through an ISP network. It demonstrates practical enterprise networking concepts, including network segmentation, dynamic routing, redundancy, network services and security.

## 2. Network Topology

The enterprise network consists of:

- One Head Office (HQ)
- Two Branch Offices
- An ISP network connecting the sites
- Centralized network services

### Network Topology Diagram
![MAGIC Technologies Network Topology](Topology/enterprise-topology.png)


## 3. Device Inventory

| Device              | Quantity | Model / Purpose                   |
| ------------------- | -------: | --------------------------------- |
| Routers             |        4 | Cisco 2911 (3 enterprise + 1 ISP) |
| Multilayer Switches |        2 | Cisco 3560-24PS                   |
| Access Switches     |        6 | Cisco 2960-24TT                   |
| PCs                 |       22 | End-user devices                  |
| Servers             |        2 | DHCP and FTP services             |

## 4. Technologies Implemented

### Network Segmentation

- VLAN creation and configuration
- VLAN-based network segmentation
- Access and trunk port configuration

### Routing and Switching

- Inter-VLAN routing
- Layer 2 and Layer 3 switching
- OSPF dynamic routing
- EtherChannel
- Rapid PVST+

### Network Redundancy

- HSRP gateway redundancy
- EtherChannel link aggregation
- Rapid PVST+ loop prevention

### Network Services

- DHCP server configuration
- DHCP Relay configuration
- FTP server configuration

### NAT and Internet Connectivity

- Network Address Translation (NAT)
- Port Address Translation (PAT)

### Network Security

- Standard ACLs
- Extended ACLs
- Switch Port Security
- DHCP Snooping
- Dynamic ARP Inspection (DAI)

## 5. Project Files

The repository contains the following project resources:

| File / Folder             | Description                                 |
| ------------------------- | ------------------------------------------- |
| Packet Tracer `.pkt` file | Complete simulated enterprise network       |
| `Topology/`               | Network topology diagram                    |
| `Configurations/`         | Router and multilayer switch configurations |

### Configuration Files

- `isp.txt` – Router 1 configuration
- `R2.txt` – Router 2 configuration
- `MLS1.txt` – Multilayer Switch 1 configuration
- `MLS2.txt` – Multilayer Switch 2 configuration

## 6. Verification and Testing

The completed lab was tested through practical network configuration and connectivity checks, including:

- VLAN and inter-VLAN connectivity
- Dynamic routing between network segments and sites
- Redundancy configuration
- DHCP address allocation and relay
- NAT/PAT connectivity
- Network access control and Layer 2 security features

## 7. Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## 8. Project Status

**Completed**

This project was built as a hands-on networking lab to develop practical knowledge of enterprise network design, configuration, troubleshooting and security.

---

**Author:** Ajnas VP
**Project:** Enterprise Network Design – MAGIC Technologies
**Platform:** Cisco Packet Tracer
