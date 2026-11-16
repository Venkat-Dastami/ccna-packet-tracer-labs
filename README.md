# CCNA Packet Tracer Lab Portfolio
**Venkat Dastami | Aspiring Junior Systems Administrator · Cloud Support Associate · Junior IT Systems Analyst**

## Project overview

Hands-on networking practice in Cisco Packet Tracer, developed while preparing for CCNA 200-301 and targeting Junior Systems Administrator, Cloud Support Associate, and Junior IT Systems Analyst roles. This portfolio connects IPv4 address planning with router and switch configuration, traffic control, and connectivity troubleshooting.

The repository contains **11 Packet Tracer files across nine lab folders**, plus networking-fundamentals notes. The index below summarizes the existing files and their accompanying documentation; it does not represent independently verified test results.

## Lab index

Each linked folder includes a README describing the practice and the listed `.pkt` files.

| Lab | Files | Documented focus |
|---|---|---|
| [01 · Static routing](01-static-routing/) | `4-router-topology.pkt` | Interface addressing, static/default routes, next hops, forward and return paths |
| [02 · VLSM](02-vlsm/) | `vlsm-point-to-point-subnet.pkt` | /25–/28 LANs, /30 links, static routing, DHCP/default-gateway troubleshooting |
| [03 · RIP](03-rip/) | `configuring-rip.pkt` | Route advertisement, learned routes, connectivity testing |
| [04 · EIGRP](04-eigrp/) | `eigrp-configuration-topology.pkt` | Process configuration, neighbors, network advertisement, routing tables |
| [05 · OSPF](05-ospf/) | `ospf-single-area-topology.pkt`; `ospf-backbone-area-topology.pkt` | Single-area configuration, wildcard masks, neighbors, backbone/multi-area concepts |
| [06 · VLANs](06-vlans/) | `creating-and-managing-vlans.pkt` | VLAN creation, access ports, membership, same-VLAN communication, trunk concepts |
| [07 · Inter-VLAN routing](07-inter-vlan-routing/) | `inter-vlan-routing-svi-roas.pkt` | SVIs, router-on-a-stick, 802.1Q subinterfaces, VLAN gateways |
| [08 · STP](08-stp/) | `stp-spanning-tree-protocol.pkt` | Root bridge, port roles, loop prevention, redundancy and convergence |
| [09 · ACLs](09-acls/) | `access-control-lists.pkt`; `extended-acl-telnet.pkt` | Standard/extended ACLs, permit/deny logic, placement, Telnet access control |
| [10 · Networking fundamentals](10-networking-fundamentals/) | Written notes; no separate `.pkt` file | OSI/TCP-IP models, binary conversion, IPv4/CIDR, subnetting, VLSM and address planning |

## Technologies and protocols practiced

- **Tools:** Cisco Packet Tracer and Cisco IOS CLI.
- **Addressing:** IPv4, CIDR, subnet masks, usable host ranges, VLSM and /30 point-to-point networks.
- **Routing:** Static/default routes, RIP, EIGRP and OSPF.
- **Switching:** VLANs, 802.1Q trunks, SVIs, router-on-a-stick and STP.
- **Services and traffic control:** DHCP/default-gateway troubleshooting, standard/extended ACLs and Telnet access-control scenarios.

## Troubleshooting skills demonstrated

The lab notes document practice identifying addressing and subnet-mask mismatches, incorrect default gateways, DHCP pool errors, missing or incorrect static-route next hops, and failed end-to-end connectivity. Switching and routing notes also cover VLAN membership, trunk links, learned routes and OSPF neighbor verification.

Verification commands documented in the repository include:

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

These exercises build a structured approach to support incidents: inspect addressing and interface state, follow the traffic path, review routing or VLAN configuration, and retest reachability.

## Relevance to my target roles

| Target role | Networking foundation demonstrated by this portfolio |
|---|---|
| Junior Systems Administrator | IPv4 addressing, default gateways, VLANs and routed connectivity provide a foundation for investigating server connectivity issues. |
| Cloud Support Associate | Subnet planning, routing and traffic-filtering concepts provide a foundation for learning cloud networking and diagnosing reachability. |
| Junior IT Systems Analyst | Address planning, topology review and configuration verification support structured analysis of connectivity problems. |

This repository documents networking simulations and fundamentals. Windows/Linux server administration and AWS/Azure deployments would require separate project evidence.

## Setup and review

1. Install Cisco Packet Tracer. The repository does not specify a required version.
2. Download this repository using **Code → Download ZIP**, or clone it:
   ```bash
   git clone https://github.com/Venkat-Dastami/ccna-packet-tracer-labs.git
   ```
3. Read the chosen lab's README and open its `.pkt` file in Packet Tracer.
4. Inspect the topology, endpoint addressing and device CLI configurations.
5. Use the relevant verification commands and connectivity tests; use Simulation Mode to follow packet flow. Save a separate copy before experimenting.

## Discussing the labs in systems and cloud-support interviews

Start with a specific lab and explain its purpose, the configuration you worked on, and how you checked it. For a troubleshooting example, describe **the symptom → checks → cause → change → retest**, using only an issue and outcome you can demonstrate.

- **Static routing/VLSM:** Explain how you check a client's address, mask and gateway, then trace next hops and the return path.
- **VLANs/inter-VLAN routing:** Explain how VLAN membership, trunks and gateways affect communication between devices.
- **ACLs:** Explain how you distinguish a reachability problem from traffic intentionally blocked by policy.

Bring a lab file to demonstrate your reasoning. Describe this work as simulated networking practice, and support any claimed fix or successful result with the actual configuration and test output.
