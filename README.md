# Software Requirements Specification – Retail Inventory System (“The Answer”)

## Overview
This SRS defines the requirements for **“The Answer”**, a clothing storefront system to manage:
- Inventory
- Employees
- Record keeping
- Marketing

Some key functions (PoS, accounting, data management) are handled through external service APIs.  
*(Source: Introduction/Scope section of SRS)*

## System Features (FR01–FR10)
- **FR01**: Real-Time Stock Update  
- **FR02**: Inventory Management  
- **FR03**: Supplier Profile Management  
- **FR04**: Inventory Report & Analysis  
- **FR05**: Employee Profile Management  
- **FR06**: Work Schedule & Shift Management  
- **FR07**: Time Tracking & Attendance  
- **FR08**: Review & Approval  
- **FR09**: Recruitment Management  
- **FR10**: Employee Self-Service Portal  

## Nonfunctional Requirements
Examples from the SRS:
- **Performance**: average response ≤ 2s, peak ≤ 5s; DB query ≤ 1s
- **Security**: authentication/MFA, encryption in transit & at rest, RBAC
- **Compliance**: GDPR and related regulations

## Use Cases & Diagrams
- Detailed **Use Cases** (inventory update, reporting, recruitment, approval, scheduling, etc.)
- **Diagrams** included in the document:
  - Use Case Diagram
  - Swimlane Activity Diagram
  - ERD / DFD
  - State & Sequence
  - Domain Class Diagram

See `/docs/images/` for extracted PNG diagrams.

## My Role (team project of 8)
This was a **team project (8 members)**.  
My contributions (as recorded in the SRS revision history):
- Drafted and refined sections of **Nonfunctional Requirements (NFRs)**
- Wrote and edited parts of the **System Features**
- Contributed to **Use Case and Activity Diagram modeling**
- Assisted with document structure and editing

Other parts of the document (e.g., generated domain code, stakeholder register) were group contributions.

## Repository Structure
text ```
docs/
├─ SRS_TheAnswer_v1.0_anonymized.pdf # Full anonymized SRS document
├─ images/ # Extracted diagrams (PNG)
└─ appendix/
├─ revision_history.md # De-identified version of revision table
├─ stakeholder_register.md # Fictitious, AI-generated stakeholder data
└─ domain_model_generated.txt # Gemini-generated code (not executed)

privacy/
└─ NOTICE.md # Data source, anonymity, disclaimer
```


## Privacy & Data Source
See [`/privacy/NOTICE.md`](privacy/NOTICE.md).  
- Team member names, IDs, and emails have been anonymized.  
- **Stakeholder register uses fictitious, AI-generated data** (no real persons involved).  
- Generated domain model code was produced with permission for illustrative purposes only; it has not been executed.
