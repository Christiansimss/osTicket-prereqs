<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>List of Prerequisites</h2>

- An Internet Connection 
- Debit/Credit Card (Free $200 Azure Credits)
- Microsoft Azure Account (Access portal)
- Azure services Resource Groups and Virtual Machines
- Remote Destop Connection to enter Virtual Machines

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/nN1GVPx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The purpose of this lab is to aquire the practical skills needed to work as an IT Help Desk Professional. This lab teaches you to create, interacte and close tickets. Here is the osTicket Lab Overview.
</p>
<br />

<p>
<img src="https://i.imgur.com/EcpQGbv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
These two Azure Services will serve as the foundation for the osTicket Lab.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First select resource group. The resource group should be empty and will have a button that says create resource group. Click the button and this page should appear. Next below subscriptions will say resource group, you are going to give the group a name. (example RG-LAB) and select Review + Create on the bottom left. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select Create when the resource group has been verified, then go to the Azure virtual Machine service. Select Create Virtual Machine which should bring you to the new prompt above. Select the resource group create (RG-LAB) and give the Virtual Machine a name (Example VM-osTicket). select your region and image select windows 10 Pro x64 (free services eligible). Further below there will be sizes, select Standard_D4s-V3-4 Cpus and create any username and password for the admin account (keep it simple and document it so you won't forget it will be needed later). Don't forget to check the licensing below as well and just like the last step select Review + Create and the Virtual Machine will be set. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After your Virtual Machine is created head back into the Virtual Machine services within Azure. From there select the created Virtual Machine and look for the Public Ip Address under networking. (download remote destop connection from the app store) and enter Public Ip address. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have entered the public ip address, there will be a prompt that appears to enter your credentials. These were the username and password we created earlier, enter them. After that open remote destop connection into the VM, from there open up a web browser and enter the link listed within your Virtual Machine <a href='https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6'>Link</a>
</p>
<br />
This ends the prereq's for the osTicket Lab. The next step for the lab are the configurations. <a href='https://github.com/Christiansimss/post-install-config'>OsTicket Installation.</a> </p>
