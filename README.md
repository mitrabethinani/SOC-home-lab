# SOC-home-lab
Documentation for a defensive security home lab featuring a centralized SIEM, EDR monitoring, and active telemetry capture.

---
## Microsoft Sentinel Incident Response Workflow
**Platform:** Microsoft Sentinel (SIEM/SOAR)  

### 1. Project Overview
This project outlines the end-to-end lifecycle of handling a high-severity security incident within Microsoft Sentinel, proving my practical understanding of security operations workflows and triage processes.

### 2. Phase 1: Triage and Ownership
When an alert triggers a new incident in the Sentinel queue, I follow these critical steps:
* **Review Severity:** Inspect the alert's severity rating to prioritize it appropriately.
* **Assign Ownership:** Change the owner status to **"Assign to me"** to signal active investigation.
* **Update Status:** Change the incident state from **"New"** to **"Active"**.

### 3. Phase 2: Mitigation and Response
After identifying a threat (such as a suspicious login), I follow these standard containment practices:
* **Account Isolation:** Document steps to disable or lock compromised user credentials temporarily.
* **IP Analysis:** Trace the malicious origin IP address to prepare for firewall blocking rules.
* **Incident Comments:** Add clean, professional logs into the incident notes detailing findings before shifting the status to **"Closed"**.



---

## 🧠 Daily AI Learning Log

### Day 1 (20 August 2026)
* **Topic:** Tokenization 🪙
* **What I learned:** Large Language Models (LLMs) do not read whole words. They split text into smaller fragments called "tokens" and turn them into mathematical numbers to understand human language.
