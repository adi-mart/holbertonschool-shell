# Basics - Shell Command Scripts

> **Folder**: `basics/`
>
> This folder contains a series of Bash scripts to manipulate the Unix/Linux shell and get familiar with basic commands. Each file corresponds to a specific exercise or command.

## Script List

| Script                      | Description                                                        |
|-----------------------------|--------------------------------------------------------------------|
| 0-current_working_directory | Displays the current directory (`pwd`).                            |
| 1-listit                    | Lists the contents of the current directory (`ls`).                |
| 2-bring_me_home             | Moves to the user's home directory (`cd ~`).                       |
| 3-listfiles                 | Lists files with details (`ls -l`).                                |
| 4-listmorefiles             | Lists all files, including hidden, with details (`ls -la`).        |
| 5-listfilesdigitonly        | Lists files with numeric details (`ls -lna`).                      |
| 6-firstdirectory            | Creates a directory `/tmp/my_first_directory`.                     |
| 7-movethatfile              | Moves `/tmp/betty` into `/tmp/my_first_directory`.                 |
| 8-firstdelete               | Deletes `/tmp/my_first_directory/betty`.                           |
| 9-firstdirdeletion          | Deletes the directory `/tmp/my_first_directory`.                   |
| 10-back                     | Goes back to the previous directory (`cd -`).                      |
| 11-lists                    | Lists contents of several directories (`ls -la . .. /boot`).       |
| 12-file_type                | Displays the type of `/tmp/iamafile` (`file`).                     |
| 13-symbolic_link            | Creates a symbolic link `__ls__` to `/bin/ls`.                     |
| 14-copy_html                | Copies modified `.html` files to the parent directory (`cp -u`).   |
| 15-lets_move                | Moves all uppercase-named files/directories to `/tmp/u`.           |
| 16-clean_emacs              | Deletes all Emacs backup files (`rm *~`).                          |
| 17-tree                     | Creates a directory tree `welcome/to/school`.                      |

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
- Discover and use basic shell commands
- Automate common tasks
- Understand Bash script structure

## Author

Project completed as part of the Holberton School curriculum.
