the password is stored in a file and is the line that only occurs once.

for this, we will be using the command **uniq** command.

**uniq** command filters out the repeated lines in a file.

but, _uniq_ is not able to detect the duplicate lines unless they are adjacent to each other. 
the content in the file must be therefore sorted before using _uniq_ or you can simply use _sort -u_ instead of _uniq_ command. 

with, _uniq_ command, we will be using the _-c_ count command that tell ths number of times the line was repeated.

hence, the syntax: **cat [file-name] | sort | uniq -c**.
so, we will be seeing the lines, and the line with count = 1 is the line containing password.
