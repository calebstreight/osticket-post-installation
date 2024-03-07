<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Steps</h2>

- First login with the admin account you created. Next Admin panel > Agents > Roles > Add New Role. Name this role 'Supreme Admin' and enable all permissions on all three tabs, tickets, tasks, knowledgebase. Then click create. (Shown below)

 ![image](https://github.com/calebstreight/post-install-config/assets/162412951/30932eed-b0b9-49bc-bf46-e27e9b788ea0)
 ![image](https://github.com/calebstreight/post-install-config/assets/162412951/18d5cf4a-49bc-45d2-951c-1207566697a1)


- Next head over to add a new department. Admin panel > Agents > Departments > Add New departments. Name this department 'System Adminisrators'. Then click create. (Shown below)

![image](https://github.com/calebstreight/post-install-config/assets/162412951/3b66770a-de69-4fbe-8f55-686fbfcf5aea)
![image](https://github.com/calebstreight/post-install-config/assets/162412951/c2b153ee-5b1f-4f95-a3e6-d1412a5bf439)


- Next Head over to add a new team. Admin panel > Agents > Teams > Add New Team. Name this team 'Level II Support'. Then click create. (Shown below)

![image](https://github.com/calebstreight/post-install-config/assets/162412951/2cc62814-739d-4744-a03b-5f740fd119fd)
![image](https://github.com/calebstreight/post-install-config/assets/162412951/f84c6c54-5374-4dfd-96f1-a42cf757d938)


- Next we're gonna give everyone permissions to create a ticket. Admin panel > Settings > User Settings. Make sure registration and login required is unchecked. (Shown below)

 ![image](https://github.com/calebstreight/post-install-config/assets/162412951/54f4c9c1-450d-4ca4-b774-f4bd43be65fc)


- Next we're gonna create some agents (workers). Admin Panel > Agents > Add New. You can name them whatever you'd like. Set password and uncheck 'require new password on login' Assign one to 'System Administrator' department and one to 'Support' department. There will be three agents when finished. (Shown below)

![image](https://github.com/calebstreight/post-install-config/assets/162412951/9bfda319-2cb5-44c6-a1df-650f97232a96)
![image](https://github.com/calebstreight/post-install-config/assets/162412951/a39bbd9e-f11b-4143-b898-a1aa10b8a775)
![image](https://github.com/calebstreight/post-install-config/assets/162412951/6801ec11-456c-45b5-8e3d-fc498eae8224)
![image](https://github.com/calebstreight/post-install-config/assets/162412951/3bbfde2f-1279-4b16-8237-5e35dd9415ba)


- Next we're gonna create some users (customers). Agent panel > Users > Add New. You can name them whatever you'd like. There will be three users when finished (including osTicket support). (Shown below)

![image](https://github.com/calebstreight/post-install-config/assets/162412951/3ef26ecf-52c0-42ce-87d9-dc527a369889)
![image](https://github.com/calebstreight/post-install-config/assets/162412951/62b61764-0335-4e84-abad-cdc5f7a21602)


- Lastly we will create an SLA system to help organize tickets into correct severity. Admin panel > Manage > SLA > Add New SLA. We will create 3 SLA plans. SEV-A (1 hour grace period and 24/7 schedule) Next SEV-B (4 hour grace period and 24/7 schedule) lastly SEV-C (8 hour grace period buisness hours schedule) When finished you will have 4 SLA plans. (including 'default SLA' (Shown below)

![image](https://github.com/calebstreight/post-install-config/assets/162412951/2b40d59d-0324-4a14-95fb-f095b317d071)
![image](https://github.com/calebstreight/post-install-config/assets/162412951/771282f2-010f-4026-884f-a2c3ae8f2ee7)
![image](https://github.com/calebstreight/post-install-config/assets/162412951/404bf225-534d-413b-907e-4f0b76a9ef88)
![image](https://github.com/calebstreight/post-install-config/assets/162412951/2c977fde-e96f-40f1-b451-cb3508c14d1e)
