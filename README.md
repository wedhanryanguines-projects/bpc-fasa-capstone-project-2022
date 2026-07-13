# bpc-fasa-capstone-project-2022
BPC-FASA-CAPSTONE-PROJECT

Web-Based Contributions and Loan Monitoring System for FASAAn automated, secure, and responsive web-based transaction management and monitoring application developed for the Faculty Administrator and Staff Association (FASA) at Bulacan Polytechnic College.This system migrates legacy, error-prone manual spreadsheets into a centralized digital dashboard, streamlining tracking for monthly contributions, loan cycles, expenses, and internal communications.🚀 Features👤 User Roles & ManagementAdmin Dashboard: Central overview of total contributions, institutional expenses, ongoing loans, and real-time ledger balances. Full control over member status approvals and payment validation.Sub-Admin Portal: Intermediate control allowing management of local contribution approvals, expense reporting, and loan applications.Member Portal: View personal contribution logs, check loan eligibility criteria, submit online payment references (via Gcash, Union Bank, PayMaya, Land Bank), and print electronic receipts.💼 Core ModulesLoan Management: System logic automatically qualifies loan applicants based on specific criteria (e.g., minimum accumulated contribution of ₱1,000 and 1.5 years of membership). Includes automated "Draw Lots" digital queuing systems.Contribution & Expense Tracking: Direct database categorization of Monthly Dues, Damayan Plans, and institutional cash outflows.Collaboration Tools: Built-in community forum for official announcements and real-time instant messaging/chat modules directly connecting members with treasury officers.Security & Verification: Incorporates a 6-alphanumeric email verification process upon user registration and secure password hashing.🛠️ Tech Stack & ArchitectureThe system utilizes an iterative Input-Process-Output with Storage model to streamline processing times.Front-End: HTML5, CSS3, JavaScript, Bootstrap, SweetAlert2Back-End Development: PHP (Server-side scripting engine)Database Management: MySQL (Relational architecture for secure logs, user entities, and asset tracking)RAD Framework Tools: PHPRad Environment   [ Manual Data / Inputs ] 
               │
               ▼
       ┌───────────────┐
       │    PHPRad     │ ── (Processes & Validations)
       └───────────────┘
               ▲
               │ (Queries & Storage)
               ▼
       ┌───────────────┐
       │     MySQL     │
       └───────────────┘
               │
               ▼
 [ Highly Acceptable Web Output ]
 (Reliability • Security • User-Friendliness)
📊 Results & EvaluationDuring formal alpha and benchmarking phases, the system was graded by internal panels and enterprise experts using a standardized 5-point Likert Scale across core software metrics:Metric Evaluation CriteriaLegacy System (Excel)Proposed Web ApplicationOverall Score Achievement2.24 (Unacceptable)4.62 (Highly Acceptable)Key Findings: Manual spreadsheet logic was completely replaced to eliminate redundancy bugs. Security features (unique data identifiers and session tracking) effectively restrict structural modules to authenticated personnel only.👥 The Team & Project ProponentsDevelopment followed the Rapid Application Development (RAD) method, distributing project workloads symmetrically across specific development milestones:Dhan Ryan A. Guiñes – Back-End Developer & Head ProgrammerJudy Ann G. Palma – Head Researcher & Document LeadDacel Jane L. Paytan – System Analyst & Front-End Co-Designer
