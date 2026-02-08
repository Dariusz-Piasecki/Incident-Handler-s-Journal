# Incident Handler's Journal

**Author:** Dariusz Piasecki  
**Project Type:** Incident Response Documentation  
**Framework:** NIST Incident Response Lifecycle

---

## 📋 Project Description

This journal documents the investigation and response to a ransomware incident targeting a healthcare clinic. Each entry follows the incident response lifecycle — from initial detection through containment, recovery, and post-incident review — using the 5 W's framework (Who, What, When, Where, Why) to structure findings.

The goal is to demonstrate a clear, methodical approach to documenting cybersecurity incidents and the actions taken to resolve them.

---

## 📅 Incident Timeline

The ransomware attack unfolded over a two-week period. The table below provides a high-level overview of key events and when they occurred.

| Date | Event | Phase |
|------|-------|-------|
| 2024-12-13 | Phishing email received and opened by clinic employee | Detection |
| 2024-12-13 | Ransomware deployed; systems encrypted; IT team notified | Containment |
| 2024-12-14 | Impact assessment across all clinic departments | Eradication |
| 2024-12-20 | Post-incident review conducted by IT and management | Recovery |
| 2024-12-27 | Full system audit and vulnerability assessment completed | Post-Incident |

---

## 📓 Journal Entries

### Entry 1 – Initial Incident Detection

| Field | Details |
|-------|---------|
| **Date** | 2024-12-13 |
| **Tools Used** | None (incident identified manually) |

**Description:**
A phishing email was received and opened by a clinic employee, leading to the deployment of ransomware. The attack compromised patient data and disrupted clinic operations.

**The 5 W's:**

| Question | Answer |
|----------|--------|
| **Who** | Organized group of unethical hackers |
| **What** | Ransomware attack triggered by a phishing email |
| **When** | Tuesday, 9:00 AM |
| **Where** | A small American healthcare clinic |
| **Why** | Attackers used targeted phishing to gain network access |

**Additional Notes:**
Further investigation into email filtering and security awareness training is needed. Implementing multi-factor authentication (MFA) should be considered as an additional security layer.

---

### Entry 2 – Incident Response and Containment

| Field | Details |
|-------|---------|
| **Date** | 2024-12-13 |
| **Tools Used** | Antivirus software, Email filtering tools |

**Description:**
The IT security team responded immediately after the ransomware was identified. Infected systems were isolated and recovery from backups was initiated to prevent further spread.

**The 5 W's:**

| Question | Answer |
|----------|--------|
| **Who** | IT security team |
| **What** | Isolated infected systems; initiated recovery from backups |
| **When** | Immediately after discovery |
| **Where** | Clinic's main office |
| **Why** | To prevent further spread of ransomware and restore operations |

**Additional Notes:**
Backup procedures should be reviewed to ensure data integrity and availability. The effectiveness of the current cybersecurity training program needs to be evaluated.

---

### Entry 3 – Impact Assessment

| Field | Details |
|-------|---------|
| **Date** | 2024-12-14 |
| **Tools Used** | Incident response tools |

**Description:**
An assessment was conducted to evaluate the full impact of the ransomware attack on clinic operations and patient care. Delays in appointments and data retrieval were identified across all departments.

**The 5 W's:**

| Question | Answer |
|----------|--------|
| **Who** | Clinic staff and IT team |
| **What** | Delays in patient appointments and data retrieval |
| **When** | Ongoing since the attack |
| **Where** | All departments in the clinic |
| **Why** | Systems were down due to ransomware encryption |

**Additional Notes:**
A communication plan should be developed to inform patients about the incident and expected service disruptions.

---

### Entry 4 – Post-Incident Review

| Field | Details |
|-------|---------|
| **Date** | 2024-12-20 |
| **Tools Used** | Risk assessment tools |

**Description:**
One week after the attack, IT and management conducted a formal post-incident review to identify vulnerabilities and assess the effectiveness of the response.

**The 5 W's:**

| Question | Answer |
|----------|--------|
| **Who** | IT and management team |
| **What** | Conducted a post-incident review |
| **When** | One week after the attack |
| **Where** | Clinic conference room |
| **Why** | To identify vulnerabilities and improve the incident response plan |

**Additional Notes:**
A regular training schedule should be established for employees to recognize phishing attempts. Investing in advanced threat detection systems is recommended.

---

### Entry 5 – Final Audit and Vulnerability Assessment

| Field | Details |
|-------|---------|
| **Date** | 2024-12-27 |
| **Tools Used** | Security Information and Event Management (SIEM) tools |

**Description:**
Two weeks after the attack, a comprehensive system-wide audit and vulnerability assessment was completed by the cybersecurity team and external consultants to confirm all systems were secure.

**The 5 W's:**

| Question | Answer |
|----------|--------|
| **Who** | Cybersecurity team and external consultants |
| **What** | Full system audit and vulnerability assessment |
| **When** | Two weeks after the attack |
| **Where** | Across all clinic systems |
| **Why** | To ensure all vulnerabilities were addressed and systems are secure |

**Additional Notes:**
Ongoing monitoring and regular updates to security policies are recommended. Collaboration with external cybersecurity experts for periodic assessments should be considered.

---

## 📊 Tools Used – Overview

| Tool | Entry | Purpose |
|------|-------|---------|
| Antivirus software | 2 | Detect and remove malicious software from infected systems |
| Email filtering tools | 2 | Block and quarantine malicious incoming emails |
| Incident response tools | 3 | Coordinate and track the incident response process |
| Risk assessment tools | 4 | Evaluate vulnerabilities and prioritize remediation |
| SIEM tools | 5 | Aggregate and analyze security event data across systems |

---

## 📊 Incident Response Phases – Summary

| Phase | Entry | Key Action | Outcome |
|-------|-------|------------|---------|
| **Detection** | 1 | Phishing email identified | Ransomware source traced |
| **Containment** | 2 | Infected systems isolated | Spread prevented |
| **Eradication** | 3 | Impact assessed across departments | Scope of damage documented |
| **Recovery** | 4 | Post-incident review conducted | Vulnerabilities identified |
| **Post-Incident** | 5 | Full audit and vulnerability assessment | All systems verified secure |

---

## 🛡️ Recommendations

Based on the incident and the post-incident review, the following measures are recommended to strengthen the clinic's security posture:

| Priority | Recommendation | Justification |
|----------|----------------|---------------|
| 🔴 High | Implement multi-factor authentication (MFA) | Reduces risk of unauthorized access from compromised credentials |
| 🔴 High | Enhance email filtering | Blocks phishing emails before they reach employees |
| 🟡 Medium | Establish regular employee training on phishing | Reduces likelihood of human error leading to incidents |
| 🟡 Medium | Review and update backup procedures | Ensures reliable recovery in the event of data loss |
| 🟢 Low | Invest in advanced threat detection and SIEM | Improves visibility and early warning capability |
| 🟢 Low | Develop a patient communication plan | Maintains trust and transparency during future incidents |

---

## 📝 Reflections

- The importance of employee training in recognizing phishing attempts cannot be overstated. Human error remains the most common entry point for cyberattacks.
- Regular audits and assessments of security measures are essential for staying ahead of potential threats.
- Clear communication channels with patients during an incident are critical for maintaining trust and transparency.
- Continuous improvement in cybersecurity practices is vital for protecting sensitive data and ensuring operational resilience.

---

## 🎯 Skills Demonstrated

| Skill Category | Specific Skills |
|----------------|-----------------|
| **Incident Response** | Detection, containment, eradication, recovery, post-incident review |
| **Documentation** | Structured journal entries using the 5 W's framework |
| **Risk Assessment** | Vulnerability identification and prioritization |
| **Threat Analysis** | Phishing and ransomware attack investigation |
| **Communication** | Clear reporting and actionable recommendations |

---

## 📧 Contact

**Dariusz Piasecki**  
📧 Email: dariusz.piasecki.sec@gmail.com  
🔗 LinkedIn: [linkedin.com/in/piaseckiphotos](https://www.linkedin.com/in/dariusz-piasecki/)  
🐙 GitHub: [github.com/Dariusz-Piasecki](https://github.com/Dariusz-Piasecki)

---

*This incident handler's journal demonstrates structured incident response documentation and analysis as part of a cybersecurity portfolio.*
