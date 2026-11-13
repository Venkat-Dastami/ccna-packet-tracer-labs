# Networking Fundamentals & Subnetting Practice

This section documents the **theory, calculations, and design work** completed before and alongside the Cisco Packet Tracer labs.

## Topics Practiced

- OSI model and TCP/IP model
- Unicast, multicast, and broadcast communication
- IPv4 32-bit addressing and dotted-decimal notation
- Binary-to-decimal and decimal-to-binary conversion
- Historical Class A, B, and C addressing concepts
- CIDR notation and prefix lengths
- Network and host portions of an IPv4 address
- Subnet masks
- Network IDs and broadcast IDs
- Usable host ranges
- Subnet increments / block sizes
- Subnetting with /24, /25, /26, /27, /28, and /30
- Larger Class A and Class B subnetting examples
- Fixed-length subnetting concepts
- Variable Length Subnet Masking (VLSM)
- Largest-subnet-first VLSM allocation
- Point-to-point /30 subnet design
- Department-based address planning for different host requirements
- Static-route destination networks and next-hop selection
- Floating / backup static-route concepts
- DHCP pool and default-gateway troubleshooting

## Example Workflow Practiced

1. Determine the number of hosts required.
2. Select an appropriate prefix length.
3. Calculate the subnet mask.
4. Identify the network ID.
5. Identify the broadcast ID.
6. Determine the usable host range.
7. Assign router and host addresses.
8. Configure the topology in Cisco Packet Tracer.
9. Add routing or DHCP as required.
10. Verify connectivity and troubleshoot failures.

## Key Subnetting Reference

| Prefix | Subnet Mask | Total Addresses | Usable Hosts* |
|---|---|---:|---:|
| /24 | 255.255.255.0 | 256 | 254 |
| /25 | 255.255.255.128 | 128 | 126 |
| /26 | 255.255.255.192 | 64 | 62 |
| /27 | 255.255.255.224 | 32 | 30 |
| /28 | 255.255.255.240 | 16 | 14 |
| /30 | 255.255.255.252 | 4 | 2 |

\*Traditional IPv4 subnet host counts excluding the network and broadcast addresses.

## Notes on Classful Addressing

Class A, B, and C addressing was practiced as background for understanding IPv4 and subnetting. Modern networks primarily use **CIDR (Classless Inter-Domain Routing)** rather than classful addressing.

## Troubleshooting Practice

The handwritten exercises also included diagnosing issues such as:

- Incorrect subnet masks
- Wrong default gateways
- Incorrect static-route next hops
- DHCP pool configuration errors
- Addressing mismatches between connected networks
- Failed end-to-end connectivity

This theory work supports the Packet Tracer labs in the other folders by showing the addressing and routing calculations behind the configurations.
