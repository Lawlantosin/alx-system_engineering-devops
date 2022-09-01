0: su betty Script that changes your user ID to betty.

1: id -un Print the effective user ID of current user. Other alternative is whoami

2: id -Gn Prints all the groups the current user is part of.

3: chown betty hello Changes the owner of the file hello to the user betty

4: touch hello Create an empty file called hello

5: chmod u+x hello Add execute permission to the owner of the file hello

6: chmod ug+x,o+r hello Add execute permission to user and group owner, and read permission to others for file hello

7: chmod ugo+x hello Add execution permission to all for file hello.

8: chmod 007 hello Set permissions for file hello so owner and group don't have any permissions and other users have all permissions.

9: chmod 753 hello Set permissions so owner has all permissions, group has read and execute permissions and others have write and execute permissions.

10: chmod --reference=olleh hello Copies the mode of file olleh to file hello.

11: chmod -R +X . Add execute permission to all subdirectories of the current directory for the everyone. Regular files should not be changed.

12: mkdir -m 751 my_dir Create a directory called my_dir with permissions 751 in the working directory. User has all read, write, and execute permissions. Group has read and execute permissions. Others have just execute permission.

13: chgrp school hello Change gorup owner to school for the file hello

14: chown vincent:staff * Change owner to betty and the group owner to staff for all files and directories in current directory.

15: chown -h vincent:staff _hello Changes the owner and group owner of file _hello to Vincent and Staff respectively.

16: chown --from=guillaume betty hello Change owner of the file hello to betty only if it is currently owned by guillaume

17: telnet towel.blinkenlights.nl Play the Star Wars IV episode in the terminal. This is a premade script provided online.
