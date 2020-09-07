# COMMAND LINE 

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
### HISTORY
If we want to see all the commands and movements we have done inside the powershell we can access to the history and check all the register and also if we forgot a command we can check it from there.The command we use is **"history"**
```
history
```
### CREATING A NEW FILE
We can create a new file by using the command **"nano"**, command line let us create files of any type depending on the completion of the document, for example(.txt,.py,.c,etc.)
```
nano name_of_the_document.txt
```
##COPING A FILE 
If we want to copy a file we use **"cp"** following by the name of the new file because they can have the same name because it is a copy
```
cp name_of_the_file name_of_the_copy
```
### DYNAMIC COPY 
If you want to copy what is inside of a directory with all the components use the following commmand
```
cp -i *.txt
```
### RECURSIVE COPY 
To get the copy of diferent directions or directories you can use the command **"cp -R"**, you can also put the line of all your directories starting in home and it will create a copy of everything
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
```
ls name_of_the_directory/
```
### FIND
The command used to search for files is called **find**.
```
find filename
```
### 

