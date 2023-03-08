#!/bin/bash
0-current_working_directory: script that prints the absolute path name of the current working directory.
1-listit: script lists content of curernt directory.
2-bring_me_home:  script that changes the working directory to the home directory.
3-listfiles: script to diplay current directory contents in long format.
4-listmorefiles: script to display current directory contents and hidden files with .
5-listfilesdigitonly: script to display current directory contents long format, with user and group id's and hidden files.
6-firstdirectory: script creates directory my_first_directory  in /tmp.
7-movethatfile: script moves the betty file from /tmp/ to /tmp/my_first_directory.
8-firstdelete: script deletes betty file.
9-firstdirdeletion: script deletes directory my_first_directory from /tmp
10-back: script to change current working directory to previous one.
11-lists: script that lists all files. The hidden ones in the current and the parent of the working directory and the /boot directory in this order, in long format.
12-file_type: script that prints the type of the file named iamafile in /tmp.
13-symbolic_link:  script that creates a symbolic link to /bin/ls named __ls__
14-copy_html: script that copies all the HTML files from the current working directory to the parent of the working directory. Only files that  did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
100-lets_move: script that moves all files beginning with an uppercase letter to the directory /tmp/u.
101-clean_emacs: script that deletes all files in the current working directory that end with the character ~.
102-tree: script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
103-commas: script that lists all the files and directories of the current directory, separated by commas.
	Directory names end with a slash (/)
	Files and directories starting with a dot should are listed
	The listing is alpha ordered, except for the directories . and .. which are listed at the very beginning
	Only digits and letters are used to sort; Digits come first.
	The listing ends with a new line
