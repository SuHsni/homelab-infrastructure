# IP Addressing Plan

## Overview

This document describes the IP addressing strategy for the homelab environment.

The purpose of this plan is to document the current network configuration and future addressing design for the lab infrastructure.


## Current Network Configuration

The current lab environment uses VMware Workstation NAT networking.

| Item | Value |
|---|---|
| Network | 192.168.93.0/24 |
| Network Mode | VMware NAT |
| Gateway | 192.168.93.2 |


## Current IP Assignments

| Device | IP Address | Status |
|---|---|---|
| DC01 | 192.168.93.10 | Configured |


## Planned Lab Network

A dedicated network is planned for future infrastructure labs.

| Item | Value |
|---|---|
| Network | 192.168.10.0/24 |
| Subnet Mask | 255.255.255.0 |
| CIDR | /24 |
| Purpose | Future Homelab Infrastructure Network |


## Planned IP Allocation

| Device | Planned IP | Purpose |
|---|---|---|
| DC01 | 192.168.10.10 | Windows Server / Domain Controller |
| WIN11 | DHCP | Client Machine |
| KALI01 | DHCP | Security Testing |
| UBUNTU01 | DHCP | Linux Administration |


## Addressing Strategy

Infrastructure servers will use static IP addresses to provide predictable network access.

Client and testing machines may use DHCP depending on the lab scenario.


## Future Improvements

Planned improvements:

- Create a dedicated virtual lab network
- Document actual IP assignments after implementation
- Add network diagrams
- Document network changes during future projects