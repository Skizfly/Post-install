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

![image](https://github.com/Skizfly/Post-install/assets/153954157/46c43a4f-11eb-42fd-a893-7910061ab5bf)
![image](https://github.com/Skizfly/Post-install/assets/153954157/c7de9432-6f50-4699-9402-55c3e81cf7ed)


<p>
</p>
<p>
Upon osTicket installation, it's time to configure it as a ticketing system. Note the switch between Admin and Agent panels, each with distinct configurations. Identify the active panel at the top right: "Agent Panel" indicates Agent, and vice versa.

Initiate by establishing a new role, "Supreme Admin." In the Admin panel, access Agents Menu, click Roles, and craft this all-permission role for lab purposes.
</p>
<br />

![image](https://github.com/Skizfly/Post-install/assets/153954157/f52c2501-200a-4095-9ca7-e7dedffd16ce)

<p>
</p>
<p>
Proceeding, a fresh Department for System Administrators will be established. In the Admin panel, navigate to the Agents menu, and select Departments to craft a new Department in osTicket.
</p>
<br />

![image](https://github.com/Skizfly/Post-install/assets/153954157/3ed42afb-acc8-4cd3-b0cc-011d7df317d6)

<p>
</p>
<p>To complement the existing Level I Support Team in osTicket, establish a new Level II Support Team. In the Admin panel, access the Agents menu, click on Teams, and add any necessary new teams.
</p>
<br />

![image](https://github.com/Skizfly/Post-install/assets/153954157/90bcc436-9c23-4b92-988b-b0f5f49480d5)
![image](https://github.com/Skizfly/Post-install/assets/153954157/6c361aae-7f3e-41aa-b8f5-9b2b405e838b)

<p>
</p>
<p>New agents will have to be created so they can take tickets that come to the queue. To create new agents, enter the Admin panel and open the Agents menu. Click on Add New Agent and create the account credentials for each new agent. In this case, Mekhi and Caleb are created.
</p>
<br />

![image](https://github.com/Skizfly/Post-install/assets/153954157/8a966a90-bd94-4a4b-ae6f-2733b3b22f08)

<p>
</p>
<p>Generate new users to initiate ticket creation for agent triaging. In the Agents panel, access the Users menu, click Add User, and provide the required account credentials for each user. In this instance, accounts for Karen and Ken have been established.
</p>
<br />

![image](https://github.com/Skizfly/Post-install/assets/153954157/0442c074-b83e-49c9-8844-972fddf16ebb)

<p>
</p>
<p>Establish Service Level Agreements (SLAs) to categorize tickets by their impact levels. In the Admin panel, access the Manage menu, click on SLA, and generate the required SLAs. Here, SEV-A, B, and C have been created, signifying resolutions within 1, 4, and 8 hours, respectively.
</p>
<br />

![image](https://github.com/Skizfly/Post-install/assets/153954157/71bda2ab-c47e-4d16-8a21-ff12cd825184)

<p>
</p>
<p>Concluding the setup, create Help Topics to guide users in selecting categories that describe their issues. In the Admin panel, access the Manage menu, click Help Topics, and select Add New Help Topic. In this instance, I've added Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request to facilitate ticket resolution.
</p>
<br />

<h1>osTicket Configurations Complete</h1>
<p>
</p>
<p>With the configurations in place, osTicket is ready as a comprehensive ticketing system. I can seamlessly create and triage tickets, mimicking real-world scenarios.
</p>
<br />
