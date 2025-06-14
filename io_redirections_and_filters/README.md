# WEEK 2: Shell, I/O Redirections and Filters
**Requirements**
- Allowed editors: `vi`, `vim`, `emacs`
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file, at the root of the folder of the project, describing what each script is doing
- You are not allowed to use backticks, `&&`, `||` or `;`
- All your files must be executable
- You are not allowed to use `sed` or `awk`

## FILE: 0-hello_world
**0. Hello World**\
Write a script that prints “Hello, World”, followed by a new line to the standard output.

## FILE: 1-confused_smiley
**1. Confused smiley**
Write a script that displays a confused smiley `"(Ôo)'`.

## FILE: 2-hellofile
**2. Let's display a file**\
Display the content of the `/etc/passwd`.

## FILE: 3-twofiles
**3. What about 2?**\
Display the content of `/etc/passwd` and `/etc/hosts`.

## FILE: 4-lastlines
**4. Last lines of a file**\
Display the last 10 lines of `/etc/passwd`
- Tips: “Thinks of it as a cat, what is at the end of it?”

## FILE: 5-firstlines
**5. I'd prefer the first ones actually**\
Display the first 10 lines of `/etc/passwd`

## FILE: 6-third_line
**6. Line #2**\
Write a script that displays the third line of the file `iacta`.\
The file `iacta` will be in the working directory
- You’re not allowed to use `sed`
- Note: The output will differ, depending on the content of the file `iacta`

## FILE: 7-file
**7. It is a good file that cuts iron without making a noise**\
Write a shell script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line.

## FILE: 8-cwd_state
**8. Save current state of directory**\
Write a script that writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.

## FILE: 9-duplicate_last_line
**9. Duplicate last line**\
Write a script that duplicates the last line of the file `iacta`
- The file `iacta` will be in the working directory

## FILE: 10-no_more_js
**10. No more javascript**\
Write a script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.

## FILE: 11-directories
**11. Don't just count your directories, make your directories count**\
Write a script that counts the number of directories and sub-directories in the current directory.
- The current and parent directories should not be taken into account
- Hidden directories should be counted

## FILE: 12-newest_files
**12. What’s new**\
Create a script that displays the 10 newest files in the current directory.\
Requirements:
- One file per line
- Sorted from the newest to the oldest

## FILE: 13-unique
**13. Being unique is better than being perfect**\
Create a script that takes a list of words as input and prints only words that appear exactly once.
- Input format: One line, one word
- Output format: One line, one word
- Words should be sorted

## FILE: 14-findthatword
**14. It must be in that file**\
Display lines containing the pattern “root” from the file `/etc/passwd`

## FILE: 15-countthatword
**15. Count that word**\
Display the number of lines that contain the pattern “bin” in the file `/etc/passwd`

## FILE: 16-whatsnext
**16. What's next?**\
Display lines containing the pattern “root” and 3 lines after them in the file `/etc/passwd`

## FILE: 17-hidethisword
**17. I hate bins**\
Display all the lines in the file `/etc/passwd` that do not contain the pattern “bin”.

## FILE: 18-letteronly
**18. Letters only please**\
Display all lines of the file `/etc/ssh/sshd_config` starting with a letter.
- include capital letters as well

## FILE: 19-AZ
**19. A to Z**\
Replace all characters `A` and `c` from input to `Z` and `e` respectively.

## FILE: 20-hiago
**20. Without C, you would live in hiago**\
Create a script that removes all letters `c` and `C` from input.

## FILE: 21-reverse
**21. esreveR**\
Write a script that reverse its input.

## FILE: 22-users_and_homes
**22. DJ Cut Killer**\
Write a script that displays all users and their home directories, sorted by users.
- Based on the the `/etc/passwd` file

## FILE: 23-empty_casks
**23. Empty casks make the most noise**\
Write a command that finds all empty files and directories in the current directory and all sub-directories.
- Only the names of the files and directories should be displayed (not the entire path)
- Hidden files should be listed
- One file name per line
- The listing should end with a new line
- You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`

