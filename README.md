<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- Remote Desktop
- Internet Information Services (IIS)
- PHP Manager
- VC Redist
- MYSQL
- Heidi SQL
- osTicket v1.15.8
- Download Link: https://drive.usercontent.google.com/download?id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD&export=download&authuser=0

<h2>Installation Steps</h2>

1.) Start off  by creating a virtual machine in Microsoft Azure. Make sure to use Windows 10 Pro version 22H2 for the location you can use (US West). When selecting the VM make sure to choose one that has at least 2 vCPUs ang 16 gbs of memory.

![image](https://github.com/user-attachments/assets/b737b17a-a96c-4452-9ae6-f1432f4e5c1c)


2.) After setting up your virtual machine, you’ll need to connect to it using the public IP address it was assigned. Just open the Remote Desktop Connection app and you’re good to go.

3.) After connecting to your virtual machine, head over to the Control Panel. From there, open Programs and click on Turn Windows features on or off.
![image](https://github.com/user-attachments/assets/ea88f70f-0e33-4fbf-88e7-0b9076e9f7dc)

5.) You'll need to install or enable IIS in Windows, making sure to include CGI and Common HTTP Features
![image](https://github.com/user-attachments/assets/9a67e5c4-c8b0-4ac4-98cb-2da2859fca4e)

6.) You will need to install PHP Manager Install
![image](https://github.com/user-attachments/assets/07a1cf4f-cb8e-4cd7-928f-a3f9aad6fbdc)

7.) Now you will need to install the Rewrite Module 2 Setup Wizard
![image](https://github.com/user-attachments/assets/1c6c3f10-f204-45f5-8c82-1f5f7ea757f0)



