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

- you will click on the "admin panel" tab to switch over to the admin view

<img width="1243" height="558" alt="5" src="https://github.com/user-attachments/assets/7b77fe1b-b173-4175-9ae5-f4a4029513cb" />

- next click on the "agents" tab (highlighted in yellow)

- click on roles (marked in blue), and then go to "add new roles" (maarked in red)

<img width="1203" height="624" alt="7" src="https://github.com/user-attachments/assets/20f64d21-491d-472c-af16-4a55cc4a7f03" />

- new role will be named "supreme admin", then go to permissions and check all the boxes

<img width="1238" height="664" alt="8" src="https://github.com/user-attachments/assets/c5f5d1e9-da02-4e25-a919-8cc07a596703" />

- do teh same in the next tabs "tasks" & "knowledge"

- click on add role

-Step #2: configure departments

- stay in the agents tab,  but click on the "departments" tab

<img width="1305" height="692" alt="9" src="https://github.com/user-attachments/assets/9b01e7e3-c47e-432b-9817-20bbfe5f6c78" />

- when it takes you to the settings choose "top level deaprtment" and name it "SysAdmins" and then click on create department

<img width="1185" height="956" alt="10" src="https://github.com/user-attachments/assets/091eb661-2f67-4414-b1f2-db12bea2b550" />

-Step #3: Configure team, Allow ticket creation

- whle still on the agents tab, click on "teams"

- after click on "add new team", name it "online banking", click on create team

- next click on settings

- then go to users and double check "registration required" box is not checked off

-Step #4: configure agents 

- click on agents tab, then on add new agent

<img width="1166" height="566" alt="11" src="https://github.com/user-attachments/assets/eebe617d-dfe3-4300-bbe3-0e1d273eff7a" />

- name the agent jane doe, email janed@gamil.com, username: jane, password: password1

<img width="1043" height="963" alt="12" src="https://github.com/user-attachments/assets/42b85b7b-4e2d-4059-a2e0-87ec47867c02" />

- next click on access

- assing department as SysAdmin, and her role as Supereme Admin, and add her to the online banking team in the "teams" tab click on create

- following the same steps add another new agent named john doe

- email is johnd@gmail.com, username: john, password: password1

- department will be support and role is view only, no team assinged, click on create

-Step #5: configure customer

- you will click on the "Agent Panel" tab on the top right of the screen (high lighted in yellow)

<img width="1123" height="507" alt="13" src="https://github.com/user-attachments/assets/9b1e17a6-ae68-4284-9258-7038f24fb801" />

- next you will click on users tab

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
