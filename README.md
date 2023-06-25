<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to setup and configure osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- osTicket installed and ready to go
- Admin login credentials


<h2>Login URL Links</h2>

- Help desk login page: http://localhost/osTicket/scp/login.php 

- End Users osTicket URL: http://localhost/osTicket/

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/NZjRE0p.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>

    *GENERAL OVERVIEW*

<p>
<img src="https://imgur.com/RY5Xf5v.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 1:
  *Configuring roles*
1. Admin Panel -> Agents -> Roles
2. Supreme Admin

</p>
<br />

<p>
<img src="https://i.imgur.com/BrtNEee.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 2:
  *Configure Departments*
1. Admin Panel -> Agents -> Departments
2. System Administrators

</p>
<br />

<p>
<img src="https://i.imgur.com/qMhdki5.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 3:
  *Configure Teams*
 1. Admin Panel -> Agents -> Teams
2.  Level I Support
3. Level II Support

<p>
<img src="https://i.imgur.com/ajD2CN8.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 4:
  *Allow anyone to create tickets*
  1. Admin Panel -> Settings -> User Settings
2. Registration Required: Require registration and login to create tickets

<p>
<img src="https://i.imgur.com/QgcvwRP.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 5:
*Configure Agents (workers)*
1. admin Panel -> Agents -> Add New
2. Jane
3. John

<p>
<img src="https://i.imgur.com/90r8plc.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 6:
  *Configure Users (customers)*
  1. Agent Panel -> Users -> Add New
2. Karen
3. Ken

<p>
<img src="https://i.imgur.com/Dj3XUL3.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 7:
  *Configure SLA*
  1. Admin Panel -> Manage -> SLA
2. Sev-A (1 hour, 24/7)
3. Sev-B (4 hours, 24/7)
4. Sev-C (8 hours, business hours)

<p>
<img src="https://i.imgur.com/cxCsO9V.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  STEP 8:
  *Configure Help Topics*
1. Admin Panel -> Manage -> Help Topics
2. Business Critical Outage
3. Personal Computer Issues
4. Equipment Request
5. Password Reset
 
