Automated Network Request Management System – ServiceNow
----
 Overview
This project automates the end-to-end lifecycle of network service requests using ServiceNow.  
It enables users to submit requests through a Service Portal, automates approvals, generates tasks, and completes the request with minimal manual intervention.

---

 Features

-  Service Catalog form for Network Requests
-  Automated workflow using Flow Designer
-  Approval process (user/manager-based)
-  Dynamic form with auto-filled user details
-  File upload support (document attachment)
-  Email notifications for request updates
-  Task generation (Assess & Provide Service)
- End-to-end request lifecycle automation

 Tech Stack

- **Platform:** ServiceNow (PDI)
- **Automation:** Flow Designer
- **Frontend:** Service Portal
- **Scripting:** Client Scripts & UI Policies
- **Database:** Custom Table (`u_network_database`)

---

 Modules Used

- Service Catalog
- Flow Designer
- Approvals
- Catalog Variables
- Email Notifications
- Catalog Tasks

---

 Workflow

1. User submits a Network Request via Service Portal  
2. Request details are stored in a custom table  
3. Approval is triggered  
4. Upon approval:
   - "Assess or Scope Task" is created  
   - "Provide Service Task" is created  
5. Tasks are completed by the user/admin  
6. Email notifications are sent  
7. Request is marked as **Completed**

---

 File Upload Feature

- Users can upload supporting documents (e.g., ID proof)
- Upload field appears dynamically based on input
- Files are stored as ServiceNow attachments

---

Key Highlights

- Fully automated request lifecycle  
- Minimal scripting (maintainable solution)  
- Dynamic UI behavior using UI Policies & Client Scripts  
- Real-world workflow simulation  

---

Screenshots


 Approval Stage

<img width="1920" height="1080" alt="Screenshot 2026-04-25 213303" src="https://github.com/user-attachments/assets/1719d38e-c9d3-4d51-a916-5a87e0b071e1" />


 Flow Designer

<img width="1920" height="1080" alt="Screenshot 2026-04-25 135251" src="https://github.com/user-attachments/assets/bbaf542a-23ce-4a6e-8d3c-320b049c4771" />


 Learning Outcomes

- ServiceNow Service Catalog implementation  
- Workflow automation using Flow Designer  
- Approval and task management  
- Dynamic form handling  
- End-to-end system design  

---

 Conclusion

This project demonstrates how ServiceNow can be used to automate network request handling efficiently, reducing manual effort and improving workflow transparency.

---
  Author

- Name: Nitya Kandra
- Project:Automated Network Request Management
