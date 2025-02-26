# osticket-prereqs
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

- Install Operating systems
- Install webserver
- Install PHP and Required Extensions
- Install MySQL
- Create a Database for osTicket
  
<h2>Installation Steps</h2>


<img width="1440" alt="Screen Shot 2025-02-26 at 12 17 22 PM" src="https://github.com/user-attachments/assets/7c8f4aac-0b5d-43fb-b9a1-285f547efa8c" />



Microsoft Azure portal displays a virtual machine (VM) named "labuser1" that is currently running on Windows 10 Pro. It is part of the VMTEST-LAB resource group, located in West US 3 (Zone 1) under Azure subscription 1. The VM is configured with a Standard D2s v3 instance (2 vCPUs, 8 GiB memory) and has a public IP address of 20.168.1.46 and a private IP address of 10.0.0.4, connected to the labuser1-vnet/default virtual network. The agent status is ready, running version 2.7.14191.1139, and hibernation is disabled. The interface provides various management options, including Start, Restart, Stop, Hibernate, Capture, Delete, and Refresh, along with monitoring and networking settings.





<img width="861" alt="Screen Shot 2025-02-26 at 5 03 51 PM" src="https://github.com/user-attachments/assets/3321fa2a-7f6e-4d2f-b4a9-bc3f896d4048" />



Windows PowerShell session running with administrator privileges, where a ping command is executed to test connectivity to the private IP address 10.0.0.4. The output confirms successful communication with the target, as all four packets were sent and received without any loss (0%), and the response time was minimal (0ms). This demonstrates a properly functioning network connection, likely within a local or virtualized environment.

