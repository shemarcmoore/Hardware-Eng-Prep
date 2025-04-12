Environment 
- the settings and preferences of the current user
- an array of strings; name-value pairs

export var 
- allows variable to persist when exiting the script; makes it available in the environment

File permissions

d
  - displays file permission

ls -
  - lists name of files in directory
* both use lexical order; order it was entered into directory

Pipes 
- concatenation of commands; output from one command as input to other

printenv | grep var # 
- 'pipes' the output to grep which searches for a line in the environment containing the variable

wc
- program that counts lines; can be used as follows
  printenv | grep var | wc
  printenv | grep var | wc - 1 # returns the number of lines with the variable

- if you were to put script contents in your bashrc, as opposed to bashprofile, it would execute every time


Foreground/Background - run process interactively (foreground) or background

%
- run command in backgroud

fg
- run command in foregroud


Command Line Programming

find
  - recurse through given directory and prints contents
  - does not use lexical order
  example: find /data/..../files/...etc

  - -type d / wc -l
   - when preceded by find directory, provides number of associated databases 
  - -type f / wc -l
   - when preceded by find directory, provide number of associated files

  - head -x
   - gives the first x lines outputted by find command
  - tail -x
   - gives the last x lines outputted by find command

  - -exec
   - execute and additional command on output of find command
     Format: -excec grep data {} \:

  - sort
    - piping find through sort will order the data

  - shell redirection
    standard output (> filename)
      - captures output of the command in the specified file
      - creates the file; overwrites existing file if it already exists
    standard input (> filename)

history
 - provides a history of excecuted commands
 - can be paired with grep to find commands containing specific text
  examples:
  history | grep find
    - returns commands containing find
  history | grep find | grep /data
    - returns commands having find and /data on the same line

Command Line Regular Expressions
  - strings are contained between * symbol
  
  - question makes can be used to find soecific names with characters equivalent to number of question marks
  example: ??? paired with the d command find directories containing 3 letters

Useful Commands

isip_e
  - calls emacs

nohup
  - prefix to command 

