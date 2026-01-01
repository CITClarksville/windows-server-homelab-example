# Windows Server 2019 Virtual Machine Creation

## Purpose
This document outlines the process of creating a Windows Server 2019
virtual machine using VMware Workstation Pro. This VM will serve as the
Domain Controller for the Active Directory home lab.

---

## Lab Environment
- **Host OS:** Windows 10/11 (Personal Computer)
- **Hypervisor:** VMware Workstation Pro
- **Guest OS:** Windows Server 2019
- **VM Name:** DC01

---

## Virtual Machine Configuration

| Setting | Value |
|------|------|
| VM Name | DC01 |
| Guest OS | Windows Server 2019 |
| CPU | 2 vCPUs |
| Memory | 4 GB |
| Disk | 60 GB (Single file) |
| Network | NAT |

---

## Step 1: Create New Virtual Machine

In VMware Workstation Pro, a new virtual machine was created using the
**Typical (recommended)** configuration option.

![VM Creation Wizard](../screenshots/New Virtual Machine Step 1.png)

---

## Step 2: Select Guest OS Installation

Select the "I will install the operating system later" option as you 
will be able to do this at a later time.

![ISO Selection](../screenshots/New Virtual Machine Step 2.png)

---

## Step 3: Select Guest OS

Select Microsoft Windows and then select the version in the drop-down. 
You can see there are a lot of versions you can select from. 

![VM Hardware Settings](../screenshots/New Virtual Machine Step 3.png)

---

## Step 4: Name the Virtual Machine

I chose to keep it simple and just named the version of the OS. 
If you like, you can also select where you want to save it. For myself, I kept it the default.

![Server Installation](../screenshots/New Virtual Machine Step 4.png)

---

## Step 5: Specify Disk Capacity

This option depends entirely on your physical storage. 
Since I am just doing basic things with this server, I decided to keep it at the recommended 60GB. 

![Server Installed](../screenshots/New Virtual Machine Step 5.png)

---

## Step 6: Ready to create Virtual Machine, almost

Here you can verify your selections, even customize Hardware settings. 
But I usually do that after I select Finish since I still need to mount the ISO for the OS install.

![Server Installed](../screenshots/New Virtual Machine Step 6.png)

---

## Step 7: Sike! Windows requires TPM

You can either Generate a password or create your own. 
Just make sure to note it somewhere safe just in case!

![Server Installed](../screenshots/New Virtual Machine Step 7.png)

---
## Step 8: Time to make some hardware changes and mount the ISO

Select the "Edit virtual machince settings"

![Server Installed](../screenshots/New Virtual Machine Step 8.png)

and in the new window start with Memory, go ahead and increas this if you can. 
This can be the difference on how your machine runs. 
After that adjust the processors as well, if you can. Click OK to save the changes.

![Server Installed](../screenshots/New Virtual Machine Step 9.png)

Oops, you will have to get back into the virtual machine settings.
Now click on CD/DVD (SATA) and then selec the Use ISO image file and Browse to where you have your ISO file saved.

![Server Installed](../screenshots/New Virtual Machine Step 10.png)

Mine is in the Downloads directory. Once Selected click Open 

![Server Installed](../screenshots/New Virtual Machine Step 12.png)

---

## Step 9: Now the fun part, Install Server!

For this final step I recoreded my screen, make sure to pay attention to the very beginning. 
There was a certain setting that I was not aware of that blocked me from starting the installation.
Good Luck!

![Server Installed](../screenshots/ServerVM Installation important.mp4)

---

## Result
The Windows Server 2019 virtual machine was successfully created and is
ready for:
- DNS configuration
- Active Directory Domain Services installation
- Domain Controller promotion

---

## Next Step
Proceed to Active Directory installation and domain configuration.
