# Secure Three-Tier Enterprise Network Architecture – Cisco Packet Tracer Simulation

This project showcases the design and simulation of a robust, secure, and scalable three-tier enterprise network using Cisco Packet Tracer. The network architecture incorporates the access, distribution, and core layers, linking a headquarters and branch office with an emphasis on reliability, security, and fault tolerance.

## Architecture Overview

### Access Layer:
- Eight Layer 2 switches configured with VLAN segmentation, Spanning Tree, and ACL.

### Distribution Layer:
- Four multilayer switches implementing LACP for load balancing and enabling inter-VLAN routing.

### Core Layer:
- Hosts essential services such as DNS, DHCP, web and mail servers, Syslog, SNMP, and NTP.

## Key Network Features

- VLANs combined with VTP for efficient network segmentation and management.
- DHCP services with relay agents for dynamic IP addressing.

## Routing Protocols Utilized

- OSPF at HQ and Branch Offices
- BGP for Internet routing with ISP

## Security Implementations

- Access Control Lists (ACLs) for traffic filtering
- VPN tunnels securing communication between HQ and branch

## Redundancy and Load Balancing Strategies

- EtherChannel (LACP) aggregates multiple links for bandwidth and redundancy

## Additional Functionalities

- Wireless connectivity via Wireless Access Points (WAPs) with DHCP support

## Tools Used

- Cisco Packet Tracer for simulation and design

## Testing Scenarios

- Secure PC-to-PC communication between HQ and Branch through VPN
- DNS lookups
- Email transmission using SMTP
- Access to internal web pages
- Logging and monitoring through Syslog and SNMP hostname updates

## Conclusion

This simulation demonstrates how a layered network architecture, combined with dynamic routing protocols and security practices, results in a robust and scalable enterprise network. The design ensures confidentiality, integrity, and availability while maintaining flexibility for future expansion.
