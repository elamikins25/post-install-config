<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1 Access Admin Panel,Navigate to your osTicket admin panel by going to `http://yourdomain.com/support/scp`. Use the admin credentials you set during installation to log in.
- Item 2 Set Up Departments,**Navigate to Departments:** Go to the "Admin Panel" > "Manage" > "Departments." Create departments that align with your organization’s structure, e.g., Sales, Support, Billing.
- Item 3 In the admin panel, navigate to "Emails" > "Email Settings."  Set up email accounts for each department. This includes configuring mail fetching (POP/IMAP) settings to ensure tickets are created from incoming emails.
- Item 4 Go to "Admin Panel" > "Manage" > "Ticket Filters." Set up rules to automatically assign, prioritize, or route tickets based on criteria like keywords, department, or ticket source.
- Item 5 Go to "Admin Panel" > "Manage" > "Help Topics."  Define help topics that users can choose when submitting tickets, making it easier to categorize and manage requests.
