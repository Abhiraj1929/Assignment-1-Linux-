# Assignment-1-Linux

Google Docs Assignment link - https://docs.google.com/document/d/17uUEUagRuiRKIANIJTBgwTYYqfzQ2VCRM1rhrf5ypg4/edit?usp=sharing


Explaination 1

The mkdir (make directory) command is used to create a new directory.


The Touch command creates a new file. So we created the file name called example.txt


The mv (move) command can be used to either move a file to a different directory or rename it. Therefore, Renamed example.txt to renamed_example.txt.


Explaination 2

The cat (concatenate) command reads data from files and outputs their contents to the standard output. This command will display the entire content of the /etc/passwd file, which contains user account information.


The head command, by default, shows the first 10 lines of a file. The -n option allows you to specify a different number of lines. This command will display only the first 5 lines.



the tail command shows the last 10 lines of a file by default. The -n 5 option modifies this to show only the last 5 lines.


Explaination 3

The grep (global regular expression print) command searches for a specified pattern in a file and prints the lines that contain it. This command will find and display every line in /etc/passwd that contains the string "root"


Explaination 4

The zip command is used to compress files. The -r option is crucial here, as it stands for "recursive" and ensures that the command includes all files and subdirectories within test_dir.


The unzip command extracts files from a ZIP archive. The -d option allows you to specify a destination directory where the files will be extracted. If unzipped_dir doesn't exist, unzip will create it.


Explaination 5

wget is a command-line utility for downloading files from the web. It is non-interactive, meaning it can run in the background.


Explaination 6
Explanation: First, create an empty file named secure.txt. The chmod (change mode) command changes the permissions of a file. The numbers represent permissions for the owner, the group, and everyone else, respectively.

Explaination 7
To verify that the variable was set, you can use the echo command. The $ prefix is used to access the value of a variable. This command will print "Hello, Linux!" to the console.

