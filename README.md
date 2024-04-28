<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

Part 1 (Post Installation Setup)
- Configure Roles
 - Admin Panel -> Agents -> Roles
  - Supreme Admin
   - Configure Departments
    - Admin Panel -> Agents -> Departments
     - System Administrators
      - Configure Teams
       - Admin Panel -> Agents -> Teams
        - Level I Support
         - Level II Support
          - Allow anyone to create tickets
           - Admin Panel -> Settings -> User Settings
            - Registration Required: Require registration and login to create tickets 
             - Configure Agents (workers)
- Admin Panel -> Agents -> Add New
Jane
John
- Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
- Configure SLA
Admin Panel -> Manage -> SLA
- Sev-A (1 hour, 24/7)
- Sev-B (4 hours, 24/7)
- Sev-C (8 hours, business hours)
Configure Help Topics
- Admin Panel -> Manage -> Help Topics
- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset

- Part 4 (Tickets and Ticket Lifecycle)
Just practice creating, triaging, and solving tickets. I recommend watching the video to learn about triaging multiple tickets.
Ticket examples:
- Sev-A (1 hour, 24/7) [entire mobile/online banking system is down] -> SysAdmins
- Sev-B (4 hours, 24/7) [accounting department needs adobe upgrade, broken]
- Sev-B/C (2 hours, business hours) [CFO’s laptop seems a bit slow]


