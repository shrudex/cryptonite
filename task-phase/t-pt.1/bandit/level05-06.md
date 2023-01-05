the password is stored in a file which has the following properties:
1. human-readable
2. 1033 bytes in size
3. not executable

to find write: **find . -type f -size 1033c ! -executable**

_find_ command to find for a file/directory.

_._ refers to the current directory.

_-type f_ says to find for a file.

_-size 1033c_ helps in defining property of the file - size 1033 bytes. _c_ defines _bytes_.

_! -executable_ tells that the file is not executable.

after the command, we got the file name and hence open it using **cat** command.
