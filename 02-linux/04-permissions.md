ls -l Output

-rw-r----- 1 testuser developers 0 Jul 6 17:23 test.txt

-rw-r-----      → File Type & Permissions
1               → Hard Link Count
testuser        → Owner
developers      → Group
0               → File Size (Bytes)
Jul 6 17:23     → Last Modified Date
test.txt        → File Name

change owner -> chown username:groupname filename
change mod -> chmod 755 filename(read:4, write:2, execute:1)
add/remove permission -> chmod u+x filename(user:u, group:g, others:o, all:a)
------------------------------

display all users -> cat /etc/passwd
display all groups -> cat /etc/group

display a user -> id username
display a user's groups -> groups username

create user -> useradd
delete user -> userdel

create group -> groupadd
delete group -> groupdel

add user to group ->usermod -aG
