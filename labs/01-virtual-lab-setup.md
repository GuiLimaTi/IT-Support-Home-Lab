# Lab 01 — Build the virtual lab

**Status:** ⬜ Planned
**Date completed:** 
**Skills:** Virtualisation, Windows installation, virtual networking

---

## 🎫 Scenario

> "We need a safe test environment where we can practise Windows and Active Directory tasks without touching real users or devices."

## 🎯 Objective

Two virtual machines running on my PC and able to talk to each other on an isolated network:

- **DC01** — Windows Server (will become the domain controller in Lab 02)
- **CLIENT01** — Windows 11 (will be the end-user PC in Lab 03)

## 🛠️ Steps (plan)

1. Install Oracle VirtualBox (or enable Hyper-V on Windows Pro).
2. Download the Windows Server and Windows 11 evaluation ISOs from the Microsoft Evaluation Center.
3. Create an **internal network** in VirtualBox (e.g. `LabNet`) so the VMs are isolated from my home network.
4. Create **DC01**: 2 vCPU, 4 GB RAM, 60 GB disk, network adapter on `LabNet`. Install Windows Server (Desktop Experience).
5. Create **CLIENT01**: 2 vCPU, 4 GB RAM, 60 GB disk, network adapter on `LabNet`. Install Windows 11.
6. Rename both machines (`DC01`, `CLIENT01`).
7. Give DC01 a static IP (e.g. `192.168.10.10/24`) and CLIENT01 a static IP for now (e.g. `192.168.10.20/24`).
8. Take a **snapshot** of both VMs ("Clean install") so I can roll back if something breaks.

## ✅ Verification

- [ ] Both VMs boot and I can log in
- [ ] `ipconfig` shows the expected IP addresses
- [ ] `ping 192.168.10.10` from CLIENT01 works (allow ICMP in Windows Firewall if needed)
- [ ] Snapshots created

## 🔧 Troubleshooting notes

| Problem | Cause | Fix |
|---|---|---|
|  |  |  |

## 💡 What I learned

- 
