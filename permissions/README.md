Each file contains a seperate answer to a question about permissions.
0. Switch current user - {su betty}
1. Prints effective username of current user - {whoami}
2. Prints all groups the current user is in - {groups}
3. Changes owner of file - {chown new-owner FileName}
4. Creates empty file - {touch FileName}
5. Adds execute permission to owner of file - {chmod u+x FileName}
6. Adds execute permission to owner and group, read permissions to other - {chmod u+rwx,g+rx,o+r FileName} 
7. Adds execute permission to owner, group owner, and other users - {chmod ugo+x FileName}
8. Sets permissions to owner -no permission, group - no permissions, other - all permissions {chmod 007 FileName}
9. Sets mode of file 'hello' to -rwxr-x-wx - {chmod 753 FileName}
10. Sets a file permission to the same as another file - {chmod --reference=olleh hello}
11. Adds execute permission to all subdirectories of current directory for all users, owner, groups
12. Creates directory with name and permissions 751
13. Changes the group owner of a file
14. Changes owner and group owner for all files in working directory
15. Changes owner and group owner for a file
16. Changes owner of file only if owned by another certain user

