
ALX PROJECT: SIMPLE SHELL
Description
The Simple Shell is a command line interpreter made in the format written by Ken Thompson in 1971. Standard functions and system calls employed in simple_shell include: access, execve, exit, fork, free, fstat, getline, malloc, perror, signal, stat, wait, write.

Installation and Usage 
- Clone this repository: `https://github.com/OkayTrevor/simple_shell`.
 - Change directories into the repository: `cd simple_shell`
 - Compile: `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
 - Run the shell in interactive mode: `./hsh`
 - Or run the shell in non-interactive mode: example `echo "pwd" | ./hsh`

Features
 uses the PATH
 implements builtins
 handles command line arguments
 custom strtok function
 uses exit status
 shell continues upon Crtl+C (^C)
 handles comments (#)
 handles ;
 custom getline type function
 handles && and ||
 aliases
 variable replacement

Builtins
 exit
 env
 setenv
 unsetenv
 cd
 help
 history

Authors
Virginia Wabuke

Trevor Okoth

