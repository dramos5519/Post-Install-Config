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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>
This part is done with the individual already being logged into OsTicket
These are the two pages that consist of Admin and User logins
Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

End Users osTicket URL:
http://localhost/osTicket 

<p>
<img width="385" alt="image" src="https://github.com/user-attachments/assets/652d7a63-998b-48ec-8bc1-8716866632ad" />

<p>
<img width="586" alt="image" src="https://github.com/user-attachments/assets/5302f508-bb7d-4b76-86de-497e7402d78d" />
  
Agents tab/ Roles/ Add New Role 

<img width="512" alt="image" src="https://github.com/user-attachments/assets/8778b6d2-762e-4413-94f5-4163b3bb288a" />

We are going to Create a Supreme Admin (Your Choice of Title)

</p>
<p>


<img width="524" alt="image" src="https://github.com/user-attachments/assets/be7ec525-6413-4e64-b895-9b24d89803e5" />

Here we check all boxes containing permissions, including all Tickets, Tasks, and Knowledgebase tabs seen here.

<img width="457" alt="image" src="https://github.com/user-attachments/assets/1fc9b629-d9fe-4fa8-bc38-36f254147c2c" />


Here you can see the new role "Supreme Admin" is now available. 

+ Next, we will CONFIGURE DEPARTMENTS.



