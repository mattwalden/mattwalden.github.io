---
title: Homelab
---

# Homelab Infrastructure

This homelab is a practical learning environment designed to mirror
real-world IT infrastructure patterns. The focus is on clean design,
documentation, and repeatable builds — not just experimentation.

---

## 🎯 Goals

- Practice enterprise-style infrastructure design at small scale
- Build and document systems as if they were production
- Learn by designing, breaking, fixing, and documenting

---

## 🧱 Core Components

### Virtualization
- Proxmox VE as the primary hypervisor
- Dedicated management and server networks
- Standardized VM naming and roles

### Networking
- pfSense firewall
- VLAN-based network segmentation
- Explicit firewall rules between trust zones

### Documentation
- GitHub for source-controlled documentation
- Markdown-based docs for clarity and portability
- Change tracking and design decisions logged

---

## 🗂️ Network Segmentation (High Level)

- **Management VLAN**  
  Hypervisors, network devices, admin-only access

- **Server VLAN**  
  Internal services and application workloads

- **IoT / Restricted VLANs**  
  Limited east-west access, controlled via firewall rules

---

## 📌 Status

This environment is actively evolving.  
Design decisions, diagrams, and configurations are added as the lab grows.

👉 **[View the infrastructure repository](https://github.com/mattwalden/homelab-infra)**

---

## 🔮 Planned Areas

- Monitoring and alerting
- Automation and configuration management
- Identity and access controls
- Backup and recovery strategies
