# File System Navigation

## Key Concepts

- Changing permissions of files
- Changing ownership of files
- Creating script files


## Commands

`chmod` - changes permissions of files
`sudo chgrp` - changes the group of a file
`sudo chown` - Changes the directory's and file's owner and group
`sudo chown -R` = Changes the owner and group of a directory recursively

## Examples
`chmod u+x,g+w,o-x`
`sudo chgrp admin2 example.txt`
`sudo chown newuser:admin2 example.txt`
`sudo chown -R newuser:admin2 my_directory`


## What I Learned
I learned how to change the permissons of a file using chmod.
You can create script files from an executable file.
You can change the user and group of a directory recursively.
