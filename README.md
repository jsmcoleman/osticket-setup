<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Setup </h1>
This tutorial outlines the setup and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Configure roles, departments, and teams
- Allow anyone to create tickets
- Configure agents and users
- Configure SLA
- Configure Help Topics

<h2>Setup Steps</h2>

<p>
<img src="https://i.imgur.com/EIlF89Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/J0QcGmd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, I needed to create admin roles. I created a supreme admin role that would have access to all components of osticket. This role will need to be assigned to a department, so I created a department named "System Adminstrators". Finally, I created teams for the potential agents; Level I support and Level II support.
</p>
<br />

<p>
<img src="https://i.imgur.com/uIjR2Sx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I allowed anyone to create tickets and removed "require registration" in the user settings. 
</p>
<br />

<p>
<img src="https://i.imgur.com/FBtNbbI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/baYfki3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then, I created my agents and users. One agent was assign to the supreme admin role and the other was a standard employee. I created two users to submit tickets to these agents.
</p>
<br />

<p>
<img src="https://i.imgur.com/kqwlzpJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I configured SLA and created three levels to the importance of tickets that are submitted. Sev-A would have a timeframe of 1 hour to be serviced on a 24/7 schedule. Sev-B would have a timeframe of 4 hours to be serviced on a 24/7 schedule. Sev-C would have a timeframe of 8 hours to be serviced during business hours. 
</p>
<br />

<p>
<img src="https://i.imgur.com/adgoBXj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, I configured help topics to categorize tickets. I added Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.
</p>
<br />
