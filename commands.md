# There will Be NO order Between The Commands, for example may be the first command is about user management, then about file systems then about ssh authentication and etc...

## To see the user is member of which groups.

`groups <username>`

`id <username>`

`grep <groupname> /etc/group`

`id -nG <username> | grep -qw <groupname> && echo "Yes" || echo "No" /etc/group`
