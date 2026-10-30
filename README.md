# Danny Stanfield

**Junior SecOps Analyst** @ Quartex | Perth, Western Australia

I triage security incidents and run a homelab built as code. Open to SOC analyst and detection engineering roles.

---

## Featured Write-ups

- [A backup job that failed silently for a month](https://dstanfield-creator.github.io/writeups/silent-backup-failure.html)
- [The UFW rule was correct and still locked me out](https://dstanfield-creator.github.io/writeups/ufw-lockout.html)

---

## Current Focus

- **SIEM & EDR Operations**: alert triage, threat investigation, incident response
- **Detection Engineering**: writing and tuning Sigma rules in a home SOC lab
- **Zero Trust / SASE**: operating Cato SASE and Zero Trust access controls
- **Homelab Automation**: Docker, Proxmox, n8n, self-hosted infrastructure
- **Security Research**: HTB CPTS labs and defender-side technique write-ups

---

## Repositories

The full index is on [dstanfield-creator.github.io](https://dstanfield-creator.github.io/).

### Security Operations
Sigma detections, lab monitoring, technique notes and a cyber range.

- **[cyber-resources](https://github.com/Dstanfield-Creator/cyber-resources)**: the security department in one repo
  - [detections/](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/detections): detection-as-code. Sigma rules mapped to MITRE ATT&CK and validated in CI, plus the [Windows AD logging baseline](https://github.com/Dstanfield-Creator/cyber-resources/blob/master/detections/docs/windows-ad-logging-baseline-for-detection.md) they depend on
  - [monitoring/](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/monitoring): [MyDashboard](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/monitoring/mydashboard) lab health dashboard design, [reference](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/monitoring/compose/monitoring-stack) and [lab](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/monitoring/compose/lab-monitoring) Prometheus/Grafana Compose stacks, and [node_exporter setup](https://github.com/Dstanfield-Creator/cyber-resources/blob/master/monitoring/docs/prometheus-node-exporter-setup.md)
  - 48 technique and tool notes written from a defender's point of view, the [Ludus cyber range](https://github.com/Dstanfield-Creator/cyber-resources/tree/master/labs/ludus-cyber-range), and a HackTheBox tracker

### Infrastructure & Platform
Proxmox, backups, Ansible, Terraform, hardening and runbooks.

- **[lab-ops](https://github.com/Dstanfield-Creator/lab-ops)**: the homelab as code. Ansible host baseline, Compose services, Proxmox VM Terraform, and build write-ups for [Proxmox Lab Platform](https://github.com/Dstanfield-Creator/lab-ops/tree/main/docs/proxmox-lab-platform), [Proxmox Backup Server](https://github.com/Dstanfield-Creator/lab-ops/tree/main/docs/proxmox-backup-server), [Docker Services Host](https://github.com/Dstanfield-Creator/lab-ops/tree/main/docs/docker-services-host) and [Minecraft Server](https://github.com/Dstanfield-Creator/lab-ops/tree/main/docs/minecraft-server)
- **[server-administration](https://github.com/Dstanfield-Creator/server-administration)**: OpenSSH and systemd hardening, Proxmox CLI reference, and guides on [API tokens with least privilege](https://github.com/Dstanfield-Creator/server-administration/blob/master/guides/proxmox-api-token-least-privilege.md), [new-VM checklist](https://github.com/Dstanfield-Creator/server-administration/blob/master/guides/new-proxmox-vm-checklist.md) and [SSH key-auth failures](https://github.com/Dstanfield-Creator/server-administration/blob/master/guides/ssh-key-auth-failures.md)

### Network
Remote access, network design, firewalls and troubleshooting.

- **[network](https://github.com/Dstanfield-Creator/network)**: [Tailscale remote access](https://github.com/Dstanfield-Creator/network/tree/main/remote-access/tailscale-remote-access), [Pi travel router](https://github.com/Dstanfield-Creator/network/tree/main/remote-access/pi-travel-router), [Cisco enterprise network design](https://github.com/Dstanfield-Creator/network/tree/main/design/cisco-enterprise-network-design), a [firewall dead-man switch](https://github.com/Dstanfield-Creator/network/tree/main/firewall/firewall-deadman-switch) with its [runbook](https://github.com/Dstanfield-Creator/network/blob/main/firewall/remote-firewall-change.md) and [UFW baseline](https://github.com/Dstanfield-Creator/network/blob/main/firewall/ufw-baseline-linux.md), [DNS/DHCP troubleshooting](https://github.com/Dstanfield-Creator/network/blob/main/troubleshooting/dns-dhcp-and-connectivity.md), and a [network security case study](https://github.com/Dstanfield-Creator/network/tree/main/case-studies/network-security-enhancement)

### Cloud
Infrastructure as Code and cloud operations on AWS and Azure.

- **[cloud-infrastructure](https://github.com/Dstanfield-Creator/cloud-infrastructure)**: Terraform AWS VPC/EC2 baseline, AWS and Azure CLI cheatsheet, and a [Cloud Services & VM Management](https://github.com/Dstanfield-Creator/cloud-infrastructure/tree/master/case-studies/cloud-vm-management) case study

### General IT & Service Desk
Service desk methods, identity administration and PowerShell tooling.

- **[general-it](https://github.com/Dstanfield-Creator/general-it)**: troubleshooting methodology, AD and Microsoft 365 joiner-leaver checklist, change management
- **[Powershell-Scripts](https://github.com/Dstanfield-Creator/Powershell-Scripts)**: Active Directory GUI tooling for a service desk

---

## Tech Stack

**Security:** CrowdStrike Falcon, Microsoft Defender XDR, Datadog, Entra ID, Vanta, Cato SASE
**Infrastructure:** Proxmox, VMware ESXi/vCenter, Hyper-V, Zabbix, Docker, n8n, Ansible, Tailscale
**Languages:** PowerShell, Python, Bash
**Tools:** Kali Linux, Burp Suite, Nmap, Wireshark, Metasploit

---

## Certifications

- **HTB Certified Penetration Testing Specialist (CPTS)**: in progress
- **Fortinet Certified Associate in Cybersecurity** (Aug 2025, expires Aug 2027)
- **Cato Networks Zero Trust Certification** (Jul 2026)
- **Sophos Central Endpoint & Server v4.0 Engineer (ET15)** (Aug 2023)
- **Sophos Firewall Administrator**
- **Acronis Cyber Security Associate** (expires Jul 2027)
- **ITIL Foundation (PeopleCert)** (Jul 2022)

---

## Professional Experience

**Quartex**, Junior SecOps Analyst (Jan 2026 – Present)
Incident triage across CrowdStrike Falcon, Defender XDR, Datadog, Entra ID and AWS; cloud EDR coverage, SOC 2 access reviews, pen-test remediation, Zero Trust operations

**VenuesWest**, Network Analyst (Jan 2025 – Jan 2026)
Match-day IT and networking for three Matildas games at HBF Park, network infrastructure, digital signage, risk assessments

**Aeris Networks**, System Administrator / Desktop Support, Contract (Jan 2022 – Jan 2023)
Legacy file server to SharePoint and OneDrive migration, backups and disaster recovery, desktop and Microsoft 365 support, around 20 how-to guides and 5 IT policies

**NXDH**, System Engineer, BizLinQ contract (Jul 2024 – Jan 2025)
Built around 10 physical servers into two VMware vSphere clusters managed in vCenter, administered Hyper-V hosts, Zabbix alerts for server health and low disk space, network support for South West clients

**NXDH**, Junior System Engineer (Jan 2023 – Jul 2024)
Server administration, virtualisation, Active Directory, endpoint management, patching, documentation, and client website builds (HTML, CSS, JavaScript) with web/VPS hosting

**Kinetic IT / Woodside**, Senior Service Desk Officer, Contract (Jan 2021 – Jan 2022)
Escalated IT support, team mentoring, policy enforcement

**Kinetic IT / Water Corporation**, Service Desk Analyst, Contract (Jan 2020 – Jan 2021)
Desktop support, Microsoft 365, user account management, cloud/on-premise systems

**Aussie Broadband**, Help Desk Specialist (Jan 2019 – Jan 2020, alongside TAFE study)
Customer and technical support, ticket management, broadband/ISP support

---

## Education

- **Diploma of Information Technology and Advanced Networking**, South Metropolitan TAFE (2019–2020)

---

## Connect

- **LinkedIn:** [danny-stanfield](https://linkedin.com/in/danny-stanfield)
- **GitHub:** [@Dstanfield-Creator](https://github.com/Dstanfield-Creator)
- **Website:** [dstanfield-creator.github.io](https://dstanfield-creator.github.io/)

---

*Last updated: October 2026*
