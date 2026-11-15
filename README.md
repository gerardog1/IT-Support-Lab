# IT Support Lab
In this lab, I set up a DC and Workstation and troubleshoot issues inside the environment.

## Summary
* Set up AD DS, DNS, & DHCP on the Domain Controller.
* Joined DC and Workstation to domain.
* Conected both to virtual switch in Hyper-V.
* Did some basic Troubleshooting.

## Troubleshooting Scenarios

### 1. No Internet Connectivity
Workstation pulled an APIPA address and could not access the internet. [Apipa-Dhcp.md]

### 2. User Unable to write files to Mapped Drive
User received an "Access Denied" error when trying to write to their mapped drive. [Mapped-Drive.md]

### 3. Unauthorized Access to Department Folders
Standard users were able to access all department folders. [Folder-Permissions.md]

### 4. Share VS. NTFS Permissions
Share permissions being more restrictive prevented needed access. [Share-NTFS-Permissions.md]
