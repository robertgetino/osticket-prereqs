<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Windows 10 Virtual Machine through Microsoft Azure
- Remote Desktop
- osTicket Installation Files
- PHP Manager
- Rewrite Module

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/robertgetino/osticket-prereqs/blob/52d63644a1df57bcf48a77f6b2d7743093210467/osticketvm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/robertgetino/osticket-prereqs/blob/b726f0d39834e8a196a736ed2a1d89d0a2fd617a/osticketfiles.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Above, I create a Windows 10 Virtual Machine in Microsoft Azure. Once I log into the VM, I then search for the osTicket Installation Files on osticket.com and download the files then extract them when necessary. I install PHP Manager, Rewrite Module, mySQL and Internet Information Services.
</p>
<br />

<p>
<img src="https://github.com/robertgetino/osticket-prereqs/blob/d0b85d5399ac3262b9f8d5c0a058b36f2c86d73b/PHP%20Manager.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <img src="https://github.com/robertgetino/osticket-prereqs/blob/2061ed7d53e010df9bb2da12b489b1c474d9dc83/PHP%20Manager%20exts.png" height="80%" width="80%"/>
<p>
<img src="https://github.com/robertgetino/osticket-prereqs/blob/4c83ad43ec3c6daf9f4039a0d9b6c9a08a38bc7c/osTicket%20Installation.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, I go back to the PHP Manager and register it with IIS as well as enable certain extensions within the PHP Manager. I then go to the browser to complete the setup of osTicket. In order to complete the installation, I go to Heidi SQL to create a username and password. After that, I enter the credentials in the installation of osTicket on the browser and it has now been completed.
</p>
