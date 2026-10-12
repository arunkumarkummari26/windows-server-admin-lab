# Windows Server Administration Lab

## 📌 Project Overview

This project demonstrates my hands-on experience configuring, managing, and troubleshooting a Windows Server environment in a personal virtual lab. It covers core Windows infrastructure services, Active Directory administration, DNS configuration, Group Policy, file sharing, and PowerShell administration.

Configuration steps, verification procedures, and screenshots are documented to demonstrate practical system administration skills.

## 🎯 Objectives

- Install and configure Windows Server.
- Implement Active Directory Domain Services (AD DS).
- Configure DNS zones and resource records.
- Manage Active Directory users, groups, and Organizational Units.
- Configure and test Group Policy Objects (GPOs).
- Join Windows client machines to a domain.
- Configure file sharing and NTFS permissions inheritance.
- Perform administrative tasks using PowerShell.
- Document troubleshooting procedures and verification results.

## 🖥️ Lab Environment

| Component | Details |
|---|---|
| Server OS | Windows Server [Version] |
| Client OS | Windows 10/11 |
| Environment | Personal Virtual Lab |
| Virtualization | [Hyper-V / VMware / VirtualBox] |
| Administration Tools | Server Manager, ADUC, DNS Manager, GPMC, PowerShell |

## ⚙️ Tasks and Implementation

### 1. Windows Server Installation and Configuration
- [ ] Install Windows Server.
- [ ] Configure hostname and static IP address.
- [ ] Configure network settings and system updates.
- [ ] Verify network connectivity.

### 2. Active Directory Domain Services (AD DS)
- [ ] Install the AD DS role.
- [ ] Promote the server to a domain controller.
- [ ] Configure the Active Directory domain.
- [ ] Verify domain controller functionality.

### 3. DNS Configuration
- [ ] Configure forward lookup zones.
- [ ] Configure reverse lookup zones.
- [ ] Create and verify Host (A/AAAA) records.
- [ ] Create and verify Pointer (PTR) records.
- [ ] Configure Mail Exchanger (MX) records and supporting DNS records, where applicable.
- [ ] Test DNS resolution using `nslookup` and PowerShell.

### 4. Active Directory Users, Groups, and OUs
- [ ] Create and organize Organizational Units (OUs).
- [ ] Create and manage domain user accounts.
- [ ] Create security groups and assign group membership.
- [ ] Verify user and group configurations.

### 5. Group Policy Management
- [ ] Create and configure Group Policy Objects (GPOs).
- [ ] Link GPOs to the appropriate domain or OUs.
- [ ] Implement and test policy settings.
- [ ] Verify policy application using `gpupdate` and `gpresult`.

### 6. Windows Client Domain Join
- [ ] Configure the client to use the domain DNS server.
- [ ] Join the Windows client to the Active Directory domain.
- [ ] Test domain user authentication.
- [ ] Verify domain connectivity and Group Policy application.

### 7. File Sharing and NTFS Permissions
- [ ] Create and configure shared folders.
- [ ] Configure share permissions.
- [ ] Assign NTFS permissions to users and groups.
- [ ] Configure and verify NTFS permission inheritance.
- [ ] Test access using different user accounts.

### 8. PowerShell Administration
- [ ] Inspect system configuration and Windows services.
- [ ] Verify IP configuration and network connectivity.
- [ ] Query DNS records and test name resolution.
- [ ] Perform selected Active Directory administration tasks.
      
## 📸 Screenshots and Evidence

Screenshots will be added to document completed configurations and successful verification.


## 🔍 Troubleshooting and Verification

The following commands can be used to verify the lab configuration.

**Check IP configuration**
```powershell
ipconfig /all
```

**Test network connectivity**
```powershell
ping <server-ip>
```

**Verify DNS resolution**
```powershell
nslookup <domain-name>
```

**Verify applied Group Policy**
```powershell
gpresult /r
```

**Check Windows service status**
```powershell
Get-Service
```

Issues, root causes, corrective actions, and verification results will be documented as the lab progresses.
```

## 📚 Skills Demonstrated

- Windows Server Administration
- Active Directory Domain Services (AD DS)
- DNS Configuration and Troubleshooting
- User and Group Management
- Group Policy Management
- Windows Domain Join and Authentication
- File Sharing and NTFS Permissions
- PowerShell Administration
- Technical Documentation and Troubleshooting

## ✅ Project Outcome

This lab demonstrates practical Windows Server administration concepts through hands-on configuration, testing, and technical documentation. It serves as a record of my learning and development in Windows infrastructure administration.

**Project Status:** **Completed**
