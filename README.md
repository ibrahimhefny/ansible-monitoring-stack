
# 📊 Ansible Monitoring Stack  
### Prometheus • Grafana • Alertmanager

A **production-grade, fully automated monitoring stack** built using **Ansible** and **Podman**, designed for **RHEL-based Linux systems** 🐧.

This project deploys and configures the entire monitoring pipeline with **zero manual UI steps**, proper **SELinux handling**, and **persistent services that survive reboots**.

---

## 📌 Overview

This stack includes:

- 📊 **Prometheus** — Metrics collection & scraping
- 🖥 **Node Exporter** — Host-level system metrics
- 📈 **Grafana** — Visualization with auto-provisioned dashboards
- 🚨 **Alertmanager** — Alert routing & notifications (Telegram)

All components are deployed as **Podman containers** and orchestrated using **Ansible roles**.

---

## 🏗 Architecture
<img width="228" height="218" alt="image" src="https://github.com/user-attachments/assets/7f0c75f7-06d6-4e98-ac53-b26502b78f7f" />


## ✨ Key Features

- ⚙️ Fully automated deployment using Ansible
- 🧩 Clean, role-based project structure
- 🐳 Podman containers (no Docker dependency)
- 📊 Auto-provisioned Grafana dashboards & datasources
- 🔁 Persistent data volumes
- 🔐 SELinux-safe volume labeling
- 🔄 Services automatically restart after reboot
- 📲 Real-time alert notifications via Telegram
- ❌ No hardcoded secrets in the repository

## 🧰 Requirements

- RHEL / Rocky Linux / AlmaLinux
- Ansible
- Podman
- SSH access to all target nodes

## 🖼 Screenshots:

### Grafana Dashboard
<img width="1907" height="983" alt="image" src="https://github.com/user-attachments/assets/13cd99dd-a305-49fe-9624-e720b58bb157" />

### Prometheus Dashboard
<img width="1915" height="641" alt="image" src="https://github.com/user-attachments/assets/347d1b9a-96b1-4807-a081-5295bbe49552" />

### Alerts-Manager + Telegram notification test: 
![WhatsApp Image 2025-12-31 at 7 39 44 PM](https://github.com/user-attachments/assets/891064b6-412c-4420-a878-e82337eb0657)


















