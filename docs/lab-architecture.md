# Lab Architecture

## Overview

This document describes the basic architecture of my homelab environment.

The purpose of this lab is to create a small virtual environment for learning:

- Networking
- Windows Server
- Linux Administration
- System Administration
- Security Fundamentals

## Physical Host

The lab runs on a physical computer with the following resources:

- Operating System: Windows 10
- CPU: Intel Core i7-6500U
- RAM: 8GB
- Storage: SSD

## Virtualization Platform

The virtualization platform used in this lab:

- VMware Workstation

## Virtual Machines

The current planned virtual machines are:

| VM Name  | Operating System    | Purpose                       |
| -------- | ------------------- | ----------------------------- |
| DC01     | Windows Server 2025 | Domain Controller Practice    |
| WIN11    | Windows 11          | Client Machine Practice       |
| KALI01   | Kali Linux          | Security Testing Practice     |
| UBUNTU01 | Ubuntu Server       | Linux Administration Practice |

## Network Overview

The current lab network is based on VMware Workstation NAT networking.

The virtual machines use NAT mode to access external networks through the host machine.

A dedicated internal lab network (192.168.10.0/24) is planned for future Active Directory and infrastructure configuration.

## Lab Goals

The main goals of this lab are:

- Learn Active Directory
- Practice Windows Server administration
- Improve networking skills
- Practice Linux server management
- Document technical learning
