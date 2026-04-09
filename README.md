<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />
<p>
Two URL's are used to complete the tasks for osTicket, The first one is for End Users Submitting Tickets → </head>
<body>
	<a href="https://localhost/osTicket">End Users osTicket URL:</a>
</body>
</html><br /> and The second one is used to Login as an Admin/Helpdesk Technician → <body>
	<a href="https://localhost/osTicket/scp/login.php">Admin/Analyst Login Page:</a>
</body>
</html><br />
</p>



<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 11Pro</b> (24H2)

<h2>Ticket Lifecycle Stages</h2>
<p>
	
**- Stage 1. Intake -** This is where End Users create and submit tickets that captures the user's issue or request with intial details.

</p>

<p>
	
**- Stage 2. Assignment and Communication -** This is when the ticket is assigned to the appropriate agent/team, and communication starts to clarify and update the issue.

</p>

<p>
	
**-Stage 3. Working the Issue -** This is when the assigned agent acitively investigates, troubleshoots, and works toward resolving the problem.

</p>

<p>
	
**-Stage 4. Resolution -** This is when the issue is resolved, the solution is documented, and the ticket is closed after confirming completion.

</p>

<h2>Lifecycle Stages</h2>

<p>

**Stage 1 - Intake**

Begin the Intake Stage by using → </head> <body>
	<a href="https://localhost/osTicket">End Users osTicket URL:</a> to submit a ticket as Karen. Click "Open a New Ticket" to Begin.
	
</p>


<p>
<img width="821" height="465" alt="Screenshot 2025-11-06 at 4 55 10 PM" src="https://github.com/user-attachments/assets/f44f1f98-aa77-4cd4-819a-a69b9c04309b" />

<p>
Next, After clicking "Open a New Ticket" fill in the Contact Information Form↓
</p>

<p>
Email Address: karen@lognpacific.com
</p>

<p>
Full Name: karen
</p>

<p>
Help Topic: General Inquiry / Other	
</p>

<p>
Issue Summary: "The entire mobile/online banking system seems to be down."	
</p>

<p>
Under the Issue Summary, Give further detail in the allocated space. Then, submit the ticket by clicking "Create Ticket."	
</p>
	
<img width="845" height="879" alt="Screenshot 2026-02-18 at 2 02 39 AM" src="https://github.com/user-attachments/assets/b0bf51d4-ca47-4a2f-82d6-2b45d79c3fdb" />

<p>
The support ticket request was successfully created and sent over to the Support Team.	
</p>
<img width="820" height="288" alt="Screenshot 2025-11-06 at 4 59 00 PM" src="https://github.com/user-attachments/assets/d78573c5-0a91-4f3c-8b5c-5682c9da36cc" />

<p>

**Stage 2 - Assignment and Communication**

Begin the Assignment & Communication Stage by Logging in as the Helpdesk Technician(John) → <body>
	<a href="https://localhost/osTicket/scp/login.php">Admin/Analyst Login Page:</a> </body> </html><br />

<p>
Username: john
</p>	
<p>
Password: Password1	
</p>

<p>

**Click Log In**
	
</p>

</p>
<img width="498" height="497" alt="Screenshot 2025-11-06 at 4 59 54 PM" src="https://github.com/user-attachments/assets/21fc1ffa-51c0-4520-a522-a6da1b4418bf" />

<p>
After Logging in as Help Desk(John), observe and click on the ticket Karen submitted.	
</p>
<img width="952" height="374" alt="Screenshot 2026-02-18 at 2 11 13 AM" src="https://github.com/user-attachments/assets/29f1e2f1-2d23-4053-87c6-a0c1fe557fc7" />

<p>
After clicking into the ticket to observe it, It is clear that the Help Desk Technician(John) is unable to make changes to the ticket due to him having "Read Only" access. The only thing that John can do is create internal notes within the ticket for other agents, staff and backend people to observe/respond to. End users can't see the internal notes. Within the internal note section write: "John was here" as the title and "Testing as a user with "Read Only" access. Then, Click Post Note.
</p>
<img width="938" height="822" alt="Screenshot 2026-02-18 at 2 14 16 AM" src="https://github.com/user-attachments/assets/9140d966-77fa-4f05-a39e-57c5b8414f96" />
<p>

**Log Out of John's Account**
	
</p>
<img width="935" height="155" alt="Screenshot 2026-02-18 at 2 15 12 AM" src="https://github.com/user-attachments/assets/70d6fcbb-d8da-41d2-8d81-bc01ed912493" />

<p>
Use → <body> <a href="https://localhost/osTicket/scp/login.php">Admin/Analyst Login Page:</a> 	to Log In as a SysAdmin.
</p>


<img width="619" height="403" alt="Screenshot 2025-11-05 at 10 24 18 PM" src="https://github.com/user-attachments/assets/c85100ab-1b63-4094-8c2e-09c57d2ea206" />

<p>

**Click Admin Panel↓**
	
</p>

<p>
<img width="381" height="71" alt="Screenshot 2025-11-05 at 11 28 20 PM" src="https://github.com/user-attachments/assets/056b9792-3bf3-4123-a21a-27a65ebb6e8d" />
</p>

<p>

**Click Agents↓**
	
</p>

<img width="958" height="750" alt="Screenshot 2025-11-05 at 11 15 37 PM" src="https://github.com/user-attachments/assets/2e8dcbc5-0404-4897-992f-ca6b09f947e8" />

<p>

**Click on John Doe(Help Desk Tech/Agent)↓**
	
</p>
<img width="662" height="170" alt="Screenshot 2026-02-18 at 2 18 50 AM" src="https://github.com/user-attachments/assets/08c3283c-95f6-4b03-90ec-806f2628406d" />

<p>

**Within John's profile select "Access."↓**
	
</p>
<img width="654" height="247" alt="Screenshot 2026-02-18 at 2 19 47 AM" src="https://github.com/user-attachments/assets/5fc24cae-0018-476c-bbb4-a80f0b891a69" />

<p>

**Update John's role from "View Only" to "All Access" Then Save Changes.↓**
	
</p>
<img width="956" height="461" alt="Screenshot 2026-02-18 at 2 21 11 AM" src="https://github.com/user-attachments/assets/f4988df1-3ad4-420e-b086-b50eeb9f0e0a" />

<p>

**Logout of the SysAdmin Account.↓**
	
</p>
<img width="943" height="142" alt="Screenshot 2026-02-18 at 2 21 36 AM" src="https://github.com/user-attachments/assets/8bfb6914-b511-4617-a023-ded7cacbe2dd" />

<p>

**Stage 3 - Working the Issue**

	
</p>


<p>

Log back in as the Helpdesk Technician(John) → <body>
	<a href="https://localhost/osTicket/scp/login.php">Admin/Analyst Login Page:</a> </body> </html><br />

<p>
Username: john
</p>	
<p>
Password: Password1	
</p>



	
</p>




<img width="498" height="497" alt="Screenshot 2025-11-06 at 4 59 54 PM" src="https://github.com/user-attachments/assets/226a90d3-3d86-4a5b-847d-c2834983b8e2" />

<p>

**Click on the ticket Submitted by Karen.↓**
	
</p>
<img width="951" height="300" alt="Screenshot 2026-02-18 at 2 23 18 AM" src="https://github.com/user-attachments/assets/e723cae4-1038-4cc7-9879-84097ba6b943" />

<p>

After clicking into the ticket to observe it, The Help Desk Technician(John) is now able to make changes to the ticket after his role was switched from "View/Read Only" to "All Access." Now John is able to update things like Priority, SLA Plan, Help Topic Etc.
	
</p>
<img width="938" height="351" alt="Screenshot 2026-02-18 at 2 24 22 AM" src="https://github.com/user-attachments/assets/bb38fff2-ff62-4e4a-a962-1ed409a613e7" />

<p>
Change the priortity level from "Normal" to "Emergency" after calling end user(karen) to confirm that all teller systems are down.
<p>

**Click Update**
	
</p>	
</p>
<img width="642" height="245" alt="Screenshot 2026-02-18 at 2 27 45 AM" src="https://github.com/user-attachments/assets/1d6bd3fc-515d-47a4-88d2-f1f63722d30a" />

<p>
Change the SLA Plan from "Default SLA" to "Sev-A" Which means this ticket is Business Critical and needs to be responded to within 1-hour.

<p>

**Click Update**

</p>
	
<p>
Sev-A = 1-Hour Response Time	
</p>
<p>
Sev-B = 4-Hour Reponse Time	
</p>
<p>
Sev-C =	8-Hour Respone Time
</p>
</p>
<img width="646" height="245" alt="Screenshot 2026-02-18 at 2 30 23 AM" src="https://github.com/user-attachments/assets/6726a8a5-81fe-4304-9720-ac52fac89eb8" />

<p>
Change the Help Topic from "General Inquiry/Other" to "Business Critical Outage" because the entire banking system is offline.

<p>

**Click Update**
	
</p>
	
</p>


<img width="643" height="247" alt="Screenshot 2026-02-18 at 2 32 20 AM" src="https://github.com/user-attachments/assets/e551ef4d-e951-4c3a-88a4-d7cf3c5ca6dc" />

<p>

You can see the updates that were made to Priority, SLA Plan and Help Topic within the ticket history below as well as John escalating to the SysAdmin department after triaging the ticket.
	
</p>

<img width="934" height="701" alt="Screenshot 2026-02-18 at 2 34 26 AM" src="https://github.com/user-attachments/assets/7668ea62-d2e9-480a-b5b6-c04eaba49521" />

<p>

**Change the Assignee from John Doe to Jane Doe and Click Assign↓**
	
</p>
<img width="643" height="284" alt="Screenshot 2026-02-18 at 2 35 24 AM" src="https://github.com/user-attachments/assets/c8f99ceb-9d5d-4758-80c8-e00669092a8e" />

<p>

**Change the Department from Support to SysAdmins and Click Transfer↓** 

<p>
The Reason -  Support is for the helpdesk department and SysAdmin is for the individuals who are in charge of maintaining the systems like the Business Critical Systems
</p>


	
</p>
<img width="645" height="271" alt="Screenshot 2026-02-18 at 2 36 27 AM" src="https://github.com/user-attachments/assets/d6cdee4f-893a-4d84-984b-7fb7e6cd2777" />

<p>

Once the Department was transfered from "Support" to "SysAdmin" John's access was taken/denied because of how the permissions are setup.. Only System Administrators can access the ticket now.

<p>

**Log out as John↓**
	
</p>
	
</p>
<img width="953" height="388" alt="Screenshot 2026-02-18 at 2 36 58 AM" src="https://github.com/user-attachments/assets/cea40df6-98ac-4017-9e08-391626b10bf5" />


<p>

Log In as the SysAdmin(Jane) → <body>
	<a href="https://localhost/osTicket/scp/login.php">Admin/Analyst Login Page:</a> </body> </html><br />

<p>
Username: jane
</p>	
<p>
Password: Password1	
</p>

<p>

**Click Log In**
	
</p>

	
</p>


<img width="400" height="328" alt="Screenshot 2026-02-18 at 2 37 58 AM" src="https://github.com/user-attachments/assets/98835a4e-8ab5-4f8c-a73e-b96cbac8adb4" />


<p>

Jane observes and clicks on the ticket assigned to her for the first time.↓
	
</p>
<img width="951" height="365" alt="Screenshot 2026-02-18 at 2 38 34 AM" src="https://github.com/user-attachments/assets/17bd702d-6d1d-4e8d-944b-4bdcc5f5ca17" />

<p>

First, Jane reviewed the ticket history/internal notes to get an understanding of what happened before this ticket was assigned to her. Next, Jane explained in the internal notes "We accidentally restarted the online banking system backend server during business hours due to a configuration issue but will check the seetings and attempt to restart." 
<p>

**Post Reply**
	
</p>
	
</p>
<img width="940" height="486" alt="Screenshot 2026-04-09 at 2 06 45 PM" src="https://github.com/user-attachments/assets/2a1e134c-4bea-4318-9093-6441d17a9c43" />
<p>

<p>

**Stage 4 - Resolution**

	
</p>




Lastly, Jane restarted the server and after checking the online server it was back up and running. Confirmed with Karen.

<p>

**Post Reply**
	
</p>
	
</p>
<img width="938" height="130" alt="Screenshot 2026-04-09 at 2 07 04 PM" src="https://github.com/user-attachments/assets/71c5d5a4-3cbb-4c82-b26a-d8d86051f663" />

<p>
Jane closed out the ticket- Root cause analysis completed and issue confirmed to be resolved.	
</p>

<p>

**Click Close**
	
</p>
<img width="642" height="225" alt="Screenshot 2026-02-18 at 2 50 59 AM" src="https://github.com/user-attachments/assets/c1e4eaaf-dda2-44d4-9012-c1172b992b72" />

<p>

<h2>Another Example of Ticket Lifecycle Stages(4)</h2>


**Stage 1 - Intake**

Begin the Intake Stage by using → </head> <body>
<a href="https://localhost/osTicket">End Users osTicket URL:</a> to submit a ticket as Ken. Click "Open a New Ticket" to Begin
</p>
<img width="821" height="465" alt="Screenshot 2025-11-06 at 4 55 10 PM" src="https://github.com/user-attachments/assets/f44f1f98-aa77-4cd4-819a-a69b9c04309b" />

Next, After clicking "Open a New Ticket" fill in the Contact Information Form↓

Email Address: ken@lognpacific.com

Full Name: ken

Help Topic: Report a Problem / Personal Computer Issues

Issue Summary: "Adobe reader not working."

Under the Issue Summary, Give further detail in the allocated space. Then, submit the ticket by clicking "Create Ticket."

<img width="830" height="876" alt="Screenshot 2026-02-18 at 2 54 05 AM" src="https://github.com/user-attachments/assets/34c4150a-e408-4c71-923c-07dd267d0b8d" />
<p>
The support ticket request was successfully created and sent over to the Support Team.
</p>
<img width="837" height="377" alt="Screenshot 2026-02-18 at 2 54 17 AM" src="https://github.com/user-attachments/assets/0de914ad-899f-45e1-9304-0533e3c28a02" />
<p>
Stage 2 - Assignment and Communication

Begin the Assignment & Communication Stage by Logging in as the Helpdesk Technician(John) → Admin/Analyst Login Page:

Username: john

Password: Password1


Click Log In	
</p>
<img width="402" height="335" alt="Screenshot 2026-02-18 at 2 55 02 AM" src="https://github.com/user-attachments/assets/36f8b7c3-5da7-4699-a9bf-5f52b887ce2b" />
<p>

After Logging in as Help Desk(John), observe and click on the ticket Ken submitted.

	
</p>

<img width="954" height="372" alt="Screenshot 2026-02-18 at 2 55 29 AM" src="https://github.com/user-attachments/assets/48b5a6b6-13b1-40a1-9f54-61c034c42833" />
<p>

John clicked into the ticket and inspected it to get a sense for what was going on. Once John realized he didn't have enough information, he called Ken to get the severity of the issue. He didn’t want to guess what the SLA was. Ken stated that 10 out of 20 people were unable to open Adobe Reader. When they double-click the icon, it just hangs; nothing happens.

<p>

**Posted this as a note in the ticket↓**
	
</p>

	
</p>
<img width="938" height="377" alt="Screenshot 2026-02-18 at 2 59 14 AM" src="https://github.com/user-attachments/assets/20f3248b-deeb-4dc0-a18a-53cc35175059" />
<p>
 The priority level was changed from "Normal" to "High" because they need to use Adobe Reader to complete the audit.

<p>

**Click Update↓**
	
</p>

	
</p>
<img width="640" height="248" alt="Screenshot 2026-02-18 at 2 59 37 AM" src="https://github.com/user-attachments/assets/20ea8df8-bdd8-4e79-b86c-1651c4551a3d" />

<p>
Change the SLA Plan from "Default SLA" to "Sev-B" Because it involves another party and needs to be responded to within 4-hours.


Click Update↓

Sev-A = 1-Hour Response Time

Sev-B = 4-Hour Reponse Time

Sev-C = 8-Hour Respone Time
	
</p>
<img width="641" height="247" alt="Screenshot 2026-02-18 at 3 00 53 AM" src="https://github.com/user-attachments/assets/5e5a6fd2-b501-49be-a9b8-bef0da27c125" />

<p>

After speaking with Josh in the desktop department, John now has more clarity on what occurred with the Adobe Reader. Two solutions were presented. The first solution was to wait an hour for the new package to be deployed. Second, end users could manually install the new package from the software catalog.

	
</p>
<img width="938" height="475" alt="Screenshot 2026-02-18 at 3 08 10 AM" src="https://github.com/user-attachments/assets/e495f270-2436-491e-85e9-95d8191a9b3f" />

<p>
John closed out the ticket- Root cause analysis completed and issue confirmed to be resolved.


**Click Close↓**	

</p>


<img width="643" height="221" alt="Screenshot 2026-02-18 at 3 09 23 AM" src="https://github.com/user-attachments/assets/032db68b-c47b-43a0-ae47-cd61ac51d78c" />

<p>

**Log Out as John↓**
	
</p>
<img width="952" height="192" alt="Screenshot 2026-02-18 at 3 09 38 AM" src="https://github.com/user-attachments/assets/0f6677fa-c3d1-4163-9db8-eb26c1a3dab7" />








