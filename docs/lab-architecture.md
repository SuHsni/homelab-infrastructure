# Lab Architecture

## Overview

This document describes the basic architecture of my homelab environment.

The purpose of this lab is to build a virtual environment for hands-on learning and practicing IT infrastructure concepts, including:

- Networking Fundamentals
- Windows Server Administration
- Linux Administration
- System Administration
- Security Fundamentals

## Physical Host

The homelab is hosted on a physical computer with the following specifications:

- Operating System: Windows 10
- CPU: Intel Core i7-6500U (2 Cores / 4 Threads)
- RAM: 8GB
- Storage: SSD

## Virtualization Platform

The virtualization platform used in this lab:

- VMware Workstation

## Virtual Machines

The current and planned virtual machines are:

| VM Name  | Operating System             | Status    | Purpose                                |
| -------- | ---------------------------- | --------- | -------------------------------------- |
| DC01     | Windows Server 2025 Standard | Installed | Windows Server Infrastructure Practice |
| WIN11    | Windows 11                   | Planned   | Client Machine Testing                 |
| KALI01   | Kali Linux                   | Planned   | Security Testing Practice              |
| UBUNTU01 | Ubuntu Server                | Planned   | Linux Administration Practice          |

## Network Architecture

The current lab environment uses VMware Workstation NAT networking.

Current network:

192.168.93.0/24

The current configuration allows virtual machines to access external networks through the host machine.

A dedicated lab network is planned for future infrastructure projects:

192.168.10.0/24

## Lab Development Plan

The lab will be expanded gradually through separate projects.

Planned future projects include:

- Windows Server Lab
- Active Directory Practice
- Linux Server Administration
- Security Testing Labs
- Network Services Deployment

## Current State:

Internet
|
Host Windows 10
|
VMware NAT
|
DC01

Future State:

Host
|
VMware Internal Network
|
DC01
WIN11
UBUNTU01
KALI01

## Documentation Approach

All infrastructure changes, configurations, and learning activities will be documented to maintain a clear history of the lab development.
