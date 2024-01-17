<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Installation</h1>
<h3></h3>A walkthrough on how to install osticket

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
Step 1: Open IIS as an administrator and register PHP from within IIS. Reload IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Install OS Ticket version v1.15.8 by extracting and copying "upload" folder to c:\inetpub\wwwroot and reload IIS

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3: Go to sites -> Default -> osTicket and click "Browse*:80". To enable extensions, go back to IIS sites -> Default -> osTicket, double click PHP Manager, and click "enable or disable an extension". 

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4: Assign permissions by going to ost.conifg.php, disable inheritance -> Remove All, and New Permissions -> Everyone -> All

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5: Click "Continue", name the helpdesk, and setup a default email that recieves customers' emails

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6: Install Heidi SQL by opening the file, create and connect to a new session, and create a database

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7: Go to database, enter username and password, and click "install now"

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8: To cleanup, delete C:\inetpub\wwwroot\osTicket\setup and set permissions to "read only"


</p>
<br />
