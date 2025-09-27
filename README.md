
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

