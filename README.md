# Linux Cheat Sheet

Based on the material provided by Read Hat in [Red Hat System Administration I](https://www.redhat.com/en/services/training/rh124-red-hat-system-administration-i?section=Overview) and [Red Hat System Administration II](https://www.redhat.com/en/services/training/rh134-red-hat-system-administration-ii) courses.

## Essential CLI commands

Command                     | Meaning      | Possible Output
--------------------------- | -------------|-----------
`ssh remoteuser@remotehost` | virtually login |
`exit`  | Logout |
`passwd`  | Password change |
`whoami` |username |
`date +%R`; `date +%x`| Time and date| 19:13 <br> 03/29/2022
`date +%r` |Current time in 12-hour clock time |
`file /etc/passwd` | Scan file content and return what type the content is | ASCII
`cat /etc/passwd` <br> `cat file 1 file 2` | * Create a file in the folder<br> * Concatenate the contents from multiple files <br> * Redirect contents of the file to a terminal or files. |
`head` and `tail` | Display the beginning and the end of a file |
`wc` | * Counts lines, words, characters <br> * `-l`, `-w`, or `-c` option to display only the number of lines, words, or characters, respectively. |
`history` | List of previously executed commands |
`cd ..` | cd .. command uses the .. hidden directory to move up one level to the parent directory
`mkdir` | Create a directory
`cp file new-file` |Copy file
`cp -r directory new-directory` |Copy directory and its contents
`mv file new-file` | Move or rename a file or directory
`rm file` | Remove a file
`rm -r directory` | Remove a directory containing files
`rmdir directory` | Remove an empty directory
`ls -al` | Redirect all contents to a file named e.g. 'editing_final_lab'| `ls -al > editing_final_lab.txt`
`vim` | edit file using vim | `vim editing_final_lab.txt` 
`echo` | Append to a file | `echo " ---"`

## Shortcuts

Shortcut                     | Meaning
--------------------------- | -------------
Alt+F2  | Enter a Command and enter gnome-terminal
Windows+L  | Lock the screen
Ctrl+A | Jump to the beginning of the command line.
Ctrl+E | Jump to the end of the command line.
Ctrl+U | Clear from the cursor to the beginning of the command line.
Ctrl+K | Clear from the cursor to the end of the command line.
Ctrl+LeftArrow | Jump to the beginning of the previous word on the command line.
Ctrl+RightArrow | Jump to the end of the next word on the command line.
Ctrl+R | Search the history list of commands for a pattern.
Ctrl+V | Enter line-based visual mode
x | Delete
v | Select characters on single-line only

## Important
* If you want to type more than one command on a single line, use the semicolon `;`;
* `\`  to ignore the meaning of the character;
* `!` is a metacharacter that is used to expand previous commands without having to retype them;
*  
