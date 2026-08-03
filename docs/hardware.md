# Host Machine Hardware

## Overview

This document describes the physical host machine used to run the homelab virtualization environment.

The host machine provides the hardware resources required for running virtual machines through VMware Workstation.

## Hardware Specifications

| Component             | Specification                             |
| --------------------- | ----------------------------------------- |
| CPU                   | Intel Core i7-6500U (2 Cores / 4 Threads) |
| RAM                   | 8 GB                                      |
| Storage               | SSD                                       |
| Host Operating System | Windows 10                                |
| Hypervisor            | VMware Workstation                        |

## Virtualization Environment

The physical host runs VMware Workstation as the virtualization platform.

Virtual machines are created and managed inside this environment to simulate different IT infrastructure roles.

## Resource Considerations

Due to the limited physical memory (8GB RAM), virtual machines are started based on lab requirements.

Multiple resource-heavy virtual machines may not run simultaneously.

## Purpose

The purpose of this hardware environment is to provide a practical platform for learning and practicing:

- System Administration
- Networking
- Windows Server
- Linux Administration
- Security Fundamentals
