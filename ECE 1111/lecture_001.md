Bash is the shell for the GNU operating system
  - Bash profile is executed when you startup
  - Bash RC is executed when you generate a shell
  - only the bash rc is executed when you run a shell  
Bash Manual: https://www.gnu.org/software/bash/manual/bash.html#What-is-a-shell_003f

A shell is a macro processor that executes commands; macro indicates that the texts and symbols are expanded to create lager expressions
  
#!/bin/bash
#! : is referred to as shebang 
bin/bash : tells the computer what language to execute the script in

notation: 
- d command
  - shows us:
    -  the permissions for the files,
    -  who owns the file,
    -  the group associated, s
    -  ize in bites,
    -  last date modified
    -  filename; / indicates it is a directory,
![image](https://github.com/user-attachments/assets/7a0828fe-0c30-46d9-adbf-e2a138e7fa1e)
in the image above, the absence of the prefix d indicates it is a file rather than a directory; pay attention to the notation on the filename at the end of the line
- drxzrxwr-x.
  - The d indicates that this is a directory listing
  - the first group of three (rwx) indicates that we have read, write, and excecute permissions
  - the second group of three indicates that the users have read, wrtie, and execute permissions
  - the last group indicates that anyone has read and execute permissions
- lrxzrxwr-x.
  - the l indicates this is a link 
- ctrl+r
  - this reverse searches
- p
  - alias for pwd; this give the current location
Emacs basics: https://youtu.be/jPkIaqSh3cA?si=CG_Z7vEY88oVTgMt

