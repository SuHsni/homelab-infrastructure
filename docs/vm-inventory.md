# Virtual Machine Inventory

## Overview

This document tracks all virtual machines in the homelab environment.

The inventory includes current virtual machines, their operating systems, resources, status, and intended usage.

## Virtual Machines

| VM Name  | Operating System             | Memory  | Status    | Purpose                                  |
| -------- | ---------------------------- | ------- | --------- | ---------------------------------------- |
| DC01     | Windows Server 2025 Standard | 4096 MB | Installed | Future Windows Server Infrastructure Lab |
| WIN11    | Windows 11                   | 2048 MB | Planned   | Client Machine Testing                   |
| KALI01   | Kali Linux                   | 2048 MB | Planned   | Security Testing Practice                |
| UBUNTU01 | Ubuntu Server                | 2048 MB | Planned   | Linux Administration Practice            |

## Current Installed Virtual Machines

### DC01

| Item             | Value                        |
| ---------------- | ---------------------------- |
| Operating System | Windows Server 2025 Standard |
| RAM              | 4096 MB                      |
| Network          | VMware NAT                   |
| IP Address       | 192.168.93.10                |
| Status           | Installed                    |

## Planned Virtual Machines

### WIN11

Purpose:

- Windows client environment
- Future domain client testing

### KALI01

Purpose:

- Security tools practice
- Network analysis

### UBUNTU01

Purpose:

- Linux server administration
- Service deployment practice

## Status Legend

- **Installed** → Virtual machine has been created and operating system is installed.
- **Planned** → Virtual machine is planned but has not been created yet.

## Notes

The homelab will be expanded gradually by adding new virtual machines and documenting each configuration change.
