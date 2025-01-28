# osTicket: Post-Installation Configuration

In this tutorial, we're going to configure Admin and Agent settings, panels, and more.

<h2>Prologue:</h2> 

So let's begin by starting up the Virtual Machine if you stopped it from the previous tutorial.

![image](https://github.com/user-attachments/assets/33f483c9-f11f-4aae-844c-625bbc852ac0)

Connect to the Remote Desktop and then login to osTicket as an Admin using the credentials made in the previous tutorial -> http://localhost/osTicket/scp/login.php

<h2>Step 1: Roles, Departments, and Teams</h2>

<h3>Configure Roles (for grouping permissions)</h3>

Please make sure that you follow the red rectangles in the screenshots to know where to properly click to avoid confusion and missing any vital steps to setting up all of the post-installations. 

![image](https://github.com/user-attachments/assets/9989aabe-18ee-4f7c-85c5-0784dbbc9b3c)

![image](https://github.com/user-attachments/assets/ff18270a-a55b-4ce5-8cb2-db8ee35f572b)

![image](https://github.com/user-attachments/assets/85dbd045-e8fa-43fa-872d-1615a41f2243)

![image](https://github.com/user-attachments/assets/787e894f-e5d5-40e7-9973-0fdbe9424c29)

We going to give the name of this new role as "Supreme Admin" and give it all permissions. Think of this role as the CEO of a madeup company.

![image](https://github.com/user-attachments/assets/ee713c05-83a9-441b-90e2-b2341a74db16)

Ensure that all boxes are checked for all three tabs.

![image](https://github.com/user-attachments/assets/c0098bce-b84e-4c98-ad6e-94cd527ce92a)


Click "Save Changes" and let's go to the next step.

<h3>Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)</h3>

Admin Panel -> Agents -> Departments

![image](https://github.com/user-attachments/assets/2b433e56-0e6f-4f61-952d-895e55282d9c)

![image](https://github.com/user-attachments/assets/9219447d-0def-43fc-aae6-63e16816de7c)


<br>


We're going to name the Department as "SysAdmin" and then scroll down to the bottom and click "Create Dept" to move on to the next step.

![image](https://github.com/user-attachments/assets/b6558f41-c9ba-4b11-9bf8-a57537e899bd)


<h3>Configure Teams</h3>


Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

![image](https://github.com/user-attachments/assets/54edb94e-f49f-46d8-98ec-e78700f7e985)

![image](https://github.com/user-attachments/assets/1be6ebf7-e292-432c-8347-28ef7453b0cb)

<br>


We're going to name the Teams as "Online Banking" and then "Create Team".

![image](https://github.com/user-attachments/assets/a77749b8-d75a-4109-9575-cbc76e735a11)

<h3>Step 2: End User Setup</h3>

We are going to create two agents, Jane Doe and John Doe

# Jane Doe

![image](https://github.com/user-attachments/assets/04ce4951-1ed7-4322-a835-b92a80be6f05)

![image](https://github.com/user-attachments/assets/3f38a8ee-121a-4435-a02d-f225c9708c9f)

![image](https://github.com/user-attachments/assets/cfd33bf5-3752-430f-b76f-9fc676c82c4e)

![image](https://github.com/user-attachments/assets/e5904852-e336-44be-8c87-48179cf0aa92)

![image](https://github.com/user-attachments/assets/24cb3ac3-7161-4113-a302-f47f36bbdc46)

![image](https://github.com/user-attachments/assets/2c0800ca-4567-40cd-996a-57c769d20710)



# John Doe

With John, we'll have him in the Support Department, a View Only role, and no assigned team. We then click "Create" afterwards

![image](https://github.com/user-attachments/assets/067fe281-950c-4432-a3dd-24cb8dfd2ea0)



