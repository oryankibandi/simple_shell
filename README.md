# Simple Shell

This is an emulation of Unix shell done with C.
A simple UNIX command interpreter written using a low-level programming C.

Description

Shelby is a simple UNIX command language interpreter that reads commands from either  a file or standard input and executes them.
Shelby can be invoked both interactively and non-interactively with standard input and when connected to a terminal.
Shelby handles command lines with arguments.
In this we handled the PATH, implemented the exit built-in functions, implemented the env built-in function that prints the current environment.

Variable $

Shelby interprets the $ character for variable repalcement.
ENV_VARIABLE is subtituted with its value.

Comments #
Shelby ignores all words and characters preceeded by # character on a line.

Operators
Command separators by a ;
Logical operator &&
Logical operator ||

Builtin commands
cd - directory : changes current directory 
Otherwise the default $HOME is executed

Alias
Handles aliases
alisa : prints a list of all aliases, one per line, in the form NAME = 'VALUE'
 
exit
USAGE:  exit[STATUS]
Exits the shell.

env
USAGE: env
prints the current environment

setenv
USAGE: setenv [VARIABLE] [VALUE]
Initializes a new environment variable or modifies an existing one
Upon failure, prints an error message to stderr

usetenv
USAGE: unsetenv [VARIABLE]
Removes the environment variable
Upon failure, prints an error message to stderr

AUTHORS
Alexina Moraa
Oryan Kibandi

