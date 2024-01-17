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
Step 1: Open IIS as an administrator and register PHP from within IIS. Reload IIS.
<img width="587" alt="image" src="https://github.com/mdabro23/osticket-install-config/assets/148892244/984db0b0-802f-43e2-b57c-9f0fb0817193">
<img width="568" alt="Screenshot 2024-01-17 160540" src="https://github.com/mdabro23/osticket-install-config/assets/148892244/2bde8e17-0316-4fdf-b48d-272e1557bb0c">
</p>
<br />

<p>
Step 2: Install OS Ticket version v1.15.8 by extracting and copying "upload" folder to c:\inetpub\wwwroot and reload IIS

<p>
Step 3: Go to sites -> Default -> osTicket and click "Browse*:80". To enable extensions, go back to IIS sites, click "Default", click "osTicket", double click "PHP Manager", and click "enable or disable an extension". 

</p>
<img width="431" alt="Screenshot 2024-01-17 162022" src="https://github.com/mdabro23/osticket-install-config/assets/148892244/21a16cd6-1b5d-4e53-82f8-e0d58b936bfe">


</p>
<p>
Step 4: Assign permissions by going to ost.conifg.php, disable inheritance -> Remove All, and New Permissions -> Everyone -> All

<p>
<img width="329" alt="Screenshot 2024-01-17 162410" src="https://github.com/mdabro23/osticket-install-config/assets/148892244/9ca18cd6-efd0-4d60-92b3-3e2878c0571a">
<img width="394" alt="Screenshot 2024-01-17 162509" src="https://github.com/mdabro23/osticket-install-config/assets/148892244/a9cedb3b-76ad-4ae6-b8e1-6e586cd890e7">
</p>
<p>
Step 5: Click "Continue", name the helpdesk, and setup a default email that recieves customers' emails

</p>
<p>
Step 6: Install Heidi SQL by opening the file, create and connect to a new session, and create a database

</p>
<p>
Step 7: Go to database, enter username and password, and click "install now"

Step 8: To cleanup, delete C:\inetpub\wwwroot\osTicket\setup and set permissions to "read only"


</p>
<br />
