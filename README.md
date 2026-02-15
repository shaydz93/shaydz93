# Hi there, I'm ShaydZ 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/zachary-mason-96805190)
[![GitHub](https://img.shields.io/badge/GitHub-shaydz93-black?logo=github)](https://github.com/shaydz93)

---

## 👨‍💻 About Me

I'm a **Tier 2 IT Support & Cybersecurity Specialist** based in Carrollton, GA. I build production-grade security tools that combine AI-powered threat detection, network monitoring, and automated defense systems.

- 🔭 Currently maintaining **Super Monitor v3** — Rust-powered network defense platform
- 🛡️ Running enterprise-grade security stack: Suricata IDS, YARA malware scanning, threat intel feeds
- 🤖 Integrating local LLMs (Ollama/kimi-k2.5) for real-time threat analysis
- 🌱 Deep into OSINT, digital forensics, and purple team operations
- 💬 Ask me about: Rust, Python, network defense, threat intelligence, OSINT, Proxmox homelabs
- ⚡ Fun fact: I run a 34-device network with full packet mirroring and AI-driven anomaly detection

---

## 🛠️ Featured Projects

### 🚀 Super Monitor v3 (Rust Rewrite)
The ultimate self-learning network defense and AI threat intelligence platform — completely rewritten in Rust for memory safety and performance.

**Security Hardened:**
- ✅ Async/await architecture (Tokio + Axum)
- ✅ Argon2 + JWT authentication
- ✅ 20-30x faster startup, 5x less memory usage
- ✅ All 9 Python vulnerabilities patched

**Features:**
- 🤖 AI-powered anomaly detection with self-learning baselines
- 📊 Real-time system monitoring (CPU, RAM, disk, network)
- 🔍 Threat intelligence from CISA, KrebsOnSecurity, BleepingComputer
- 🔔 Automated responses: firewall blocking, temperature shutdowns
- 🌐 Interactive web dashboard with real-time charts

**Tech Stack:** Rust, Tokio, Axum, Askama, SQLx  
🔗 https://github.com/shaydz93/super-monitor-v3

---

### 🤖 AI Trading Bots
Automated cryptocurrency trading systems with n8n workflow orchestration and technical analysis integration.

- **cs4**: C#/.NET Core trading bot with TAAPI technical analysis
- **q3**: Python-based bot with advanced risk management

**Security Features:**
- API keys stored in n8n encrypted credential vault
- No hardcoded secrets (environment variable only)
- Docker containerized deployment

🔗 https://github.com/shaydz93/ai-trading-bot-cs4 (private)  
🔗 https://github.com/shaydz93/ai-trading-bot-q3 (private)

---

### 📱 ShaydZ-AVMo (iOS)
Swift-based iOS application for personal security and monitoring.

**Tech Stack:** Swift, SwiftUI, Supabase  
🔗 https://github.com/shaydz93/ShaydZ-AVMo

---

### 🧰 MigrationTool
Python utility for automated system migrations and configuration transfers.

🔗 https://github.com/shaydz93/MigrationTool

---

## 🔧 Tech Stack & Tools

**Languages:**
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

**Security & Defense:**
- **IDS/IPS:** Suricata with 235k+ daily updated threat IOCs
- **Malware Scanning:** ClamAV + 1,538 YARA rules
- **Network Monitoring:** Full packet capture, real-time alerting
- **OSINT Toolkit:** theHarvester, Sherlock, Recon-ng, Shodan CLI
- **Forensics:** exiftool, binwalk, foremost, steghide

**Infrastructure:**
- **Virtualization:** Proxmox VE with Windows VMs
- **Network:** 34-device network with mirrored port monitoring
- **Security Stack:** UFW, Fail2ban, rkhunter, unattended-upgrades
- **AI/LLM:** Ollama with kimi-k2.5 for local threat analysis

**DevOps:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## 🛡️ Current Security Stack

```
┌─────────────────────────────────────────────────┐
│         AI Threat Analysis (Ollama)            │
│    Daily 8 AM reports → Telegram alerts        │
└──────────────────┬──────────────────────────────┘
                   │
┌──────────────────▼──────────────────────────────┐
│         Suricata IDS (Real-time)              │
│   235k+ IOCs | Sub-10s alerting | Full mirror  │
└──────────────────┬──────────────────────────────┘
                   │
┌──────────────────▼──────────────────────────────┐
│      Active Malware Protection                  │
│   ClamAV daemon + YARA rules (1,538 rules)    │
│   Real-time file monitoring on /home, /tmp      │
└─────────────────────────────────────────────────┘
```

**Alerting:** Telegram notifications for critical events  
**Monitoring:** 24/7 automated with cron jobs and systemd services  
**Location:** Proxmox homelab (SZN-DebianBot)

---

## 🏠 Homelab Setup

**Host:** SZN-DebianBot (Debian 13 rolling, x86_64)  
**Network:** 192.168.1.0/24 with Tailscale mesh VPN  
**Virtualization:** Proxmox VE
- Windows 10 VM (192.168.1.195) - Security testing
- Debian 12 containers for services
- NAS storage (192.168.1.219)

**Network Devices:** 34 total
- Denon AVR-S760H (hardened, Telnet blocked)
- Samsung SmartThings (SSDP alerts suppressed)
- Multiple IoT devices under Suricata monitoring

---

## 🎯 OSINT & Cybersecurity Focus

**Active Projects:**
- Digital forensics toolkit development
- Threat intelligence feed automation
- AI-powered log analysis for C2 detection
- Network anomaly detection with local LLMs

**Certifications:**
- CCNA (In Progress - 200-301)
- CompTIA Security+ (Planned)

---

## 🖤💜 Dark Purple Team

We don't just defend — we hunt.

- Code reviews in hex `#663399`
- Midnight threat hunts fueled by purple tea
- Ultra Dark Purple Mode: activated
- "A bug turned purple on sight of our CI pipeline — and never returned"

---

## 📫 Connect with Me

- 🌐 **LinkedIn:** [Zachary Mason](https://www.linkedin.com/in/zachary-mason-96805190)
- 📧 **Email:** zacharym@shaydznet.com
- 💬 **Telegram:** @ShaydZ93

---

> "Monitor smarter. Secure better. Deploy with confidence."  
> — The Dark Purple Team 🖤💜

![Profile Views](https://komarev.com/ghpvc/?username=shaydz93&color=purple)
