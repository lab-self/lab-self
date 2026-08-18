<h1 align="center">⚡ Abhijit Paul</h1>

<h3 align="center">
Senior System Administrator • Infrastructure Engineer • Virtualization & Automation
</h3>

<p align="center">
  Designing, deploying and automating secure, resilient infrastructure.
</p>

<p align="center">
  <a href="https://linkedin.com/in/iamabhijitpaul">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:proxmox.self@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/lab-self">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://get.owninfra.site">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=white"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=lab-self&style=for-the-badge&color=blue" alt="Profile Views"/>
</p>

---

## 👨‍💻 About Me

I am a **Senior System Administrator / Infrastructure Engineer** focused on building, operating and automating reliable IT infrastructure.

My primary areas of interest are:

* Enterprise virtualization
* Linux and Windows Server administration
* Network architecture and security
* Infrastructure automation
* Containerized workloads
* Monitoring and observability
* Self-hosted infrastructure
* Zero Trust networking
* CI/CD and DevOps practices
* Infrastructure-as-Code

I use my homelab as an engineering environment to reproduce enterprise concepts such as **HA, VLAN segmentation, centralized authentication, reverse proxies, monitoring, automation, backup, secure remote access and container orchestration**.

---

## 🏗️ What I Build

```text
                    ┌──────────────────────────┐
                    │       INTERNET / ISP     │
                    └────────────┬─────────────┘
                                 │
                         ┌───────▼───────┐
                         │    OPNsense   │
                         │ Firewall / VPN │
                         └───────┬───────┘
                                 │
                    ┌────────────▼────────────┐
                    │      VLAN / Network     │
                    │   Segmentation Layer    │
                    └────────────┬────────────┘
                                 │
              ┌──────────────────┼──────────────────┐
              │                  │                  │
       ┌──────▼──────┐    ┌──────▼──────┐    ┌──────▼──────┐
       │ VMware ESXi │    │ Proxmox VE  │    │   Network   │
       │ Virtualized │    │ Virtualized │    │ Infrastructure│
       │ Infrastructure│  │ Infrastructure│  │   & Security │
       └──────┬──────┘    └──────┬──────┘    └─────────────┘
              │                  │
              └──────────┬───────┘
                         │
                 ┌───────▼────────┐
                 │ Compute / VMs   │
                 │ Containers      │
                 │ Kubernetes      │
                 └───────┬────────┘
                         │
        ┌────────────────┼─────────────────┐
        │                │                 │
   ┌────▼────┐      ┌────▼────┐      ┌────▼─────┐
   │ Storage │      │Monitoring│      │Automation│
   │ TrueNAS │      │ Grafana  │      │ Ansible  │
   │ ZFS/NFS │      │Prometheus│      │Terraform │
   └─────────┘      └──────────┘      └──────────┘
```

---

## 🖥️ Core Infrastructure Skills

### Virtualization

<p>
<img src="https://img.shields.io/badge/VMware_ESXi-607078?style=for-the-badge&logo=vmware&logoColor=white"/>
<img src="https://img.shields.io/badge/vCenter_Server-607078?style=for-the-badge&logo=vmware&logoColor=white"/>
<img src="https://img.shields.io/badge/vSAN-607078?style=for-the-badge&logo=vmware&logoColor=white"/>
<img src="https://img.shields.io/badge/Proxmox_VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white"/>
</p>

* VMware ESXi / vCenter
* vSphere HA / DRS concepts
* vSAN architecture
* Nested virtualization
* Proxmox VE
* VM lifecycle management
* Resource allocation and optimization
* High-availability architecture

---

## 🌐 Networking & Security

<p>
<img src="https://img.shields.io/badge/OPNsense-F80101?style=for-the-badge&logo=opnsense&logoColor=white"/>
<img src="https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white"/>
<img src="https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white"/>
<img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white"/>
<img src="https://img.shields.io/badge/AdGuard_Home-68BC71?style=for-the-badge&logo=adguard&logoColor=white"/>
</p>

* VLAN architecture
* Inter-VLAN routing
* Firewall policy design
* Dual-ISP connectivity
* VPN architecture
* WireGuard
* DNS security
* Reverse proxy
* TLS / SSL
* Secure remote access
* Zero Trust networking
* Network segmentation

---

## 📦 Containers & Platform Engineering

<p>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx" />
</p>

* Docker
* Docker Compose
* Kubernetes
* Container networking
* Persistent storage
* Reverse proxy architecture
* Container security
* Service isolation
* Portainer
* Self-hosted application platforms

---

## ⚙️ Infrastructure Automation

<p>
<img src="https://skillicons.dev/icons?i=ansible,terraform,bash,git,github" />
</p>

### Current focus

```yaml
Infrastructure_as_Code:
  - Terraform

Configuration_Management:
  - Ansible

Automation:
  - Bash
  - PowerShell
  - Python

Version_Control:
  - Git
  - GitHub

CI_CD:
  - Woodpecker CI
  - GitHub Actions
```

My automation goal is to move infrastructure from:

```text
Manual Configuration
        ↓
Documented Configuration
        ↓
Version Controlled Configuration
        ↓
Automated Deployment
        ↓
Repeatable Infrastructure
```

---

## 📊 Monitoring & Observability

<p>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
<img src="https://img.shields.io/badge/Zabbix-D00000?style=for-the-badge&logo=zabbix&logoColor=white"/>
</p>

* Prometheus
* Grafana
* Zabbix
* Uptime Kuma
* Infrastructure metrics
* Service monitoring
* Alerting
* Capacity monitoring
* Network monitoring
* Application observability

---

## 💾 Storage & Data Infrastructure

<p>
<img src="https://img.shields.io/badge/TrueNAS-0095D5?style=for-the-badge&logo=truenas&logoColor=white"/>
<img src="https://img.shields.io/badge/ZFS-2F4F4F?style=for-the-badge"/>
<img src="https://img.shields.io/badge/NFS-333333?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SMB-0078D4?style=for-the-badge"/>
</p>

* TrueNAS
* ZFS
* NFS
* SMB
* iSCSI
* Shared storage
* VM storage
* Backup architecture
* Storage performance optimization

---

## 🔐 Identity & Access

<p>
<img src="https://img.shields.io/badge/Microsoft_Active_Directory-0078D4?style=for-the-badge&logo=microsoft&logoColor=white"/>
<img src="https://img.shields.io/badge/Authentik-FD4B2D?style=for-the-badge"/>
</p>

* Active Directory
* Windows Server
* DNS / DHCP
* Group Policy
* OU design
* Authentication
* SSO
* Identity-aware access
* Zero Trust principles

---

## 🐧 Operating Systems

<p>
<img src="https://skillicons.dev/icons?i=ubuntu,debian,linux,windows" />
</p>

### Linux

* Ubuntu Server
* Debian
* Bash
* systemd
* SSH
* networking
* storage administration
* package management
* service management
* hardening

### Windows Server

* Active Directory
* DNS
* DHCP
* Group Policy
* File Services
* Certificate Services
* Windows administration

---

## 🤖 Self-Hosted AI & Modern Infrastructure

<p>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/AI_Infrastructure-412991?style=for-the-badge"/>
</p>

Exploring practical AI infrastructure including:

* Local LLM deployment
* Ollama
* AI-enabled internal services
* Private AI infrastructure
* GPU-aware workloads
* AI + automation
* AI-assisted system administration

---

## 🛠️ Remote Management & Self-Hosted Services

```text
Remote Management
├── MeshCentral
├── RustDesk
└── Nexterm

Access & Security
├── WireGuard
├── Twingate
├── Cloudflare Tunnel
├── Authentik
└── Reverse Proxy

Applications
├── Nextcloud
├── Jellyfin
├── FileCloud
├── OwnCloud
└── AdGuard Home
```

---

# 🚀 Featured Infrastructure Projects

I focus on projects that demonstrate **real infrastructure engineering**, rather than isolated technology demos.

### 🏠 OwnInfra — Enterprise Homelab

A multi-layer infrastructure environment designed around enterprise concepts.

**Architecture includes:**

* VMware ESXi
* vCenter
* Proxmox VE
* OPNsense
* VLAN segmentation
* TrueNAS
* Docker
* Kubernetes
* Monitoring
* VPN
* Reverse proxy
* Zero Trust access
* Self-hosted applications

🔗 **Infrastructure:** https://get.owninfra.site

---

### 🔄 Infrastructure Automation

Building repeatable infrastructure using:

```text
Git
 │
 ├── Ansible
 │     └── Configuration Management
 │
 ├── Terraform
 │     └── Infrastructure Provisioning
 │
 └── CI/CD
       └── Automated Deployment
```

The objective is to make infrastructure **reproducible, auditable and version controlled**.

---

### 🐳 Containerized Application Platform

Self-hosted platform for deploying and managing applications using:

* Docker
* Docker Compose
* Nginx Proxy Manager
* Portainer
* Persistent storage
* TLS
* DNS
* Authentication
* Monitoring

---

### 🔐 Zero Trust Remote Access

Designing secure remote-access architectures using:

* WireGuard
* Twingate
* Cloudflare Tunnel
* Authentik
* Reverse proxy
* Identity-based access

The goal is to minimize direct public exposure while maintaining secure access to internal services.

---

# 📚 Currently Learning & Improving

```yaml
Advanced:
  - VMware
  - Proxmox
  - Linux Administration
  - Networking
  - Network Security

Building:
  - Ansible
  - Terraform
  - Kubernetes
  - CI/CD
  - Infrastructure Automation

Exploring:
  - Platform Engineering
  - GitOps
  - Zero Trust
  - AI Infrastructure
  - Observability
  - Cloud Infrastructure
```

---

# 🧩 Engineering Philosophy

```text
Infrastructure should be:

Secure
   ↓
Reliable
   ↓
Observable
   ↓
Automated
   ↓
Repeatable
   ↓
Documented
```

I prefer infrastructure that can be:

* **Provisioned**
* **Configured**
* **Monitored**
* **Recovered**
* **Scaled**
* **Audited**
* **Automated**

rather than infrastructure that depends on undocumented manual configuration.

---

# 📈 GitHub Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=lab-self&theme=tokyo-night&hide_border=true&area=true" width="95%"/>
</p>

---

# 🧰 Technology Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,ubuntu,bash,powershell,python,git,github,docker,kubernetes,nginx,mysql,terraform,ansible,vscode,aws" />
</p>

---

# 🎯 Career Direction

```text
Senior System Administrator
          │
          ├── Virtualization
          │
          ├── Linux / Windows
          │
          ├── Networking & Security
          │
          ├── Infrastructure Automation
          │
          ├── Monitoring & Observability
          │
          └── High Availability
                    │
                    ▼
          Infrastructure Engineer
                    │
                    ▼
             DevOps / Platform
                    │
                    ▼
          Infrastructure Architect
```

My current objective is to combine **traditional systems administration** with **Infrastructure-as-Code, automation, observability and modern platform engineering**.

---

<div align="center">

### ⚡ Building Infrastructure. Automating Operations. Learning Every Day.

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=140&section=footer"/>

</div>
