<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machine)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Add Roles
- Add Departments
- Add Teams
- Add Agents
- Add Users
- Add SLAs
- Add Help Topics

<h2>Configuration Steps</h2>


<p>
1. Once osTicket has been installed you can begin to set it up depending on your organization's requirements. Firstly you can define specific roles for agents based on their responsibilities. Different roles can be given different permissions to control access to certain features, such as viewing tickets, creating reports, or managing system settings. Ensure that roles you create align with your organization's workflow and security policies to prevent unauthorized access.

To create a new role, open the Admin panel and enter the Agents Menu. Click on Roles and create the new role from there.

</p>
<br />

<p>
<img width="500" alt="Screen Shot 2025-01-04 at 6 53 59 PM" src="https://github.com/user-attachments/assets/57cb5eea-be41-4d64-894a-3256fd774e8d" />
</p>


<p>
2. Now departments can be added that reflect the structure of your organization. Tickets can then be assigned to the appropriate department for streamlined management and quicker resolution. 

In the Admin panel, open the Agents menu and click on Departments to create a new Department within osTicket.

</p>
<br />

<p>
<img width="500" alt="Screen Shot 2025-01-04 at 6 57 20 PM" src="https://github.com/user-attachments/assets/bfffc16d-50aa-4bce-8eeb-660d9c69e126" />
</p>


<p>
3. Afterward, teams can be formed, consisting of agents from within or across departments to handle specific types of tickets. Tickets can then be assigned to teams for collaborative problem-solving and specialized handling.

 To create a new Team, enter the Admin panel and open the Agents menu. Click on Teams and add any new teams that need to be created.

</p>
<br />

<p>
<img width="500" alt="Screen Shot 2025-01-04 at 6 59 08 PM" src="https://github.com/user-attachments/assets/ec36d323-9a52-4d02-b7a7-b820f47393a0" />
</p>

<p>
4. Next, Add agents to the system who will be responsible for managing and resolving tickets. They can be assigned to specific roles, departments, or teams to match their expertise and responsibilities. Contact information, working hours, and notification preferences can be set to facilitate communication and ticket assignment.


 To create new agents, enter the Admin panel and open the Agents menu. Click on Add New Agent and create the account credentials for each new agent.
 
</p>
<br />

<p>
<img width="500" alt="Screen Shot 2025-01-04 at 7 04 11 PM" src="https://github.com/user-attachments/assets/2e46fbbe-3bb3-4430-a1fb-9c0244729ecd" />
</p>

<p>
5. Add end-users who will be submitting tickets, their profiles can be set up to store contact details and maintain a history of past interactions for personalized support.
  
To create new users, enter the Agents panel and open the Users menu. Click on Add User and create the account credentials necessary for each new user.

</p>
<br />

<p>
<img width="500" alt="Screen Shot 2025-01-04 at 7 09 19 PM" src="https://github.com/user-attachments/assets/c3cd50fe-1842-4e53-9924-e890a7d6726a" />
</p>

<p>
6. SLAs can be defined to set expectations for response and resolution times based on the priority of the issue. Configure multiple SLAs to handle different scenarios, such as citical issues requiring a 1 hour response and low priority issues allowing an 8 hour resolution window. 

To make new SLAs, enter the Admin panel and open the Manage menu. Click on SLA and create any needed SLAs.

</p>
<br />

<p>
<img width="500" alt="Screen Shot 2025-01-04 at 6 59 08 PM" src="https://github.com/user-attachments/assets/ec36d323-9a52-4d02-b7a7-b820f47393a0" />
</p>

<p>
7. Finally, predefined help topics can be created to categorize the types of issues or requests users can select when submitting tickets, such as "Password Reset" 

To make a new Help Topic, enter the Admin panel and open the Manage menu. Click on Help Topics and click on Add New Help Topic.

</p>
<br />

<p>
<img width="500" alt="Screen Shot 2025-01-04 at 7 24 58 PM" src="https://github.com/user-attachments/assets/106881ae-bab0-4ed3-a9d9-df1d2a438195" />
</p>
