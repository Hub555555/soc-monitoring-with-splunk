# soc-monitoring-with-splunk
This project demonstrates a complete SIEM lab implementation using Splunk Enterprise on Kali Linux and Splunk Universal Forwarder on Windows 11 for real-time log monitoring and security analysis.

# Splunk SIEM Lab

## 📘 Overview
This project demonstrates a complete SIEM lab using Splunk Enterprise on Kali Linux and Splunk Universal Forwarder on Windows 11 for real-time security log monitoring.

## 🏗️ Architecture
Windows 11 → Universal Forwarder → Kali Linux Splunk Enterprise

## 🔥 Features
- Real-time Windows Event Monitoring
- Failed Login Detection
- Security Event Analysis
- VMware SOC Lab
- SPL Query Analysis
- 
## 📄 Documentation
[Download Full Implementation Guide](docs/Splunk_SIEM_Lab_Implementation_Guide.pdf)

## 🛠️ Technologies Used
- Splunk Enterprise
- Splunk Universal Forwarder
- Kali Linux
- Windows 11
- VMware Workstation
- 
## 📊 Sample SPL Query
index=*
All Windows Logs:
sourcetype="WinEventLog:*"

Security Logs:
sourcetype="WinEventLog:Security"

Failed Login Events:
EventCode=4625

Successful Login Events:
EventCode=4624
