<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - post install configuration </h1>
This overview outlines the post install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post Install Steps</h2>

- Configure Roles
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
                                                CONFIGURE ROLES

   ![image](https://github.com/user-attachments/assets/7a4db633-a49f-48a4-bcdd-e35c01eccc77)
![IMG_9807](https://github.com/user-attachments/assets/f73c1a1b-482a-4481-b0b1-a0403c57734f)
![IMG_9808](https://github.com/user-attachments/assets/0a40f6a4-e4eb-4d78-b216-ef8aa28675e9)
![IMG_9809](https://github.com/user-attachments/assets/36ecf619-3b47-45e2-b6c8-9d207fa93daf)


Access the admin panel and navigate to agents, select roles and create new role: Supreme Admin.  
</p>
<p>

</p>
<br />

<p>

                                           CONFIGURE AGENTS
![IMG_9810](https://github.com/user-attachments/assets/4478b42e-5795-43c8-a2e0-60114f05333b)
![IMG_9811](https://github.com/user-attachments/assets/295014f5-4473-44dc-a25b-ee2bbbb4777b)

Access aadmin panel, agents, add new.
                                         
                                           CONFIGURE USERS

 ![IMG_9820](https://github.com/user-attachments/assets/8557ff18-0ccb-46c9-b76e-49ec12b3fd32)
![IMG_9821](https://github.com/user-attachments/assets/901d7ef1-6505-41f0-b726-d1f6f9d93ca3)

 Access admin panel, users, and add new user.                                       


</p>
<p>

                                                 CONFIGURE SLA

 ![IMG_9822](https://github.com/user-attachments/assets/146eb3e0-c22e-49cc-aaa5-9d64392d3ae4)

 Access Admin panel, manage, SLA                                        
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)

</p>
<br />

<p>

                                            CONFIGURE HELP TOPICS
![IMG_9823](https://github.com/user-attachments/assets/6121d187-570d-4186-9f39-9d5a8189fb5b)


Access admin panel, manage, help topics

Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other

</p>
<br />
