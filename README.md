# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket system

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>
<ul>
  <li>Determine the differences between Agent Panel and Admin Panel</li>
  <li>Conifiguring different users</li>
  <li>Creating and developing an understanding for SLA </li>
  <li>Configure help topics</li>
</ul>

<h3>Configuration Steps</h3>
<h4>Log into Admin/Analyst Login Page via http://localhost/osTicket/scp/login.php and ensure successful login.</h4>
<img src="https://i.imgur.com/t33zJEJ.png">
<img src="https://i.imgur.com/ESaJPay.png">

<h2>Configure roles for grouping permissions </h2>
<h3>Admin Panel -> Agents -> Roles
 : Supreme Admin</h3>
<img src="https://i.imgur.com/uJ1WptD.png">
<img src="https://i.imgur.com/JVNYqmX.png">
<img src="https://i.imgur.com/vMcuSoS.png">
<img src="">

<h3>Admin Panel -> Agents -> Departments
: SysAdmin</h3>
<img src="https://i.imgur.com/jQhIkLS.png">
<img src="https://i.imgur.com/QOM0mPT.png">
<img src="https://i.imgur.com/lR1C0eR.png">

<h3>Admin Panel -> Agents -> Teams (User: Indi go -SysAdmins)
<img src="https://i.imgur.com/uPtpXgD.png"> 
<img src="https://i.imgur.com/4HbLDJY.png">
<img src="https://i.imgur.com/tac93Gl.png">
<img src="https://i.imgur.com/iOigX2I.png">
<img src="https://i.imgur.com/sGO6jd5.png">

<h3>Admin Panel -> Agents -> Teams (User: Lan Bo -Support</h3>
<img src="https://i.imgur.com/V7Qczot.png">
<img src="https://i.imgur.com/iCrbk6b.png">

<h2>Configure users</h2>
<h3>Agent Panel -> Users -> Add New</h3>
<h3>Create 2 new users</h3>
<img src="https://i.imgur.com/y6eD2C7.png">
<img src="https://i.imgur.com/n4QTchH.png">
<img src="https://i.imgur.com/sKyBUO9.png">
<img src="https://i.imgur.com/Be9TdaF.png">

<h3>Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
</h3>

<h3>Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other</h3>


