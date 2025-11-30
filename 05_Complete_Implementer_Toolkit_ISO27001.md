# The Complete ISO 27001:2022 Lead Implementer's Toolkit

## Practical Templates, Checklists, and Policies for ISMS Implementation

---

### **Introduction**

This toolkit provides a comprehensive collection of templates, policies, and checklists designed to assist ISO 27001 Lead Implementers in planning, executing, and managing an Information Security Management System (ISMS). Each resource is aligned with the requirements of ISO 27001:2022 and can be customized to fit the specific needs of your organization.

**How to Use This Toolkit:**
1.  **Start with the Project Plan:** Use the ISMS Implementation Project Plan to structure your initiative.
2.  **Conduct Risk Assessment:** Utilize the risk management templates to identify and treat security risks.
3.  **Develop Policies:** Adapt the policy templates to create the foundation of your ISMS documentation.
4.  **Implement Controls:** Use the specific templates (e.g., Access Control, Incident Management) to implement Annex A controls.
5.  **Audit and Review:** Leverage the audit and compliance templates to verify your implementation and prepare for certification.

---

### **1. ISMS Project Management Templates**

#### **1.1. ISMS Implementation Project Plan Template**

**Purpose:** To define the scope, timeline, resources, and deliverables for the entire ISO 27001 implementation project.

```markdown
# ISMS Implementation Project Plan

- **Project Title:** ISO 27001:2022 ISMS Implementation
- **Project Manager:** [Name]
- **Executive Sponsor:** [Name]
- **Version:** 1.0
- **Date:** [Date]

## 1. Project Charter
   - **Business Need:** [e.g., Achieve regulatory compliance, enhance client trust, reduce security risks.]
   - **Project Goal:** To achieve ISO 27001:2022 certification within [X] months.
   - **Scope:** [Define the boundaries of the ISMS as per the scope statement.]

## 2. Key Milestones
| Phase | Milestone | Target Date |
| :--- | :--- | :--- |
| 1. Planning | Project Kick-off & Scope Approval | [Date] |
| 2. Risk Assessment | Risk Assessment Complete | [Date] |
| 3. Control Selection | Statement of Applicability (SoA) Finalized | [Date] |
| 4. Implementation | All Annex A Controls Implemented | [Date] |
| 5. Monitoring | Internal Audit Complete | [Date] |
| 6. Certification | Stage 2 Certification Audit Complete | [Date] |

## 3. Resource Allocation
   - **Project Team:** [List team members and roles]
   - **Budget:** [Total estimated budget, broken down by category]

## 4. Risk Management
   - **Project Risks:** [e.g., Budget overruns, lack of stakeholder buy-in]
   - **Mitigation Strategies:** [e.g., Regular budget reviews, stakeholder engagement plan]

## 5. Communication Plan
   - **Stakeholder Updates:** [e.g., Weekly email updates, monthly steering committee meetings]
```

---

### **2. ISMS Scoping and Policy Templates**

#### **2.1. ISMS Scope Statement Template**

**Purpose:** To formally define the boundaries of the ISMS.

```markdown
# ISMS Scope Statement

**Version:** 1.0
**Date:** [Date]
**Approved by:** [Name, Title]

## 1. Organizational Context
[Briefly describe the organization, its mission, and its locations.]

## 2. ISMS Boundaries

The Information Security Management System (ISMS) includes the following:

- **Organizational Units:** [e.g., IT, HR, Finance, all departments]
- **Physical Locations:** [e.g., Headquarters at 123 Main St, London; Data Center at 456 Tech Park, Reading]
- **People:** [e.g., All full-time employees and contractors]
- **Processes:** [e.g., Software development, client data processing, financial reporting]
- **Technology/Assets:** [e.g., The corporate network, the 'ProductX' SaaS platform, all company-issued laptops]

## 3. Exclusions
[Clearly state anything that is out of scope and provide a justification. e.g., "The guest Wi-Fi network is excluded as it is segregated and does not process corporate data."]

## 4. Interfaces
[Describe key interfaces with third parties or other systems, e.g., "The ISMS interfaces with our cloud hosting provider (AWS) and our payment processor (Stripe)."]
```

#### **2.2. Information Security Policy Template**

**Purpose:** To create the high-level, board-approved policy that sets the direction for information security in the organization (as required by **A.5.1**).

```markdown
# Information Security Policy

## 1. Purpose
This policy states the commitment of [Organization Name] to protecting the confidentiality, integrity, and availability of its information assets.

## 2. Scope
This policy applies to all employees, contractors, and other parties at [Organization Name].

## 3. Policy Statements
- **Leadership:** Management is committed to the ISMS and will ensure the availability of resources.
- **Risk Management:** The organization will maintain a process to identify, assess, and treat information security risks.
- **Compliance:** The organization will comply with all applicable legal, statutory, regulatory, and contractual requirements.
- **Continual Improvement:** The organization is committed to the continual improvement of the ISMS.

## 4. Roles and Responsibilities
- **Management:** Responsible for providing direction and resources.
- **All Employees:** Responsible for complying with this policy and related procedures.

## 5. Review
This policy will be reviewed annually or upon significant change.
```

---

### **3. Risk Management Templates (A.5.7, A.5.8)**

#### **3.1. Risk Assessment Template**

**Purpose:** To identify, analyze, and evaluate information security risks.

| **Risk ID** | **Asset** | **Threat** | **Vulnerability** | **Existing Controls** | **Likelihood (1-5)** | **Impact (1-5)** | **Risk Score (L*I)** | **Risk Level** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| R-001 | Client DB | Ransomware | Unpatched Server | Firewall | 3 | 5 | 15 | High |
| R-002 | Laptops | Device Theft | No full-disk encryption | Physical Security | 2 | 4 | 8 | Medium |

#### **3.2. Risk Treatment Plan Template**

**Purpose:** To document how identified risks will be treated.

| **Risk ID** | **Risk Description** | **Risk Score** | **Treatment Option** | **Proposed Control(s)** | **Control Owner** | **Due Date** | **Status** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| R-001 | Ransomware on Client DB | 15 | Mitigate | Implement EDR solution (A.8.16); Enhance backup strategy (A.8.13) | IT Manager | [Date] | In Progress |
| R-002 | Laptop Theft | 8 | Mitigate | Enforce full-disk encryption on all laptops (A.8.10) | IT Support | [Date] | Completed |

---

### **4. Statement of Applicability (SoA) Template**

**Purpose:** To document the selection (or exclusion) of all 93 controls in ISO 27001:2022 Annex A.

| **Control ID** | **Control Name** | **Applicable? (Y/N)** | **Justification for Inclusion/Exclusion** | **Implementation Status** | **Link to Evidence** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **A.5.1** | Policies for information security | Y | A documented policy set is required to define management direction. | Implemented | [Link to InfoSec Policy] |
| **A.5.15** | Access control | Y | Essential for protecting information assets from unauthorized access. | Implemented | [Link to Access Control Policy] |
| **A.7.5** | Securing offices, rooms and facilities | N | The company is fully remote and has no physical offices. | N/A | N/A |

---

### **5. Control Implementation Templates**

#### **5.1. Access Control Policy Template (A.5.15)**

```markdown
# Access Control Policy

## 1. Purpose
To establish the rules for granting, reviewing, and revoking access to information systems.

## 2. Policy Statements
- **Least Privilege:** Users will be granted the minimum level of access necessary to perform their job functions.
- **Segregation of Duties:** Critical duties will be segregated to prevent fraud or error.
- **User Access Reviews:** Access rights will be reviewed on a quarterly basis by asset owners.
- **Offboarding:** Access will be revoked immediately upon termination of employment.
```

#### **5.2. User Access Review Form (A.5.18)**

**Purpose:** To document the periodic review of user access rights.

| **User** | **System/Application** | **Current Access Level** | **Still Required? (Y/N)** | **Change Required?** | **Manager Signature** | **Date** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| john.doe | Salesforce | Administrator | N | Revoke Admin, grant Read-Only | [Signature] | [Date] |
| jane.smith | GitHub | Write | Y | No Change | [Signature] | [Date] |

#### **5.3. Incident Report Form (A.5.26)**

**Purpose:** To document the details of an information security incident.

```markdown
# Information Security Incident Report

- **Incident ID:** [e.g., INC-2025-001]
- **Date/Time of Detection:** [Date & Time]
- **Reported By:** [Name]
- **Incident Type:** [e.g., Malware, Phishing, Data Leak]
- **Severity:** [Critical, High, Medium, Low]

## Description of Incident
[Detailed summary of what happened.]

## Actions Taken
[Chronological list of containment, eradication, and recovery steps.]

## Root Cause Analysis
[Analysis of the underlying cause of the incident.]

## Lessons Learned
[What can be done to prevent this from happening again?]

## Status: [Open/Closed]
```

#### **5.4. Supplier Security Assessment Questionnaire (A.5.21)**

**Purpose:** To assess the security posture of a potential third-party supplier.

```markdown
# Supplier Security Questionnaire

## Section 1: Information Security Governance
1.1. Do you have a documented Information Security Policy? (Y/N)
1.2. Are you certified against any security standards (e.g., ISO 27001, SOC 2)? (Y/N)

## Section 2: Access Control
2.1. Do you enforce Multi-Factor Authentication (MFA) for access to your systems? (Y/N)
2.2. Do you have a formal process for user access reviews? (Y/N)

## Section 3: Incident Management
3.1. Do you have a documented Incident Response Plan? (Y/N)
3.2. What is your SLA for notifying us of a security breach affecting our data?

... [etc.]
```

---

### **6. Audit and Review Templates**

#### **6.1. Internal Audit Checklist**

**Purpose:** To guide the internal audit process and ensure all aspects of the ISMS are reviewed.

| **Clause/Control** | **Audit Question** | **Evidence Reviewed** | **Compliant? (Y/N)** | **Findings/Notes** |
| :--- | :--- | :--- | :--- | :--- |
| **4.1 Context** | Has the organization determined its external and internal issues? | [e.g., SWOT Analysis, PESTLE] | Y | Context is well-defined. |
| **6.1.2 Risk Assessment** | Is there a formal risk assessment process? | [e.g., Risk Assessment Procedure] | Y | Process is documented and followed. |
| **A.8.1 Data classification** | Is information classified according to its value and sensitivity? | [e.g., Data Classification Policy] | N | Policy exists, but classification is not consistently applied. Minor NC raised. |

#### **6.2. Management Review Meeting Minutes Template**

**Purpose:** To document the formal management review of the ISMS (as required by Clause 9.3).

```markdown
# Management Review Meeting Minutes

- **Date:** [Date]
- **Attendees:** [List of attendees]

## Agenda Items
1.  **Status of actions from previous reviews.**
2.  **Changes in external and internal issues.**
3.  **Feedback on information security performance:**
    - Nonconformities and corrective actions.
    - Monitoring and measurement results.
    - Audit results.
4.  **Results of risk assessment and status of risk treatment plan.**
5.  **Opportunities for continual improvement.**

## Decisions and Actions
- **Decision:** The ISMS is deemed suitable, adequate, and effective.
- **Action Item:** [e.g., CISO to allocate additional budget for EDR solution by Q3.]
```
