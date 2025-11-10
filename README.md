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

| Repo | Focus | What to Look At |
|---|---|---|
| **Repo 1 – Detection Engineering** | Sentinel detections, templates, Sysmon signals | `detections/`, `incidents/`, `docs/templates/`, PowerShell EncodedCommand rule |
| **Repo 2 – Incident Response** | IR runbooks, timelines, artifacts | Incident reports, evidence collection checklists, triage notes |
| **Repo 3 – Threat Hunting** | Hypothesis-driven hunts | Hunting notebooks, KQL hunts, pivot patterns |
| **Repo 4 – SOC Automation** | Scripts + SOAR | `scripts/` (PowerShell/Python), Logic Apps JSON, enrichment with VT/AbuseIPDB |
| **Repo 5 – Lab & Architecture** | Infra-as-lab | `lab/` datasets, Sysmon configs, pfSense VLAN diagram |
| **Repo 6 – Cloud/Sentinel** | Azure setup | Sentinel + Log Analytics setup notes, data connectors, workbooks |

> Replace each line with real links:
>
> - Repo 1: https://github.com/your-username/repo-1  
> - Repo 2: https://github.com/your-username/repo-2  
> - Repo 3: https://github.com/your-username/repo-3  
> - Repo 4: https://github.com/your-username/repo-4  
> - Repo 5: https://github.com/your-username/repo-5  
> - Repo 6: https://github.com/your-username/repo-6

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
