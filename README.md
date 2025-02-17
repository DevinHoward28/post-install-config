<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This project outlines the post-install configuration of the open-source help desk ticketing system osTicket. In this project, we will configure all key components to help run the ticketing system, such as roles for help desk employees, and departments our employees will belong to. <br />


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
- Configure Agents
- Configure Users
- Configure SLA

<h2>Configuration Steps</h2>

<p align="center">
To configure roles, you must go to the Admin Panel, then the Agents tab, and click Roles. Roles are the permissions given to Agents based on the Department that they belong to. You can create an unlimited amount of roles and assign them to Agents across different Departments.

![roles](https://github.com/user-attachments/assets/605e4b72-f4ed-458c-b8d6-c5e0c0986ae4)



<p align="center">
To configure departments, access the Admin Panel, click on Agents, and click Departments. Tickets are routed through Departments to make sure tickets get sent to the correct group of Agents. You can also have nesting Departments inside of Parent Departments.

  
![departments](https://github.com/user-attachments/assets/ef38be5f-b3d7-408c-9ee6-5f0c82c19e4b)

<p align="center">
To configure teams, ensure you're in the Admin Panel, then click Agents, and click Teams. Teams allow you to take agents from different Departments and organize them to solve a specific problem.

![Teams](https://github.com/user-attachments/assets/a7f106fe-79fb-4484-ac0b-ac4c9c2f8da0)

<p align="center">
To configure agents, go to your Admin Panel, click Agents, and then click Add New. Agents are essentially the help desk employees who receive the tickets and work them. When adding agents you have to add them to a specific department and give them roles within that department. Agents can also be given additional access to other Departments.

![Agents](https://github.com/user-attachments/assets/fdb9302a-d4f5-4b43-880f-8502f907c6c1)
<p align="center">
To configure users, go to the Agent Panel, click Users, and then click Add New. Users are essentially the owners of the tickets and they can create an account and log in to create their tickets.


![Users](https://github.com/user-attachments/assets/dc8ff091-2682-478f-babd-eb6e0da4c076)
<p align="center">
To configure SLA, click on the Admin Panel, then click Manage, and click SLA. As the Admin you must add SLA's so that your help desk employees have a timeline to follow according to the severity of the ticket. For example, if the CEO submits a ticket stating that his  computer is being hacked, the help desk employees will determine the business impact, and they will put it in the "Sev-A" category because it has a high business impact.

![SLA](https://github.com/user-attachments/assets/ee27d304-4216-408b-91cf-b0489234a640)
<p align="center">
To configure help topics, go to the Admin Panel, click manage, and click help topics. This is where the end user will select a category that aligns with the problem. For example, if a user needs a password reset they will put it under the password reset help topic.

![Help Topics](https://github.com/user-attachments/assets/0549dcf4-991b-4ba6-b890-316b3a02f994)

<br />
<br />
