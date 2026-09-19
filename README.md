# 👋 Hi, I'm Farhan Ahmed

### Security Engineer | SOC • Detection Engineering • AppSec • DevSecOps • Security Automation

I build and secure systems across **Security Operations, Application Security, Cloud Security, DevSecOps, and Security Automation**.

My work focuses on turning security requirements into practical engineering solutions — from **SIEM deployments and detection engineering** to **VAPT, security pipelines, incident automation, and AI-assisted SOC tooling**.

> **Build. Break. Detect. Automate. Secure.**

---

## 🧑‍💻 About Me

I'm a Security Engineer with hands-on experience across defensive security and application security.

My interests sit at the intersection of:

* 🛡️ Security Operations & Detection Engineering
* 🔍 Vulnerability Assessment & Penetration Testing
* ☁️ Cloud & Infrastructure Security
* 🔐 Application Security
* ⚙️ DevSecOps & CI/CD Security
* 🤖 AI-assisted Security Operations
* 🔄 Security Automation & Incident Response
* 📊 SIEM, Threat Detection & Security Monitoring

I enjoy building security tools, automating repetitive SOC workflows, researching vulnerabilities, and turning security problems into engineering solutions.

Currently, I'm especially interested in **AI-assisted cybersecurity systems that help analysts investigate faster while keeping the human analyst in control.**

---

## 🚀 What I Do

### 🛡️ Security Operations

* SIEM deployment and administration
* Detection engineering
* Alert triage and investigation
* Log collection and analysis
* Threat intelligence enrichment
* Incident response workflows
* Security monitoring and automation
* SOC dashboards and reporting

### 🔐 Application Security

* Web Application VAPT
* OWASP Top 10
* Authentication & authorization testing
* API security
* Security headers
* Vulnerability research
* Secure development practices

### ⚙️ DevSecOps

I integrate security directly into development and deployment pipelines:

`Code → Secret Scan → SAST → Build → Container Scan → SBOM → DAST → Deploy`

Tools and technologies include:

* GitHub Actions
* Gitleaks
* Semgrep
* Trivy
* Syft
* OWASP ZAP
* Dependabot
* Docker
* DefectDojo

### ☁️ Cloud & Infrastructure Security

* Microsoft Azure
* AWS security services
* Cloud monitoring
* IAM / RBAC
* Network security
* Linux security
* Container security

---

# 🧠 Featured Project — SOCRATS

## Security Operations, Correlation, Reasoning & Threat Analysis System

**SOCRATS** is an AI-assisted SOC platform designed to help security analysts move from raw telemetry to investigation and response.

### Architecture

```text
                    ┌─────────────────────┐
                    │   Security Events   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │       Wazuh         │
                    │   Security Telemetry│
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Alert Correlation   │
                    │   & Initial Triage  │
                    └──────────┬──────────┘
                               │
                 ┌─────────────┴─────────────┐
                 ▼                           ▼
        ┌─────────────────┐        ┌─────────────────┐
        │ Threat Intel    │        │ Local AI        │
        │ Enrichment      │        │ Analysis        │
        └────────┬────────┘        └────────┬────────┘
                 │                           │
                 └─────────────┬─────────────┘
                               ▼
                    ┌─────────────────────┐
                    │ Investigation / Case│
                    │      Management      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Response & Decision │
                    └─────────────────────┘
```

### Key capabilities

* 🚨 Alert aggregation and triage
* 🤖 Local AI-assisted alert analysis
* 🔎 IOC extraction and enrichment
* 🧩 Case-centric investigations
* 📝 Analyst notes and collaboration
* 👥 Shift assignment and handovers
* 📧 Investigation and client communication workflows
* 🛡️ NSG-based response actions
* 📊 SOC metrics and reporting
* 🔄 Security automation
* 💬 SOC analyst chatbot
* 🔐 Role-based access control

### AI Architecture

SOCRATS uses **local LLM inference** to assist analysts with security analysis while keeping sensitive security telemetry within the organization's environment.

> **AI assists the analyst. The analyst makes the final decision.**

---

# 🔥 Selected Projects

### 🛡️ SOCRATS

**AI-assisted Security Operations Platform**

Security operations platform combining Wazuh telemetry, alert triage, threat intelligence, case management, automation and local AI assistance.

`Python` `Wazuh` `LLM` `Ollama` `Qwen` `SQLite` `Security Automation`

---

### 🔎 SearchOL

Security-focused search and reconnaissance tooling for information gathering and OSINT workflows.

`Python` `OSINT` `Reconnaissance` `Automation`

---

### 🕵️ SearchOL Footprinting Tool

A reconnaissance and footprinting tool that helps collect and organize discovered resources.

`Python` `Reconnaissance` `OSINT`

---

### 🧬 DFAT / FileCarver

GUI-based digital forensics tool designed for file carving and recovery from disk data.

`Python` `Tkinter` `Digital Forensics`

---

### 🔐 FarhanCryptool

Cryptography-focused security tool built for experimenting with cryptographic concepts and implementations.

`Java` `Cryptography` `Cybersecurity`

---

### 🚦 LogSentinel

Lightweight, offline-first, behavior-based web traffic defender for Apache/Nginx environments.

`Shell` `Linux` `Web Security` `Detection`

---

# 🧰 Technical Skills

### Security

![Security](https://skillicons.dev/icons?i=linux,windows)

`SOC` `SIEM` `Detection Engineering` `Threat Hunting` `VAPT` `Web Security` `API Security` `OWASP` `Incident Response` `Threat Intelligence`

### SIEM & Security Platforms

`Wazuh` `Elastic Security` `OpenSearch` `Splunk` `IBM QRadar`

### DevSecOps

`GitHub Actions` `Azure DevOps` `Gitleaks` `Semgrep` `Trivy` `Syft` `OWASP ZAP` `Dependabot` `DefectDojo`

### Cloud & Infrastructure

`Microsoft Azure` `AWS` `Docker` `Docker Compose` `Linux` `Windows Server`

### Development

`Python` `Shell` `Java` `SQL` `REST APIs` `Git` `GitHub`

### AI / Security AI

`Ollama` `Qwen` `LLM` `RAG` `AI-assisted SOC` `Local AI Inference`

---

# 🏗️ Security Engineering Philosophy

```text
                    ┌────────────────────┐
                    │      SECURITY      │
                    └─────────┬──────────┘
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
        ▼                     ▼                     ▼
   PREVENT                  DETECT               RESPOND
        │                     │                     │
        ▼                     ▼                     ▼
   AppSec /                 SIEM /              Automation /
   DevSecOps              Detection             IR / SOAR
        │                     │                     │
        └─────────────────────┼─────────────────────┘
                              │
                              ▼
                         CONTINUOUS
                         IMPROVEMENT
```

I believe security should not exist as an isolated stage.

It should be integrated throughout the lifecycle:

**Design → Develop → Test → Deploy → Monitor → Detect → Respond → Improve**

---

# 📚 Currently Exploring

* 🤖 AI for Security Operations
* 🧠 LLMs & RAG for cybersecurity
* 🔍 Detection Engineering
* 🛡️ Threat Detection & Response
* ☁️ Cloud Security
* 🔐 Application Security
* ⚙️ Security Automation
* 🏗️ Security Engineering

---

## <img src="https://cdn.simpleicons.org/github/ffffff" width="22" /> GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=farhanahmedindia&show_icons=true&theme=transparent&hide_border=true" height="170" alt="GitHub Statistics" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=farhanahmedindia&layout=compact&theme=transparent&hide_border=true&langs_count=8" height="170" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=farhanahmedindia&theme=transparent&hide_border=true" height="170" alt="GitHub Contribution Streak" />
</p>

---

# 🌐 Find Me Online

### 💼 Professional

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Farhan%20Ahmed-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/farhanahmedindia/)

### 💻 GitHub

[![GitHub](https://img.shields.io/badge/GitHub-farhanahmedindia-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/farhanahmedindia)

### ▶️ YouTube

[![YouTube](https://img.shields.io/badge/YouTube-Alfabit-FF0000?style=for-the-badge\&logo=youtube\&logoColor=white)](https://www.youtube.com/@Alfabitsec)

### 📸 Instagram

[![Instagram](https://img.shields.io/badge/Instagram-Farhan%20Ahmed-E4405F?style=for-the-badge\&logo=instagram\&logoColor=white)](https://www.instagram.com/farhan.ahmed647/)

---

# 🌍 Projects & Work

### 🔐 RiskBrief

Cybersecurity-focused project exploring security information, research and threat awareness.

🌐 **riskbrief.io**

### 🦉 SOCRATS

AI-assisted Security Operations platform focused on helping SOC analysts investigate and respond to security events.

---

# ✍️ I Write About

I regularly share content around:

* Cybersecurity
* Security incidents & breaches
* Vulnerability research
* SOC & SIEM
* Application Security
* DevSecOps
* Security tools
* AI & cybersecurity
* Practical security engineering

---

# 🤝 Let's Connect

I'm interested in connecting with:

* Security Engineers
* SOC Analysts
* Detection Engineers
* AppSec Engineers
* DevSecOps Engineers
* Security Researchers
* Cybersecurity builders
* Open-source contributors
* People building AI × Security products

If you're building something interesting in cybersecurity, feel free to connect.

---

<p align="center">

### 🔐 Secure by Design. Detect by Default. Automate Everything Possible.

**— Farhan Ahmed**

</p>
