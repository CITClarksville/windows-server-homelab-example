# Windows Server Active Directory Home Lab

## Overview
This home lab was built using VMware Workstation Pro to simulate a small
enterprise Active Directory environment. The goal of this lab is to practice
installing, configuring, testing, and deploying Group Policies in a controlled
environment before pushing them into production.

## Lab Goals
- Install and configure Windows Server 2019
- Configure DNS and Active Directory Domain Services
- Join Windows 11 Pro to the domain
- Create and manage domain users
- Design, test, and deploy Group Policies

## Virtual Environment
| VM Name | OS | Purpose |
|------|----|--------|
| AD-HomeLab | Windows Server 2019 | Domain Controller, DNS |
| ADLABWS1 | Windows 11 Pro | Domain-joined client |
| WIN11-ENT | Windows 11 Enterprise | Future GPO testing |

## Tools & Technologies
- VMware Workstation Pro
- Windows Server 2019
- Windows 11 Pro / Enterprise
- Active Directory
- DNS
- Group Policy Management

## Current Progress
- ✅ VMware Workstation installed
- ✅ Windows Server 2019 VM created
- ✅ DNS configured
- ✅ Active Directory installed
- ✅ Windows 11 Pro joined to domain
- ✅ Domain users created
- ⏳ Group Policy testing in progress

## Screenshots
Screenshots documenting installation and configuration steps are included
in the `/screenshots` folder.

## Next Steps
- Create test Organizational Units (OUs)
- Develop test Group Policies
- Validate policies on Windows 11 Enterprise
- Deploy approved GPOs to production OUs
