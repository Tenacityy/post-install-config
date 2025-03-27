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

- Configure Roles (for grouping permissions
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Configure Agents (Workers)
- Configure Users (Customers)
- Configure SLA (Service Level Agreement)
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
From the osTicket home screen Navigate to Admin Panel -> Agents -> Roles
<p>
<img src="https://i.imgur.com/3ij92ER.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MoDDSRI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/WKxuvun.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
1) I will create a new role and assign permissions.
</p>
<img src="https://i.imgur.com/R3Bhz1p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/nFOtRyE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
I checked all boxes for  Tickets, Tasks and Knowledgebase
<p>
<img src="https://i.imgur.com/nZUKWZt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/W356abG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
From the Admin Panel go to -> Agents -> Departments
<p>
<img src="https://i.imgur.com/faPC7mx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/K4PpHaj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
2) Lets create a new department!
<p>
<img src="https://i.imgur.com/y23878u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MawQZqW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Here you can add specific Agents to your new Department
<p>
<img src="https://i.imgur.com/cJrrIqr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/EyCyuxA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
From the Admin Panel go to -> Agents -> Teams (Pull Agents from different Departments)
<p>
<img src="https://i.imgur.com/vtpcNrt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>

<p>
3) Let's create a Team!
<p>
<img src="https://i.imgur.com/AVMZRnm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/0c8n55G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/09DDwp5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<p>
From the Admin Panel go to -> Agents -> Add New Agent
<p>
<img src="https://i.imgur.com/kgDfuqO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<p>
4) Let's create a New Agent!
<p>
<img src="https://i.imgur.com/vvIqELX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
You can also set permissions and assign the New Agent to a Team
<p>
<img src="https://i.imgur.com/KB6AnVt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<p>
5) Now let's create Users (Customers). Navigate to Agent Panel -> Users -> Add New User
<p>
<img src="https://i.imgur.com/CSDnmwy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/0nsMEGz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/cFFs13m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<p>
</p>
<p>
6) Now let's Configure SLA (Service Level Agreement). Navigate to Admin Panel -> Manage -> SLA
<p>
<img src="https://i.imgur.com/w6TlEbY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/LCSxGpL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/C4Hoeve.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TqJWkOh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/St2xPmd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/uiz6tnC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<p>
7) Now let's Configure Help Topics (For when Users create tickets). From Admin Panel Naviagte to -> Manage -> Help Topics
<p>
<img src="https://i.imgur.com/LCSxGpL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Ez7FJTu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/xA22X4H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/luNw2g3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/tgMNdde.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
That's it for the Post-Install Configuration of osTicket! This was just the basics to get familiar with the program.
</p>
<p>
</p>
<p>


