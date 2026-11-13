# CCNA 200-301 Packet Tracer Labs

Hands-on Cisco Packet Tracer labs created while preparing for the **Cisco CCNA 200-301** certification.

This repository documents practical work with IPv4 addressing, subnetting, VLSM, routing protocols, VLANs, inter-VLAN routing, Spanning Tree Protocol, access control lists, remote device access, and network troubleshooting.

> **Status:** CCNA 200-301 in progress

## Lab Portfolio

| # | Topic | Packet Tracer Lab |
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

## Skills Practiced

- Cisco IOS CLI
- IPv4 addressing and subnetting
- Variable Length Subnet Masking (VLSM)
- Point-to-point subnet design
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
- Connectivity verification and troubleshooting

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

The labs also include troubleshooting of issues such as incorrect addressing, subnet masks, default gateways, DHCP configuration, interface state, static-route next hops, and end-to-end reachability.

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
└── 09-acls/
```

## Opening the Labs

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
