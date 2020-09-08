
# COMMAND LINE 
___
### CREATING A NEW DIRECTORY
If we want to creae a new directory we use the command **"mkdir":**
```
mkdir name_of_the_new_directory
```
### CHANGING DIRECTORIES 
serves to change the directory, ie we can enter a directory or likewise can leave. For it we use the command **"cd/cd .."**

***in***
```
cd name_of_the_directory    
```
***out***
```
cd ..
```
### CHECK ALL THE FILES/DIRECTORIES WITHIN A DIRECTORY
It is useful to see which files and even which directories we have inside of a directory, for that we use the command **"ls"** 
```
ls
```
Also if you want to check the **HIDE FILES** you can use the command **"ls .*"**
```
ls .* 
```
To see all the files and also de hiden 
--> ls -a, ls -l, ls -A, ls -Al, ls -h, ls -lh, ls -Alh

To search some file or directory and you don`t know the hole name you can abreviate it and find it like this:
```
ls my*
``` 
* ls my?dir = it gives the content that is inside of the directory
* ls my*dir = "*"it means one or cero or more characters

If we have a directory with any number in the name,for example another_9hing, we can open it like this:
```
ls another_[[:digit:]]hing
```
you can do the dame with any alphabetic digit for example another_thing:
```
ls another_[[:alpha:]]hing
```
also you can do it in other ways:
```
ls another_[[:alnum:]]*
ls another_[[:lower:]]*
ls another_[[:upper:]]*
```
### HISTORY
If we want to see all the commands and movements we have done inside the powershell we can access to the history and check all the register and also if we forgot a command we can check it from there.The command we use is **"history"**
```
history
```
### CREATING A NEW FILE
We can create a new file by using the command **"nano"**, command line let us create files of any type depending on the completion of the document, for example(.txt,.py,.c,etc.)
```
nano name_of_the_file.type
```
if you want to create a **hiden file**
```
nano .name_of_the_file.type
```
## COPING A FILE 
If we want to copy a file we use **"cp"** following by the name of the new file because they can have the same name because it is a copy
```
cp name_of_the_file name_of_the_copy
```
### DYNAMIC COPY 
If you want to copy what is inside of a directory with all the components use the following commmand
```
cp -i *.txt
```
### COPY TO ANOTHER DIRECTORY
If you want to copy the file in anothe directory use **"cp * ../_/."**
```
cp * ../name_of_directory/.
```
### RECURSIVE COPY 
To get the copy of diferent directions or directories you can use the command **"cp -R"**, you can also put the line of all your directories starting in home and it will create a copy of everything(the direction)
```
cp -R names_of_the_file/directories_you_want_to_copy  name_copy
```
### CHECK WHERE YOU ARE 
If you want to check in what directory you are, use command "pwd" and it will give you the complete line starting with home until you are
```
pwd
```
### SHOW WHAT IS INSIDE OF THE FILE
If you want to see what is inside of your file and of what is composed you can use te command **"cat"**
```
cat name_of_the_file
```
### REMOVING A FILE 
To delete a file use the command **"rm"**
```
rm name_of_the_file
```
### REMOVING THE SAME TYPE
If you have many files with the same typo (.txt.py.c) you don`t have to remove one by one, you can delete all of them(they have to be the same type) by using the command **"rm *."**
```
rm name_of_the_file*.type(txt,py,c,...)
```
### REMOVING A DIRECTORY
If you want to remove a directory you can use the command **"ls /"**
***if it is not empty***
```
rm -R name_of_directory
```
***If it is empty***
```
rmdir name_of_directory
```
### CHECK HOW DOES A COMMAND WORK
If you want to check how does a comand word you just put **"man"**
```
man name_of_the_command
```
###MOVE A FILE TROUGHT CARPETS
To move a file to another carpet use the command **"mv"**
```
mv name_of_the_file ../.  <---(direction_carpet)
```
## MODIFIED FILES
There are documents that you can modified/access and there are other that you cant because of the access of the user
there are diferent types of path
* Absolute paths: the direcctions of the directories 
* Relative paths: they are refered to the directory home

## SEARCH LOCATION SHORTCUTS
The 1rst argument after 'find' is the location you want to search, but you have to specify a specific directory using one of the metacharacters:
* Period(.): Specifies th current and all nested folders.
* Forward Slash (/): Specifies the entire filesystem.
* Tilde (~): Specifies the active user's home directory.
### FIND
The command used to search for files is called **find**.
```
find filename
```
### FIND FILES ACCESSED MORE THAN A CERTAIN NUMBER OF DAYS AGO
```
find ~ -atime + 100
``` 
### FIND EMPTY FILES AND FOLDERS
```
find / -empty
```
### FIND EXECUTABLE FILES
```
find / -executable
```
### FIND READABLE FILES
```
find / -readable
```
### FIND FILES UNDER HOME DIRECTORY
```
find /home -name file.txt
```
### PATTERN
Search for all files with extension mp3:
```
find / -name *.mp3

```
### FIND EXECUTABLE FILES 
```
find / -perm /a=x
```
