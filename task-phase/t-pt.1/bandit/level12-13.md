the password is stored in a file, which is a hexdump of a file that has been repeatedly compressed. 

so,  a hex dump is a hexadecimal view of a data. looking at a hex dump of data is usually done in the context of debugging.
in a hex dump, each byte is represented as a two-digit hexadecimal number. Hex dumps are commonly organized into rows of 8 or 16 bytes.

so, **xxd** command is used to create a dump of a file.
**xxd -r** will reverse, i.e., convert a hexadump to a file.

_xxd -r [file-name] > [new file-name]_ will extract the hexadump file to a new file.

after converting, we will be getting different formats and we have to decode them again and again till we get a text file.

the commands that can be used:
1. _file [file-name]_ tells about the type of data stored in file.
2. _mv [file-name] [new file-name with diff extension]_ will move the file to a new file w/ different extension.
3. _[compression-type] -d [file-name]_ decodes the file.
4. _tar xf [file-name]_ is used to extract tar files.
5. _rm [file-name]_ is used to remove a file.

we are not allowed to perform de-compression and de-coding on the original file so we have to firstly make a new directory using **mkdir** 
and then copy the file using **cp** command.

1. _mkdir [new-directory address]_.
2. _cp [file-name] [destination-address]_ copies the data.
