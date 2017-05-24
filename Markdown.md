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
Debugging Your Code
===
Console.count()
---
Logs the number of times that this particular call to count() has been called. This function takes in an optional argument label1. If label is omitted, the function logs the number of times count() has been called at this particular line.

```bash
var count = (function() {
  var counter = {};
  return function(v) {
    return (counter[v] = (counter[v] || 0) + 1);
  }
}());

console.log('foo', count('foo'));
console.log('foo', count('foo'));
console.log('bar', count('bar'));
```
Console.assert()
---
The console.assert() method takes two parameters, a boolean expression, and an object. If the result of the expression is false the object will be printed in the console. In the example below, the expression here checks to see if the count variable is larger than 10. If it’s not, the message ‘count is not larger than 10’ is printed in the console.

```bash
var count = 5;
console.assert(count > 10,'count is not larger than 10')
#Assertion failed: count is not larger than 10
```
Console.error()
---
The console.error() method takes one or more objects and prints them to the console. This method is similar to console.log() however console.error() will also print a stack trace from where the method was called. The output will also be flagged as an error in the console.

```bash
function findPage(){
  console.error('Page not found (404)');
}
undefined
findPage()
#Page not found 404
```
Get Good at Git and GitHub
===
[Sandbox GitHub repository link]((https://daringfireball.net/projects/markdown/)
Git commands
---
```bash
$ git clone https://www.cloned-repo-url.command
# This will create a folder with cloned project in current directory.
$ git add nameOfFileBeingStaged.txt
# will stage changes for commit nameOfFileBeingStaged.txt
$ git reset nameOfFileBeingStaged.txt
# will unstage nameOfFileBeingStaged.txt
$ git commit -m "Your message here"
# Will commit and add message to commit
$ git commit --amend
# Convenient way to fix up the most recent commit. It lets you combine staged changes with the previous commit instead of committing again
$ git branch branchhNameHere
# This will create branch branchhNameHere
$ git branch -d branchhNameHere
# THis will delete branch branchhNameHere
$ git push
# This will push up committed changes.
$ git pull
# This will update local and incorporate changes
$ git push alias branchhNameHere
# Uploads all local branch commits to GitHub
$ git reset --hard [commit]
# This will delete commits after specified [commit]
$ git rebase [branch]
# Move branch to new base commit
$ git rebase -i [branch]
# Opens editor with list of commits and allows user to edit before initiating the rebase.
$ git cherry-pick master
# Chery picking means to choose a commit from one branch and apply it to another.
```
Typing
---
```bash
Jose Moreno:  
Type.io - 34, 35, and 35 WPM

Meisha Booker:
Type.io - 19, 18, and 17 WPM
```
Master Your Editor
---
A text editor is a program for editing stored documents, performing such functions as adding, deleting, or moving text. The 5 most used editors for software developers are: Atom, UltraEdit, Sublime Text, Notepad++ , and CoffeCup.
```bash
Favorite Features of Atom

1. Multi/Split Screens
2. Package Installer
3. Tree View of your folder and files
4. Customization with color

Favorite Plugins of Atom

1. Markdown Preview
2. HTML Preview
3. Merge Conflicts
```  
