# Secure Three-Tier Enterprise Network Architecture – Cisco Packet Tracer Simulation

This project showcases the design and simulation of a robust, secure, and scalable three-tier enterprise network using Cisco Packet Tracer. The network architecture incorporates the access, distribution, and core layers, linking a headquarters and branch office with an emphasis on reliability, security, and fault tolerance.

## Architecture Overview

- **Access Layer:**  
  Six Layer 2 switches configured with port security, VLAN segmentation, BPDU Guard, and PortFast.

- **Distribution Layer:**  
  Four multilayer switches implementing HSRP for load balancing and enabling inter-VLAN routing.

- **Core Layer:**  
  Hosts essential services such as DNS, DHCP, web and mail servers, Syslog, SNMP, AAA, and NTP.

## Key Network Features

- VLANs combined with VTP for efficient network segmentation and management.  
- DHCP services with relay agents for dynamic IP addressing.

### Routing Protocols Utilized

- EIGRP at Headquarters  
- OSPF at Branch Office  
- BGP for Internet routing with ISP

### Security Implementations

- Access Control Lists (ACLs) for traffic filtering  
- Network Address Translation (NAT)  
- VPN tunnels securing communication between HQ and branch  
- AAA framework for user authentication and authorization

## Redundancy and Load Balancing Strategies

- HSRP ensures gateway redundancy and failover  
- EtherChannel (LACP) aggregates multiple links for bandwidth and redundancy

## Additional Functionalities

- Wireless connectivity managed via Wireless LAN Controller (WLC) with DHCP support  
- Firewall rules controlling traffic between internal networks and external internet

## Tools Used

- Cisco Packet Tracer for simulation and design

## Testing Scenarios

- Secure PC-to-PC communication between HQ and Branch through VPN  
- DNS lookups  
- Email transmission using SMTP  
- Access to internal web pages  
- Logging and monitoring through Syslog and SNMP hostname updates

## Conclusion

This simulation highlights how a multi-layered network design combined with contemporary routing protocols and security practices can build a dependable and scalable enterprise network. The architecture supports confidentiality, availability, and integrity, while remaining adaptable for future growth.
