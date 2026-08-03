# Network Plan

## Overview

This document describes the planned network configuration for the homelab environment.

---

## Network Topology

- Hypervisor: VMware Workstation
- Network Mode: NAT

---

## Planned Address Space

| Network      | Subnet Mask | Purpose                  |
| ------------ | ----------- | ------------------------ |
| 192.168.10.0 | /24         | Internal Homelab Network |

---

## Planned Devices

| Device   | Planned IP    | Status  |
| -------- | ------------- | ------- |
| DC01     | 192.168.10.10 | Planned |
| WIN11    | DHCP          | Planned |
| KALI01   | DHCP          | Planned |
| UBUNTU01 | DHCP          | Planned |

---

## Notes

The Domain Controller will use a static IPv4 address.

Client machines will initially obtain their addresses using DHCP. This configuration may change as additional services are deployed.
