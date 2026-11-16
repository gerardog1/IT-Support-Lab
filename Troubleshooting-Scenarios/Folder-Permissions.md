# Department Folder Permissions Troubleshooting

## Problem

`employee01` could access the other department folders inside the `IT-Shared` network share.

The goal was to enforce least priviledge.

## Investigation

Upon review of NTFS permissions, it was discovered that the parent folder `IT-Shared` permissions were being inherited by chlid folders.

'Domain Users' group was in the parent folder permissions, allowing that group to access all other department folders by inheritance.

## Resolution

Made sure the `Domain Users` group on the parent folder only has "List Folder Contents" and nothing more.
Disabled Inheritance and removed `Domain Users` from the department folders.

## Verification

I logged into the workstation verified the following (I should only have access to general:

* `General` → Accessible and writable (good)
* `IT` → Access denied (good)
* `HR` → Access denied (good)

The department folders now restrict access based on the user's department security group.
