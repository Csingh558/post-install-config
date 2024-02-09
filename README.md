<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

1. **Role Configuration:**
   - Objective: Establish a Supreme Admin role for managing system-wide settings and access controls.

2. **Department Setup:**
   - Objective: Create a System Administrators department to categorize and organize agents based on their responsibilities.

3. **Team Configuration:**
   - Objective: Define teams such as Level I Support and Level II Support to facilitate collaborative ticket resolution.

4. **User Access Control:**
   - Objective: Allow anyone to create tickets by configuring user settings in the Admin Panel, requiring registration and login for ticket creation.

5. **Agent and User Creation:**
   - Objective: Add agents (workers) like Jane and John, as well as users (customers) such as Karen and Ken, to populate the system with active participants.

These configuration objectives aim to establish a structured and collaborative environment within osTicket, ensuring effective management and streamlined ticket resolution processes.

<h2>Configuration Steps</h2>

<p>

</p>
<p>


**Step 1: Configure Roles**
- Navigate to Admin Panel -> Agents -> Roles.
- Create the "Supreme Admin" role.

**Step 2: Configure Departments**
- Navigate to Admin Panel -> Agents -> Departments.
- Create the "System Administrators" department.

**Step 3: Configure Teams**
- Navigate to Admin Panel -> Agents -> Teams.
- Create "Level I Support" team.
- Create "Level II Support" team.

**Step 4: Allow Anyone to Create Tickets**
- Navigate to Admin Panel -> Settings -> User Settings.
- Set "Registration Required" to require registration and login to create tickets.

**Step 5: Configure Agents (Workers)**
- Navigate to Admin Panel -> Agents -> Add New.
- Add agents:
  - Jane
  - John

**Step 6: Configure Users (Customers)**
- Navigate to Agent Panel -> Users -> Add New.
- Add users:
  - Karen
  - Ken

**Step 7: Configure SLA (Service Level Agreements)**
- Navigate to Admin Panel -> Manage -> SLA.
- Set up SLA levels:
  - Sev-A (1 hour, 24/7)
  - Sev-B (4 hours, 24/7)
  - Sev-C (8 hours, business hours)

**Step 8: Configure Help Topics**
- Navigate to Admin Panel -> Manage -> Help Topics.
- Create help topics:
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset

These steps guide you through the post-installation setup, configuring roles, departments, teams, user settings, agents, users, SLAs, and help topics for effective osTicket management.
</p>
<br />


<br />
