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

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets


<h2>Configuration</h2>
<p></p>

<h2>Configure Roles</h2>
<p>
<img src="https://i.imgur.com/nUaqO0l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Admin panel (http://localhost/osTicket/scp/login.php ) make sure you're logged in as the admin profile user/password from setup 
  
  -Switch to the correct page, the admin panel will read "Agent Panel" in the top right as highlighted.
  
  -Select Agents and Roles to add a new Role
  
  -https://docs.osticket.com/en/latest/Admin/Agents/Roles.html Follow link to osTickets web page for full breakdown of functionality 
</p>
<h2>Configure Departments</h2>
<br />

<p>
<img src="https://i.imgur.com/4mlELRJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  -Switch to the correct page, the admin panel will read "Agent Panel" in the top right as highlighted.
  
  -Select Agents and Departments to add a new Departments
  
  -https://docs.osticket.com/en/latest/Admin/Agents/Departments.html Follow link to osTickets web page for full breakdown of functionality 
</p>
<h2>Configure Teams</h2>
<br />

<p>
<img src="https://i.imgur.com/KDmapWs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  -Switch to the correct page, the admin panel will read "Agent Panel" in the top right as highlighted.
  
  -Select Agents and Teams to add a new Teams
  
  -https://docs.osticket.com/en/latest/Admin/Agents/Teams.html Follow link to osTickets web page for full breakdown of functionality 
</p>
<br />
<h2>Allow anyone to create tickets</h2>
<p>
<img src="https://i.imgur.com/50Souo2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
  
  -Registration Required: Require registration and login to create tickets 
