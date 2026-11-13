# CCNA 200-301 Networking & Packet Tracer Lab Portfolio

Hands-on networking practice created while preparing for the **Cisco CCNA 200-301** certification.

This repository combines **manual networking calculations and design work** with Cisco Packet Tracer labs. It documents IPv4 addressing, binary conversion, subnetting, CIDR, VLSM, routing, switching, access control, and troubleshooting.

> **Status:** CCNA 200-301 in progress

## Lab Portfolio

| # | Topic | Practice |
|---|---|---|
| 01 | Static Routing | 4 Router Topology |
| 02 | VLSM | Point-to-Point Subnet Topology |
| 03 | RIP | Configuring RIP |
| 04 | EIGRP | EIGRP Configuration Topology |
| 05 | OSPF | OSPF Configuration + Backbone Area |
| 06 | VLANs | Creating and Managing VLANs |
| 07 | Inter-VLAN Routing | SVI and Router-on-a-Stick (ROAS) |
| 08 | STP | Spanning Tree Protocol |
| 09 | ACLs | Standard ACLs + Extended ACLs with Telnet |
| 10 | Networking Fundamentals | IPv4, Binary, CIDR, Subnetting, VLSM & Routing Calculations |

## Networking Fundamentals Practiced

Before and alongside Packet Tracer configuration, I worked through networking concepts and calculations by hand, including:

- OSI and TCP/IP models
- Unicast, multicast, and broadcast
- IPv4 32-bit addressing
- Binary-to-decimal and decimal-to-binary conversion
- Historical Class A/B/C concepts
- CIDR and prefix lengths
- Network and host portions
- Subnet masks
- Network IDs and broadcast IDs
- Usable host ranges
- Subnet increments / block sizes
- /24, /25, /26, /27, /28, and /30 subnetting
- Larger Class A and Class B subnetting exercises
- VLSM and largest-subnet-first allocation
- Point-to-point /30 addressing
- Department-based network design
- Static-route next-hop planning
- Floating / backup static-route concepts
- DHCP and default-gateway troubleshooting

## Cisco Packet Tracer Skills Practiced

- Cisco IOS CLI
- IPv4 addressing and subnetting
- VLSM
- DHCP
- Static and default routing
- RIP
- EIGRP
- OSPF
- VLAN creation and access-port assignment
- 802.1Q trunking
- Inter-VLAN routing using SVI and Router-on-a-Stick
- Spanning Tree Protocol (STP)
- Standard and extended ACLs
- Telnet access-control scenarios
- Multi-router and multi-switch troubleshooting

## Troubleshooting & Verification

Commands used throughout the labs include:

```text
show ip interface brief
show ip route
show running-config
show vlan brief
show interfaces trunk
show ip ospf neighbor
ping
traceroute
```

Troubleshooting practice included incorrect addressing, subnet masks, default gateways, DHCP configuration, interface state, static-route next hops, and end-to-end reachability.

## Learning Approach

My workflow has been:

```text
Networking fundamentals
        ↓
IPv4 + Binary
        ↓
Subnetting + CIDR
        ↓
VLSM
        ↓
Router/interface configuration
        ↓
DHCP
        ↓
Static/default/floating routes
        ↓
Dynamic routing
RIP → EIGRP → OSPF
        ↓
Switching
VLANs → Trunks → Inter-VLAN → STP
        ↓
Security
ACLs
        ↓
Troubleshooting
ping / traceroute / show commands
```

## Repository Structure

```text
ccna-packet-tracer-labs/
├── 01-static-routing/
├── 02-vlsm/
├── 03-rip/
├── 04-eigrp/
├── 05-ospf/
├── 06-vlans/
├── 07-inter-vlan-routing/
├── 08-stp/
├── 09-acls/
└── 10-networking-fundamentals/
```

## Opening the Packet Tracer Labs

1. Install **Cisco Packet Tracer**.
2. Download the desired `.pkt` file.
3. Open it in Packet Tracer.
4. Inspect the topology and device configurations.
5. Use Simulation Mode, `ping`, `traceroute`, and Cisco IOS verification commands to test connectivity.

## About

I am developing hands-on networking and troubleshooting skills while preparing for CCNA 200-301, with a career focus on technical support, network support, and systems administration.

---

**Author:** Venkat Dastami  
**GitHub:** [Venkat-Dastami](https://github.com/Venkat-Dastami)
