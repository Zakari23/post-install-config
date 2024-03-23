# Post-Install-Config
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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
Step 1. Configure Roles
  <p>
  After logging in, go to the ADMIN panel.
Click "Agents" on the top menu bar.
Then, click "Roles" on the lower menu bar.
Choose "Add New Role" to make roles for the organization. These roles decide who can do what tasks based on their departments and abilities, like assigning or closing tickets.
<p>
<img width="1046" alt="1" src="https://github.com/Zakari23/post-install-config/assets/158666482/b93b07ef-9e53-4f3d-b38e-4a967ad58119">

</p>
<p>
Step 2. Configure Departments
<p>
After logging in, go to the ADMIN panel.
Click "Agents" on the top menu bar.
Then, click "Departments" on the lower menu bar and choose "Add New Department".
Here, you can set up access levels for this department. Departments have various settings that affect how tickets move through them, including visibility and routing permissions.
<p></p>
<img width="994" alt="11" src="https://github.com/Zakari23/post-install-config/assets/158666482/a3bb3e12-64cb-4d55-9df4-64cc4897a143">

</p>
<p>
Step 3. Configure Teams
<p>
After logging in, go to the ADMIN panel.
Click "Agents" on the top menu bar.
Then, click "Teams" on the lower menu bar and choose "Add New Team".
Here, select team members and set their access levels. Setting up teams helps organize agents from different departments to address specific issues or users through Help Topics or Ticket Filters, regardless of their department's rules.
<p></p>
<img width="985" alt="13" src="https://github.com/Zakari23/post-install-config/assets/158666482/ae412015-f5f3-45d0-a0d5-326bb3f0dc33">


</p>
<p>
Step 4. Configure User
<p>
After logging in, go to the AGENT panel.
Click "Users" on the top menu bar.
Select "Add User" to create a new user and fill in their details.
Select the suitable options for "Require registration and login to create tickets." In osTicket, users are customers or internal members seeking assistance and own the ticket. Each user is linked to their email address.
<p></p>
<img width="1078" alt="15" src="https://github.com/Zakari23/post-install-config/assets/158666482/03c62498-b0e5-4eff-8302-014f6543c7ad">


</p>
<p>
Step 5. Configure SLA
<p>
After logging in, go to the ADMIN panel.
Click "Manage" on the top menu bar.
Then, click "SLA" on the lower menu bar and choose "Add New SLA Plan."
Here, could you select the right grace period hours and response schedule? SLA Plans determine the time help desk workers have to close a ticket.

<p></p>
<img width="971" alt="22" src="https://github.com/Zakari23/post-install-config/assets/158666482/b5cccaaa-ca06-4c72-89de-a4d188951c91">

</p>
<p>
Step 6. Configure Help Topics
<p>
Upon login, toggle to the ADMIN panel
Select "Manage" from the top menu bar
Select "Help Topics" from the lower menu bar and select "Add New Help Topic" Help Topics are created to ensure proper assignment and response of a ticket by assigning specific topics to the proper teams or departments.

<p></p>
<img width="973" alt="25" src="https://github.com/Zakari23/post-install-config/assets/158666482/fbc5f0e5-034f-4c0e-9cec-021addbf5ca3">

</p>
