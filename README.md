<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Installation</h1>
<h3></h3>A walkthrough on how to install OS Ticket

<h2>Environments and Technologies Used</h2>

- Microsoft Azure Virtual Machine
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

 <h3> Prerequisites Installed</h3>

- Enable IIS
- CGI and Common HTTP features 
- IIS Management Console
- PHP Manager for IIS
- Rewrite Module
- PHP 7.3.8
- VC_redist.x86.exe
- MySQL 5.5.62


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Create a Resource Group and a virtual machine in Azure with Windows 10 and 4vCPUs
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Open IIS as an administrator and register PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3: Install OS Ticket by extracting and copying "upload" folder to c:\inetpub\wwwroot and reload IIS

</p>
<br />
