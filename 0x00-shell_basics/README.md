#!/bin/bash
pwd prints the absolute path name of the current working directory
ls displays the contents list of your current directory
cd ~ is used to change from current working directory to user's home directory
ls -l displays current directory contents in a long format
ls -a -l displays current directory contents, including hidden files (starting with .). Use the long format.
ls -lan displays current directory contents,long format,with user and group IDs displayed numerically and hidden files
mkdir /tmp/my_first_directory Create a script that creates a directory
mv /tmp/betty /tmp/my_first_directory moves files from one directory to another
rm /tmp/my_first_directory/betty  Deletes file betty inside the my_first_directory
rmdir /tmp/my_first_directory to delete a directory inside another director
cd - changes the working directory to previous one
ls -la . .. /boot command to list all files in long format in current directory and parent directory
file /tmp/iamafile command to print the type of file named
ln -s /bin/ls __ls__ command to create a symbolic link betweeen files
cp -u *.html ../  command to copy all HTML files from current to parent directory
