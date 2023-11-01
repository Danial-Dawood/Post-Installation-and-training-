# <p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. As well as Navigation and the basic Operation of osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1 - Configuring Roles (Admin Panel/Agents/Roles) - https://docs.osticket.com/en/latest/Admin/Agents/Roles.html
- Item 1.5 - To Configure a Role make sure that on the Top right it says "Agent Panel".(if it says admin panel click it and it will change To Agent panel) Then Click "Agents" and under   the agents tab there will be a "Roles" subsection. Then click "Add New Role."(This is what is looks like)<img width="1440" alt="Screen Shot 2023-11-01 at 2 26 12 PM" src="https://github.com/Danial-Dawood/Post-Installation-and-training-/assets/149525309/b33ac542-ca23-487f-b45a-72c889146ae5">
- Item 1.75 - Make a New Role call is "Supreme Admin," and under the Permissions tab give this role All of the permissions(check everything.) 
- Item 2 - Configure Departments(Admin Panel/Agents/Departments) - https://docs.osticket.com/en/latest/Admin/Agents/Departments.html
- Item 2.5 - While still being in the Agent Panel click 'Departments" (This is what the Department Panel Looks like)<img width="1440" alt="Screen Shot 2023-11-01 at 3 01 15 PM" src="https://github.com/Danial-Dawood/Post-Installation-and-training-/assets/149525309/2e01fd92-a2cf-40dd-9a5b-74f0c67eb2bb">
- Item 2.75 - Create a new department and name it "System Administrators" (Leave all other options in their default position.) 
- Item 3 - Configure Teams(Admin Panel/Agents/Teams) - https://docs.osticket.com/en/latest/Admin/Agents/Teams.html
- Item 3.5 - Still under the Agent Panel clik on the teams Subsection and create two different teams "Level One Support" and "Level Two Support(Add yourself to Level Two"(example below take note how it even displays that we have assigned one team member to level two support)<img width="1440" alt="Screen Shot 2023-11-01 at 3 23 36 PM" src="https://github.com/Danial-Dawood/Post-Installation-and-training-/assets/149525309/6849e06e-59d9-4970-a49f-f8b676edd512">
- Item 4 - Allow all to Create Tickets(Admin Panel/Settings/Authentication Settings) 
- Item 5 - Configure Agents(Workers) (Admin Panel/Agents/Add New)
- Item 6 - Configure Users(Customers)(Agent Panel/Users/Add New)
- Item 7 - Configure SLA(Level of service expected by a customer from a supplier)(Admin Panel/Manage/SLA)
- Item 8 - Configure Help Topics(Admin Panel/Manage/Help Topics)




