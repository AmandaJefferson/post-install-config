# osTicket
Setting up to use osTicket as Admin
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

Part 1.  Configure Roles

Part 2.  Configure Departments

Part 3.  Configure Teams

Part 4.  Configure Agents

Part 5.  Configure Service Level Agreements

Part 6.  Configure Help Topics

Part 7.  Set to Allow Anyone to Create Tickets

Part 8.  Configure User

<h2>Configuration Steps</h2>
Login to the osTicket as an admin. Note that you can also switch between admin and agents panel by clicking on the top right corner of the screen.
<p>
<img src="https://i.imgur.com/mVxKwt5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

 Part 1. Configure Roles
  
A role is the permission granted to agents essentially the person who will take care of the ticket in the department that they have access to. Each role has different permissions that can be checked or unchecked for the agent. I created a “supreme admin” role and give people with this “supreme admin” role access to everything. The Roles are set up according to what access levels each group of members needs depending upon their departments and abilities to assign or close tickets etc.
  


- Login
- ADMIN panel
- Agents
- Roles
- Add New Role
- Supreme Admin
  
    
</p>
<br />

<p>
<img src="https://i.imgur.com/pyDCmKx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  
Part 2. Configure Departments
  
The ticket gets associated with a department, and that specific department will take care of the ticket. The Departments have different settings which apply to tickets as they are routed through the departments and determine the visibility as well as whether tickets can be routed to each department.

To do this:  
- Admin panel
- Agents" from top menu bar
- Departments
- Add New Departments
  
  
</p>
<br />

<p>
<img src="https://i.imgur.com/hnbBFCH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Part 3. Configure Teams
  
Every department can have multiple teams, choose the appropriate members for the team, and set the access levels that will apply. Configuring Teams will allow Agents from different Departments to be organized to manage a specific issue or user via a Help Topic or Ticket Filter, regardless of the parameters of the Agents' Department rules.


To do this:
Add level II support and in members add yourself.
  
- Admin panel
- Agents
- Teams
- Add New Teams

</p>
<br />

<p>
<img src="https://i.imgur.com/snYkIHK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/99jsxhn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
<img src="https://i.imgur.com/wN6iSsb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Part 4. Configure Agents

An Agent is the person who solves the ticket. You can add anyone to the agent list by creating their usernames, emails, and passwords. In this case, I added Shelle James and Byron White as agents.

Shelle James
Access> Set to System Administrators>Set role to supreme admin>check permission>check teams and to level II support and create

Byron White
Access>support>role set to view only>Extended Access set to support and create

- Admin panel
- Agents
- Add New Agents


<p>
<img src="https://i.imgur.com/CXYfNc2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Part 5. Configure SLA

Choose the appropriate grace period hours and schedule allowed to respond Service Level Agreements (SLA Plans) are set to provide a length of time for the help desk workers to close a ticket.

- Admin panel
- Manage
- SLA
- Add New SLA Plan


<p>
<img src="https://i.imgur.com/2nhLmrp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Part 6. Configure Help Topics

End users can choose the problem they need help with. Help Topics are created to ensure proper assignment and response of a ticket by assigning specific topics to the proper teams or departments.

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset

To do this:

- Admin panel
- Manage
- Help Topics
- Add New Help Topic

<p>
<img src="https://i.imgur.com/VFwHoez.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Part 7. Configure osTicket to Allow Anyone to Create Tickets

Require registration and log in to create tickets.

To do this:

- Admin panel
- Settings
- Users


<p>
<img src="https://i.imgur.com/yeY7zKN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


Part 8. Configure Users

Choose the appropriate options for "Require registration and login to create tickets" Users in osTicket are the customer, or internal member who needs assistance, and are the owner of the ticket. The User is associated with their email address.


To do this:

- Agent panel
- Users
- Add User

