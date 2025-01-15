<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
Showcase the ability to set up and configure a help desk ticketing system with roles, departments, teams, users, SLAs, and help topics.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

Windows 10</b> (21H2)

<h2>Configuring a Help Desk Ticketing System</h2>

**Step 1: Configure Roles (Group Permissions)**

1.Navigate to the Admin Panel -> Agents -> Roles.

2.Create a new role:

  a.Role Name: Supreme Admin.
  
  b.Permissions: Assign all necessary administrative permissions.
  
**Step 2: Configure Departments (Control Ticket Visibility)**

1.Navigate to the Admin Panel -> Agents -> Departments.

2.Create the following departments:

  -SysAdmins
  
  -Help Desk
  
  -Networking
  
**Step 3: Configure Teams (Combine Agents Across Departments)**

1.Go to the Admin Panel -> Agents -> Teams.

2.Create a team:

  -Team Name: Online Banking.
  
  -Assign Agents: Pull agents from different departments as needed.
  
**Step 4: Configure User Access to Tickets**

1.Go to the Admin Panel -> Settings -> User Settings.

2.Configure ticket creation permissions:

  -UNCHECK: "Unregistered users can create tickets."
  
  -Enable: Require user registration and login to create tickets.
  
**Step 5: Configure Agents (Workers)**

1.Navigate to the Admin Panel -> Agents -> Add New.

2.Add the following agents:

  -Jane: Assign to the SysAdmins department.
  
  -John: Assign to the Support department.
  
**Step 6: Configure Users (Customers)**

1.Go to the Agent Panel -> Users -> Add New.

2.Add the following users:

  -Karen  
  
  -Ken
  
**Step 7: Configure SLA (Service Level Agreements)**

1.Navigate to the Admin Panel -> Manage -> SLA.

2.Create the following SLAs:

  a.Sev-A: Grace Period: 1 hour, Schedule: 24/7.
  
  b.Sev-B: Grace Period: 4 hours, Schedule: 24/7.
  
  c.Sev-C: Grace Period: 8 hours, Schedule: Business Hours.
  
**Step 8: Configure Help Topics**

1.Go to the Admin Panel -> Manage -> Help Topics.

2.Add the following help topics for ticket creation:

  -Business Critical Outage
  
  -Personal Computer Issues
  
  -Equipment Request
  
  -Password Reset
  
  -Other

