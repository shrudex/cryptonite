the password is stored in a file, which contains base64 encoded data.

_base64_ is an encoding scheme that represents binary data in an ASCII string format by translating it into a radix-64 representation.
this is done to ensure that the data remain intact without modification during transport.

*-d* or *--decode* command is used to decode any encoded data from any file.

here, we have to decode the _base64_ data.

to do this, syntax: **cat [file-name] | [encoding-format] -d**
OR
**echo [encoded-data] | [encoding-format] --decode**.
