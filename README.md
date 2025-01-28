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

- Enable IIS
- Install Web Platform Installer 
- Install MYSQL and setup Username and Password
- Install C++ 
- Configure Permissions and Install Os-Ticket

<h2>Installation Steps</h2>

<img width="482" alt="Screenshot 2024-06-26 at 12 17 38 PM" src="https://github.com/user-attachments/assets/c8601367-5019-4164-bdc6-e5a111a977f8" /> <img width="482" alt="Screenshot 2024-06-26 at 12 18 27 PM" src="https://github.com/user-attachments/assets/28624afd-ff57-44d6-a8d4-dfe9ae17774b" />


<p>


</p>
<p>
Within the Windows 10 Virtual Machine Enable IIS by going to the Start Menu-> Control Panel-> Programs (Uninstall programs), On the Left hand side click on the hyperlink "Turn Windows Features ON or OFF"-> Enable IIS-> World Wide Web Services-> Application Development Features-> Enable "CGI"
</p>
<br />


<img width="482" alt="Screenshot 2024-06-26 at 12 29 27 PM" src="https://github.com/user-attachments/assets/e4556a4f-e7e6-4f67-8136-7fcb30273ef5" />

<p>
</p>
<p>
Install the ReWRite Module for IIS. Follow the prompts of the configuration wizard and at the end click "Install"
</p>
<br />
<img width="480" alt="Screenshot 2024-06-26 at 12 42 13 PM" src="https://github.com/user-attachments/assets/7621dca8-07f9-4b60-b0bf-59e3af1d4634" /> <img width="480" alt="Screenshot 2024-06-26 at 12 42 29 PM" src="https://github.com/user-attachments/assets/a57b2301-fc33-4501-90fc-6fd2124a61be" /> <img width="500" alt="Screenshot 2024-06-26 at 12 43 53 PM" src="https://github.com/user-attachments/assets/c2a8dfaf-a16d-4d9d-bb92-09c0343434b5" /> <img width="500" alt="Screenshot 2024-06-26 at 12 44 02 PM" src="https://github.com/user-attachments/assets/6606c7ae-bc2e-4f78-b890-f6013860b700" />

Download MYSQL and then launch the configuration Wizard. Follow the prompts as shown in the screenshots and setup the password for MYSQL "root"
</p>
<p>

</p>
<br />
<img width="464" alt="Screenshot 2024-06-26 at 12 41 17 PM" src="https://github.com/user-attachments/assets/c69b4bf5-0dc4-429a-ab2f-af833345c462" />


Install C++ and go through the configuration Wizard. At the end of the configuration Click "Install and Finish"


<br />

<img width="1440" alt="Screenshot 2025-01-16 at 12 05 41 PM" src="https://github.com/user-attachments/assets/d571d5f1-f64e-407a-a2e2-3ad0d25a516c" />

Configure settings and Permissions within IIS Manager including PHP Extensions. Once done Apply all changes and downlaod the recommeneded version of Os-Ticket. 
