the password is stored in a file in one of the few human-readable strings, preceded by several characters.

for this, we will be using the **strings** command.

_strings_ command displays the strings-text from the file.

for matching pattern, **grep** command is used. so, in this case we have to use it with **strings** command.

syntax: **strings [file-name] | grep "[pattern]"**

hence, for this level: _strings data.txt | grep "="_ and the password will be displayed.
