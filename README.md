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

## Nonfunctional Requirements (My Contribution)

I contributed to drafting and refining the **Nonfunctional Requirements (NFR-1 to NFR-13)** section of the SRS.  
Key requirements include:

- **Performance Requirements**  
  - System should respond to user actions within **2 seconds under normal load** (≤100 users)  
  - Under peak load (≤200 users), responses should not exceed **5 seconds**  
  - Database queries should return results within **1 second**

- **Safety Requirements**  
  - Ensure data integrity via validation, backup, and recovery  
  - Graceful error handling with informative (non-sensitive) error messages  
  - Role-based access control for employees and managers

- **Security Requirements**  
  - Strong authentication (≥12-char password with complexity) or MFA  
  - Data encryption in transit (HTTPS) and at rest  
  - Compliance with **GDPR** and similar regulations

- **Software Quality Attributes**  
  - Consistent, intuitive user interface  
  - Modular design for maintainability and modifiability

- **Business Rules**  
  - Real-time inventory updates after each sale  
  - Employee data security and payroll integration  
  - Sales record retention for **≥5 years** for auditing

These NFRs provided the foundation for system robustness, security, and compliance in the Retail Inventory System project.


## Use Cases (My Contribution)

I also contributed to drafting the **Use Case Scenarios** that defined how system features (FR01–FR10) interact with actors.  
Examples include:

- **Update inventory quantity (FR01)**  
  Actor: Sales Associate  
  Description: During checkout, POS scans items, sends details to ERP, and updates inventory levels automatically.

- **Generate inventory reports (FR04)**  
  Actor: Store Manager  
  Description: Manager filters stock in/out dates, suppliers, and costs to generate a report. The system exports results in chosen format.

- **Stock in from a new supplier (FR02, FR03)**  
  Actor: Sales Associate  
  Description: Sales Associate enters supplier details (item name, quantity, cost). ERP records info under supplier ID and updates inventory.

- **Manage employee work schedule (FR06, FR07, FR10)**  
  Actor: Store Manager, Sales Associate  
  Description: Employees submit availability, manager finalizes and publishes schedules. System sends notifications and alerts for conflicts.

These use cases, together with the NFRs, modeled key interactions of the Retail Inventory System.


## My Role (team project of 8)
This was a **team project (8 members)**.  
In summary, my contributions were:
- Authored the **Nonfunctional Requirements (NFRs)** section  
- Drafted multiple **Use Case Scenarios** and contributed feedback on diagrams  
- Assisted in writing parts of the **System Features** section  
- Helped with document structure and editing

Other parts of the document (e.g., generated domain code, stakeholder register, additional diagrams) were group contributions.

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
