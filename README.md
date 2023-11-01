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
- Item 4.5 - To enable all to make tickets we Click on "Settings" and then "User Setting." make sure "Registration Required:[	] Require registration and login to create tickets is unchecked. this makes it so that we can make tickets without have to worry about logins)<img width="1440" alt="Screen Shot 2023-11-01 at 3 31 59 PM" src="https://github.com/Danial-Dawood/Post-Installation-and-training-/assets/149525309/126f3edf-3161-4b82-bb38-02a692277ab9">
- Item 5 - Configure Agents(This is the acutal help desk workers) (Admin Panel/Agents/Add New) https://docs.osticket.com/en/latest/Admin/Agents/Agents.html
- Item 5.5 - Create Two agents, click "Agents" and then "Add New Agent." When creating their Username make sure you write it down. right next to the username there will be a tab with the refresh logo as well as the words "Set Password" when you click this is will give you the ability to set this agents password(make sure you have these two options no checked when setting the password)<img width="1440" alt="Screen Shot 2023-11-01 at 3 46 42 PM" src="https://github.com/Danial-Dawood/Post-Installation-and-training-/assets/149525309/f6ea6881-d7ae-4388-9975-46fd422fbf61">
- Item 5.75 - Under the Acess panel when creating this agent for "Primary Department" Put them as a "System administrators" and as "Supreme Admin" <img width="1440" alt="Screen Shot 2023-11-01 at 3 57 45 PM" src="https://github.com/Danial-Dawood/Post-Installation-and-training-/assets/149525309/e338bf4e-9b22-4750-86e7-6b444cf1eb6e"> For the last step for the creation of this Agent under "Teams" Assign them to "Level Two Support"
- Item 6 - For the Next agent we are creating everything will be about the same exact for the "Access" tab. Under "Primary Department" put this agent under "Support" and "View only"(This is the only setting that will be chnaged the rest will be left in its defualt postion)<img width="1440" alt="Screen Shot 2023-11-01 at 4 04 57 PM" src="https://github.com/Danial-Dawood/Post-Installation-and-training-/assets/149525309/3ad81e8b-217b-48a5-a80e-1ba73f954394">
- Item 7 - Configure Users(Customers)(Agent Panel/Users/Add New) https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html 
- Item 7.5 - To create New users We will Have to Switch over to the "Admin Panel" so click at the very top right of the screen.(Right next to your username it will say what panel youre going to go if you click it.) Then go over "Users" and under "User Directory" click "Add User" andc create two new users (should look somthing like this when you're done) <img width="1440" alt="Screen Shot 2023-11-01 at 4 28 17 PM" src="https://github.com/Danial-Dawood/Post-Installation-and-training-/assets/149525309/566c9910-5925-4a28-815d-4c16481bef34">
- Item 8 - Configure SLA(The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.)(Admin Panel/Manage/SLA) https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html
- Item 8.5 - To make SLA we will have to switch Agent Panel we are currently in to the Admin panel. Then click manage and one of the subsections under willl be titlesd SLA thats where we will be creating our three SLA Plans. Sev-A(1 Hour-24/7), Sev-B(4 Hour-24/7) Sev-C(8 Hours-Business hours). This is what it should look like youre done making those three SLA Plans<img width="1440" alt="Screen Shot 2023-11-01 at 4 52 58 PM" src="https://github.com/Danial-Dawood/Post-Installation-and-training-/assets/149525309/52497fba-60d6-4ec5-825f-6055acc35f46">

- Item 8 - Configure Help Topics(Admin Panel/Manage/Help Topics)




