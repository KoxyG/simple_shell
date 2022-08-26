ALX SIMPLE SHELL TEAM PROJECT

This is an ALX collaboration project on shell. We were tasked to create a simple shell that mimics the Bash Shell. Our Shell shall be called the hsh.

PROJECT WAS COMPLETED USING

C language
Shell
Betty Linter


GENERAL REQUIREMENT FOR THE PROJECT

All files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
Use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
Shell should not have any memory leaks
No more than 5 functions per file
All header files should be include guarded
Write a README with the description of the project


DESCRIPTION

hsh is a simple UNIX command language interpreter that reads commands from either a file or standard input and executes it


HOW HSH WORKS

Prints a prompt and waits for a command from the user
Creates a child process in which the command is checked
Checks for built-ins, aliases in the PATH, and local executable programs
The child process is replaced by the command, which accepts arguments
When the command is done, the program returns to the parents process and prints the prompt
The program is ready to receive a new command
To exit: press Ctrl-D or enter "exit" (with or without a status)
Works also in non interactive mode


COMPILATION

gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

INVOCATION

AUTHORS

👤 PROGRESS OCHUKO EYAADAH
GitHub:
Twitter: 
LinkedIn:

👤
