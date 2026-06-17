
# File System Navigation

## Key Concepts

- Creating directories
- Copying files
- Removing files
- Copying files
- Renaming files
- listing current directory contents

## Commands

`ls` - prints the directory contents
`-l` - prints the file permissions, date and the size
`-a` - prints out the hidden files starting with .
`-h`- prints out human-readable sizes instead of raw bytes
`touch` - creates an empty file in the current directory
`mv` - renames a file

## Examples
touch test.txt
mkdir projects/demo
mv projects/demo/test.txt projects/demo/backup.txt


## What I Learned
The command cp test.txt project/demo/ copies the file test.txt and places it in the folder demo.

The command mkdir creates directories in the current directory.

The command less /var/log/syslog prints out the content of systems log but in a scrollable view.
The command head -n 20 /etc/services prints out the first 20 lines of /etc/services
