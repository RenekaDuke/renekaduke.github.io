# Phishing Email Analysis and Threat Hunting

### Objective:
Analyze a phishing email using MxToolbox, VirusTotal, Shodan, and Sophos to detect, respond to, and block associated threats across the organization.

---

### Tools Used:
- MxToolbox (header and domain inspection)
- VirusTotal (file and URL scanning)
- Shodan (IP/host reconnaissance)
- Sophos Central (endpoint protection)

---

### What I Did:

- Collected and analyzed a phishing email sample received internally  
- Inspected email headers and sender reputation using **MxToolbox**  
- Scanned embedded URLs and attachments through **VirusTotal** to confirm malicious indicators  
- Queried destination IPs on **Shodan** to gather intelligence on hosting infrastructure and exposed ports  
- Investigated endpoint activity in **Sophos Central** to confirm if any users interacted with the email  
- Blocked malicious domains and IPs across appropriate platforms to prevent further exposure  
- Documented the full threat hunting and remediation process  

---

### Outcome:

- Identified and confirmed a real phishing threat using layered analysis tools  
- Prevented potential compromise by proactively blocking all IOCs across the environment  
- Strengthened incident detection and response skills through real-world threat triage  
- Enhanced team visibility with a detailed write-up of investigation steps and impact  

---

[🔙 Back to Portfolio](../README.md)
