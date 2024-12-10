# osTicket: Post-installation-configuration
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

This tutorial provides a step-by-step guide for the post-installation configuration of the open-source help desk ticketing system, osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Configuration Steps</h2>

After installing osTicket, the next step is to configure it for use as a ticketing system. It's important to note that I switch between the Admin Panel and the Agent Panel during the configuration process, as each panel offers different settings. To determine which panel you are currently using, check the top-right corner of the osTicket screen. If it displays "Agent Panel," you are in the Admin Panel, and vice versa.

The first configuration task is to create a new role called Supreme Admin. For this lab, I am intentionally setting up a role with all available permissions. To create the new role, navigate to the Admin Panel, open the Agents menu, and click on Roles. From there, create the new role and configure it as needed. 



<img width="920" alt="adding a new department Sys Admin" src="https://github.com/user-attachments/assets/b10dbb2e-82c7-4107-b502-3a2bffa2043f">
</p>
<p>
</p>
<p>

Next, create a new department for System Administrators. To do this, navigate to the Admin Panel, open the Agents menu, and select Departments. From there, create the new department within osTicket.
</p>
<p>
</p>
<p>





<img width="929" alt="onloine banking team" src="https://github.com/user-attachments/assets/2a4a70b7-2f4c-466d-9f74-b26f0d1e5eac">
</p>
<p>
</p>
A new Level II Support Team needs to be created to complement the existing Level I Support Team in osTicket. To add a new team, navigate to the Admin Panel, open the Agents menu, and select Teams. From there, create any additional teams as needed.
</p>
<p>
</p>
<p>

  
<img width="932" alt="both agents" src="https://github.com/user-attachments/assets/e2750521-5b4b-4ffa-b0d8-ce552bc8e3ac">
</p>
<p>
</p>
New agents need to be added to handle tickets in the queue. To create new agents, go to the Admin Panel, open the Agents menu, and select Add New Agent. From there, set up account credentials for each agent. For this example, agents Jane Doe and John Doe were created.
</p>
<p>
</p>
<p>
<img width="932" alt="creating new users" src="https://github.com/user-attachments/assets/b1139425-324c-4186-8d8a-e0cacb7437bc">



New users need to be added so they can submit tickets for agents to receive and triage. To create new users, navigate to the Agents Panel, open the Users menu, and select Add User. From there, set up the necessary account credentials for each user. In this example, Karen and Ken were created.
</p>
<p>
</p>
<p>
<img width="928" alt="SLA's" src="https://github.com/user-attachments/assets/67eb9385-213a-4346-81dc-53d42b24d48f">


Service Level Agreements (SLAs) are required to categorize tickets based on their level of impact. To create new SLAs, go to the Admin Panel, open the Manage menu, and select SLA. From there, set up the necessary SLAs. For this lab, SEV-A, SEV-B, and SEV-C were created to prioritize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours, respectively.
</p>
<p>
</p>
<p>



<img width="932" alt="Help Topics" src="https://github.com/user-attachments/assets/07659d24-c2f1-4bf5-971c-3989738de595">


Finally, Help Topics must be created to allow users to categorize their issues, giving agents a clearer understanding of the problem described in the ticket. To add a new Help Topic, navigate to the Admin Panel, open the Manage menu, and select Help Topics. Click on Add New Help Topic and create the required categories. For this lab, the following Help Topics were added for future ticket creation and resolution: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Reset.


<h2>osTicket Configuration completed!<h2>

With the configurations complete, osTicket is now ready to function as a fully operational ticketing system. I can create tickets and triage them, simulating a real-world environment.














































