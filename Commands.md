<h1 align="center">Linux/Unix Commands</h1>

## Listing Files
-`ls`\
-If you want to see the list of files on your UNIX or Linux system, use the `ls` command

## Creating & Viewing Files
-To create a new file, use the command\
1.`cat > filename`\
2.Add content\
3.Press `ctrl + d` to return to command prompt.\
-To view a file, use the command\
`cat filename`

## Searching for content in a file/ files in a directory
- To search for a word in a file using terminal,use the command ```grep```
- For eg., if you want to search for the word GNU in a file named ```GNU.txt```,type ``` grep GNU GNU.txt```
- This will show all lines which have the word ```GNU``` in that file
- To search over multiple files in a directory, use ```grep``` with ```-r``` flag, like ``` grep -r GNU .```. Here ```-r``` stands for recursive search and ```.``` specifies the search root to be the current directory.


## Updating, Installing and Listing applications

The commands for installing and updating applications depend on the version of Linux you are using, specifically whether it's Debian- or RPM-based.

* Debian Based systems
  - Update the list of available packages and their versions, but doen not install or upgrade any packages. use the command ```sudo apt update```
  - Install newer versions of installed packages,use the command ```sudo apt upgrade```
  - Install any required package,use ```sudo apt install 'your package name'```. Example: ```sudo apt install apache2```
  
* RPM-based systems
  - Update all or specified packages,use ```sudo yum update```. Example for updating specific package: ```sudo yum update mysql```
  - Lists known and installed packages,use ```sudo yum list``` ```sudo yum list --installed```
  - Install requested package,use ```yum install```. Example: ```sudo yum -y install firefox```
  
