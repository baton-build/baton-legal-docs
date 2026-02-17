---
title: "Data Processing Agreement"
version: "1.0.0"
effective_date: 2025-10-25
last_updated: 2026-02-17
company: "Baton Software Limited (Company No. 16657849)"
jurisdiction: "England & Wales"
canonical_url: "https://baton.build/legal?doc=dpa"
contact: "info@baton.build"
document_type: data_processing_agreement
---
This Data Processing Agreement (**DPA**) forms part of the agreement between **Baton Software Limited** (**Processor**, “Baton”) and the **Client** (**Controller**) governing Client’s use of the Baton Service. Capitalised terms not defined here have the meanings in the main agreement.

---

## 1. Scope & Roles
1.1 **Roles.** Client is **Controller** of Client Data. Baton acts as **Processor** of Client Data and as **independent controller** for limited operational data described in Baton’s Privacy Policy.  
1.2 **Instructions.** Baton shall process Client Data **only on Client’s documented instructions**, including with respect to international transfers, unless required by law. Where a legal requirement prevents notice, Baton will notify when permitted.  
1.3 **Details of processing.** Subject matter, duration, nature, purpose, types of personal data, and categories of data subjects are set out in **Annex 0 (Processing Details)**.

---

## 2. Processor Obligations
2.1 **Confidentiality.** Baton ensures all authorised personnel are bound by confidentiality.  
2.2 **Security.** Baton implements appropriate **technical and organisational measures (TOMs)** as described in **Annex 1 (Technical and Organisational Measures)**, taking into account the state of the art, costs, nature, scope, context, purposes, and risks.  
2.3 **Sub-processors.** Client provides **general authorisation** for sub-processors listed at **https://baton.build/legal?doc=subprocessors**. Baton will (a) impose data-protection terms no less protective than this DPA; (b) remain responsible for sub-processors; (c) notify of material changes; and (d) allow reasonable objections.  
2.4 **Assistance.** Taking into account the nature of processing, Baton will assist Client with: (a) data-subject requests; (b) security, breach notifications, DPIAs and consultations; and (c) demonstrating compliance with Article 28.  
2.5 **Breach Notification.** Baton will notify Client **without undue delay** after becoming aware of a personal data breach affecting Client Data and provide information reasonably required for Client’s regulatory obligations.  
2.6 **Return/Deletion.** On termination or at Client’s written instruction, Baton will **delete or return** Client Data and delete existing copies within **60 days**, unless retention is required by law or confined to immutable backups (then securely isolated until expiry).  
2.7 **Records & Audit.** Baton maintains records of processing and will make available information reasonably necessary to demonstrate compliance. Subject to confidentiality and security, Client (or an independent auditor) may audit once in any 12-month period on **30 days’ notice**. Baton may satisfy audits via **third-party reports** (e.g., certifications/attestations) and **remote reviews**; on-site audits where mandated by law/regulator and limited to relevant systems.

---

## 3. International Transfers
3.1 **Safeguards.** Where Client Data is transferred to, or accessed from, a third country lacking adequacy, Baton will implement appropriate safeguards, including the **UK International Data Transfer Addendum** and/or **EU Standard Contractual Clauses (SCCs, Module 2)** plus supplementary measures.  
3.2 **Remote Access.** Support or engineering personnel (including authorised sub-processors) may **remotely access** Client Data from outside the UK/EEA **only as necessary** to provide the Service/support and subject to the safeguards above.  
3.3 **Documentation.** Baton will provide details of applicable transfer mechanisms relevant to Client’s deployment upon request.

---

## 4. Client Obligations
4.1 **Lawfulness & Transparency.** Client is responsible for a valid legal basis and transparency for Client Data and for its content and accuracy.  
4.2 **Configuration & Access.** Client manages user access, configuration, and secure use of the Service.  
4.3 **Instructions.** Client will not instruct Baton to process Client Data in breach of data-protection law.

---

## 5. Order of Precedence & Liability
5.1 **Precedence.** For personal-data processing, this DPA prevails over conflicting terms in the main agreement.  
5.2 **Liability.** Liability is governed by the main agreement; nothing limits liability that cannot be limited under law.

---

## Annex 0 — Processing Details (Article 28(3))
- **Subject matter:** Provision of the Baton Service and related support.  
- **Duration:** Subscription Term + any return/deletion window and legal retention.  
- **Nature & purpose:** Hosting, storage, retrieval, transmission, calculation, reporting, support, security monitoring, backup.  
- **Types of personal data:** Identification data (name, contact), worker qualifications/certifications, NI/tax-related data required for wage calculations, employment/project metadata, authentication and access logs; other data uploaded by Client in the ordinary use of the Service.  
- **Categories of data subjects:** Client’s workers, contractors, and administrators.

---

## Annex 1 — Technical and Organisational Measures (TOMs)
**Version:** 1.2 | **Effective date:** 17 October 2025 | **Jurisdiction:** United Kingdom

### 1. Purpose and Legal Basis
In accordance with **Article 32 of the UK GDPR (Security of Processing)**, Baton implements the following technical and organisational measures to ensure a level of security appropriate to the risk.  
These measures protect Personal Data against unauthorised or unlawful processing, accidental loss, destruction, or damage, and are reviewed and improved on an ongoing basis.

### 2. Governance and Accountability
- Documented Information Security Management System (ISMS) aligned with ISO 27001 / SOC 2 principles.  
- Roles and responsibilities for data protection and information security are clearly assigned, with oversight by the Chief Information Officer and Data Protection Officer.  
- All employees complete regular data protection and security awareness training and are bound by confidentiality undertakings.  
- Sub-processors and vendors are assessed for security and data protection compliance before engagement and periodically thereafter.

### 3. Access Control
- Access to systems handling Personal Data is restricted through strong authentication controls.  
- Multi-Factor Authentication (MFA) is used for administrative and high-privilege accounts and is being progressively expanded across other user groups.  
- “Multi-Factor Authentication (MFA)” means using at least two distinct factors (e.g. password + authenticator app or hardware token) to verify identity before access is granted.  
- Access rights follow the principle of least privilege and are reviewed periodically.  
- Inactive sessions automatically terminate; failed logins trigger alerts.  
- Remote access is restricted to secure, monitored connections.

### 4. Data Encryption
- **In transit:** TLS 1.2+ encryption for all communications between client, API, and storage layers.  
- **At rest:** AES-256 or equivalent encryption for all stored Personal Data.  
- **Key management:** Keys are securely managed, rotated, and stored separately from encrypted data.

### 5. System and Infrastructure Security
- Production environment hosted on reputable cloud infrastructure (e.g., AWS, GCP, Azure) with robust security controls.  
- Logical separation of development, testing, and production environments.  
- Regular patching and hardening to mitigate vulnerabilities.  
- Security logs maintained, monitored, and retained for audit and incident response.

### 6. Data Integrity and Availability
- Regular, encrypted backups tested for recoverability.  
- Redundant and failover systems to ensure high availability.  
- Documented disaster recovery plan tested periodically.

### 7. Data Minimisation and Retention
- Only necessary Personal Data is processed for contractual purposes.  
- Retention limited to the period required for those purposes or as required by law.  
- Secure deletion or anonymisation when no longer needed.

### 8. Incident Detection and Response
- Documented incident response plan with defined escalation, containment, and communication procedures.  
- Automated and manual monitoring for unauthorised activity.  
- Controller notified without undue delay following any Personal Data Breach.

### 9. Testing and Continuous Improvement
- Regular vulnerability assessments are performed, and Baton plans to introduce scheduled penetration testing as part of its security-maturity roadmap.  
- Findings are prioritised and remediated under Baton’s risk management process.  
- Measures reviewed annually or upon material changes to processing.

### 10. Sub-Processor Controls
- Only sub-processors providing sufficient guarantees of technical and organisational measures are engaged.  
- Bound by written contracts consistent with this Annex and subject to ongoing oversight.

### 11. Review and Updates
Annex reviewed at least annually and updated to reflect evolving regulatory, technical, or operational changes.  
Material updates communicated to Controllers per DPA notice provisions.

---

## Annex 2 — Sub-processors
Baton’s current list is maintained at **https://baton.build/legal?doc=subprocessors** and forms part of this DPA.

---

## Annex 3 — Data Return & Deletion
- **Standard export:** During the term and for **30 days** after termination, Client may export Client Data using standard export tooling.  
- **Deletion:** Baton deletes Client Data within **60 days** after termination, save for legally-required retention or immutable backups (then isolated and deleted on rotation).

---

## Notices
All DPA notices must be sent to **info@baton.build** (required) and may also be sent to the registered office:

Baton Software Limited (Company No. **16657849**)  
Burgundy House, 24 The Forresters, Harpenden, Hertfordshire, AL5 2FB, United Kingdom.
