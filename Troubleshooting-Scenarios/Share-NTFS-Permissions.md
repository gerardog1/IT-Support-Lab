# Network Share Permissions Troubleshooting

## Problem

The workstation was able to open the `IT-Shared` network share, but was unable to create a file inside it.

## Investigation & Solution

Share permissions were `Read only` for `Everyone`. Since the most restrictive permissions win when NTFS vs. Share permissions, that was the root cause.

I changed the share permissions for Everyone to Full Control, while using NTFS permissions to control the specific access level.

## Root Cause

The user was able to access the network share but could not create files because the share permissions were more restrictive than the NTFS permissions.
