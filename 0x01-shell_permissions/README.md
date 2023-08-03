# Shell Permissions Scripts

This repository contains shell scripts that demonstrate various permission-related tasks in Linux. Each script is named accordingly and performs a specific action related to file and directory permissions.

## Scripts List

1. 0-iam_betty:
   - Switches the current user to the user 'betty'.

2. 1-who_am_i:
   - Prints the effective username of the current user.

3. 2-groups:
   - Prints all the groups the current user is part of.

4. 3-new_owner:
   - Changes the owner of the file 'hello' to the user 'betty'.

5. 4-empty:
   - Creates an empty file called 'hello'.

6. 5-execute:
   - Adds execute permission to the owner of the file 'hello'.

7. 6-multiple_permissions:
   - Adds execute permission to the owner and group owner, and read permission to other users, to the file 'hello'.

8. 7-everybody:
   - Adds execution permission to the owner, group owner, and other users, to the file 'hello'.

9. 8-James_Bond:
   - Sets the permission of the file 'hello' as follows: Owner: no permission, Group: no permission, Other users: all permissions.

10. 9-John_Doe:
    - Sets the mode of the file 'hello' to '-rwxr-x-wx'.

11. 10-mirror_permissions:
    - Sets the mode of the file 'hello' the same as the mode of the file 'olleh'.

12. 11-directories_permissions:
    - Adds execute permission to all subdirectories of the current directory for the owner, group owner, and all other users. Regular files are not changed.

13. 12-directory_permissions:
    - Creates a directory called 'my_dir' with permissions '751' in the working directory.

14. 13-change_group:
    - Changes the group owner of the file 'hello' to 'school'
