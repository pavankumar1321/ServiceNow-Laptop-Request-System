<h1 align="center">ServiceNow-Based Employee Laptop Request Application</h1> <p align="center"> <b>A centralized, automated ServiceNow application for employee laptop requests, manager approval, and IT provisioning.</b> </p> <p align="center"> <img src="https://img.shields.io/badge/Platform-ServiceNow-2E8B57?style=for-the-badge"> <img src="https://img.shields.io/badge/Workflow-Flow%20Designer-2980B9?style=for-the-badge"> <img src="https://img.shields.io/badge/Security-Role%20Based%20ACLs-8E44AD?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-Completed-27AE60?style=for-the-badge"> </p>
📌 About the Project

This project replaces a manual, email-based laptop request process with a fully automated ServiceNow solution. Employees submit requests through a self-service Service Catalog item, managers approve or reject with a single click via an automated Flow Designer workflow, and the system enforces eligibility (one request per employee per year) and access-control policy — all without any manual follow-up.

✨ Key Features
🖥️ Self-service Record Producer — employees submit laptop requests (Basic or Advance) through the Service Catalog
🔁 Automated Approval Flow — routes requests to the employee's manager and updates status automatically
📧 Email Notifications — sent at submission, approval, and rejection
🚫 Duplicate Prevention — a Business Rule blocks more than one request per employee per year
🔐 Role-Based Access Control — it_manager (read-only) and it_employee (create/read/write on own records)
📦 Deployable Update Set — all 52 customizations packaged for migration to any ServiceNow instance
🎬 Project Demo

▶️ Watch the demo video here: https://youtu.be/mkGfbRHs5o4?si=NUTa8_lgd0YPWBbM

🏗️ Solution Architecture

Employee Service Portal → Record Producer → Laptop Request Form Table → Flow Designer Approval Workflow → Business Rule / ACLs → Email Notifications

📁 Repository Structure
ServiceNow-Laptop-Request-System/
│
└── SLRS/
    │
    ├── 1. Ideation Phase/
    │   ├── Empathy_Map_Canvas.pdf
    │   ├── Define_Problem_Statements.pdf
    │   └── Brainstorm_Idea_Prioritization.pdf
    │
    ├── 2. Requirement Analysis/
    │   ├── Customer_Journey_Map.pdf
    │   ├── Data_Flow_Diagram_and_User_Stories.pdf
    │   ├── Solution_Requirements.pdf
    │   └── Technology_Stack.pdf
    │
    ├── 3. Project Design Phase/
    │   ├── Problem_Solution_Fit_Canvas.pdf
    │   ├── Proposed_Solution.pdf
    │   └── Solution_Architecture.pdf
    │
    ├── 4. Project Planning Phase/
    │   └── Project_Planning.pdf
    │
    ├── 5. Project Development Phase/
    │   ├── Functional_Performance_Testing.pdf
    │   ├── Platform_Automation_Summary.pdf
    │   ├── User_Acceptance_Testing_Template.pdf
    │   └── UAT_Execution_Report.pdf
    │
    ├── 6. Project Documentation/
    │   └── Final_Project_Report.pdf
    │
    └── 7. Project Demonstration/
        └── Project_Demonstration.pdf
🛠️ Tech Stack
Layer	Technology
Front-end	ServiceNow Service Portal (Record Producer, Catalog Item)
Workflow	ServiceNow Flow Designer, Business Rules
Data	Custom Table (Laptop Request Form), Approval Table
Security	Roles, Groups, Access Control Lists (ACLs)
Notifications	ServiceNow Email Notifications (SMTP)
Deployment	Update Sets (scoped application)
📊 Project Status
Phase	Status
Ideation	✅ Complete
Requirement Analysis	✅ Complete
Project Design	✅ Complete
Project Planning	✅ Complete
Development & Testing	✅ Complete
Final Documentation	✅ Complete
🙌 Acknowledgements

Built as part of a ServiceNow certification project, demonstrating end-to-end platform automation — from requirement gathering through deployment-ready configuration.

<p align="center"><i>⭐ If you found this project useful, consider starring the repository!</i></p>
