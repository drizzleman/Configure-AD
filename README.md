<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1-Create Resource group and give it a name
- Step 2-Create Virtual Machine 1 and make it your Domain Controller
- Step 3- Create Virtual Machine 2 and make it your Client
- Step 4- Set the NIC private IP address of VM1 to static

<h2>Deployment and Configuration Steps</h2>

<p><img width="858" alt="image" src="https://github.com/drizzleman/Configure-AD/assets/166667455/183bf39f-8468-4657-909b-db58fc4fb610">

</p>
<p>
Download Active Directory on DC1 by selecting add roles and features and click domian services. When installation is finished click flag in right corner and promote this server to a domain controller and add a new forest name.
</p>
<br />

<p>
<img width="425" alt="image" src="https://github.com/drizzleman/Configure-AD/assets/166667455/0daffff5-7114-4f79-8676-c42299581104">

</p>
<p> When AD restarts you will login with the fully qualified domain name (FQDN) as shown in the photo above.
</p>
<br />

<p>
<img width="947" alt="image" src="https://github.com/drizzleman/Configure-AD/assets/166667455/77eda25a-18c7-4f0a-a4f4-4b1e32c5ee7f">


</p>

<p> When logged backed in to DC1 click tools and go to AD users and computers.Next you will right click mydomain.com click new and create two new organizational units.
</p>
<br />

<p>
<img width="950" alt="image" src="https://github.com/drizzleman/Configure-AD/assets/166667455/93fc64b8-ca55-4116-a164-073e5310245a">
>

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
