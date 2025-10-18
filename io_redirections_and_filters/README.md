# IO Redirections and Filters - Shell Scripts

> **Folder**: `io_redirections_and_filters/`
>
> This folder contains Bash scripts to manipulate input/output redirections and classic shell filters.

## Script List

| Script                | Description                                                        |
|-----------------------|--------------------------------------------------------------------|
| 0-hello_world         | Displays "Hello, World".                                           |
| 1-confused_smiley     | Displays a confused smiley.                                        |
| 2-hellofile           | Displays the contents of `/etc/passwd`.                            |
| 3-twofiles            | Displays the contents of two files.                                |
| 4-lastlines           | Displays the last 10 lines of a file.                              |
| 5-firstlines          | Displays the first 10 lines of a file.                             |
| 6-third_line          | Displays the 3rd line of a file.                                   |
| 7-file                | Adds a line to a file with a complex name.                        |
| 8-cwd_state           | Saves the current directory contents to a file.                    |
| 9-duplicate_last_line | Duplicates the last line of a file.                                |
| 10-no_more_js         | Deletes all `.js` files in the current and subdirectories.         |
| 11-directories        | Counts the number of directories in the current directory.         |
| 12-newest_files       | Displays the 10 most recent files.                                 |
| 13-unique             | Displays unique lines from a sorted input.                         |
| 14-findthatword       | Searches for the word "root" in `/etc/passwd`.                    |
| 15-countthatword      | Counts occurrences of the word "bin" in `/etc/passwd`.             |
| 16-whatsnext          | Displays 3 lines after the first "root" occurrence in `/etc/passwd`|
| 17-hidethisword       | Displays lines not containing "bin" in `/etc/passwd`.              |
| 18-letteronly         | Displays lines starting with a letter in a config file.            |
| 19-AZ                 | Replaces certain characters with others.                           |
| 20-hiago              | Removes 'c' and 'C' characters from input.                        |
| 21-reverse            | Reverses each line of input.                                       |
| 22-users_and_homes    | Displays users and their home directories.                         |

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
- Master input/output redirections
- Use classic shell filters (grep, sort, uniq, tr, etc.)
- Automate file processing

## Author

Project completed as part of the Holberton School curriculum.
