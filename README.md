# 🔐 Wazuh SIEM – File Integrity Monitoring (FIM)

## 📌 Project Overview
This project demonstrates the implementation of **Wazuh SIEM** to perform **File Integrity Monitoring (FIM)** in a controlled home lab environment. The lab focuses on detecting unauthorized file changes, generating real-time alerts, and analyzing security events through the Wazuh dashboard, aligned with **SOC Analyst** responsibilities.

---

## 🎯 Objectives
- Deploy a functional Wazuh SIEM environment
- Register and monitor an endpoint using Wazuh Agent
- Enable File Integrity Monitoring (FIM)
- Detect file creation, modification, and deletion
- Analyze security alerts in the Wazuh Dashboard

---

## 🧱 Lab Architecture

- **SIEM Server:** Ubuntu (Wazuh Manager & Dashboard)
- **Monitored Endpoint:** Linux / Windows Agent
- **Attack Simulation:** Manual file modification

Architecture Flow:  
Agent → Wazuh Manager → Dashboard Alerts

---

## 🛠 Tools & Technologies
- **Wazuh SIEM**
- **Ubuntu Server (20.04+)**
- **Windows OS (Agent endpoint)**
- VirtualBox
- Linux system logs


---

## ⚙ Configuration Summary
- Installed and configured Wazuh Manager
- Deployed Wazuh agent on monitored system
- Enabled **File Integrity Monitoring (FIM)**
- Configured monitored directories and files
- Verified agent-to-manager communication

---

## 🧪 Activity Simulation
To validate File Integrity Monitoring, the following actions were performed:
- Created new files in the monitored directory
- Modified existing files
- Deleted files
- Observed permission-related changes

---

## 🚨 Detection & Alert Analysis
- File change events were successfully detected
- Alerts were generated in real time
- Alert details included:
- File path
- Type of change (created / modified / deleted)
- Timestamp
- Affected user
- Events were visible in the **Integrity Monitoring** section of the Wazuh dashboard

---

## 📸 Evidence
The following evidence can be found in the repository:
- Wazuh dashboard overview
- Active agent status
- File integrity alert details

(Screenshots stored in `/screenshots` directory)

---

## 📈 Key Learnings
- Practical understanding of SIEM architecture
- Agent–Manager communication in Wazuh
- Real-time File Integrity Monitoring using Syscheck
- Alert validation and investigation workflow

---

## 📚 Reference
- Wazuh Home Lab – SIEM and File Integrity Monitoring
  
  Guide By-  Royden Rebello (The Social Dork) 
