# IT Support Home Lab

Hands-on IT support labs that I'm working through while studying for CompTIA A+ and my Higher Diploma in Science in Computing at the National College of Ireland.

**Focus:** Windows, Active Directory, networking, troubleshooting · **Platform:** VirtualBox / Hyper-V · **Status:** In progress

## Overview

The goal is to practise the tasks a Service Desk / IT Support technician does every day, in a safe virtual environment, and to document each one clearly, the same way I'd write up a ticket or a knowledge-base article.

Labs are added as I complete them. Each lab has its own write-up in the [`labs/`](labs) folder.

## Lab environment

| Component | Purpose |
|---|---|
| Oracle VirtualBox (or Hyper-V) | Runs the virtual machines on my own PC |
| Windows Server (evaluation) | Domain controller: Active Directory, DNS, DHCP, Group Policy |
| Windows 11 (evaluation) | Client machine joined to the domain, used as the "end user" PC |
| Internal virtual network | Isolated network, so nothing touches my real home network |

## Lab roadmap

| # | Lab | Skills practised | Status |
|---|---|---|---|
| 01 | [Build the virtual lab](labs/01-virtual-lab-setup.md) | Virtualisation, Windows installation, networking basics | Planned |
| 02 | Promote a domain controller | Active Directory Domain Services, DNS | Planned |
| 03 | Join a Windows 11 PC to the domain | Domain join, DNS troubleshooting | Planned |
| 04 | User and group management | Create users, OUs and groups, reset passwords, unlock accounts | Planned |
| 05 | Group Policy basics | Password policy, mapped drives, desktop restrictions | Planned |
| 06 | File shares and permissions | NTFS vs share permissions, troubleshooting "access denied" | Planned |
| 07 | Printer deployment | Shared printers and deploying them with Group Policy | Planned |
| 08 | Network troubleshooting | `ipconfig`, `ping`, `tracert`, `nslookup`, DHCP issues | Planned |
| 09 | Windows troubleshooting | Event Viewer, Task Manager, Safe Mode, System Restore | Planned |
| 10 | Basic PowerShell for helpdesk | Querying users and resetting passwords with PowerShell | Planned |
| 11 | Security basics | Windows Defender, BitLocker, MFA concepts, spotting phishing | Planned |

## How each lab is documented

Every lab follows the same [template](labs/lab-template.md):

1. **Scenario:** the "ticket" or problem, written as a user would report it
2. **Objective:** what needs to work at the end
3. **Steps:** what I did, in order
4. **Verification:** how I proved it worked
5. **Troubleshooting notes:** what went wrong and how I fixed it
6. **What I learned**

## About me

I'm moving into IT support after more than 10 years of hands-on technical troubleshooting in Brazil, including running my own electrical and CCTV business (installing CCTV systems and configuring networks for remote access).

---

**Guilherme Lima** · Aspiring IT Support Technician · [LinkedIn](https://www.linkedin.com/in/glimaalmeida) · [GitHub](https://github.com/GuiLimaTi)
