# 🛡️ ACTIS – Advanced Cyber Threat Intelligence System

ACTIS (Advanced Cyber Threat Intelligence System) is a Machine Learning-powered cybersecurity application designed to detect, classify, analyze, and monitor potential cyber threats.

The system combines **Python, Flask, Machine Learning, SQLite, and MITRE ATT&CK** to provide an intelligent platform for cybersecurity threat detection and security alert management.

---

## 🎯 Project Overview

ACTIS analyzes network-traffic characteristics and uses a **Random Forest Machine Learning model** to identify potential security threats.

The system can classify network activity into different threat categories, calculate confidence and risk scores, generate security alerts, and correlate detected threats with relevant **MITRE ATT&CK techniques**.

ACTIS also provides an interactive dashboard, traffic simulation, alert management, and PDF/Excel security reporting.

---

## 🚨 Threats Detected

ACTIS currently supports the following threat categories:

| Threat | Severity |
|---|---|
| 🟢 Normal | None |
| 🔎 Port Scan | Low |
| 🎣 Phishing | Medium |
| 🔑 Brute Force | Medium |
| 🦠 Malware | High |
| 💥 DDoS | Critical |

---

## ✨ Key Features

### 🤖 Machine Learning Threat Detection

- Random Forest classification
- Network traffic analysis
- Threat classification
- Prediction confidence
- Risk score calculation
- Feature-based detection

### 🛡️ MITRE ATT&CK Integration

ACTIS maps detected threats to relevant MITRE ATT&CK techniques and provides security recommendations.

Example mappings:

| Threat | MITRE ATT&CK |
|---|---|
| DDoS | T1498 |
| Phishing | T1566 |
| Brute Force | T1110 |
| Port Scan | T1046 |

### 🚨 Alert Management

- Create security alerts
- View alerts
- Search alerts
- Filter by severity
- Filter by threat type
- Update alert status
- Delete alerts
- Track investigation status

Alert statuses include:

```text
Open
Investigating
Resolved
