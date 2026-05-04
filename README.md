# home-IT-lab-active-directory

##Objective
To simulate a real-world IT infrastructure using Windows Server and client machines.

##What I will build
- Domain Controller
- User management system
- Network configuration
- Group policies

##Progress Log
Day 1: Repository created and environment setup started
- Installed Windows server 2019 on Virtualbox.
- Created virtual machine (DC-Server)
- Allocated 4GB RAM and 50GB Storage
- Successfully booted OS

Day 2: Configured core server settings
- Set static IP address (192.168.1.10)
- Renamed server to DC01
- Installed Active Directory Domain Services
- Added AD DS role via Server Manager
- Promoted server to Domain Controller
- Created new forest: piyushlab.local
- Configured domain environment

Day 3: Created Organizational structure
- Added OUs: HR, IT, Sales
- Created Users: Added multiple users across departments
- Implemented group-based access control
- Created Security Groups (HR_Group, IT_Group, Sales_Group)
- Assigned users to groups
- Configured shared resources
- Created shared folder (CompanyData)
- Applied role-based permissions
