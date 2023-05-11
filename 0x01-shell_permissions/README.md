0x01. Shell, permissions

This repository contains scripts that demonstrate various aspects of file permissions in shell scripting.
Scripts

Here is a list of scripts contained in this repository:

0-iam_betty


This script switches the current user to the user betty. The command used is exactly 8 characters long. The file is located at 0x01-shell_permissions/0-iam_betty.

1-who_am_i

This script prints the effective username of the current user. The file is located at 0x01-shell_permissions/1-who_am_i.

2-groups

This script prints all the groups the current user is part of. The output may vary depending on the user. The file is located at 0x01-shell_permissions/2-groups.

3-new_owner

This script changes the owner of the file hello to the user betty. The file is located at 0x01-shell_permissions/3-new_owner.

4-empty

This script creates an empty file called hello. The file is located at 0x01-shell_permissions/4-empty.

5-execute

This script adds execute permission to the owner of the file hello. The file is located at 0x01-shell_permissions/5-execute.

6-multiple_permissions

This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. The file is located at 0x01-shell_permissions/6-multiple_permissions.

7-everybody

This script adds execution permission to the owner, the group owner and the other users, to the file hello. The file is located at 0x01-shell_permissions/7-everybody. Note that commas are not used in this script.

Usage

To run any of the scripts, navigate to the directory containing the script and execute it. 

For example:

cd 0x01-shell_permissions
./0-iam_betty


