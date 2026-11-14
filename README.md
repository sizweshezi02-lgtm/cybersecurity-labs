# Cybersecurity Portfolio and Hands-On Labs

Welcome to my repository showcasing practical cybersecurity engineering, Threat Monitoring/SIEM pipelines, and internal penetration testing lab reports.

## Featured Labs and Projects

### 1. Wazuh SIEM Deployment & Tier 1 Security Event Triage Lab
- **Environment:** Wazuh v4.9.2, Docker Compose, Windows 11 Pro, WSL 2 (CachyOS), Windows PowerShell.
- **Overview:** Deployed a local single-node Wazuh SIEM stack via Docker, enrolled a Windows endpoint agent (`Windows-Host-01`), and executed a controlled failed logon simulation (`Event ID 4625`) to validate **Rule ID 60122** (MITRE ATT&CK **T1110 - Brute Force**) and perform raw JSON Tier 1 SOC triage.
- **Documentation:** [View Wazuh SIEM Lab Folder](./wazuh-siem-soc-triage-lab)

### 2. Real-Time Threat Monitoring and SIEM Incident Detection Pipeline
- **Environment:** Windows 11 Pro, WSL 2, CachyOS (Arch-based), Kali Linux.
- **Overview:** Engineered a lightweight security telemetry pipeline using micro-VM kernel pooling and custom Python log-monitoring scripts (`analyzer.py`) to intercept real-time Indicators of Compromise (IoCs).
- **Documentation:** [View SIEM Lab Folder](./siem-threat-monitoring)

### 3. Internal Penetration Testing and Vulnerability Lab
- **Environment:** Oracle VM VirtualBox, Kali Linux, Metasploitable 2.
- **Overview:** Deployed an isolated host-only virtual network sandbox to conduct active Nmap reconnaissance, service mapping, and exploit execution against legacy unauthenticated services (`vsftpd 2.3.4`).
- **Documentation:** [View Pentest Lab Folder](./metasploitable2-pentest)

## Professional Background
Combining hands-on defensive security labs with over 8 years of high-volume financial operations, regulatory compliance (FICA/AML), and rigorous risk-management experience.
