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

- Also 1
- Also 2
- Also 3
- Also 4
- Also 5

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/b2f0f6a6-8216-465f-b6ea-e540d2afdb02"/>

</p>
<p>
You must first start by creating a Microsoft Azure account as well as a resource group in Microsoft Azure. Once the resource group is created, you will create a Virtual Machine within the resource group and give it a name and all the proper specifications. You must select the proper region for the server, as well as Windows 10 Pro under the “Image” option. Ensure that the size of your server has at lease two vcpus and 8 Gib memory.  After that select a user name and password (please save this userername and password to a notecard for later use) for you virtual machine and click “Next” to complete the remaining prompts. Once you get to the “Networking” tab click “Review & Create”.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/542335d5-b100-48a7-a3da-484898dafd22"/>
</p>
<p>
Once the virtual machine is created in Microsoft Azure, you can go ahead and log into it through Remote Desktop. Go to the Windows Start search bar and type in Remote Desktop Connection. Once the app is open, back to to your virtual machine in Microsoft Azure and copy the Public IP Address. Past this address into the "Computer" window in the Remote Desktop Connection and complete the login with the username and password you created earlier for the virtual machine. Download and Install the osTicket installation file onto the virtual machine.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/c2fde4d7-3aa4-4d7f-882d-070ee817b920"/>
  

</p>
<p>
After the osTicket file is downloaded onto the virtual machine, it is important to activate the Internet Information Services (IIS) and also activate CGI as well. Begin by going to the Start menu and search for the Control Panel. Once the Control Panel is open navigate to "Programs" - "Turn Windows Features on or off" and select "Internet Information Services" to activate it. Once you have ISS activated, expand the menu to "World Wide Web Services" and underneath the "Application Development Features" select "CGI" to activate it. 
</p>
<br />
