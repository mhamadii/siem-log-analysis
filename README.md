
# SIEM Log Analysis — Brute Force & Phishing

Detect brute-force SSH logins and suspicious phishing emails using Splunk/Elastic. Includes sample logs, queries, dashboard guidance, and a mini triage playbook.

## Files
- data/linux_ssh_logins.csv
- data/email_gateway.csv
- queries/splunk/ssh_bruteforce.spl
- queries/splunk/phishing.spl
- queries/elastic/ssh_bruteforce.kql
- queries/elastic/phishing.kql
- docs/triage-playbook.md
- docs/screenshots/ (add your images here)

## Quick run
1) Upload both CSVs into Splunk (Add Data → Upload).  
2) Run the two searches (SSH + phishing).  
3) Build a simple dashboard (top IPs, timechart failures/successes, suspicious emails table).  
4) Save 2–3 screenshots to docs/screenshots and commit.

## Screenshots

### Brute Force Detection
![Brute Force](docs/screenshots/BruteForce.png)

### Phishing Detection - Auth Checks (DMARC/DKIM)
![Phishing Auth Checks](docs/screenshots/Phishing_AuthChecks_DMARC_DKIM.png)

### Phishing Detection - High Spam Score
![Phishing High Spam Score 1](docs/screenshots/Phishing_High_SpamScorePT1.png)
![Phishing High Spam Score 2](docs/screenshots/Phishing_High_SpamScorePT2.png)

### Phishing Detection - Suspicious Subjects
![Phishing Suspicious Subjects](docs/screenshots/Phishing_SuspiciousSubjects.png)

### Phishing Detection - Suspicious Attachments
![Suspicious Attachments](docs/screenshots/Suspicious_Attachments.png)