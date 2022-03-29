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

## Important
* If you want to type more than one command on a single line, use the semicolon `;`;
* `\`  to ignore the meaning of the character;
* `!` is a metacharacter that is used to expand previous commands without having to retype them;
* 
