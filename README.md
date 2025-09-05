# SIEM Log Analysis – Brute Force & Phishing Detection

## 📌 Project Overview
This project demonstrates how to analyze **security logs** to detect brute force and phishing attacks using a **Security Information and Event Management (SIEM)** tool (e.g., Splunk/Elastic).

The goal is to simulate log ingestion, create detection queries, and document how alerts can identify malicious activity.

## 🗂️ Project Files
- **BruteForce_Log_Sample.json** → Sample logs of brute force attempts (username/password failures).
- **Phishing_Log_Sample.json** → Sample email/security gateway logs showing phishing attempts.
- **SIEM_Detection_Queries.txt** → Detection queries used to flag suspicious activity.
- **SIEM_Log_Analysis_Report.pdf** → A short written report explaining detection steps and findings.

## 🛠️ Skills Demonstrated
- Log ingestion and parsing  
- Writing SIEM queries for brute force detection  
- Creating phishing detection rules  
- Documenting alerts and triage workflow  

## 📊 Key Findings (Sample)
- **Brute Force Detection:** Identified repeated failed login attempts from the same IP address within a short time window.  
- **Phishing Detection:** Flagged inbound emails with suspicious domains and high SPF/DKIM failures.  
- **Alerting:** Configured SIEM to generate alerts and dashboards for monitoring these attacks.  

## 🚩 Status
✅ Completed – Sample logs, detection queries, and report included.
