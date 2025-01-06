<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/watch?v=WRr7XhbUlJg)

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
In Step 1, I create a Windows 10 Virtual Machine in Microsoft Azure. Once I log into the VM, I search for the osTicket Installation Files and download the .zip file, then extract it.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Step 2, I install the PHP Manager from the installation files. Next I install the Rewrite Module and create the directory "C:\PHP".
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Step 3, the last step, I extract the PHP 7.3.8 folder into the C:\PHP folder. Finally, I install the VC_redistx86.exe file and MySQL 5.5.62 file as well and set the permissions to "Read" only.
</p>
<br />
