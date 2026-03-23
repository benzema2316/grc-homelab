# GRC Homelab – Vulnerability Management Project

## 🚀 Project Summary

This project demonstrates a full vulnerability management lifecycle in a simulated enterprise environment.

Activities performed include:

- Conducted vulnerability scanning using Nessus Essentials  
- Identified and analyzed security risks  
- Developed a Risk Register and POA&M  
- Mapped vulnerabilities to NIST SP 800-53 controls  
- Documented findings in an SSP-style format  

This project highlights practical experience in Governance, Risk, and Compliance (GRC) aligned with the NIST Risk Management Framework (RMF).

## 📌 Overview

This project demonstrates hands-on experience in Governance, Risk, and Compliance (GRC) by building a home lab environment and conducting a vulnerability assessment using industry-standard tools.

The goal of this lab is to simulate a real-world enterprise environment and perform risk identification, analysis, and remediation planning aligned with NIST Risk Management Framework (RMF) principles.

---

## 🧠 Skills Demonstrated

- Vulnerability Assessment (Nessus)
- Risk Analysis & Risk Register Development
- POA&M Creation (Remediation Planning)
- Network Security Analysis
- GRC Documentation aligned with NIST RMF

## 📂 Project Files

- [Vulnerability Scan Report](vulnerability-management/nessus-scan.md)
- [Risk Register](vulnerability-management/risk-register.xlsx)
- [POA&M](vulnerability-management/poam.xlsx)
- [NIST Control Mapping](vulnerability-management/nist-mapping.md)
- [SSP Section](vulnerability-management/ssp-section.md)

## 🏗️ Lab Environment

[ Nessus (Host) ] → [ Metasploitable VM ]

* Host Machine (Windows) – Nessus Scanner
* Metasploitable 2 VM – Vulnerable target system
* VirtualBox – Virtualization platform

---

## 🛠️ Tools Used

* Nessus Essentials (Vulnerability Scanner)
* VirtualBox
* Metasploitable 2

---

## 🔍 Vulnerability Assessment

A vulnerability scan was performed against the Metasploitable 2 system.

### 📊 Results Summary

* Critical: 3
* High: 5
* Informational: 35

### 🚨 Key Findings

* Samba Badlock Vulnerability
* NFS Shares World Readable
* DNS/BIND Multiple Vulnerabilities

---

## 📋 Risk Analysis

Identified vulnerabilities were analyzed and documented in a structured Risk Register, including:

* Risk identification
* Impact and likelihood assessment

## 💼 Business Impact

The identified vulnerabilities could lead to:

- Unauthorized access to sensitive data (NFS misconfiguration)
- Credential compromise (Samba vulnerability)
- Service disruption (DNS/BIND issues)

Proper remediation reduces organizational risk and improves security posture.

## 📊 GRC Dashboard (Power BI)

A vulnerability management dashboard was developed using Power BI to visualize risk metrics and support decision-making.

### Features:
- Vulnerability severity distribution
- Critical and high-risk summary
- Top vulnerabilities identification
- Risk table for detailed analysis

![Dashboard](vulnerability-management/screenshots/dashboar-final.png)