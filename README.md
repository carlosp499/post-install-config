# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

-These are some of the configurations that I will cover. 

- Configure roles
- Configure Departments 
- Configure teams 
- Configure agents 
- Configure users
- Configure SLA
- Configure Help topics

<h2>Configuration Steps</h2>
-Step #1: configure roles

you will log on to the admin/analyst page

Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 
<img width="1789" height="927" alt="4" src="https://github.com/user-attachments/assets/f2fb6978-b8a3-405f-80bc-46907b0b6063" />

once logged in we will create a new role:

- you will click on the "admin panel" tab to swithc over to the admin view

- neext click on the "agents" tab (highlighted in yellow)

- click on roles (marked in blue), and then go to "add new roles" (maarked in red)

- new role will be named "supreme admin", then go to permissions and check all the boxes

- do teh same in teh next tabs "tasks" & "knowledge"

- click on add role

-Step #2: configure departments

- stay in the agents tab,  but click on the "departments" tab

- when it takes you to the settings choose "top level deaprtment" and name it "SysAdmins" and then click on create department

-Step #3: Configure team, Allow ticket creation

- whle still on the agents tab, click on "teams"

- after click on "add new team", name it "online banking", click on create team

- next click on settings

- then go to users and double check "registration required" box is not checked off

-Step #4: configure agents 

- click on agents tab, then on add new agent

- name the agent jane doe, email janed@gamil.com, username: jane, password: password1

- next click on access

- assing department as SysAdmin, and her role as Supereme Admin, and add her to the online banking team in the "teams" tab click on create

- following the same steps add another new agent named john doe

- email is johnd@gmail.com, username: john, password: password1

- department will be support and role is view only, no team assinged, click on create

-Step #5: configure customer

- you will click on the "Agent Panel" tab on the top right of the screen (high lighted in yellow)

- next you willl click on users tab

- click on add new user

- new user's name is karen

- email: karen@gmail.com

- then you will click on add user

-Step #6: configure SLA

- Click on Admin panel

- go to "Manage" tab, then click on the "add new SLA" tab

- name of the new SLA is SEV-A, Grace Period: 1hr, Schedule: 24/7

- then click on add plan

- following the same instructions, click on add new SLA

- new SLA name is SeV-B, Grace Period: 4hr, Schedule: 24\7

- click on add paln

- click on addd new SLA plan

- new SLA name is Sev-C, Grace Period: 8hr, Schedule: M-F 8AM-5PM with U.S. Holidays

-Steo #7: Configure Help Topics

- on the manage tab you will go to the "Help Topic" section

- click on the "add new help topic" tab (marked in red)

- the topic will be named "Business Critical Outage", put parent topic as "report a problem"

- click on add topic

- go back to the help topic tab and click on the add new help topic

- the help topic will be named Personal Computer Issues, and parent topic is "report a problem"

- click add topic

- following the last instructions creater new help topic

- help topic name Equipment Request, parent topic is "general inquiry"

-  next mew help topic will be called Password Reset, parent topic is  "report a problem"

-  last new help topic will named " other", parent topic is "general inquiry" 
