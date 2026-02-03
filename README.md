# SOC Analyst Portfolio - Beginner Projects (2026)

**Current SOC Analyst** rebuilding skills after 1.5yr gap. Hands-on projects showing Windows logs, Splunk, Sysmon.

## 📋 Projects

### 1. Windows Event Log Analysis
**What I did:** Analyzed Event IDs 4624 (login success), 4625 (login failure)  
**Found:** Brute force patterns, suspicious logins  
**[Screenshots →](#screenshots)**

### 2. Splunk Failed Login Detection
**What I did:** Built SPL query to detect >10 failed logins/minute  
**Tools:** Splunk Enterprise (free trial)  
**Code:** `index=windows EventCode=4625 | stats count by src_ip | where count>10`  
**[Dashboard →](#screenshots)**

### 3. Sysmon Process Hunting
**What I did:** Installed Sysmon, hunted suspicious PowerShell execution  
**Found:** Event ID 1 with malicious command line  
**[Hunt report →](#screenshots)**

## 🛠 Skills Demonstrated
- Windows Event Logs (4624, 4625, 4672)
- Splunk Search Processing Language (SPL)
- Sysmon Event ID 1 analysis
- MITRE ATT&CK mapping

## 📈 Progress
