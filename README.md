# 👋 Hey, I'm Khalil Ghiati

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=4000&pause=1000&color=4ADE80&center=true&vCenter=true&width=650&lines=AI+Infrastructure+Engineer;DevSecOps+%26+Cloud+Security;LLM+Agents+for+Production+Systems;5G+%26+Telecom+Expert)](https://portfolio-khalil-secure.vercel.app/)

**Lyon, France — Open to opportunities at the intersection of AI and infrastructure**

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-khalil-secure.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Khalil-secure)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-ghiati-khalil)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:medkhalilghiati@gmail.com)

---

## About Me

```yaml
name: M. Khalil Ghiati
role: AI Infrastructure Engineer
focus:
  - LLM agents for infrastructure automation
  - DevSecOps & Cloud Security
  - Zero Trust architectures on Kubernetes
  - 5G / Telecom Infrastructure
current_position: Chef de Projet Télécom @ Bouygues Telecom
location: Lyon, France
languages: [French, English (TOEIC 940), Arabic]
seeking: AI Infrastructure / DevSecOps / Tech-Ops roles
```

I build systems where **AI is a first-class infrastructure component** — not a plugin bolted on top.
My background spans **5G telecom, cloud architecture, and cybersecurity**, and I'm now applying that foundation to make infrastructure smarter and self-healing through LLM agents.

---

## 🤖 Featured Project — AI as Infrastructure

> **An autonomous agent that monitors, diagnoses, and heals your infrastructure**

[![AII Demo](https://raw.githubusercontent.com/Khalil-secure/AI_as_infrastructure/main/AI_as_infrastructure_demo.gif)](https://github.com/Khalil-secure/AI_as_infrastructure)

**[→ View Project](https://github.com/Khalil-secure/AI_as_infrastructure)**

### What it does

A **LangGraph** multi-agent pipeline that runs alongside your Docker infrastructure:

- **Watcher** — monitors containers 24/7, zero tokens spent when everything is nominal
- **Detector** — classifies anomalies: `OOM | CONTAINER_CRASH | NETWORK | DISK_FULL | SERVICE_DOWN`
- **Responder** — calls Claude (Anthropic) to diagnose root cause and generate a targeted action plan
- **Memory** — ChromaDB vector store remembers past incidents, recognises known patterns instantly
- **Trust Layer** — every action requires human approval before execution. Approve, modify, or skip
- **Verifier** — after executing a fix, re-checks the system to confirm the incident is actually resolved
- **Budget guard** — hard stop at €0.50. Average cost per incident: ~€0.02. Cost at 0 anomalies: €0

```
LOCAL CONTROL PLANE  ──→  watcher.py detects anomaly (0 tokens)
        │
        ▼
  pipeline.py triggers
    detector.py  ──→  classify incident
    responder.py ──→  Claude diagnoses + action plan
    memory.py    ──→  ChromaDB pattern matching
        │
        ▼
  TRUST LAYER  ──→  human approves / modifies / skips
        │
        ▼
  Docker SDK executes  ──→  verifier re-checks (resolved / still present)
```

### Stack
`Python` `LangGraph` `Claude API (Anthropic)` `ChromaDB` `Docker SDK` `Prometheus` `Grafana` `Nginx`

---

### 🔭 Future Vision

This project is a foundation. Here's where it goes next:

| Milestone | Description | Status |
|-----------|-------------|--------|
| **Kubernetes support** | Extend watcher to K8s pods, deployments, CrashLoopBackOffs | 🔜 Planned |
| **AI Post-Mortem Generator** | Auto-generate incident reports from logs + metrics after every incident | 🔜 Planned |
| **Natural Language Infra** | Describe infrastructure in plain English → agent writes & deploys Terraform/Compose | 🔜 Planned |
| **Adaptive thresholds** | Learn baseline behaviour per service, replace fixed 95% CPU threshold | 🔜 Planned |
| **Multi-environment** | Dev / staging / prod config profiles with environment-aware actions | 🔜 Planned |
| **Auto-execution mode** | Skip trust layer above a configurable confidence score (>80%) | 🔜 Planned |
| **Alert deduplication** | Prevent notification spam on persistent unresolved issues | 🔜 Planned |
| **Grafana AII dashboard** | Real-time visibility into the agent's own activity and cost | 🔜 Planned |

> The end goal: infrastructure that explains itself, fixes itself, and documents itself — with a human always in the loop.

---

## 🛡️ Other Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [**MailGuard**](https://github.com/Khalil-secure/Mailguard_extension_preview) | Browser extension detecting phishing & social engineering in real time | JS, Chrome API, NLP |
| [**MailGuard Alternative**](https://github.com/Khalil-secure/MailGuard_alternative) | Lightweight variant with extended BEC & spoofing detection rules | JS, Chrome API |
| **Zero Trust Lab** | Full K8s Zero Trust: Istio mTLS, Cilium, OPA Gatekeeper | Kubernetes, Istio, Terraform |
| **ELK SIEM** | Production SIEM with Suricata IDS, automated Wazuh responses | ELK, Suricata, Wazuh |

---

## 🛠️ Tech Stack

### AI & Automation
![Claude API](https://img.shields.io/badge/Claude_API-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-4B0082?style=for-the-badge&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1a73e8?style=for-the-badge&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Cloud & Infrastructure
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### DevOps & Automation
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Security & Zero Trust
![Istio](https://img.shields.io/badge/Istio_mTLS-466BB0?style=for-the-badge&logo=istio&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata_IDS-EF3B2D?style=for-the-badge&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard_VPN-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![Vault](https://img.shields.io/badge/HashiCorp_Vault-000000?style=for-the-badge&logo=vault&logoColor=white)
![OPA](https://img.shields.io/badge/OPA_Gatekeeper-7D3F98?style=for-the-badge)

### Monitoring & Observability
![ELK](https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F7A81B?style=for-the-badge)

### Telecom
![5G](https://img.shields.io/badge/5G%2FLTE-00979D?style=for-the-badge)
![FTTH](https://img.shields.io/badge/FTTH%2FDWDM-004B87?style=for-the-badge)
![ANSSI](https://img.shields.io/badge/ANSSI_Compliance-003087?style=for-the-badge)

---

## 📊 GitHub Stats

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Khalil-secure&theme=tokyonight)](https://git.io/streak-stats)

[![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=Khalil-secure&theme=tokyo-night)](https://github.com/Khalil-secure)

---

## Beyond the Terminal

**Languages:** 🇫🇷 French — Fluent &nbsp;|&nbsp; 🇬🇧 English — TOEIC 940/990 &nbsp;|&nbsp; 🇸🇦 Arabic — Native

**Interests:** 🥋 Karate Shodan (Black Belt) &nbsp;|&nbsp; 🤼 BJJ &nbsp;|&nbsp; 🏆 CTF (Root-Me, TryHackMe) &nbsp;|&nbsp; 🌐 Hackathons (Lablab.ai)

---

[![Email](https://img.shields.io/badge/Get_in_touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:medkhalilghiati@gmail.com)
[![Portfolio](https://img.shields.io/badge/View_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-khalil-secure.vercel.app/)

![Profile Views](https://komarev.com/ghpvc/?username=Khalil-secure&label=Profile+Views&color=4ade80&style=flat)
