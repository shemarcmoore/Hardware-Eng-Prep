Environment 
- the settings and preferences of the current user
- an array of strings; name-value pairs

export var 
- allows variable to persist when exiting the script; makes it available in the environment
printenv | grep var # 
- 'pipes' the output to grep which searches for a line in the environment containing the variable
wc
- program that counts lines; can be used as follows
  printenv | grep var | wc
  printenv | grep var | wc - 1 # returns the number of lines with the variable
  
- if you were to put script contents in your bashrc, as opposed to bashprofile, it would execute every time

* File permissions
  - x
  - 
* Pipes - concatenation of commands; output from one command as input to other
  - x
  - 
* Foreground/Background - run process interactively (foreground) or background
  - x
  - 
* Command Line Regular Expression
  - x
  - 
* Command Line Programming
  - x
  - 
* Regular Expression
* Useful Commands
