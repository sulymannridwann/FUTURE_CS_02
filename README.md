# 🛡️ SOC Analyst Internship Project – Security Alert Monitoring & Incident Response

This internship project simulates real-world tasks in a Security Operations Center (SOC), using **Splunk** to monitor alerts, investigate suspicious activity, and respond to potential threats. The goal was to build situational awareness through log analysis, threat classification, and actionable reporting.

---

## 🎯 Objective

- Ingest and analyze simulated log files using Splunk  
- Detect potential security threats  
- Classify alerts by severity  
- Document incident response actions  
- Build a real-time visual dashboard

---

## 🧰 Tools & Technologies

| Tool        | Description                                      |
|-------------|--------------------------------------------------|
| **Splunk**  | SIEM tool for log ingestion, analysis, and visualization |
| Sample Logs | Simulated security logs for SOC investigation     |

---

## 🧪 Tasks Performed

### 1. **Log Ingestion**
Uploaded and indexed sample logs in Splunk for structured analysis.

### 2. **Threat Detection**
Analyzed log patterns to uncover multiple suspicious behaviors including:

- Rootkit traces  
- Spyware detection  
- Trojan activity  
- Unauthorized file access  
- Multiple failed login attempts

### 3. **Alert Classification**
Each alert was analyzed and categorized based on impact and likelihood:

| Alert Name           | Severity | Description                                    |
|----------------------|----------|------------------------------------------------|
| **Rootkit Detected** | 🔴 High  | Kernel-level malicious tool attempting to hide its presence |
| **Threat Spyware**   | 🟠 Medium| Activity indicating data exfiltration or tracking |
| **Trojan Found**     | 🔴 High  | Malicious file embedded and executing commands |
| **Failed Login**     | 🟡 Low   | Brute-force or unauthorized login attempts     |
| **File Accessed**    | 🟠 Medium| Access to sensitive or restricted files        |

### 4. **Incident Report Creation**
Compiled a structured report containing:
- Description of each alert  
- MITRE ATT&CK mapping (where applicable)  
- Severity level  
- Recommended response steps

### 5. **Splunk Dashboard**
Created a visual dashboard that summarizes:
- Top alerts by type  
- Alert count by severity  
- User and host activity  
- Timeline of triggered alerts

---

## 📂 Repository Structure

| Path                      | Description                                 |
|---------------------------|---------------------------------------------|
| `/screenshots/`           | Dashboard and alert visuals from Splunk     |
| `/report/Incident_Report.pdf` | PDF report detailing each alert and response |
| `/alert-log.xlsx`         | Sheet listing all detected alerts and classification |

---

## 🚀 Outcome

This project enhanced my skills in:

- Real-time threat detection  
- Log correlation and analysis  
- Incident triage and response  
- Dashboarding and executive reporting  

It reflects my hands-on understanding of what SOC teams do daily to protect digital infrastructure.

---

## 📬 Contact

- 📧 Email: [rsulyman19@gmail.com](mailto:rsulyman19@gmail.com)  
- 🔗 LinkedIn: linkedin.com/in/ridwan-sulyman-b83b2b341

---

> “Log data doesn’t lie — it tells the story. As a SOC Analyst, it’s my job to read it.”
