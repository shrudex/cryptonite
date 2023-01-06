the password is stored somewhere on the server with the properties:
1. owned by user bandit7
2. owned by group bandit6
3. 33 bytes in size

to find for this, we will type:
**find / -type f -user bandit7 -group bandit6 -size 33c**

_/_ tells to find in the entire file system as the password is stored somewhere so we need to check the entire file system.

_-type f_ to tell that it is a file.

_-user bandit7 & -group bandit6_ tells about the ownership of the file.

after executing the statement, we get the location of the file somewhere and we will open it used **cat**.
