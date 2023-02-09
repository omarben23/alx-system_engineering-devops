su a script that switches the current user to the user betty
whoami prints the effective username of the current use
groups prints all the groups the current user is part of
chwon betty hello change the owner of the file hello to the user betty
touch create an empty file
chmod u+x adds execute permission to the owner of the file hello
ug+x,o+r hello adds execute permission to the owner and the group owner, and read permission to other users, to the file
chmod ugo+x hello adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello, sets the permissions to the file hello as follows: owner no permission at all, group no permission at all and other users got all the permissions 
chmod --reference=olleh hello sets the mode of the file hello the same as olleh’s mode.
