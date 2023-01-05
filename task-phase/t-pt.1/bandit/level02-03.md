the password is stored in a file called *spaces*.

we cannot access the contents of this file directly because the terminal reads the “space” differently.
for eg. a directory named "shubh sinha" will be considered as 2 different directory - "shubh" and "sinha".

so, the 2 approaches to handle this situation is:
1. using escape character: **cat [file-name before space]\ [file-name after space]**
2. using quotation marks: **cat "[file-name]"**

hence the required command for this level: _cat "spaces in this filename"_.
