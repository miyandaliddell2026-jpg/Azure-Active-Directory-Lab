# Azure Active Directory Home Lab

## Project Overview
This project demonstrates the deployment and configuration of an Active Directory Domain Services (AD DS) environment in Microsoft Azure. The lab includes creating a Windows Server virtual machine, promoting the server to a Domain Controller, creating Organizational Units (OUs), managing users, and implementing Group Policy security settings.

This lab was built to strengthen hands-on skills in:
- Active Directory Administration
- Group Policy Management
- Windows Server Administration
- Azure Virtual Machines
- User and Organizational Unit Management
- Security Policy Configuration

---

# Lab Environment

| Component | Details |
|---|---|
| Cloud Platform | Microsoft Azure |
| Operating System | Windows Server 2025 Datacenter |
| Domain Name | lab.local |
| Tools Used | Active Directory Users and Computers, Group Policy Management |
| VM Name | testVM |

---

# Step 1 - Create Azure Virtual Machine

A Windows Server 2025 virtual machine was created in Microsoft Azure to host the Active Directory environment.

![Step 1](Step1.png.png)

---

# Step 2 - Connect to the Virtual Machine

Remote Desktop Protocol (RDP) was used to securely connect to the Windows Server virtual machine.

![Step 2](Step2.png.png)

---

# Step 3 - Open Server Manager

After connecting to the server, Server Manager was used to begin configuring Active Directory services.

![Step 3](Step3.png.png)

---

# Step 4 - Install Active Directory Domain Services (AD DS)

The Active Directory Domain Services role was selected and installed through the Add Roles and Features Wizard.

![Step 4](Step4.png.png)

---

# Step 5 - Confirm Installation Settings

The AD DS installation settings and required management tools were confirmed before deployment.

![Step 5](Step5.png.png)

---
# Step 6 - AD DS Installation Progress

The installation process completed successfully and installed the required Active Directory services and management tools.

![Step 6](Step6.png.png)

---

# Step 7 - Promote Server to Domain Controller

The server was promoted to a Domain Controller using the Active Directory Domain Services Configuration Wizard.

![Step 7](Step7.png.png)

---

# Step 8 - Configure New Forest

A new Active Directory forest named lab.local was created.

![Step 8](Step8.png.png)

---

# Step 9 - Verify AD DS Deployment

The AD DS role and services were successfully installed and visible in Server Manager.

![Step 9](Step9.png.png)

---

# Step 10 - Open Active Directory Administrative Tools

Administrative tools such as Active Directory Users and Computers were launched to begin managing the domain environment.

![Step 10](Step10.png.png)

---

# Step 11 - Create Organizational Units (OUs)

Organizational Units were created to organize users and systems by department.

Examples:
- HR
- Finance
- IT
- Sales
- Workstations

![Step 11](Step11.png.png)

---

# Step 12 - Verify Organizational Units

The Organizational Units were successfully created and displayed within Active Directory Users and Computers.

![Step 12](Step13.png.png)

---
