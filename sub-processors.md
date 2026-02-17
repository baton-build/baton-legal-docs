---
title: "Sub Processors"
version: "1.0.0"
effective_date: 2025-10-25
last_updated: 2026-02-17
company: "Baton Software Limited (Company No. 16657849)"
jurisdiction: "England & Wales"
canonical_url: "https://baton.build/legal?=subprocessors"
contact: "info@baton.build"
document_type: sub_processors
---
Baton engages the following third parties as **sub-processors** to support delivery of the Service. Baton imposes data-protection terms no less protective than those in the DPA and remains responsible for their performance. International access or transfer (if any) is protected by appropriate safeguards (e.g., SCCs / UK IDTA).

> **Notice of changes.** We’ll post updates here. Material changes will be notified to admin contacts or in-product. You may object on reasonable grounds by emailing **info@baton.build** within 30 days; we’ll work in good faith to address objections, and you may terminate the affected services if unresolved.

---

## Current sub-processors

| Sub-processor | Role / Purpose | Typical Processing Location(s) | Example Data Processed | Notes |
|---|---|---|---|---|
| **Microsoft Azure** | Authentication & credential store; platform services (compute, storage, networking) | UK / EU regions (e.g., UK South/West Europe) | Authentication events, hashed credentials/identity tokens (no worker profile data stored here per Baton design), platform metadata | Azure may involve global support access under strict controls. |
| **MongoDB Atlas** | Primary database hosting for application data | EU/UK data regions (selected by Baton) | Client Data including worker profiles, qualifications, wage-related calculation inputs, audit logs | Encryption at rest & in transit configured. |
| **Atlassian (Jira Cloud)** | Ticketing for support/bug tracking | EU/UK data residency where available; limited global support access possible | Ticket metadata; **redacted** screenshots/log excerpts (Baton policy prohibits uploading raw datasets or unnecessary personal data) | Access restricted; DP terms in place; SCCs/UK IDTA as applicable; short retention for attachments. |
| **Google Workspace (Drive/Docs)** | Document intake during onboarding (optional, Client-provided files) | EU/UK data regions and/or Ireland; may involve limited global support access | Files a Client uploads or shares to Baton for ingestion (e.g., spreadsheets with worker details) | Used only when Clients send files to Baton for import; data moved into Baton DB post-ingestion. |
| **Oskfel Software Limited** | Development & support services for Baton | United Kingdom and remote engineering locations, including outside the UK/EEA | Limited access to Client Data as necessary for support and engineering | Access controlled; SCCs/IDTA and confidentiality obligations in place. |

> **Support Data Minimisation.** Baton’s support process prohibits uploading raw datasets or unnecessary personal data into ticketing systems. Where personal data is unavoidable (e.g., reproducing an issue), files are uploaded via Baton’s secure intake and referenced in Jira, not stored in Jira.

---

## Regionality & transfers
- Baton aims to store Client Data in **UK/EU regions**.  
- Engineering and support work may take place in the **UK or remotely, including from outside the UK/EEA**, and is governed by **SCCs/UK IDTA** and appropriate supplementary measures.

---

## How to receive updates
- Check this page periodically: **https://baton.build/legal?doc=subprocessors**  
- Ensure your admin contact email is current to receive change notices.

---

## Objecting to a sub-processor
If you have reasonable grounds to object to a change, email **info@baton.build** within **30 days** of notice. We will work in good faith to propose alternatives; if unresolved, you may terminate the affected services per the Agreement.

---

## Questions
Contact **info@baton.build** for privacy, security, or data-protection enquiries.
