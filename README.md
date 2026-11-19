# IT Support Lab
In this lab, I set up a DC and Workstation and troubleshoot issues inside the environment.

## Summary
* Set up AD DS, DNS, & DHCP on the Domain Controller.
* Joined Windows Server and Workstation to domain.
* Conected both to virtual switch in Hyper-V.
* Did some basic Troubleshooting.

## Troubleshooting Scenarios

### 1. No Internet Connectivity Without DHCP

Workstation pulled an APIPA address and could not access the internet. [View Troubleshooting Steps](../Troubleshooting-Scenarios/Apipa-Dhcp.md)

### 2. User Unable to Write Files to Mapped Drive

User received an "Access Denied" error when trying to write to their mapped drive. [View Troubleshooting Steps](Mapped-Drive.md)

### 3. Unauthorized Access to Department Folders

The issue of standard users being able to access all department folders was addressed. [View Troubleshooting Steps](Folder-Permissions.md)

### 4. Share vs. NTFS Permissions

Share permissions being more restrictive than NTFS permissions prevented access. [View Troubleshooting Steps](Share-NTFS-Permissions.md)

## Environment setup
[See Screenshots Here](DC-Setup.md)
