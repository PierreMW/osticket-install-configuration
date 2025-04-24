<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Internet Information Services (IIS)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
  
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>


![image](https://github.com/user-attachments/assets/27b13131-83e4-483a-9a13-1bafbdb81e93)

Since we have sucessfully installed osTicket and making sure it is running correctly. We will then make sure that the roles and tasks are given to the correct users through the administrator role. You will be able to manage.

![image](https://github.com/user-attachments/assets/3fa17a02-3e26-4361-afbd-c217a768391c)

To set up a new role in the help desk, go to the administrator panel, then click on agents and choose roles. Click add new role and type in the name, supreme admin. This lets you choose what the role can and cannot do. Since you're creating a supreme administration role, make sure to give it all the permissions so it has full access to everything.

![image](https://github.com/user-attachments/assets/881afdd4-0da6-442e-a5a4-375674419a63)

You should then see an option for supreme administration. 

![image](https://github.com/user-attachments/assets/dc35e0e7-5cfa-45a2-866a-bcfdb3ddefa7)

Click on the departments button under the agents tab. Here, you can create a new department and assign agents to it based on their roles. Make a department called system administration for the supreme admins. 

![image](https://github.com/user-attachments/assets/9984f7eb-cb3c-4a25-882f-ba31515a2baf)

Next we're going to configure teams. This will allow you to put multiple agents to collaborate in one area. Create the team under online banking.

![image](https://github.com/user-attachments/assets/e0dffea4-500f-4578-b034-2fedb009b541)

Next is to configure agents. Stay in the admin panel, then agents and add new. You will want to fill out the following sections with the specific details of the agent. Rememeber the password you set for each agent created.

![image](https://github.com/user-attachments/assets/9066c1da-e74e-47ac-ad7c-e2009845924d)


![image](https://github.com/user-attachments/assets/bd8790e8-d291-468d-8968-eeef5a761b4b)

Next we are going to set up our users, also known as our customers. To do so go to the agent panel then users and add new. This will let the customers send in and manage support tickets.

![image](https://github.com/user-attachments/assets/5123941f-bfca-4763-958d-5a5a461579e5)

Further more configuring SLA's. Configuring SLA's in osTicket is important. It helps keep support efficient and reliable. As well as determining the time of when an agent will receive a ticket. You want to make sure you set the correct grace periods, business hours and schedules. 

![image](https://github.com/user-attachments/assets/53e5487f-ea91-4145-a5da-3d70bce555ed)

Lastly we're going to configure help topics. This will help end users categorize the tickets when creating them.


