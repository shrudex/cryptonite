**DESCRIPTION** : Python scripts are invoked kind of like programs in the Terminal... Can you run this Python script using this password to get the flag?

we get the links to the 3 files : python script, password file and an encrypted file.

reading the contents of files using **cat** command.

to run any python file : **python [file-name.py]**

after running the python file, it asks us to write in the format _python [file-name.py] (-e/-d) [file]_.
so, **-h** command with the python prints the usage for interpreter executable.

so, _python ende.py -h_ asks us to write in the format : _python ende.py -d [file]_, to decrypt the file.

the flag which which downloaded is to be decrypted, so : _python ende.py -d flag.txt.en_ will run the script and asks for password. 
tha password is stored in the password file and can be extracted using **cat** command.
