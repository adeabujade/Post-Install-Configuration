<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Project Overview</h1>
Showcase the ability to set up and configure a help desk ticketing system with roles, departments, teams, users, SLAs, and help topics.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

Windows 10</b> (21H2)

<h2>Configuring a Help Desk Ticketing System</h2>

**Step 1: Configure Roles (Group Permissions)**

**1.Navigate to the Admin Panel -> Agents -> Roles.**

**2.Create a new role:**

    a.Role Name: Supreme Admin.
  
    b.Permissions: Assign all necessary administrative permissions.

![image](https://github.com/user-attachments/assets/7cc0b905-ec63-4b24-95c6-51382dbfef79)

  
**Step 2: Configure Departments (Control Ticket Visibility)**

**1.Navigate to the Admin Panel -> Agents -> Departments.**

**2.Create the following departments:**

    a.SysAdmins

![image](https://github.com/user-attachments/assets/77e50c32-00f9-4897-9802-a5c8abaee390)


  
**Step 3: Configure Teams (Combine Agents Across Departments)**

**1.Go to the Admin Panel -> Agents -> Teams.**

**2.Create a team:**

    a.Team Name: Online Banking.
  
    b.Assign Agents: Pull agents from different departments as needed.
  
**Step 4: Configure User Access to Tickets**

**1.Go to the Admin Panel -> Settings -> User Settings.**

**2.Configure ticket creation permissions:**

    a.UNCHECK: "Require registration and login to create Tickets"

![image](https://github.com/user-attachments/assets/dc77933e-684c-463a-ba95-5a7df2b97edf)

  
**Step 5: Configure Agents (Workers)**

**1.Navigate to the Admin Panel -> Agents -> Add New.**

**2.Add the following agents:**

    a.Ken: Assign to the SysAdmins department.    

        -Select a password in Set Password
    
        -For Access > Primary Department select support SysAdmin and Supreme Admin
    
  
    b.Ben: Assign to the Support department.

        -Select a password in Set Password
        
        - For Access > Primary Department select Support and All Access

![image](https://github.com/user-attachments/assets/547bc326-9548-49db-805b-13891bd49269)

  
**Step 6: Configure Users (Customers)**

**1.Go to the Agent Panel -> Users -> Add New.**

**2.Add the following users:**

    a.Jen
  
    b.Gwen

![image](https://github.com/user-attachments/assets/4f9eddb4-a4bf-4a46-a5ff-2f8b4a008794)


**Step 7: Configure SLA (Service Level Agreements)**

**1.Navigate to the Admin Panel -> Manage -> SLA.**

**2.Create the following SLAs:**

    a.Sev-A: Grace Period: 1 hour, Schedule: 24/7.
  
    b.Sev-B: Grace Period: 4 hours, Schedule: 24/7.
  
    c.Sev-C: Grace Period: 8 hours, Schedule: Business Hours.

![image](https://github.com/user-attachments/assets/60750a39-a391-43a2-8b28-f3adf16fcd7d)

  
**Step 8: Configure Help Topics**

**1.Go to the Admin Panel -> Manage -> Help Topics.**

**2.Add the following help topics for ticket creation:**

      a.Business Critical Outage
  
      b.Personal Computer Issues
  
      c.Equipment Request
  
      d.Password Reset
      
      e.Other

![image](https://github.com/user-attachments/assets/7341ef6a-e35c-4365-a397-945773d170f5)


