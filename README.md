# Multi-VM Departmental Homelab

## Overview

The **Multi-VM Departmental Homelab** is an enterprise-style virtualised network environment built using **Oracle VirtualBox**.

The lab simulates a segmented corporate network across five organisational departments:

- Finance
- Audit
- Information Technology
- Procurement
- Guest

The environment consists of **18 virtual machines**, including Windows Server 2022 departmental servers and Windows 8 workstations. Each department is logically separated using **VirtualBox Internal Networks**, while VirtualBox Groups are used to organise the virtual machines according to their departmental structure.

The lab was designed to provide a controlled environment for practising system administration, Active Directory, Group Policy, user and computer management, network configuration, security hardening, and incident simulation.

## Lab Environment

| Component | Details |
|---|---|
| Virtualisation Platform | Oracle VirtualBox |
| Servers | Windows Server 2022 |
| Workstations | Windows 8 |
| Departments | Finance, Audit, IT, Procurement, Guest |
| Total VMs | 18 |
| Network Isolation | VirtualBox Internal Networks |
| Management | Active Directory & Group Policy |

## Repository Contents

This repository contains the documentation and supporting evidence for the complete homelab build.

```text
Multi-VM-Departmental-Homelab/
│
├── README.md
├── Project-Documentation.pdf
├── Screenshots/
└── ...
