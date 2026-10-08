# Danny Stanfield

**Junior SecOps Analyst** @ Quartex | Perth, Western Australia

Cybersecurity professional focused on SIEM/EDR triage, Zero Trust architecture, detection automation, and homelab infrastructure. Building secure, efficient systems and developing effective security detections.

---

## 🔐 Current Focus

- **SIEM & EDR Operations** - Alert triage, threat investigation, incident response
- **Detection Engineering** - Writing and tuning detection rules
- **Zero Trust / SASE** - Security architecture and implementation
- **Homelab Automation** - Docker, Proxmox, n8n, self-hosted infrastructure
- **Threat Intelligence** - Security research and threat actor tracking

---

## 🏢 Work by Department

Every repository belongs to exactly one of seven departments. The full per-document index lives on [dstanfield-creator.github.io](https://dstanfield-creator.github.io/).

### 🛡️ Security Operations
Detection engineering, threat hunting, offensive technique references and the lab range they are tested in.

- **[detections](https://github.com/Dstanfield-Creator/detections)** - detection-as-code: Sigma rules for a home SOC lab, mapped to MITRE ATT&CK and validated in CI, plus the [Windows AD logging baseline](https://github.com/Dstanfield-Creator/detections/blob/main/docs/windows-ad-logging-baseline-for-detection.md) the rules depend on
- **[cyber-resources](https://github.com/Dstanfield-Creator/cyber-resources)** - 48 technique, tool and topic pages written from the defender's side, the [Ludus cyber range](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/labs/ludus-cyber-range) and a HackTheBox tracker

### 🖥️ Infrastructure & Platform
Proxmox, backups, configuration management, hardening and the runbooks that keep it running.

- **[lab-ops](https://github.com/Dstanfield-Creator/lab-ops)** - the homelab as code and in prose: Ansible host baseline, Compose services, Proxmox VM Terraform, `lab-up` / `lab-down` / `lab-ssh-check`, and the build write-ups ([Proxmox Lab Platform](https://github.com/Dstanfield-Creator/lab-ops/tree/main/docs/proxmox-lab-platform), [Proxmox Backup Server](https://github.com/Dstanfield-Creator/lab-ops/tree/main/docs/proxmox-backup-server), [Docker Services Host](https://github.com/Dstanfield-Creator/lab-ops/tree/main/docs/docker-services-host), [Minecraft Server](https://github.com/Dstanfield-Creator/lab-ops/tree/main/docs/minecraft-server))
- **[server-administration](https://github.com/Dstanfield-Creator/server-administration)** - OpenSSH and systemd hardening, Proxmox CLI reference, and guides: [API tokens with least privilege](https://github.com/Dstanfield-Creator/server-administration/blob/master/guides/proxmox-api-token-least-privilege.md), [new-VM checklist](https://github.com/Dstanfield-Creator/server-administration/blob/master/guides/new-proxmox-vm-checklist.md), [SSH key-auth failures](https://github.com/Dstanfield-Creator/server-administration/blob/master/guides/ssh-key-auth-failures.md)
- Write-up: [A backup job that failed silently for a month](https://dstanfield-creator.github.io/writeups/silent-backup-failure.html)

### 🌐 Network
Zero-trust access, campus design, firewalls and the connectivity troubleshooting that goes with them.

- **[network](https://github.com/Dstanfield-Creator/network)** - [Tailscale remote access](https://github.com/Dstanfield-Creator/network/tree/main/remote-access/tailscale-remote-access), [Pi travel router](https://github.com/Dstanfield-Creator/network/tree/main/remote-access/pi-travel-router), [Cisco enterprise network design](https://github.com/Dstanfield-Creator/network/tree/main/design/cisco-enterprise-network-design), the [firewall dead-man switch](https://github.com/Dstanfield-Creator/network/tree/main/firewall/firewall-deadman-switch) with its [runbook](https://github.com/Dstanfield-Creator/network/blob/main/firewall/remote-firewall-change.md) and [UFW baseline](https://github.com/Dstanfield-Creator/network/blob/main/firewall/ufw-baseline-linux.md), [DNS/DHCP troubleshooting](https://github.com/Dstanfield-Creator/network/blob/main/troubleshooting/dns-dhcp-and-connectivity.md), and a [network security enhancement case study](https://github.com/Dstanfield-Creator/network/tree/main/case-studies/network-security-enhancement)
- Write-up: [The UFW rule was correct and still locked me out](https://dstanfield-creator.github.io/writeups/ufw-lockout.html)

### ☁️ Cloud
Infrastructure as Code and cloud operations on AWS and Azure.

- **[cloud-infrastructure](https://github.com/Dstanfield-Creator/cloud-infrastructure)** - Terraform AWS VPC/EC2 baseline, AWS and Azure CLI cheatsheet, and the [Cloud Services & VM Management](https://github.com/Dstanfield-Creator/cloud-infrastructure/tree/master/case-studies/cloud-vm-management) case study

### 🤖 AI & Automation
AI agents with real operational reach, held to the same controls as a junior admin's service account.

- **[ai-automation](https://github.com/Dstanfield-Creator/ai-automation)** - [Paperclip AI agents](https://github.com/Dstanfield-Creator/ai-automation/tree/main/paperclip-ai-agents) with least-privilege Proxmox/PBS tokens, protected VMs and a hardened host; n8n automation runs on the lab's Docker host

### 📈 Monitoring & Observability
Prometheus, Grafana and the alerts derived from real incidents.

- **[monitoring](https://github.com/Dstanfield-Creator/monitoring)** - [MyDashboard](https://github.com/Dstanfield-Creator/monitoring/tree/main/mydashboard) lab health dashboard design, the [reference](https://github.com/Dstanfield-Creator/monitoring/tree/main/compose/monitoring-stack) and [lab](https://github.com/Dstanfield-Creator/monitoring/tree/main/compose/lab-monitoring) Compose stacks, and [node_exporter setup](https://github.com/Dstanfield-Creator/monitoring/blob/main/docs/prometheus-node-exporter-setup.md)

### 🔧 General IT & Service Desk
Methodology, identity administration and the tooling that takes repetition out of first-line work.

- **[general-it](https://github.com/Dstanfield-Creator/general-it)** - troubleshooting methodology, AD and Microsoft 365 joiner-leaver checklist, command equivalents, change management, documentation vs live state
- **[Powershell-Scripts](https://github.com/Dstanfield-Creator/Powershell-Scripts)** - Active Directory GUI tooling for a service desk

---

## 🛠️ Tech Stack

**Security:** SIEM platforms, EDR tools, IDS/IPS, threat intelligence, log management  
**Infrastructure:** Proxmox, Docker, n8n, Ansible, Tailscale  
**Languages:** PowerShell, Python, Bash  
**Tools:** Kali Linux, Burp Suite, Nmap, Wireshark, Metasploit

---

## 📜 Certifications

- **Cato Zero Trust Security Essentials** (Jul 2026)
- **Fortinet FCA Cybersecurity**
- **Acronis Cyber Security Associate Advanced**
- **Sophos Firewall Administrator**
- **AWS Academy Cloud Foundations**
- **Diploma of Information and Technology Advanced Networking** (South Metropolitan TAFE, 2020)

---

## 💼 Professional Experience

**Quartex** - Junior SecOps Analyst (Feb 2026–Present)  
SIEM/EDR triage, detection engineering, threat investigation, Zero Trust operations

**VenuesWest** - Network Analyst (Jan 2025–Jan 2026)  
Network infrastructure, digital signage, risk assessments, business analysis

**NXDH (Next Day Heroes)** - Systems Engineer (Jan 2021–Jan 2025)  
Infrastructure design, server administration, virtualization, Active Directory, endpoint management

**Kinetic IT / Woodside** - Senior Service Desk Officer (Jan 2022–May 2023)  
Escalated IT support, team mentoring, system administration, policy enforcement

**Kinetic IT / Water Corporation** - Service Desk Analyst (Jan 2021–Jan 2022)  
Desktop support, Microsoft 365, user account management, cloud/on-premise systems

**BixlinQ** - Junior Systems Engineer (Jan 2023–Jan 2024)  
On-site/off-site support, network monitoring, hardware configuration, managed services

**Aeris Networks** - System Administrator Desktop Support (May 2023–Jul 2024)  
Desktop support, systems administration, Microsoft 365, disaster recovery, compliance support

---

## 🔗 Connect

- **LinkedIn:** [danny-stanfield](https://linkedin.com/in/danny-stanfield)
- **GitHub:** [@Dstanfield-Creator](https://github.com/Dstanfield-Creator)
- **Website:** [dstanfield-creator.github.io](https://dstanfield-creator.github.io/)

---

**License:** MIT | **Last Updated:** October 2026
