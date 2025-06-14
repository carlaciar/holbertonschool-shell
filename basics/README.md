# Week 2: Shell Basics
**Requirements**
- Allowed editors: `vi`, `vim`, `emacs`
- All your scripts will be tested on Ubuntu 22.04 LTS
- All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file at the root of the repo, containing a description of the repository
- A `README.md` file, at the root of the folder of this project, describing what each script is doing
- You are not allowed to use backticks, `&&`, `||` or `;`
- All your scripts must be executable. To make your file executable, use the `chmod` command: `chmod u+x FILENAME_GOES_HERE`. Later, we’ll learn more about how to utilize this command.

## FILE: 0-current_working_directory
**0. Where am I?**\
Write a script that prints the absolute path name of the current working directory.

## FILE: 1-listit
**1. What’s in there?**\
Display the contents list of your current directory.

## FILE: 2-bring_me_home
**2. There is no place like home**\
Write a script that changes the working directory to the user’s home directory.
- You are not allowed to use any shell variables

## FILE: 3-listfiles
**3. The long format**\
Display current directory contents in a long format

## FILE: 4-listmorefiles
**4. Hidden files**\
Display current directory contents, including hidden files (starting with `.`). Use the long format.

## FILE: 5-listfilesdigitonly
**5. I love numbers**\
Display current directory contents.
- Long format
- with user and group IDs displayed numerically
- And hidden files (starting with .)

## FILE: 6-firstdirectory
**6. Welcome**\
Create a script that creates a directory named `my_first_directory` in the `/tmp/` directory.

## FILE: 7-movethatfile
**7. Betty in my first directory**\
Move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

## FILE: 8-firstdelete
**8. Bye bye Betty**\
Delete the file `betty`.
- The file `betty` is in `/tmp/my_first_directory`

## FILE: 9-firstdirdeletion
**9. Bye bye My first directory**\
Delete the directory `my_first_directory` that is in the `/tmp` directory.

## FILE: 10-back
**10. Back to the future**\
Write a script that changes the working directory to the previous one.

## FILE: 11-lists
**11. Lists**\
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format.\
Be careful with the `/`

## FILE: 12-file_type
**12. File type**\
Write a script that prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory when we will run your script.

## FILE: 13-symbolic_link
**13. We are symbols, and inhabit symbols**\
Create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.

## FILE: 14-copy_html
**14. Copy HTML files**\
Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.\
You can consider that all HTML files have the extension `.html`

## FILE: 15-lets_move
**15. Let’s move**\
Create a script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.\
You can assume that the directory `/tmp/u` will exist when we will run your script

## FILE: 16-clean_emacs
**16. Clean Emacs**\
Create a script that deletes all files in the current working directory that end with the character `~`.

## FILE: 17-tree
**17. Tree**\
Create a script that creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory.\
You are only allowed to use two spaces (and lines) in your script, not more.

