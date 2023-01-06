the password is stored in a text file next to a give word.

for this, we will be using the **grep** command. it searches a file for a particular pattern or expression and returns all the lines that contain the pattern.

syntax to find: **cat [file-name] | grep "[pattern]"**

since, in the level, the file-name is _data.txt_ and the pattern is _millionth_, so we will write: 
**cat data.txt | grep "millionth"**, and the line containing the word will be displayed.
