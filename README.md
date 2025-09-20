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

## Use Cases
- Detailed **Use Cases** (inventory update, reporting, recruitment, approval, scheduling, etc.)
- Additional diagrams (Use Case, Swimlane Activity, ERD/DFD, State, Sequence, Domain Class) are included in the full document.

## My Role (team project of 8)
This was a **team project (8 members)**.  
My contributions (as recorded in the SRS revision history):
- Drafted and refined sections of **Nonfunctional Requirements (NFRs)**
- Wrote and edited parts of the **System Features**
- Contributed to **Use Case scenario writing** (feedback on diagrams)
- Assisted with document structure and editing

Other parts of the document (e.g., generated domain code, stakeholder register) were group contributions.

## Full Document
The complete anonymized Software Requirements Specification (SRS) can be found here:

📄 [Retail Inventory System – Anonymized SRS (PDF)](docs/Retail_Inventory_System_SRS.pdf)

## Repository Structure
```text
docs/
└─ Retail_Inventory_System_SRS.pdf   # Full anonymized SRS document

privacy/
└─ NOTICE.md                         # Data source, anonymity, disclaimer
```


## Privacy & Data Source
See [`/privacy/NOTICE.md`](privacy/NOTICE.md).  
- Team member names, IDs, and emails have been anonymized.  
- **Stakeholder register uses fictitious, AI-generated data** (no real persons involved).  
- Generated domain model code was produced with permission for illustrative purposes only; it has not been executed.
