# pfSense – Initial SOC Lab 2026-01-16

## Overview

Basic deployment of a pfSense firewall in a virtualized environment as part of my personal SOC lab.

This lab focuses on understanding firewall fundamentals and basic network segmentation using WAN and LAN interfaces.

---

## Environment

- Hypervisor: VirtualBox
- Firewall: pfSense CE
- Host OS: Windows 10
- Lab type: Personal SOC Lab

---

## Implementation

- Installed pfSense from official ISO image
- Created a virtual machine in VirtualBox
- Configured network interfaces:
  - WAN (external)
  - LAN (internal)
- Enabled WebGUI access via WAN (testing purposes only)
- Assigned basic IP configuration
- Tested connectivity (ICMP, web access)
- Accessed and explored pfSense Web Interface

---

## Current Scope

- Basic firewall deployment
- WAN / LAN interface segmentation
- Remote management enabled (lab environment only)

> Note: WAN management is enabled only for testing and learning purposes.

---

## Lab Goals

- Learn firewall fundamentals
- Gain hands-on experience with pfSense
- Understand network segmentation concepts
- Build foundation for future SOC projects

---

## Next Steps

- Create custom firewall rules
- Configure NAT
- Explore IDS/IPS solutions
- Set up VPN access
- Centralize logs
- Learn VLAN segmentation

---

## Key Takeaways

- Basic firewall architecture
- Interface roles (WAN vs LAN)
- Virtualized security labs
- Network troubleshooting basics

---

## Status

In Progress
