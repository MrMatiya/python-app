# Rain IT Change Management Policy

---

## 📜 Policy Statement  
**“A change is an addition, deletion or modification to an IT system.”**

---

## A. Introduction

### A.1 Objectives  
The objectives of this Change Policy are to:  

- **A1.1** Provide standardized methods and procedures to meet Change Management requirements supporting Rain’s operations.  
- **A1.2** Eliminate uncontrolled changes to IT systems, infrastructure, and applications that could cause disruption, data corruption, or loss.  
- **A1.3** Minimize risk and severity of disruptions caused by changes.  
- **A1.4** Ensure all changes are logged in a centralized repository for transparency and sharing.  
- **A1.5** Systematically assess changes based on impact, benefit, and risk, approving or rejecting Requests for Change accordingly.  
- **A1.6** Schedule changes considering business needs, resource availability, and other ongoing changes.  
- **A1.7** Ensure all changes are tested, certified, and supported by implementation and remediation plans.  
- **A1.8** Provide reporting capabilities including trend analysis and relevant metrics.

---

### A.2 Scope  
This policy applies to:  

- **A2.1** All IT systems, infrastructure, and applications managed by Rain (Pty) Ltd and its subsidiaries, vendors, and contractors handling information processing or transmission.  
- **A2.2** All formal change requests including Work Orders, Normal Planned, Standard, and Emergency Changes.

---

## B. Definitions

### B.1 General Definitions  

| Term          | Definition                                                                                         |
|---------------|--------------------------------------------------------------------------------------------------|
| **rain**      | Rain Group Holdings (Pty.) Ltd and its subsidiaries.                                             |
| **CAB**       | Change Advisory Board: decision-making group for impactful IT changes, chaired by Change Manager.|
| **eCAB**      | Emergency Change Advisory Board: decision group for high-risk emergency changes.                  |
| **ITSM**      | IT Service Management Tool used for managing changes.                                            |

---

### B.2 Categories of Change Requests  

| Change Type       | Description                                                                                         |
|-------------------|---------------------------------------------------------------------------------------------------|
| **Work Order**    | Planned, low-impact/risk modifications that may be urgent with minimal lead time to maintain agility. |
| **Normal Planned Change** | Medium to high-risk changes requiring thorough technical review and CAB approval.               |
| **Standard Change**| Pre-defined, documented, and pre-approved changes that do not require formal approval.             |
| **Emergency Change** | Unplanned, immediate changes to resolve service disruptions or compliance issues, approved by eCAB.|

---

## 📌 Summary  
This Change Management Policy ensures that all IT changes at Rain are controlled, assessed, and implemented with minimal risk, supporting operational stability and business continuity.

---

*For detailed procedures and forms, please refer to the internal ITSM platform or contact the Change Manager.*

---

*Rain (Pty) Ltd – IT Governance Team*  
*Date: May 20, 2025*

---
# Rain IT Change Management Policy

---

## C. Guiding Principles and Policies

### C1. Change Window / Maintenance Slot  
- **Change Window:** 00:00 - 06:00 (including Rollback Period)  
- **Requirement:** All changes must be completed within this window.  
- **Exceptions:**  
  - RAN, Tx, Systems, and Dev changes can start at this time.  
  - **Emergency Changes:** Allowed throughout the day across **all domains** to address urgent issues.

---

### C2. Lead Times for Submission  
- Refer to **Section D.2** for detailed lead time requirements for submitting change requests.

---

### C3. Same-Day Implementation Changes (‘Urgent’ or ‘Emergency’)  
- Must allow sufficient time for:  
  - Technical review of the change.  
  - Obtaining additional approvals if needed.  
- All **High Urgency** changes require appropriate justification.  
- The Change Manager evaluates whether the justification is sufficient for late submissions.

---

### C4. Implementation Timing  
- Changes submitted for same-day implementation must be implemented on the same day unless explicitly marked otherwise.  
- Failure to obtain approval within the specified timeframe will result in rescheduling the change to a later date/time.

---

### C5. Peer Review Requirement  
- Any change with **internal or external customer impact** must be peer-reviewed by a colleague **before submission**.

---

### C6. Classification of Changes  
- All Changes and Work Orders must be correctly classified **based on impact and risk** before processing.  
- Classifications include:  
  - **Work Order**  
  - **Standard Change**  
  - **Emergency Change**

---

### C7. Purpose of Classification  
- Ensures:  
  - Correct planning and analysis.  
  - Appropriate approval aligned with potential implementation risks.

---

### C8. Approval Process  
- All Changes and Work Orders require approval from the designated Approvers **before implementation**.  
- **Unauthorized changes are strictly prohibited.**  
- Change Management reserves the right to invoke **HR disciplinary processes** for unauthorized changes.

---

## D. Risk and Response Assessment

### D1. Risk Categorisation

| Change Classification | Criteria                                                                                                  | Risk Score     |
|-----------------------|-----------------------------------------------------------------------------------------------------------|----------------|
| **Zero Risk**          | - Changes with zero probability of failure.<br>- Minimal testing required.<br>- No significant impact.    | ZERO RISK      |
| **Medium Risk**        | - Changes with previous successful history.<br>- Well-documented and tested rollback plans.<br>- Moderate risk of failure. | MEDIUM RISK    |
| **High Risk**          | - Changes requiring many resources.<br>- Approval only by CAB.<br>- High failure risk due to complexity or impact.<br>- Impacts >15% of network traffic or users.<br>- Requires Senior Engineer or Department HOD approval. | HIGH RISK      |

---

### Risk Override  
- Change Management reserves the right to **reject any change** potentially impacting the network negatively, regardless of classification.

---

## Summary  
This section outlines the core principles ensuring changes are controlled within defined maintenance windows, properly classified, reviewed, and approved to minimize risk and maintain operational stability.

---

*For detailed lead times and approval workflows, please refer to Section D.2 and the internal ITSM platform.*

---

*Rain (Pty) Ltd – IT Governance Team*  
*Date: May 20, 2025*

---
# Rain IT Change Management Policy

---

## D.2 Change Request Classifications, Lead Times, and Approvals

| **TYPE**             | **DEFINITION**                                                                                             | **LEAD TIME**                                         | **REQUIRED DOCUMENTS**                                                                                 | **APPROVAL DEADLINES**                      | **APPROVED BY**                                       |
|----------------------|------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------------------------------------------------------|---------------------------------------------|-------------------------------------------------------|
| **WORK ORDER**       | - Low / Medium Risk<br>- Short duration and rollback changes<br>- Less complex implementation and rollback<br>- Can be used to implement urgent business solutions | - No specific lead time required                      | - Recorded in ITSM<br>- All relevant attachments<br>- Implementation details                            | - As per submission                          | - Line Manager<br>- Senior Department Engineer(s)<br>- Change Manager |
| **PLANNED CHANGE (CAB)** | - Major upgrades<br>- Medium / High Risk<br>- Complex implementation and rollback                        | - Submit **Friday prior** to the following Thursday’s CAB meeting | - Change Request Document<br>- Recorded in ITSM<br>- All related documents<br>- Technical approval by HOD / Senior Engineer(s) by Friday COB before CAB | - Final approval by **11:00 AM** on CAB meeting day | - Line Manager<br>- Senior Department Engineer(s)<br>- Change Manager<br>- CAB Forum |
| **STANDARD CHANGE**  | - Pre-approved<br>- Repeatable, tested implementation and rollback plans                                   | - None required                                        | - Recorded in ITSM<br>- Pre-approved Implementation Plan<br>- Site lists / Configuration steps including rollback steps | - Not applicable                            | - Not required                                         |
| **EMERGENCY CHANGE (ECAB)** | - To resolve major outages<br>- To prevent significant service degradation or imminent crisis<br>- For regulatory compliance issues | - ASAP, unless retrospective                           | - None required at submission<br>- Retrospective Root Cause Analysis (RCA) Report<br>- Recorded in ITSM   | - ASAP unless retrospective                  | - Emergency Change Advisory Board (eCAB) Forum         |

---

### Notes:  
- **ITSM** refers to the IT Service Management tool used for logging and tracking changes.  
- **CAB** = Change Advisory Board, responsible for approving medium to high-risk planned changes.  
- **eCAB** = Emergency Change Advisory Board, convened for urgent emergency changes.  
- Adherence to lead times and approval deadlines is critical to ensure smooth change implementation and risk mitigation.

---

*Rain (Pty) Ltd – IT Governance Team*  
*Date: May 20, 2025*

---
# Rain IT Change Management Policy

---

## E. Roles and Responsibilities

To ensure a smooth and effective Change Process, the following roles must be clearly understood and accepted:

- **Change Requester**  
- **Change Owner**  
- **Change Approver**  
- **Change Implementer**  
- **Change Manager**  
- **CAB / eCAB Membership**

Each role is outlined in detail below.

---

### E.1 Role: Change Requester  
- **E1.1** The individual who formally requests and/or records the Change Request into the ITSM or equivalent system.  
- **E1.2** The Change Requester can also act as the Change Owner.

---

### E.2 Role: Change Owner  
The Change Owner is responsible for:  

- **E2.1** Completing all relevant change details in ITSM, including:  
  - a) Build plans  
  - b) Test plans  
  - c) Implementation plans  
  - d) Roll-Back plans  

- **E2.2** Keeping the Change Requester and all relevant stakeholders informed about the change progress:  
  - a) Mandatory communication via the Change Management WhatsApp Group.  
  - b) Communication required at the start, during (if applicable), and at the end of each approved change.  
  - c) Email updates can be used as supplementary communication.  

- **E2.3** Coordinating efforts of all relevant Implementation Teams.  

- **E2.4** Completing all post-implementation documentation, including but not limited to:  
  - a) Change Failure Report  
  - b) Root Cause Analysis (RCA) Documents  
  - c) Other relevant documentation  

- **E2.5** Representing the Change (or delegating a representative) at CAB / eCAB sessions.  

- **E2.6** Actively participating in relevant CAB / eCAB meetings.

---

*Rain (Pty) Ltd – IT Governance Team*  
*Date: May 20, 2025*

---
# Rain IT Change Management Policy

---

## E. Roles and Responsibilities (Continued)

### E.3 Role: Change Approver  
The Change Approver is responsible for:  
- **E3.1** Providing online (ITSM) technical reviews and approvals of upcoming changes.  
- **E3.2** Evaluating the risk and impact potential of changes to ensure informed decision-making.

---

### E.4 Role: Change Implementer  
The Change Implementer is responsible for:  
- **E4.1** Performing the change to achieve the intended outcome.  
- **E4.2** Executing the Roll-Back Plan if required.  
- **E4.3** Being assigned by the Change Owner to update the change details in ITSM.  
- **E4.4** Updating the Change Management WhatsApp Group at both the **start** and **end** of all approved changes (during office and after hours) using the agreed communication format.  
- **E4.5** Updating and closing the ticket in the ITSM tool within **48 hours** of change completion.

---

### E.5 Role: Change Manager  
The Change Manager is responsible for:  
- **E5.1** Overall accountability for the Change Management Process.  
- **E5.2** Validating change type and risk, with guidance from Change Appro

