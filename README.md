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
In the Vindows VM, Open the Start Menu and go to Control Panel.

Navigate to Programs > Uninstall a program.

On the left panel, click Turn Windows Features ON or OFF.

Enable Internet Information Services (IIS).

Expand World Wide Web Services > Application Development Features.

Enable CGI.

Click OK and wait for the installation to complete."
</p>
<br />


<img width="482" alt="Screenshot 2024-06-26 at 12 29 27 PM" src="https://github.com/user-attachments/assets/e4556a4f-e7e6-4f67-8136-7fcb30273ef5" />

<p>
</p>
<p>
Download and install the IIS Rewrite Module.

Follow the prompts in the configuration wizard.

Click Install and wait for the process to finish.
</p>
<br />
<img width="480" alt="Screenshot 2024-06-26 at 12 42 13 PM" src="https://github.com/user-attachments/assets/7621dca8-07f9-4b60-b0bf-59e3af1d4634" /> <img width="480" alt="Screenshot 2024-06-26 at 12 42 29 PM" src="https://github.com/user-attachments/assets/a57b2301-fc33-4501-90fc-6fd2124a61be" /> <img width="500" alt="Screenshot 2024-06-26 at 12 43 53 PM" src="https://github.com/user-attachments/assets/c2a8dfaf-a16d-4d9d-bb92-09c0343434b5" /> <img width="500" alt="Screenshot 2024-06-26 at 12 44 02 PM" src="https://github.com/user-attachments/assets/6606c7ae-bc2e-4f78-b890-f6013860b700" />

Download MySQL from the official website.

Run the MySQL Configuration Wizard.

Follow the setup prompts.

Set the root password when prompted.

Complete the installation and configuration.
</p>
<p>

</p>
<br />
<img width="464" alt="Screenshot 2024-06-26 at 12 41 17 PM" src="https://github.com/user-attachments/assets/c69b4bf5-0dc4-429a-ab2f-af833345c462" />


Download and install the required Microsoft Visual C++ Redistributables.

Follow the configuration wizard.

Click Install and then Finish once the installation is complete.


<br />

<img width="1440" alt="Screenshot 2025-01-16 at 12 05 41 PM" src="https://github.com/user-attachments/assets/d571d5f1-f64e-407a-a2e2-3ad0d25a516c" />

Open IIS Manager.

Configure necessary settings and Permissions.

Ensure PHP Extensions are enabled.

Download the recommended version of Os-Ticket.

Follow the installation steps to complete the setup
