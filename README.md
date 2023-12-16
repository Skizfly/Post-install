<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial illustrates the essential modifications I implement to set up osTicket as a functional ticketing system.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Establish Roles
- Create Departments
- Create Support Groups
- Establish Service Level Agreements (SLA's)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Upon osTicket installation, it's time to configure it as a ticketing system. Note the switch between Admin and Agent panels, each with distinct configurations. Identify the active panel at the top right: "Agent Panel" indicates Agent, and vice versa.

Initiate by establishing a new role, "Supreme Admin." In the Admin panel, access Agents Menu, click Roles, and craft this all-permission role for lab purposes.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Proceeding, a fresh Department for System Administrators will be established. In the Admin panel, navigate to the Agents menu, and select Departments to craft a new Department in osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>To complement the existing Level I Support Team in osTicket, establish a new Level II Support Team. In the Admin panel, access the Agents menu, click on Teams, and add any necessary new teams.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>New agents will have to be created so they can take tickets that come to the queue. To create new agents, enter the Admin panel and open the Agents menu. Click on Add New Agent and create the account credentials for each new agent. In this case, Jane and John Doe are created.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Generate new users to initiate ticket creation for agent triaging. In the Agents panel, access the Users menu, click Add User, and provide the required account credentials for each user. In this instance, accounts for Karen and Ken have been established.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Establish Service Level Agreements (SLAs) to categorize tickets by their impact levels. In the Admin panel, access the Manage menu, click on SLA, and generate the required SLAs. Here, SEV-A, B, and C have been created, signifying resolutions within 1, 4, and 8 hours, respectively.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Concluding the setup, create Help Topics to guide users in selecting categories that describe their issues. In the Admin panel, access the Manage menu, click Help Topics, and select Add New Help Topic. In this instance, I've added Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request to facilitate ticket resolution.
</p>
<br />

<h1>osTicket Configurations Complete</h1>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>With the configurations in place, osTicket is ready as a comprehensive ticketing system. I can seamlessly create and triage tickets, mimicking real-world scenarios.
</p>
<br />
