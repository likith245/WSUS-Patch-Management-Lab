# WSUS-Patch-Management-Lab
Designed and implemented an enterprise-style WSUS patch management lab using Windows Server 2025, Active Directory, DNS, and Group Policy. Configured centralized update deployment, client targeting, compliance reporting, and patch validation across Windows Server and Windows 11 systems.

Objectives:

Deploy and configure Windows Server Update Services (WSUS)
Configure Active Directory and Group Policy for update management
Create computer groups for phased deployment
Synchronize updates from Microsoft Update
Approve and deploy updates to managed devices
Monitor update compliance and reporting
Verify successful patch installation on client systems

Lab Environment:

DC01--Active Directory Domain Controller & DNS
WSUS01--Windows Server Update Services
WIN10-CLIENT01	Windows 11 Client

Technologies Used:
Windows Server 2025
Active Directory Domain Services
DNS
Windows Server Update Services (WSUS)
Group Policy Management
Windows 11 Pro
PowerShell
VMware Workstation

This project demonstrates the implementation of a centralized Windows patch management solution using Windows Server Update Services (WSUS), Active Directory Domain Services, DNS, and Group Policy. The lab was designed to simulate an enterprise environment where updates are managed, approved, deployed, and monitored from a central WSUS server.

The environment consists of a Domain Controller, a WSUS server, a Windows Server client, and a Windows 10 endpoint. Group Policy was configured to direct domain-joined systems to the internal WSUS server for update management. Computer groups were created to support staged deployments, allowing updates to be tested before production rollout.

The project includes WSUS installation and configuration, update synchronization, computer targeting, policy deployment, update approval workflows, compliance reporting, and PowerShell-based validation of installed updates. Successful communication between clients and WSUS was verified through reporting, status monitoring, and patch installation results.

This lab demonstrates practical skills in Windows Server administration, Active Directory, Group Policy, WSUS administration, patch management, troubleshooting, compliance monitoring, and endpoint management, reflecting real-world tasks performed by System Administrators and IT Support Engineers.

