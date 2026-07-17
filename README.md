# wazuh-security-monitoring-lab
Hands-on Security Monitoring and Security Configuration Assessment using Wazuh SIEM as part of the Threat Modelling and Security Monitoring Sessional (SEC 204).
# Wazuh Security Monitoring Lab

> Hands-on Security Monitoring and Security Configuration Assessment using **Wazuh SIEM** as part of the **Threat Modelling and Security Monitoring Sessional (SEC 204)** course.

---

## Overview

This project demonstrates the deployment and configuration of **Wazuh SIEM** to monitor a Windows 11 endpoint, perform security configuration assessment, analyze security events, and evaluate compliance using CIS Benchmarks.

---

# Lab Architecture

```text
Ubuntu Server (Wazuh Manager)
            │
            │ Secure Communication
            │
Windows 11 (Wazuh Agent)
            │
Security Events
Integrity Monitoring
SCA
MITRE ATT&CK
Compliance
```

---

# Dashboard Preview

## 1. Security Events Overview

![Security Events Overview](screenshots/security-events-overview.png)

This dashboard provides a centralized view of Windows security events, rule groups, alert trends, PCI DSS mappings, and event statistics collected by Wazuh.

---

## 2. Windows Agent Dashboard

![Windows Agent Dashboard](screenshots/windows-agent-dashboard.png)

The agent dashboard displays endpoint status, MITRE ATT&CK mappings, compliance information, file integrity monitoring (FIM), and Security Configuration Assessment (SCA) results.

---

## 3. Security Events Analysis

![Security Events Dashboard](screenshots/security-events-dashboard.png)

This view highlights alert evolution, top MITRE ATT&CK techniques, monitored agents, and security event trends for threat analysis.

---

## 4. Security Configuration Assessment (SCA)

![SCA Results](screenshots/sca-results.png)

Security assessment performed using the **CIS Microsoft Windows 11 Enterprise Benchmark v1.0.0**.

### Assessment Summary

| Metric | Value |
|---------|------:|
| Total Checks | 395 |
| Passed | 127 |
| Failed | 260 |
| Not Applicable | 8 |
| Compliance Score | 32% |

The assessment identified multiple opportunities to strengthen Windows security, particularly in password policies, account lockout configuration, and system hardening.

---

# Technologies Used

- Wazuh SIEM
- Ubuntu Server
- Windows 11 Enterprise
- Wazuh Agent
- Security Configuration Assessment (SCA)
- File Integrity Monitoring (FIM)
- MITRE ATT&CK
- CIS Benchmark
- PCI DSS
- HIPAA

---

# Learning Outcomes

Through this lab, I gained practical experience in:

- Deploying and configuring Wazuh SIEM
- Registering and managing Windows agents
- Monitoring Windows security events
- Analyzing alerts using MITRE ATT&CK
- Security Configuration Assessment
- Compliance monitoring
- Endpoint security analysis
- File Integrity Monitoring (FIM)

---

# Future Improvements

- Sysmon Integration
- Active Response
- Email Alerting
- Custom Detection Rules
- Sigma Rules
- Threat Hunting
- Malware Detection
- Multi-Agent Monitoring

---

# Course Information

**Course:** Threat Modelling and Security Monitoring Sessional (SEC 204)

**Program:** B.Sc. in Cyber Security Engineering

---

# Author

**Abu Sufian**

Cyber Security Engineering Student

University of Frontier Technology Bangladesh

---
