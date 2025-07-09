<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/watch?v=Kscty7Zg-Iw)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>List of Prerequisites</h2>

- Internet Information Services (IIS) with CGI enabled
- PHP Manager and PHP 7+ files
- MySQL Community Server (root/root default for lab)
- VC++ Redistributable (vcredist)
- HeidiSQL (to manage the database)

<h2>Installation Steps</h2>

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Download osTicket Installer"/>
</p>
<p>
<strong>Step 1: Download and Extract osTicket</strong><br />
Visit the GitHub link provided in the video and download the osTicket ZIP file. Extract it onto your desktop.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Enable IIS and CGI"/>
</p>
<p>
<strong>Step 2: Enable IIS and CGI in Windows</strong><br />
Go to Control Panel > Programs > Turn Windows features on or off. Enable "Internet Information Services" and under "Application Development Features," check "CGI".
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Install PHP Manager and Setup PHP Folder"/>
</p>
<p>
<strong>Step 3: Install PHP and Setup PHP Directory</strong><br />
Install PHP Manager. Then, create a new folder in C:\ named <code>PHP</code>. Extract the downloaded PHP files into this folder.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Install VC++ Redistributable"/>
</p>
<p>
<strong>Step 4: Install VC++ Redistributable</strong><br />
Run the <code>vcredist_x86.exe</code> installer and complete the installation. This ensures PHP dependencies function properly.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Install MySQL and Setup Root User"/>
</p>
<p>
<strong>Step 5: Install MySQL and Configure User</strong><br />
Install MySQL 5.7 (or 5.3 in the video). During setup, choose "Standard Configuration" and set both the username and password to <code>root</code> for lab simplicity.
</p>
<br />
