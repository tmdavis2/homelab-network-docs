# Proxmox VE Homelab Cluster

Welcome to my homelab documentation! This repository tracks the architecture, network layout, storage configurations, and hosted services running across my 5-node Proxmox VE cluster.

---

## Cluster Overview

My cluster consists of a high-compute main desktop node supported by four lightweight, energy-efficient mini PCs.

| Node Name | Hardware Model | Primary Role | CPU / RAM / Storage |
| :--- | :--- | :--- | :--- |
| **pve-01** *(Primary)* | Alienware Aurora R11 | Heavy Workloads & Labbing | Intel Core i7 / 64GB / ZFS Pool |
| **pve-02** | Kamrui GK3V | Cluster Compute / Lightweight LXCs | Intel J4125 / 12B / NVMe |
| **pve-03** | Kamrui GK3V | Cluster Compute / Lightweight LXCs | Intel J4125 / 8GB / NVMe |
| **pve-04** | Kamrui GK3V | Cluster Compute / Lightweight LXCs | Intel J4125 / 8GB / NVMe |
| **pve-05** | Kamrui GK3V | Cluster Compute / Lightweight LXCs | Intel J4125 / 8GB / NVMe |

---

