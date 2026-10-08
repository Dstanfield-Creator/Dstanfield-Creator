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

Everything on this GitHub is organised into seven departments. Each repo has a home department; folders that belong elsewhere are listed under the department they serve. The full per-document index lives on [dstanfield-creator.github.io](https://dstanfield-creator.github.io/).

### 🛡️ Security Operations
Detection engineering, threat hunting, offensive technique references and lab ranges.

- **[detections](https://github.com/Dstanfield-Creator/detections)** - detection-as-code: Sigma rules for a home SOC lab, mapped to MITRE ATT&CK and validated in CI
- **[cyber-resources](https://github.com/Dstanfield-Creator/cyber-resources)** - 48 technique, tool and topic pages written from the defender's side, plus a HackTheBox tracker
- [Ludus Cyber Range](https://github.com/Dstanfield-Creator/projects/tree/master/homelab/ludus-cyber-range) - reproducible AD attack / detection range (projects)
- [Windows AD Logging Baseline for Detection](https://github.com/Dstanfield-Creator/server-administration/blob/master/docs/windows-ad-logging-baseline-for-detection.md) - audit policy, Sysmon, forwarding, attack-to-event map (server-administration)

### 🖥️ Infrastructure & Platform
Proxmox, backups, configuration management, hardening and the runbooks that keep it running.

- **[lab-ops](https://github.com/Dstanfield-Creator/lab-ops)** - the homelab as code: Ansible host baseline, Docker Compose stacks, Renovate
- **[server-administration](https://github.com/Dstanfield-Creator/server-administration)** - OpenSSH and systemd hardening, Proxmox CLI reference
- **[guides](https://github.com/Dstanfield-Creator/guides)** - Proxmox API tokens with least privilege, new-VM checklist, SSH key-auth troubleshooting
- [Proxmox Lab Platform](https://github.com/Dstanfield-Creator/projects/tree/master/homelab/proxmox-lab-platform) · [Proxmox Backup Server](https://github.com/Dstanfield-Creator/projects/tree/master/homelab/proxmox-backup-server) · [Docker Services Host](https://github.com/Dstanfield-Creator/projects/tree/master/homelab/docker-services-host) · [Minecraft Server](https://github.com/Dstanfield-Creator/projects/tree/master/homelab/minecraft-server) (projects)
- [Lab Power Scripts](https://github.com/Dstanfield-Creator/projects/tree/master/tools/lab-power-scripts) · [lab-ssh-check](https://github.com/Dstanfield-Creator/projects/tree/master/tools/lab-ssh-check) - Wake-on-LAN and Proxmox API orchestration, parallel SSH reachability checks (projects)
- [Terraform: Proxmox VM](https://github.com/Dstanfield-Creator/cloud-infrastructure/tree/master/terraform/proxmox-vm) · [Cloud-init for Proxmox and Cloud VMs](https://github.com/Dstanfield-Creator/cloud-infrastructure/blob/master/docs/cloud-init-for-proxmox-and-cloud-vms.md) (cloud-infrastructure)
- Write-up: [A backup job that failed silently for a month](https://dstanfield-creator.github.io/writeups/silent-backup-failure.html)

### 🌐 Network
Zero-trust access, campus design, firewalls and the connectivity troubleshooting that goes with them.

- [Tailscale Remote Access](https://github.com/Dstanfield-Creator/projects/tree/master/homelab/tailscale-remote-access) - WireGuard mesh, MagicDNS names as SSH handles, no port-forwards (projects)
- [Raspberry Pi Travel Router](https://github.com/Dstanfield-Creator/projects/tree/master/homelab/pi-travel-router) - OpenWrt pocket router with a Tailscale exit node (projects)
- [Cisco Enterprise Network Design](https://github.com/Dstanfield-Creator/projects/tree/master/infrastructure/cisco-enterprise-network-design) - multi-VLAN campus, ASA edge, DHCP relay (projects)
- [Network Optimisation & Security Enhancement](https://github.com/Dstanfield-Creator/projects/tree/master/infrastructure/network-security-enhancement) - segmentation, Fortinet firewall/IDS, backup redesign (projects)
- [Firewall Dead-Man Switch](https://github.com/Dstanfield-Creator/projects/tree/master/tools/firewall-deadman-switch) · [Remote Firewall Change Without Lockout](https://github.com/Dstanfield-Creator/guides/blob/master/runbooks/remote-firewall-change.md) · [UFW Baseline for Headless Servers](https://github.com/Dstanfield-Creator/server-administration/blob/master/hardening/ufw-baseline-linux.md)
- [DNS, DHCP and Connectivity](https://github.com/Dstanfield-Creator/general-it/blob/master/troubleshooting/dns-dhcp-and-connectivity.md) · [Firewall Configuration](https://github.com/Dstanfield-Creator/cyber-resources/blob/master/docs/firewall-configuration.md) · [Network Segmentation](https://github.com/Dstanfield-Creator/cyber-resources/blob/master/docs/network-segmentation.md) · [Network Scanning](https://github.com/Dstanfield-Creator/cyber-resources/blob/master/techniques/network-scanning.md)
- Write-up: [The UFW rule was correct and still locked me out](https://dstanfield-creator.github.io/writeups/ufw-lockout.html)

### ☁️ Cloud
Infrastructure as Code and cloud operations on AWS and Azure.

- **[cloud-infrastructure](https://github.com/Dstanfield-Creator/cloud-infrastructure)** - Terraform AWS VPC/EC2 baseline, AWS and Azure CLI cheatsheet
- [Cloud Services & VM Management](https://github.com/Dstanfield-Creator/projects/tree/master/infrastructure/cloud-vm-management) - Azure VM, storage and network operations with PowerShell and ServiceNow (projects)

### 🤖 AI & Automation
AI agents with real operational reach, held to the same controls as a junior admin's service account.

- [Paperclip AI Agents](https://github.com/Dstanfield-Creator/projects/tree/master/homelab/paperclip-ai-agents) - self-hosted agent platform with least-privilege Proxmox/PBS tokens, protected VMs and a hardened host (projects)
- n8n workflow automation for lab notifications and scheduled checks, running on the [Docker Services Host](https://github.com/Dstanfield-Creator/projects/tree/master/homelab/docker-services-host)

### 📈 Monitoring & Observability
Prometheus, Grafana and the alerts derived from real incidents.

- **[MyDashboard](https://github.com/Dstanfield-Creator/projects/tree/master/poc/mydashboard)** - Prometheus + Grafana lab health dashboard design with alerts derived from real incidents (projects; the build repo goes public when it lands)
- [Monitoring Stack (Compose)](https://github.com/Dstanfield-Creator/cloud-infrastructure/tree/master/docker-compose/monitoring-stack) - Prometheus, Alertmanager, Grafana, node_exporter, cAdvisor, blackbox (cloud-infrastructure)
- [Prometheus node_exporter Setup](https://github.com/Dstanfield-Creator/server-administration/blob/master/monitoring/prometheus-node-exporter-setup.md) (server-administration) · [compose/monitoring](https://github.com/Dstanfield-Creator/lab-ops/tree/main/compose/monitoring) (lab-ops)

### 🔧 General IT & Service Desk
Methodology, identity administration and the tooling that takes repetition out of first-line work.

- **[general-it](https://github.com/Dstanfield-Creator/general-it)** - troubleshooting methodology, AD and Microsoft 365 joiner-leaver checklist, command equivalents, change management
- **[Powershell-Scripts](https://github.com/Dstanfield-Creator/Powershell-Scripts)** - Active Directory GUI tooling for a service desk
- [Documentation vs Live State](https://github.com/Dstanfield-Creator/guides/blob/master/best-practices/documentation-vs-live-state.md) (guides)

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
