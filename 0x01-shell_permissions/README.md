#!/bin/bash
su betty changes user from me to betty
whoami  a script that prints the effective username of the current user
groups  a script that prints all the groups the current user is part of
chown a script that changes the owner of the file
touch a script that creates an empty file
chmod u+x a script that adds execute permission to the owner of the file
chmod 754 a script that adds execute permission to owner and the group ,read permission to other users, to the file
chmod ugo+x a script that adds execution permission to the owner, the group owner and the other users, to the file
chmod 007 no permission to user and group,but all permissions to other users
chmod 753 a script that sets the mode of the file -rwxr-x-wx
chmod --reference=filename other_file  to mirror permissions with new file
chmod -R a+X  adds execute permission to all subdirectories of the current directory for owner, the group owner and all  users.
