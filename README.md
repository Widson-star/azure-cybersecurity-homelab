# ☁️ Azure Cybersecurity HomeLab 🔐

## Overview
This project documents my hands-on experience building a **cloud-based cybersecurity homelab** on **Microsoft Azure**.  
The lab simulates a real-world enterprise environment to practice **cloud security operations**, **log analysis**, and **threat detection**.

---

## 🔧 Azure Resources Used
- **Resource Group:** HomeLab  
- **Virtual Machine:** Server2025 (Windows Server)  
- **Virtual Network:** Server2025-vnet  
- **Network Security Group:** Server2025-nsg  
- **Public IP:** Server2025-ip  
- **Log Analytics Workspace:** LAW-HomeLab  

---

## 🧠 Key Skills Demonstrated
- Cloud architecture and security configuration  
- Network segmentation using NSGs  
- Security event monitoring with Log Analytics  
- Querying logs using **Kusto Query Language (KQL)**  
- Threat investigation and IP geolocation analysis  

---

## 🔍 Example KQL Query
```kql
SecurityEvent 
| where Account == "\\sysadmin"
| project TimeGenerated, Account, Computer, IPAddress
```

This query helped identify a login attempt from an external IP located in **Moscow, Russia**, demonstrating how **Log Analytics** can detect anomalous activity in the cloud.

---

## 📊 Screenshots
*(Add your 2–3 screenshots here with short captions — e.g., KQL query results, LAW dashboard, NSG rules.)*

---

## 🌍 Future Work
This Azure-based project is part of a larger multi-cloud initiative:
- ✅ **Completed:** Azure Cybersecurity HomeLab  
- 🚀 **Next:** AWS Security Lab (in progress)  
- ☁️ **Upcoming:** GCP Security Lab  

Each environment will be used to compare **cloud-native security controls**, **SIEM capabilities**, and **incident response workflows**.

---

## 📘 Author
**Widson Ambaisi**  
Cloud Security Enthusiast | SOC Analyst | Multi-Cloud Learner  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/widson-ambaisi-010)
