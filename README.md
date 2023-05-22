<p align="center">
<img src="https://imgur.com/GtGHaCx.png alt="Traffic Examination"/>
</p>

<h2>osTicket Main Configuration<h2/>
In this tutorial I go through the steps to configure and setup osTicket after the osTicket installation that was demonstrated in https://github.com/AlfredoDGallardo/osTicket-Prereqs 
<br />
<br />

<h2>Technologies and Environments Used<h2/>

- PHP 
- osTicket (Help Desk Ticketing System)
<br />
<br />


<h2>Main Steps<h2/>

Step 1. Configure roles in the admin panel.
Go to:
- Admin Panel -> Agents -> Roles
- For testing purposes create the role: Supreme Admin and assign permissions

<p align="center">
<img src=https://i.ibb.co/hmNxm7r/1.jpg
</p>
<br />
<br />

1b.
<p align="center">
<img src=https://i.ibb.co/GJpQf80/2.jpg
</p>
<br />
<br />

1c.
<p align="center">
<img src=https://i.ibb.co/chdfR8B/3.jpg
</p>
<br />
<br />

1d.
<p align="center">
<img src=https://i.ibb.co/h2vnjYw/4.jpg
</p>
<br />
<br />

1e.
<p align="center">
<img src=https://i.ibb.co/0frB5qt/5.jpg
</p>
<br />
<br />

Step 2. Configure the Departments
- Admin Panel -> Agents -> Departments
- For testing purposes create the department: System Administrators  

<p align="center">
<img src=https://i.ibb.co/cQ4QMz2/6.jpg
</p>
<br />
<br />

2b. 
<p align="center">
<img src=https://i.ibb.co/vwWx44Z/7.jpg
</p>
<br />
<br />


Step 3. Configure Teams
- Admin Panel -> Agents -> Teams
- For the purposes of testing create two teams (Level I Support, Level II Support)

<p align="center">
<img src=https://i.ibb.co/tLHT2JJ/8.jpg
</p>
<br />
<br />

3b.
<p align="center">
<img src=https://i.ibb.co/khDzXtf/9.jpg
</p>
<br />
<br />

3c. Add a member to the team and Create Team
<p align="center">
<img src=https://i.ibb.co/tBzc7Y2/10.jpg
</p>
<br />
<br />



Step 4. Configure Agents (Workers who will work the tickets). Go to:
- Admin Panel -> Agents -> Add New
- (Whatever names you choose)          

<p align="center">
<img src=https://i.ibb.co/ssBzXQH/11.jpg
</p>
<br />
<br />

4b. Fill out agent information

<p align="center">
<img src=https://i.ibb.co/JQ3kT9b/12.jpg
</p>
<br />
<br />
                 
4c. Set the agent password

<p align="center">
<img src=https://i.ibb.co/HBT18Q5/13.jpg
</p>
<br />
<br />

4d. Set the department for the agent

<p align="center">
<img src=https://i.ibb.co/y6rjYYJ/14.jpg
</p>
<br />
<br />

4e. Set the permissions for the new agent 

<p align="center">
<img src=https://i.ibb.co/ZWhNKNR/15.jpg
</p>
<br />
<br />

4f. Set the team for the new agent 

<p align="center">
<img src=https://i.ibb.co/qMBSM9z/16.jpg
</p>
<br />
<br />

4g. New agent has been created

<p align="center">
<img src=https://i.ibb.co/2qr3vkX/17.jpg
</p>
<br />
<br />

Step 5. Go the the agent panel and create new user (Customers who can create a service ticket request). Go to:
- Agent Panel -> Users -> Add New
- For the purposes of testing create two users (whatever names you choose)

<p align="center">
<img src=https://i.ibb.co/Ydx2k2m/18.jpg
</p>
<br />
<br />

5b. Enter the details of the new user

<p align="center">
<img src=https://i.ibb.co/GkRDY6v/19.jpg
</p>
<br />
<br />


5c. New user has been created

<p align="center">
<img src=https://i.ibb.co/GRfTx1z/20.jpg
</p>
<br />
<br />


5d. Create second user using same previous steps

<p align="center">
<img src=https://i.ibb.co/NxKhBsQ/21.jpg
</p>
<br />
<br />


Step 7. Configure SLA (Service Level Agreements)
- Admin Panel -> Manage -> SLA
- For the purposes of testing configure three
 - Sev-A (1 hour, 24/7)
 - Sev-B (4 hours, 24/7)
 - Sev-C (8 hours, business hours)

<p align="center">
<img src=https://i.ibb.co/HN52N4x/22.jpg
</p>
<br />
<br />

7b. Give the plan a name and set the schedule

<p align="center">
<img src="https://i.ibb.co/XJqc4xg/23.jpg
</p>
<br />
<br />

7c. SLA Plans Created 

<p align="center">
<img src=https://i.ibb.co/p0W0qNh/24.jpg
</p>
<br />
<br />


Step 8. Configure Help Topics
- Admin Panel -> Manage -> Help Topics
- For the purposes of testing create four topics
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset

<p align="center">
<img src=https://i.ibb.co/9wL13zK/25.jpg
</p>
<br />
<br />

8b. Set the help topic details (Name, Status, Parent Topic)

<p align="center">
<img src=https://i.ibb.co/gzkgFT3/26.jpg
</p>
<br />
<br />

8d. Help Topics Have Been Created

<p align="center">
<img src=https://i.ibb.co/rsLtnYm/27.jpg
</p>
<br />
<br />
