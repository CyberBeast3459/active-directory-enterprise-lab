# Active Directory Enterprise Lab

## Overview

This project demonstrates the deployment and configuration of a Windows Server 2025 Active Directory environment using VMware Workstation.

The lab includes:

- Active Directory Domain Services (AD DS)
- DNS Configuration
- Organizational Units (OUs)
- Security Groups
- User Account Management
- Domain Controller Promotion
- Domain Join Operations
- Windows 11 Client Integration

## Technologies Used

- Windows Server 2025
- Windows 11
- Active Directory Domain Services
- DNS
- VMware Workstation
- PowerShell
- Active Directory Users and Computers (ADUC)

## Environment

| System | Purpose |
|----------|----------|
| Windows Server 2025 | Domain Controller |
| Windows 11 | Domain Client |
| VMware Workstation | Virtualization Platform |

## Configuration Tasks

### Active Directory
- Installed AD DS role
- Promoted server to Domain Controller
- Created corp.local domain
- Configured DNS services

### Organizational Units
- IT
- HelpDesk
- Workstations
- Servers

### Security Groups
- IT_Admins
- HelpDesk
- Employees

### User Management
- Created domain user accounts
- Assigned users to security groups
- Verified authentication and permissions

### Domain Join
- Configured Windows 11 DNS settings
- Joined Windows 11 workstation to corp.local
- Verified successful authentication

## Validation

Domain authentication was verified successfully using:

```powershell
whoami
```

Output:

```text
corp\merickson
```

## Skills Demonstrated

- Active Directory Administration
- DNS Administration
- User & Group Management
- Windows Server Administration
- Domain Authentication
- VMware Virtualization
- IT Support Fundamentals
- Identity & Access Management (IAM)

## Screenshots

Screenshots documenting the build process are available in the screenshots directory.
