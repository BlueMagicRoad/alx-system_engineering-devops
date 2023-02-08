This directory contains the following scripts:

0-current_working_directory - Script prints the absolute path name of the current working directory (pwd)  
1-listit - Script prints the contents of the current directory (ls)  
2-bring_me_home - Script returns user to their designated home directory (cd ~)  
3-listfiles - Script prints the current directory's contents in the long format (ls -l)  
4-listmorefiles - Script prints the current directory's contents, including hidden content, in the long format (ls -a -l)  
5-listfilesdigitonly - Script prints prints the current directory's contents, including hidden content, in the long format, with user and group IDs displayed numerically (ls -l -n -a)  
6-firstdirectory - Script creates a new directroy (my_first_directory) in the directory 'tmp' (mkdir /tmp/my_first_directory)  
7-movethatfile - Script is moves the file 'betty' from the directory 'tmp' to 'tmp/my_first_directory' (mv /tmp/betty /tmp/my_first_directory)  
8-firstdelete - Script deletes the file 'betty' from the directory 'tmp/my_first_directory' (rm /tmp/my_first_directory/betty)  
9-firstdirdeletion - Script deletes the directory 'my_first_directory' (rm -r /tmp/my_first_directory)  
10-back - Script changes the working directory to the previous one (cd -)  
11-lists - Script prints all files, including hidden files, in the long format, in the order of current directory, parent directory and 'boot' (ls -a -l . .. /boot)  
12-file_type - Script checks the file type of the file 'iamafile' in the directory 'tmp' (file /tmp/iamafile)  
13-symbolic_link - Script creates a symlink called __ls__ for '/bin/ls' (ln -s /bin/ls __ls__)  
14-copy_html - Script prints  
