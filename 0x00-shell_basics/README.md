pwd-prints the absolute path name of current working directory
Displays the absolute path at any given time when command is entered
ls-Display the contents list of your current directory
cd~-changes the working directory to the user’s home directory
ls -l  Display current directory contents in a long format
ls -al     Display current directory contents, including hidden files and using long format
ls -lna    mandatory
Display current directory contents.

Long format
with user and group IDs displayed numerically
And hidden files (starting with
mkdir /tmp/my_first_directory    Create a script that creates a directory named my_first_directory in the /tmp/ directory
mv /tmp/betty /tmp/my_first_directory         Move the file betty from /tmp/ to /tmp/my_first_directory
rm /tmp/my_first_directory/betty            Delete the file betty
rm -r /tmp/my_first_directory    Delete the directory my_first_directory that is in the /tmp directory
cd -         changes the working directory to the previous one
ls -al . .. /boot    mandatory
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
file /tmp/iamfile
prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script
ln -s /bin/ls __ls__                  Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory
