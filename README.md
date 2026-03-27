# Active Directory Homelab
 
This project shows a basic Active Directory setup created in a virtual lab using Windows Server.

## 🧩 Project Overview

The lab simulates a simple domain environment with:
- Domain Controller (DC01)
- Client machine (CLIENT01)
- Active Directory Domain Services (AD DS)
- DNS configuration
- User and Organizational Units (OU)
- Group Policy Object (GPO)

## ⚙️ What was configured

- Installed and promoted Windows Server to Domain Controller
- Configured static IP and DNS
- Joined client machine to domain
- Created domain user
- Created Organizational Units (OU)
- Applied Group Policy to restrict user access (Control Panel)
- Verified policy on client machine

## 🧠 Key Concepts

- **GPO (Group Policy Object)** – used to manage and enforce user/system settings
- **OU (Organizational Unit)** – used to organize users and apply policies
- **Domain Controller** – central authentication and management server
- **DNS** – resolves domain names to IP addresses

## 🖼️ Screenshots

### Environment setup
![VM Setup](screenshots/01_vm_setup.png)

### Domain Controller network configuration
![DC Network](screenshots/02_dc_network.png)

### Server Manager
![Server Manager](screenshots/03_server_manager.png)

### User created in Active Directory
![User Created](screenshots/04_user_created.png)

### Organizational Units (OU)
![OU IT](screenshots/05_ou_it.png)
![OU Clients](screenshots/06_ou_clients.png)

### Network configuration
![DC IP](screenshots/07_dc_ip_settings.png)
![Client DNS](screenshots/08_client_dns.png)

### Domain join
![Domain Join](screenshots/09_domain_join.png)

### User login
![User Login](screenshots/10_user_login.png)

### Group Policy configuration
![GPO Overview](screenshots/11_gpo_overview.png)
![GPO Created](screenshots/12_gpo_created.png)
![GPO Enabled](screenshots/13_gpo_enabled.png)

### Result (policy applied)
![Blocked](screenshots/14_result_blocked.png)

## ✅ Result

User access to Control Panel was successfully restricted using Group Policy, confirming correct GPO configuration and application.
