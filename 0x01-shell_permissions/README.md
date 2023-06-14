#!/bin/bash

0x01. Shell, permissions


0. su betty : is the command that switches the current user to the user betty.
1. whoami : is the command that prints the effective username of the current user.
2. groups : is the command that prints all the groups the current user is part of.
3. chown betty hello : is the command that changes the owner of the file hello to the user betty.
4. touch hello : is the command that creates an empty file called hello.
5. chmod u+x hello : is the command that adds execute permission to the owner of the file hello.
6. chmod u+x,g+x,o+r hello : is the command that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7. chmod a+x hello : is the command that adds execution permission to the owner, the group owner and the other users, to the file hello.
8. chmod 007 hello : is the command Write a script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions

9. chmod 753 hello : is the command that sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

10. chmod --reference=olleh hello : is the command that sets the mode of the file hello the same as olleh’s mode.
11. chmod -R a+x */ : is the command that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12. mkdir -m 751 my_dir : the command that creates a directory called my_dir with permissions 751 in the working directory.
13. chgrp school hello : is the command that changes the group owner to school for the file hello.
14. chown vincent:staff * : is the command changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15. chown -h vincent:staff _hello : is the command that changes the owner and the group owner of _hello to vincent and staff respectively.

The file _hello is in the working directory
The file _hello is a symbolic link

16. chown --from=guillaume betty hello : is the command that changes the owner of the file hello to betty only if it is owned by the user guillaume.
17. telnet towel.blinkenlights.nl : is the command that will play the StarWars IV episode in the terminal.
