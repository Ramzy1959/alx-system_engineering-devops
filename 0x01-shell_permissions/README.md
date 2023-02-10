su; this is a command used to switche the current user to another user
whoami; this is a command that prints the effective username of the current user.
group; this is a command that prints all the groups the current user is part of.
chown; this is a command thatthat changes the owner of the file from one user to another
touch; this is the command used for creating empty files
chmod u+x; this is a command used to add execute permission to a file or source code
chmod ug+x,o+r; this is a command that adds execute permission to the owner and the group owner, and read permission to other users,on a particular file

chmod ugo+x; this is another command that  adds execution permission to the owner, the group owner and the other users, to the file without commas
chmod 007; this is a command  that sets the permission to a file  as follows:



Owner: no permission at all

Group: no permission at all

Other users: all the permissions

chmod 753; this is a command  that sets the mode of a file
chmod –reference= filenames; this is a command that sets the mode of a file to the same as another file
chmod -R +111 */; this is a command that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. regular files are not changed at the sametime.

