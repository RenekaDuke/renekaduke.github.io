# Automated Threat IOC Replacement and Panorama Firewall Deployment

### Objective:
To replace a manual process for updating outdated threat indicators with a fully automated script, enabling faster and more accurate deployment of malicious IPs to Panorama and firewalls.

---

### Tools & Technologies Used:
- Python (via Notepad++ PythonScript plugin)
- Regular Expressions (IP format matching)
- PuTTY (SSH client)
- Panorama Firewall CLI
- Structured IP input files

---

### What I Did:

- Identified inefficiencies in the manual workflow of updating a 2400+ line IP blocklist, which involved find-and-replace edits in Notepad++  
- Developed a PythonScript to automate the process by:
  - Reading new IOCs from a structured “key” input file  
  - Parsing the old IP blocklist in 3-line blocks (two IPs + "!" separator)  
  - Replacing old IPs with new IOCs sequentially, while preserving the exact formatting required by Panorama  
- Automated the full blocklist update in under 10 minutes  
- Used PuTTY to securely SSH into Panorama  
- Imported the updated list via Panorama CLI and successfully pushed changes to all connected firewalls  

---

### Results:

- Reduced manual update and implementation time from 2 business days to 2 hours  
- Enabled faster response to evolving threats through streamlined firewall rule updates  
- Increased accuracy and consistency by eliminating human error in IOC formatting  

---

### Key Takeaways:

- Applied Python scripting to solve a real-world cybersecurity operations challenge  
- Gained experience with firewall CLI and configuration propagation  
- Demonstrated initiative, automation, and critical thinking to improve team efficiency  

---

[🔙 Back to Portfolio](../README.md)
