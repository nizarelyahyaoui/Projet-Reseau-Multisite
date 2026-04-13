# Advanced Network Security Configuration – Final Training Project (PFF 2025)

**Student:** EL YAHYAOUI Nizar  
**Group:** IDOSR 202  
**Institution:** Institut Spécialisé de Technologie Appliquée (ISTA) Lazaret  
**Base IP Address:** 192.168.36.0/22  

---

## Overview

This project is the Final Training Report (Projet de Fin de Formation) for the Digital Infrastructure – Systems & Networks program. It covers the design, configuration, and security hardening of a multi-site enterprise network built on Cisco equipment.

---

## Objectives

- Design and implement an IPv4 addressing plan across 3 sites
- Configure Layer 2 protocols: VTP, STP, EtherChannel (PAgP & LACP)
- Set up Inter-VLAN routing and dynamic routing with OSPFv2 (multi-area)
- Configure NAT (static, dynamic, PAT) and DHCP services
- Deploy a VoIP gateway with IP phone registration
- Implement Layer 2 security features including DHCP Snooping

---

## Network Architecture

The project simulates a real enterprise environment with 3 interconnected sites:

| Site | Domain | Key VLANs |
|------|--------|-----------|
| Site 1 | ENTREPRISEA.COM | VLAN 10, 20, 30 + DMZ + VPN |
| Site 2 | ENTREPRISEB.COM | VLAN 50, 60 |
| Site 3 | Agency 1 | VLAN 70 (Voice), 80 (Data) |

---

## Technologies Used

| Category | Technologies |
|----------|-------------|
| Routing | OSPFv2 Multi-Area, Inter-VLAN, Static Routes |
| Switching | VTP, STP, EtherChannel (PAgP / LACP), 802.1Q Trunking |
| Security | DHCP Snooping, Layer 2 security features, DMZ, VPN |
| Services | NAT (Static / Dynamic / PAT), DHCP, VoIP (SCCP) |
| Equipment | Cisco Routers & Switches |

---

## Project Structure
---

## Configuration Format

All configurations are provided in two versions:

- **With prompt** – includes CLI context (e.g., `Switch(config)#hostname SW1`)
- **Script (no prompt)** – clean commands ready to paste directly into a device

---

## Supervisors

- **Mr. Bouchema** – Trainer & Academic Supervisor  
- **Mr. Taleb** – Trainer & Academic Supervisor  

---

## Notes

> This project was completed as part of the Digital Infrastructure – Systems & Networks 
> training program at ISTA Lazaret. All configurations use the `192.168.36.0/22` address space.
