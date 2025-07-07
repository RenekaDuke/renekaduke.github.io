# Malware Detection Simulation with Sophos

### Objective:
Trigger a safe malware detection event using the EICAR test file and document Sophos’s detection, response, and reporting capabilities.

---

### Tools Used:
- Sophos Endpoint Agent  
- Sophos Central Admin Console  
- EICAR Test File

---

### Steps Taken:

1. Logged into a corporate-managed endpoint with Sophos Endpoint Protection installed  
2. Opened Notepad and pasted the EICAR test string
3. Saved the file as `eicar.com` to the local Desktop directory  
4. Sophos immediately detected and quarantined the file (within 11 seconds)  
5. Logged into Sophos Central and navigated to **Alerts > Events**  
6. Reviewed alert details including:
- Device name  
- Username  
- File name  
- Threat response (quarantined)

---

### Findings:

- The EICAR file was detected in real time  
- Sophos automatically quarantined and cleaned the file  
- The event was logged and visible in the Sophos Central Admin Console  
- No manual action was required beyond file creation

---

### Outcome:

- Verified that real-time malware detection is working as intended  
- Confirmed that endpoint alerts are fully integrated with Sophos Central  
- Demonstrated automated quarantine and incident response capabilities  
- Provided assurance that users are protected against common malware behaviors  

---

### Conclusion:

Sophos Endpoint Protection effectively detected and responded to the EICAR test file, confirming that malware detection, alerting, and logging are functioning properly. This simulation validated real-time protection and centralized visibility for administrators.

---

### What I Did Summary:

I conducted a malware detection simulation using the EICAR test file to validate Sophos Endpoint Protection. After saving the file to a managed endpoint, Sophos automatically quarantined the threat and logged the alert in Sophos Central. This confirmed the system’s ability to detect and respond to malware without manual intervention.

---

[🔙 Back to Portfolio](../README.md)
 
