# 🛡️ Security Engineering Portfolio — Blue Team / SecOps / Detection Engineering

Hands-on projects demonstrating **Microsoft Sentinel**, **detection engineering**, **incident response**, **threat hunting**, and **automation**. This is the hub that links all repos in my blue-team stack.

---

## 🎯 Core Skills Demonstrated
- Detection Engineering (KQL, Sigma, Windows/Linux/Sysmon signals)
- SIEM Operations in Microsoft Sentinel
- Incident Triage & Investigation (MITRE ATT&CK aligned)
- Threat Hunting Workflows
- Log Ingestion & Normalization (Sysmon, Windows Event Logs, Linux auth, DNS)
- Automation & Enrichment (PowerShell/Python, SOAR/Logic Apps)
- Lab Architecture (pfSense, VLANs, Proxmox/VMware/Hyper-V, Azure)

---

## 📂 Project Index (6 Repos)

### ✅ **Repo 1 – Security Operations & Detection Engineering**
**Focus:** SIEM, Detection Rules, Incident Response  
This project showcases hands-on SecOps skills using Microsoft Sentinel. It includes detection rules, incident investigations, log samples, and automation scripts used to identify and respond to suspicious activity in a simulated enterprise environment.  
🔗 Repo: https://github.com/kvntynito/1-secops-detentions-sentinel

### ✅ **Repo 2 – Vulnerability Management**
**Focus:** Nmap, OpenVAS/GVM, Risk Analysis  
This project demonstrates hands-on vulnerability management using Nmap and OpenVAS/GVM. Includes scan outputs, analysis reports, risk matrices, and remediation planning based on real test environments.  
🔗 Repo: https://github.com/kvntynito/2-vuln-mgmt-openvas-lab

### ✅ **Repo 3 – Endpoint Hardening (Windows & Linux)**
**Focus:** System Hardening, Baselines, Validation  
This project shows practical endpoint hardening for both Windows and Linux systems. Includes baselines, configuration changes, validation steps, and evidence showing how systems were strengthened against common attack vectors.  
🔗 Repo: https://github.com/kvntynito/3-endpoint-hardening-windows-linux

### ✅ **Repo 4 – Cloud Security (Azure)**
**Focus:** Azure IAM, Security Reviews, Sentinel  
This project demonstrates hands-on cloud security inside Microsoft Azure. It includes Azure security reviews, Sentinel analyses, IAM evaluations, architecture mapping, and evidence from a real mini-lab built on Azure free-tier resources.  
🔗 Repo: https://github.com/kvntynito/4-azure-security-mini-lab

### ✅ **Repo 5 – Governance, Risk & Compliance (GRC)**
**Focus:** NIST, ISO, PCI, Risk Management  
This project demonstrates core GRC skills including security policies, risk matrices, governance documentation, and mapping to frameworks such as NIST CSF, NIST 800-53, ISO27001, and PCI-DSS.  
🔗 Repo: https://github.com/kvntynito/5-grc-policies-and-risk

### ✅ **Repo 6 – Cybersecurity Automation & Scripting**
**Focus:** PowerShell, Python, Bash, Automation Tools  
This project showcases cybersecurity automation across multiple scripting languages. It includes tools for log parsing, alert generation, evidence collection, and security task automation used in real SecOps, SOC, and IR workflows.  
🔗 Repo: https://github.com/kvntynito/6-sec-automation-py-ps-bash


---

## 🧪 Lab Topology (Quick View)
- **Hosts:** Proxmox/VMware/Hyper-V/Docker
- **VMs:** Windows Server 2019, Ubuntu 22.04, Kali
- **Network:** pfSense with two VLANs (Home / Lab)
- **Cloud:** Azure (Sentinel, Log Analytics, Defender for Cloud, Entra ID)

> Diagram lives in: `repo-5/docs/architecture/` (linked above)

---

## 🚨 What’s Implemented
- ✅ Detection rules (KQL) — mapped to MITRE ATT&CK  
- ✅ Incident reports — triage, queries, findings  
- ✅ Sample logs — Windows/Sysmon/Linux for reproducible tests  
- ✅ Sentinel configuration — Analytics, Data Connectors, Incidents  
- ✅ Automation — enrichment scripts & SOAR (work-in-progress)

---

## ▶️ How to Explore
1. Start with **Repo 1** (detections) → read the `README` and open `detections/`.
2. Open **Repo 6** (Sentinel) → see how detections deploy and generate incidents.
3. Check **Repo 2** (IR) → read a full investigation writeup with screenshots.
4. Browse **Repo 4** (automation) → run a small enrichment script on sample IOCs.
5. View **Repo 5** (lab) → see the architecture + IaC/config snapshots.

---

## 📈 Roadmap (Next Up)
- +10 detections (brute force, persistence, malware, lateral movement)
- Logic Apps (SOAR) auto-response flows
- Enrichment with VirusTotal/AbuseIPDB integrations
- Add Apache & DNS logs; build a hunting workbook
- Publish a small “Playbook Pack” PDF in `docs/`

---

## 🧠 Selected Learnings
- Writing reliable **KQL** detections and tuning false positives
- Joining log sources (Windows/Sysmon/Linux) for better signal
- Mapping detections to **MITRE ATT&CK** tactics/techniques
- Sentinel Incident flow: Analytics → Alerts → Incidents → Investigation
- Repeatable lab patterns using pfSense + VLANs + Azure

---

## 📬 Contact
- GitHub: https://github.com/kvntynito 
- LinkedIn/Portfolio/Email: _add your links here_

---

## ⚖️ License
MIT — see `LICENSE`.
