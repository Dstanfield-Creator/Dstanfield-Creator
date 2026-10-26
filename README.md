# Danny Stanfield

**Junior SecOps Analyst** @ Quartex | Perth, Western Australia

Cybersecurity professional focused on SIEM/EDR triage, Zero Trust architecture, detection automation, and homelab infrastructure. Building secure, efficient systems and developing effective security detections.

---

## 🔐 Current Focus

- **SIEM & EDR Operations** - Alert triage, threat investigation, incident response
- **Detection Engineering** - Writing and tuning Sigma detection rules in a home SOC lab
- **Zero Trust / SASE** - Security architecture and implementation
- **Homelab Automation** - Docker, Proxmox, n8n, self-hosted infrastructure
- **Threat Intelligence** - Security research and threat actor tracking

---

## 🏢 Work by Department

Every repository belongs to exactly one of six departments. The full per-document index lives on [dstanfield-creator.github.io](https://dstanfield-creator.github.io/).

### 🛡️ Security Operations
Detection engineering, the monitoring that feeds it, offensive technique references and the lab range they are tested in.

- **[cyber-resources](https://github.com/Dstanfield-Creator/cyber-resources)** - the whole department in one repo:
  - [detections/](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/detections) - detection-as-code: Sigma rules for a home SOC lab, mapped to MITRE ATT&CK and validated in CI, plus the [Windows AD logging baseline](https://github.com/Dstanfield-Creator/cyber-resources/blob/master/detections/docs/windows-ad-logging-baseline-for-detection.md) the rules depend on
  - [monitoring/](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/monitoring) - [MyDashboard](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/monitoring/mydashboard) lab health dashboard design, the [reference](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/monitoring/compose/monitoring-stack) and [lab](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/monitoring/compose/lab-monitoring) Prometheus/Grafana Compose stacks, [node_exporter setup](https://github.com/Dstanfield-Creator/cyber-resources/blob/master/monitoring/docs/prometheus-node-exporter-setup.md)
  - 48 technique, tool and topic pages written from the defender's side, the [Ludus cyber range](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/labs/ludus-cyber-range) and a HackTheBox tracker

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
- **Sophos Central Endpoint & Server Engineer (ET15)** (Aug 2023)
- **ITIL Foundation** (Jul 2022)
- **HTB Certified Penetration Testing Specialist (CPTS)** - in progress

---

## 💼 Professional Experience

**Quartex** - Junior SecOps Analyst (Feb 2026–Present)  
Incident triage across CrowdStrike Falcon, Defender XDR, Datadog, Entra ID and AWS; cloud EDR coverage, SOC 2 access reviews, pen-test remediation, Zero Trust operations

**VenuesWest** - Network Analyst (Jan 2025–Jan 2026)  
Network infrastructure, digital signage, risk assessments, business analysis

**Aeris Networks** - System Administrator / Desktop Support, Contract (Feb 2024–Jan 2025)  
Desktop support, systems administration, Microsoft 365, disaster recovery, compliance support

**NXDH** - System Engineer, BizLinQ contract (Jan 2023–Jan 2024)  
On-site/remote infrastructure support, network monitoring and managed services for South West clients

**NXDH** - Junior System Engineer (Jan 2022–Dec 2022)  
Server administration, virtualisation, Active Directory, endpoint management, patching and documentation

**Kinetic IT / Woodside** - Senior Service Desk Officer (Jan 2021–Dec 2021)  
Escalated IT support, team mentoring, policy enforcement

**Kinetic IT / Water Corporation** - Service Desk Analyst (Jan 2020–Jan 2021)  
Desktop support, Microsoft 365, user account management, cloud/on-premise systems

**Aussie Broadband** - Help Desk Specialist (Jan 2019–Jan 2020)  
Customer and technical support, ticket management, broadband/ISP support

---

## 🎓 Education

- **Diploma of Information Technology and Advanced Networking** (South Metropolitan TAFE, 2019–2020)

---

## 🔗 Connect

- **LinkedIn:** [danny-stanfield](https://linkedin.com/in/danny-stanfield)
- **GitHub:** [@Dstanfield-Creator](https://github.com/Dstanfield-Creator)
- **Website:** [dstanfield-creator.github.io](https://dstanfield-creator.github.io/)

---

**License:** MIT | **Last Updated:** October 2026
