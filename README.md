# K3s HomeLab

A lightweight Kubernetes cluster running on three Raspberry Pi 4B nodes, built for learning and experimenting with DevOps tooling.

## Hardware

| Node | Role |
|---|---|---|
| pi-master | Control Plane + Pi-hole (for personal use) |
| pi-worker-1 | Worker |
| pi-worker-2 | Worker |

- Raspberry Pi 4B, 4GB RAM each
- Raspberry Pi OS Lite 64-bit
- Connected via Ethernet to FritzBox 7560

## Stack

- **K3s** v1.34.6 – lightweight Kubernetes distribution
- **Prometheus + Grafana** – cluster monitoring

## Setup

Managed via SSH from PowerShell. SSH key authentication only, password login disabled.

## Status

- [x] K3s cluster (1 master, 2 workers)
- [x] Prometheus + Grafana monitoring
- [ ] First application workload
- [ ] CI/CD Pipeline
- [ ] GitOps
