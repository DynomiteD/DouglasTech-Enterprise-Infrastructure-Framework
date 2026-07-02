# Enterprise Architecture

## Infrastructure Overview

The Active Directory environment consists of a centralized Windows Server 2022 Domain Controller providing authentication, authorization, DNS, directory services, and Group Policy management for Windows Enterprise workstations.

The environment was deployed within Oracle VirtualBox to simulate a production Windows enterprise network while allowing isolated testing, administration, troubleshooting, and validation.

---

## Infrastructure Components

### Domain Controller

- Hostname: DC01
- Operating System: Windows Server 2022
- Primary Role: Active Directory Domain Controller
- Services:
  - Active Directory Domain Services (AD DS)
  - DNS Server
  - Group Policy Management
  - Authentication Services

---

### Domain

- Domain Name: douglastech.local

---

### Client Workstation

- Operating System: Windows 11 Enterprise
- Joined to the Active Directory domain
- Used for authentication testing, Group Policy validation, and administrative verification.

---

## Directory Services

The Active Directory infrastructure includes:

- Organizational Units (OUs)
- Domain Users
- Security Groups
- Computer Objects
- Group Policy Objects (GPOs)

---

## Core Services

- Active Directory Domain Services
- DNS
- Authentication
- Authorization
- Group Policy
- Centralized User Management

---

## Administrative Tools

- Active Directory Users and Computers
- DNS Manager
- Group Policy Management Console
- Server Manager
- Command Prompt
- Windows PowerShell

---

## Validation

The deployment was validated using:

- dcdiag
- ping
- nslookup
- whoami
- gpresult
- Windows domain authentication
