# Permissions - Shell Scripts

> **Folder**: `permissions/`
>
> This folder contains Bash scripts to manipulate permissions, owners, and groups of files and directories on Unix/Linux systems.

## Script List

| Script                      | Description                                                        |
|-----------------------------|--------------------------------------------------------------------|
| 0-iam_betty                 | Switch to user betty.                                              |
| 1-who_am_i                  | Display the current user's name.                                   |
| 2-groups                    | Display the current user's groups.                                 |
| 3-new_owner                 | Change the owner of the file `hello` to betty.                     |
| 4-empty                     | Create an empty file named `hello`.                                |
| 5-execute                   | Give the user execute permission on `hello`.                       |
| 6-multiple_permissions      | Set permissions 754 on `hello`.                                    |
| 7-everybody                 | Give everyone execute permission on `hello`.                       |
| 8-James_Bond                | Set permissions 007 on `hello`.                                    |
| 9-John_Doe                  | Set permissions 753 on `hello`.                                    |
| 10-mirror_permissions       | Copy permissions from one file to another.                         |
| 11-directories_permissions  | Give everyone execute permission on all directories.               |
| 12-directory_permissions    | Create a directory with specific permissions.                      |
| 13-change_group             | Change the group of the file `hello`.                              |
| 14-change_owner_and_group   | Change the owner and group of all files.                           |
| 15-symbolic_link_permissions| Change the owner/group of a symbolic link.                         |
| 16-if_only                  | Change the owner if the previous one is guillaume.                 |

## Usage

Each script is executable and can be run directly from the terminal:

```bash
./script_name
```

Give execution rights if needed:

```bash
chmod +x script_name
```

## Learning Goals

This folder aims to:
- Understand and manipulate Unix permissions
- Manage users, groups, and access rights
- Automate rights management in Bash

## Author

Project completed as part of the Holberton School curriculum.
