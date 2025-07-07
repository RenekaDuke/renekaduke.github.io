# CAB Pre-Implementation Report using Gytpol

### Objective:
Run a Gytpol scan to identify endpoint misconfigurations prior to a change implementation and document a pre-CAB report addressing potential risks.

---

### Tools Used:
- Gytpol Validator
- Change Request Form (CRF)
- Change Advisory Board (CAB)

---

### Process Overview:

**Misconfiguration Identified:**  
Used Gytpol to detect an insecure guest logon setting that could allow unauthorized access to shared folders on corporate endpoints.

**Pre-CAB Report Created:**  
Documented the misconfiguration in a formal pre-CAB report, including:
- Vulnerability details  
- Business impact  
- Proposed mitigation strategy  
- Validation strategy  
- Rollback plan

**Mitigation Strategy Proposed:**  
Recommended using Gytpol to disable insecure guest logons locally on affected endpoints. This method provided a secure, auditable, and reversible fix with minimal operational impact.

**Validation:**  
Tested access to shared folders after remediation to ensure guest authentication was successfully blocked without affecting authorized users.

**CAB Approval & Implementation:**  
Submitted the CRF to the Change Advisory Board, presented the proposal, and received approval. Implemented the change across affected systems and validated success with a follow-up Gytpol scan.

---

### Outcome:

- Successfully remediated a high-risk misconfiguration through a structured change management process  
- Strengthened corporate endpoint security posture  
- Gained experience with formal change proposals, risk evaluation, and post-change validation  
- Demonstrated initiative and follow-through by seeing the project through CAB approval and implementation  

---

[🔙 Back to Portfolio](../README.md)
