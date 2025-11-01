# osTicket: Post-Installation Configuration

In this tutorial, we're going to configure Admin and Agent settings, panels, and more.

<h2>Prologue:</h2> 

So let's begin by starting up the Virtual Machine if you stopped it from the previous tutorial.

![image](https://github.com/user-attachments/assets/33f483c9-f11f-4aae-844c-625bbc852ac0)

Connect to the Remote Desktop and then login to osTicket as an Admin using the credentials made in the previous tutorial <a href="http://localhost/osTicket/scp/login.php/"> here.

For future reference copy and paste these URLs inside of the VM.


Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 


End Users osTicket URL:
http://localhost/osTicket 



<h2>Step 1: Roles, Departments, and Teams</h2>

<h3>Configure Roles (for grouping permissions)</h3>

Please make sure that you follow the red rectangles in the screenshots to know where to properly click to avoid confusion and missing any vital steps to setting up all of the post-installations. To clear up some additional confusion, I'll explain the difference between the Admin and the Agent.

Admin - Setting up osTicket from the backend.

Agent - For help desk employees.


![image](https://github.com/user-attachments/assets/9989aabe-18ee-4f7c-85c5-0784dbbc9b3c)

![image](https://github.com/user-attachments/assets/ff18270a-a55b-4ce5-8cb2-db8ee35f572b)

![image](https://github.com/user-attachments/assets/85dbd045-e8fa-43fa-872d-1615a41f2243)

![image](https://github.com/user-attachments/assets/787e894f-e5d5-40e7-9973-0fdbe9424c29)

We going to give the name of this new role as "Supreme Admin" and give it all permissions. Think of this role as the CEO of a madeup company.

![image](https://github.com/user-attachments/assets/ee713c05-83a9-441b-90e2-b2341a74db16)

Ensure that all boxes are checked for the "Tickets" and "Tasks" tabs. Ignore the Knowledge base tab.

![image](https://github.com/user-attachments/assets/c0098bce-b84e-4c98-ad6e-94cd527ce92a)


Click "Save Changes" and let's go to the next step.

<h3>Configure Departments</h3>


Think of Departments as ticket visibility for certain employees within the IT field. 


Admin Panel -> Agents -> Departments

![image](https://github.com/user-attachments/assets/2b433e56-0e6f-4f61-952d-895e55282d9c)

![image](https://github.com/user-attachments/assets/9219447d-0def-43fc-aae6-63e16816de7c)


<br>


We're going to name the Department as "SysAdmin" and then scroll down to the bottom and click "Create Dept" to move on to the next step.

![image](https://github.com/user-attachments/assets/b6558f41-c9ba-4b11-9bf8-a57537e899bd)


<h3>Configure Teams</h3>

Teams can be best explains as a group of people created together from a different department.

Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

![image](https://github.com/user-attachments/assets/54edb94e-f49f-46d8-98ec-e78700f7e985)

![image](https://github.com/user-attachments/assets/1be6ebf7-e292-432c-8347-28ef7453b0cb)

<br>


We're going to name the Teams as "Online Banking" and then "Create Team".

![image](https://github.com/user-attachments/assets/a77749b8-d75a-4109-9575-cbc76e735a11)

<h3>Step 2: End User Setup</h3>

<h3>Agents</h3>

We are going to create two agents, Jane Doe and John Doe.

Agents are all employees within an organization, including those within IT and even executive roles.

<h4>Jane Doe</h4>

![image](https://github.com/user-attachments/assets/04ce4951-1ed7-4322-a835-b92a80be6f05)

![image](https://github.com/user-attachments/assets/3f38a8ee-121a-4435-a02d-f225c9708c9f)

![image](https://github.com/user-attachments/assets/cfd33bf5-3752-430f-b76f-9fc676c82c4e)


Make sure that these two checkboxes are UNCHECKED before clicking "Update".

<img width="808" height="492" alt="image" src="https://github.com/user-attachments/assets/9d964c61-88c2-4889-bf52-a5f461b5573a" />


<img width="1072" height="510" alt="image" src="https://github.com/user-attachments/assets/4c3f725e-96b5-4192-92b9-87d3c2a2cc14" />

![image](https://github.com/user-attachments/assets/2c0800ca-4567-40cd-996a-57c769d20710)



<h4>John Doe</h4>

With John, we'll use his first name, last name, email, and create a password like we did with Jane. The difference is we'll have John in the Support Department, a View Only role, and no assigned team. We'll then click "Create" afterwards.

![image](https://github.com/user-attachments/assets/067fe281-950c-4432-a3dd-24cb8dfd2ea0)


<h3>Users</h3>
Will be configuring Users under the Agent Panel this time. Users are the customers that are using an organization's service or product.

Agent Panel -> Users -> Add User

<h4>User Karen</h4>

![image](https://github.com/user-attachments/assets/830b71b1-58bc-4b32-8246-1cdaff32a3ba)

![image](https://github.com/user-attachments/assets/75389b9a-5d64-466f-b2ee-14b76a80f428)


Save Karen's credentials for later.

<h3>Service Level Agreement (SLA)</h3>

Let's go back into the Admin Panel to setup the SLAs. 

*Remember, an SLA is basically an agreement on how long the support team has to communicate with end users and resolve tickets depending on the severity of the issues at hand.

Admin Panel -> Manage -> "Add New SLA Plan"

We'll be creating three individual plans here. Follow along using the screenshots shown below.

1. Sev-A (Grace Period: 1 hour, Schedule: 24/7) - High Priority


2. Sev-B (Grace Period: 4 hours, Schedule: 24/7) - Middle Priority


3. Sev-C (Grace Period: 8 hours, Monday - Friday 8am - 5pm) - Low Priority



![image](https://github.com/user-attachments/assets/73bfab97-5b2f-4d81-901b-6ebe834d6578)

![image](https://github.com/user-attachments/assets/ca9264ec-b3d8-4e42-83d1-8a7153742c5f)

![image](https://github.com/user-attachments/assets/79202765-a9c2-4ef9-88f4-31138239931f)

![image](https://github.com/user-attachments/assets/8e3f2c3c-6e2e-4000-b48d-c682c9330526)

![image](https://github.com/user-attachments/assets/2692137b-31f0-4b42-943f-b979000eeb1d)


<h3>Creating Help Topics</h3>

Help Topics are used when an end user or employee needs to submit a ticket with the best category of an issue they're having.

Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics -> "Add New Help Topic"

![image](https://github.com/user-attachments/assets/09a075e1-2e38-4c52-9a7d-4cd8502b4593)

![image](https://github.com/user-attachments/assets/a0cc30cc-f897-424d-abe6-f5e50d510ef4)

Repeat the steps above for the following Topics:

*Personal Computer Issues / Report a Problem

*Equipment Request / General Inquiry

*Password Reset / Report a Problem

*Other / General Inquiry

This covers the installation needed to get started working on osTicket. To recap this section we learned the differences between Admin and Agent Panels, and we configured Roles, Departments, Teams, Agents, Users, Service Level Agreements, and Help Topics.

In the next Tutorial, we'll be tackling a mockup ticket. When you're ready, click <a href="https://github.com/khalil-poole/osTicket-Creating-Working-and-Completing/">here</a>.


As a quick reminder, if you need to take a break or come back at a later time, this is how you can stop the VM. 

![image](https://github.com/user-attachments/assets/92abfa3a-0dc5-4284-8fde-ab364f9f546d)

