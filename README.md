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

4.) You'll need to install or enable IIS in Windows, making sure to include CGI and Common HTTP Features
![image](https://github.com/user-attachments/assets/9a67e5c4-c8b0-4ac4-98cb-2da2859fca4e)

5.) Within the VM (osticket-vm), download the osTicket-Installation-Files.zip and unzip it onto your desktop. The folder should be called “osTicket-Installation-Files”

6.) You will need to install PHP Manager Install
![image](https://github.com/user-attachments/assets/07a1cf4f-cb8e-4cd7-928f-a3f9aad6fbdc)

7.) Now you will need to install and Extract the Rewrite Module 2 Setup Wizard
![image](https://github.com/user-attachments/assets/1c6c3f10-f204-45f5-8c82-1f5f7ea757f0)

8.) Go to the osTicket-Installation-Files folder and run VC_redist.x86.exe to install it.
![image](https://github.com/user-attachments/assets/c209a261-0710-4fe3-a1d6-94ca6fd2d898)

9.) Open the osTicket-Installation-Files folder and run the MySQL 5.5.62 installer to set it up.
![image](https://github.com/user-attachments/assets/a1568a85-64bd-4198-8e72-6341a7b18542)

10.) Setup SQL Server configuration.
![image](https://github.com/user-attachments/assets/e2507ce5-8e8d-4572-a824-4b00f8a4f44d)

11.) Open IIS (Internet Information Services) as an Admin
![image](https://github.com/user-attachments/assets/549165a4-72cf-4b28-912c-a95e376b04af)

12.) Register PHP from within IIS (PHP Manager -> C:\PHP\php-cgi.exe)
![image](https://github.com/user-attachments/assets/cd99b35a-1679-4cb1-949a-e8ecfc8db453)
![image](https://github.com/user-attachments/assets/7b9704fa-60db-4307-a033-1ec19e2e070c)
![image](https://github.com/user-attachments/assets/228444f9-3565-4a94-b4a1-82490304dae2)

13.) Restart IIS by opening it up, then just stop and start the server.
![image](https://github.com/user-attachments/assets/ff15a1b5-df04-4bcd-9fd0-c689ebc45776)
![image](https://github.com/user-attachments/assets/365eda83-0ae8-40aa-a851-b0824832d5a6)

14.) Install osTicket v1.15.8
![image](https://github.com/user-attachments/assets/0c57238e-3a5b-48a6-86b0-d37283e35ef8)

15.) Change the name of "upload folder" to "osTicket"
![image](https://github.com/user-attachments/assets/0ccbfa71-d3bd-44ae-b186-06661c80b324)

16.) Browse osTicket
![image](https://github.com/user-attachments/assets/89f842b9-ec2d-4197-a05b-b593c2994a73)



















