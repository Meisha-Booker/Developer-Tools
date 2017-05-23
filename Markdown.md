Developer Tools - Jose and Meisha
===
Markdown
===
What is Markdown? Markdown is a plain text formatting syntax designed so that it can be converted to HTML using a tool by the same name. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

Helpful Markdown Links
---
1. Markdown Official [Website]((https://daringfireball.net/projects/markdown/)

2. Markdown [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

3. Markdown [Tutorial](http://www.markdowntutorial.com/)


'Shell'ing Like A Pro
===
How To Change Directories
---
You can change folders(directories) by utilizing the 'cd' command in the terminal followed by the name of the directory you want to go to.

```bash
cd file_name

# This would take you into the directory 'file_name'.
```
Show Contents Of Directory
---
You can view the contents of the directory using the 'ls' command.
```bash
ls
text-file.txt index.html style.css
#These are the listed files in the current directory.
```
Rename A file
---
You can rename a file using the command 'mv' short for move.
```bash
$ echo "Example text" > exampleFile
$ mv exampleFile exampleFile.txt
$ ls
exampleFile.txt
#This command renamed exampleFile to exampleFile.txt
```
Copy A File
---
The way to copy a file with 'cp', short for copy.
```bash
$ cp exampleFile.txt newExampleFile.txt
$ ls
newExampleFile.txt exampleFile.txt
```
Delete A File
---
The command for deleting a file is 'rm', for remove.
```bash
$ rm newExampleFile.txt
remove newExampleFile.txt? y
$ ls newExampleFile.txt
ls: newExampleFile.txt: No such file or directory
```
Create A Directory
---
The command to create a directory is 'mkdir'.
```bash
$ mkdir exampleDirectory
# This would create a new Directory called exampleDirectory in the current directory.
```
Create A File
---
The command to create a file is 'touch'
```bash
$ touch exampleFile.txt
$ ls
touch exampleFile.txt
#This will create a file called exampleFile.txt in current directory.
```
Get Help Using Manual [man]
---
A tool used to learn more about available commands.
```bash
$ man ls

-A  List all entries except for . and ...  Always set for the super-user.

-a  Include directory entries whose names begin with a dot (.).
#This will direct you to the manual for command requested.
```
Read From A File
---
The command to read from a file is 'cat'.
```bash
$ cat fileWithText.txt
'This is the text inside the file'
#This command will display contents of fileWithText.txt
```
Write To A File
---
```bash
echo "some data for the file" > fileName.txt
#This would write "some data for the file" into fileName.txt
```
