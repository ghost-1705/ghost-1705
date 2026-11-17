<div align="center">

# Aswin CP
### Security Researcher • Red Team Operator • Technical Instructor
**Offensive & Defensive Security • Zero Trust Architecture • MCP AI Security • Mobile VAPT**

[![Focus: Offensive & Defensive Security](https://img.shields.io/badge/Focus-Red%20%26%20Blue%20Team%20Tradecraft-163832?style=for-the-badge)](#)
[![Domain: Zero Trust & NAC](https://img.shields.io/badge/Architecture-NIST%20SP%20800--207%20Zero%20Trust-235347?style=for-the-badge)](#)
[![AI Security: MCP & LLM](https://img.shields.io/badge/AI%20Security-Model%20Context%20Protocol%20(MCP)-0B2B26?style=for-the-badge)](#)
[![Role: Technical Instructor](https://img.shields.io/badge/Role-Technical%20Instructor-051F20?style=for-the-badge)](#)

<br/>

[🌐 **Explore Interactive Web Portfolio**](https://ghost-1705.github.io/portfolio) • [📧 **Secure Email (Proton)**](mailto:aswin.cp.sec@proton.me) • [💼 **LinkedIn**](https://www.linkedin.com/in/aswin-cp-2493bb1ba)

</div>

---

### 🛡️ Executive Dossier

Security researcher and technical instructor bridging adversary emulation (**Red Teaming**) with enterprise defensive engineering (**Blue Teaming**). Specializing in **Zero Trust Network Access Control (Cisco ISE 3.2 / 802.1X)**, high-throughput **attack surface discovery (VAPT)**, **Model Context Protocol (MCP)** toolchain engineering for autonomous security operations, and hands-on **mobile application reverse engineering**.

---

### 🎖️ Certifications & Professional Accreditations

<div align="center">

| Credential | Specialization / Scope |
| :--- | :--- |
| **OSCP / CRTO** | Adversary Emulation, Active Directory Exploitation, Cobalt Strike / Sliver C2 |
| **Cisco ISE 3.2** | Enterprise Network Access Control (NAC), 802.1X EAP-TLS, Dynamic Segmentation & dACLs |
| **CEH Master / PNPT** | Enterprise Vulnerability Assessment & Practical Penetration Testing |
| **NIST SP 800-207** | Enterprise Zero Trust Architecture & Policy Enforcement Design |
| **Technical Instructor** | Accredited Lead for Hands-On Advanced Defensive & Offensive Labs |

</div>

---

### 🎯 Core Specializations

| Domain | Focus Areas & Competencies |
| :--- | :--- |
| **⚔️ Offensive Security & Red Teaming** | Active Directory exploitation (Kerberoasting, BloodHound), C2 operations (Cobalt Strike, Sliver), userland EDR unhooking, direct Win32 syscalls, API & Web App VAPT (OWASP Top 10). |
| **🛡️ Defensive Architecture & Zero Trust** | Zero Trust Architecture (NIST SP 800-207), Identity Services Engine (Cisco ISE 3.2, 802.1X, EAP-TLS), Dynamic Segmentation (dACLs, VLAN steering), RFC 5176 CoA. |
| **🤖 AI Security & Model Context Protocol (MCP)** | Custom MCP servers (JSON-RPC over stdio/SSE) connecting LLMs (Claude, GPT, Gemini) to sandboxed security tools, LLM Red Teaming (OWASP Top 10 for LLMs), prompt injection guardrails. |
| **📡 SOC & Detection Engineering** | Real-time threat detection (Splunk, Wazuh EDR, Elastic SIEM), authoring custom Sigma detection rules & YARA signatures mapped to MITRE ATT&CK, Suricata & Sysmon telemetry. |
| **📱 Mobile Pentesting & Reversing** | Dynamic APK/IPA instrumentation with Frida, SSL pinning & root/jailbreak detection bypass, OWASP Mobile Top 10, cryptographic audit. |
| **⚙️ Security Automation & DevSecOps** | Infrastructure as Code for security (Ansible, Docker), Python AsyncIO high-throughput tooling, CI/CD pipeline vulnerability auditing. |

---

### 🛠️ Technical Arsenal

| Category | Technologies & Tools |
| :--- | :--- |
| **Offensive & Auditing** | `Cobalt Strike` `Sliver` `Burp Suite Pro` `Frida` `BloodHound` `Impacket` `Nmap` `Metasploit` `Nuclei` |
| **Defensive & Telemetry** | `Cisco ISE 3.2` `Splunk Enterprise` `Wazuh EDR` `Elastic SIEM` `Sysmon` `Suricata` `Zeek` `Wireshark` |
| **AI & Automation** | `Model Context Protocol (MCP)` `Python AsyncIO` `Ansible` `JSON-RPC` `Docker` `GitHub Actions` |
| **Protocols & Standards** | `802.1X` `EAP-TLS` `RADIUS (RFC 2865 / 5176)` `NIST SP 800-207` `OWASP Top 10` `MITRE ATT&CK` |

---

### 🏆 Featured Research & Architecture

#### 1. 🔐 [Zero Trust Network Access Control (ZTNA) Reference Architecture](https://github.com/ghost-1705/zero-trust-cisco-ise)
*Enterprise-grade implementation of NIST SP 800-207 Zero Trust Architecture using Cisco ISE 3.2, 802.1X/EAP-TLS, and Python/Ansible automation.*

<p align="left">
  <a href="https://github.com/ghost-1705/zero-trust-cisco-ise"><img src="https://img.shields.io/badge/Cisco%20ISE-3.2-163832?style=flat-square&logo=cisco" alt="Cisco ISE" /></a>
  <a href="https://github.com/ghost-1705/zero-trust-cisco-ise"><img src="https://img.shields.io/badge/Protocol-802.1X%20%7C%20EAP--TLS-235347?style=flat-square" alt="Protocol" /></a>
  <a href="https://github.com/ghost-1705/zero-trust-cisco-ise"><img src="https://img.shields.io/badge/Framework-NIST%20SP%20800--207-0B2B26?style=flat-square" alt="Framework" /></a>
  <a href="https://github.com/ghost-1705/zero-trust-cisco-ise"><img src="https://img.shields.io/badge/Automation-Ansible%20%7C%20Python-051F20?style=flat-square&logo=ansible" alt="Automation" /></a>
  <a href="https://github.com/ghost-1705/zero-trust-cisco-ise/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-8EB69B.svg?style=flat-square" alt="License" /></a>
</p>

- **Identity & Access Management**: Enforces strict policy decision/enforcement separation with mutual certificate authentication (EAP-TLS).
- **Dynamic Policy Enforcement**: Implements dynamic VLAN allocation, downloadable ACLs (dACLs), and automated Change of Authorization (CoA).
- **Automation & Telemetry**: Ansible playbooks for repeatable network hardening alongside Wireshark PCAPs validating protocol handshakes.

---

#### 2. 🤖 [SecOps-MCP Server — Autonomous Security Operations via LLM](https://github.com/ghost-1705/secops-mcp-server)
*Enterprise Model Context Protocol (MCP) server connecting LLM agents to offensive and defensive security toolchains with sandboxed privilege isolation.*

<p align="left">
  <a href="https://github.com/ghost-1705/secops-mcp-server"><img src="https://img.shields.io/badge/Protocol-Model%20Context%20Protocol%20(MCP)-0B2B26?style=flat-square" alt="MCP" /></a>
  <a href="https://github.com/ghost-1705/secops-mcp-server"><img src="https://img.shields.io/badge/Transport-JSON--RPC%20over%20stdio%20%26%20SSE-163832?style=flat-square" alt="JSON-RPC" /></a>
  <a href="https://github.com/ghost-1705/secops-mcp-server"><img src="https://img.shields.io/badge/Security-Zero--Credential%20Sandbox-235347?style=flat-square" alt="Security" /></a>
</p>

- **16+ Sandboxed SecOps Tools**: Exposes automated Wazuh EDR querying, VirusTotal & Shodan threat enrichment, and live Nmap scanning.
- **Autonomous Incident Triage**: Compiles natural-language incident queries into production-ready Sigma detection rules mapped to MITRE ATT&CK.

---

#### 3. ⚡ [OmniRecon-Engine — High-Throughput Attack Surface Discovery](https://github.com/ghost-1705/omnirecon-engine)
*Asynchronous, multi-threaded attack surface exploration platform parsing 50,000 req/sec across DNS, ASN records, and Certificate Transparency.*

<p align="left">
  <a href="https://github.com/ghost-1705/omnirecon-engine"><img src="https://img.shields.io/badge/Engine-Python%20AsyncIO%20%7C%20MassDNS-0B2B26?style=flat-square" alt="AsyncIO" /></a>
  <a href="https://github.com/ghost-1705/omnirecon-engine"><img src="https://img.shields.io/badge/Throughput-50%2C000%20req%2Fsec-163832?style=flat-square" alt="Speed" /></a>
  <a href="https://github.com/ghost-1705/omnirecon-engine"><img src="https://img.shields.io/badge/VAPT-OWASP%20Perimeter%20Audit-235347?style=flat-square" alt="VAPT" /></a>
</p>

- **Massive Concurrency**: Correlates ASN allocations, subdomains, and live services across large enterprise network blocks in minutes.
- **Automated VAPT Reporting**: Identifies exposed admin panels, GraphQL introspection endpoints, and expired certificates with structured JSON exports.

---

### 📈 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ghost-1705&show_icons=true&bg_color=051F20&title_color=DAF1DE&text_color=8EB69B&icon_color=235347&border_color=163832&hide_border=false&count_private=true" width="48%" alt="Aswin's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ghost-1705&layout=compact&bg_color=051F20&title_color=DAF1DE&text_color=8EB69B&border_color=163832&hide_border=false" width="48%" alt="Top Languages" />
</div>

---

### 📬 Get in Touch

<div align="center">

Whether you're interested in offensive/defensive security research, Model Context Protocol (MCP) integrations, enterprise architecture, or technical training & workshops:

<br/>

[![Email Proton](https://img.shields.io/badge/Email-aswin.cp.sec%40proton.me-163832?style=for-the-badge&logo=protonmail&logoColor=DAF1DE)](mailto:aswin.cp.sec@proton.me)
[![Email Gmail](https://img.shields.io/badge/Email-aswincp1705%40gmail.com-235347?style=for-the-badge&logo=gmail&logoColor=DAF1DE)](mailto:aswincp1705@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aswin%20CP-0B2B26?style=for-the-badge&logo=linkedin&logoColor=DAF1DE)](https://www.linkedin.com/in/aswin-cp-2493bb1ba)
[![Signal](https://img.shields.io/badge/Signal-%40aswincp.01-163832?style=for-the-badge&logo=signal&logoColor=DAF1DE)](https://signal.me)
[![GitHub](https://img.shields.io/badge/GitHub-ghost--1705-051F20?style=for-the-badge&logo=github&logoColor=DAF1DE)](https://github.com/ghost-1705)

</div>
