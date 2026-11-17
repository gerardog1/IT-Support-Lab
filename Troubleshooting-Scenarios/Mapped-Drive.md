# Mapped Network Drive

## Overview

I mapped the `IT-Shared` network share to the `S:` drive on the workstation.

## Configuration

* **Drive:** `S:`
* **Network path:** `\\DC01\IT-Shared`
* **User:** `ITLAB\employee01`
* **Reconnect at sign-in:** Enabled

## Verification

After signing in as employee01, the `S:` drive was available in File Explorer and provided access to the `IT-Shared` network share.

The mapped drive provides the employee with a convenient way to access the shared network resources without manually entering the UNC path.
<img width="982" height="738" alt="mapped-drive" src="https://github.com/user-attachments/assets/b8b965d9-8afa-4ec3-bda3-cd17b5739551" />

