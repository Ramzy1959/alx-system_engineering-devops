pwd; this prints the current working directory
ls; this displays the content lists of the working directory
cd ~; this is used to change the working directory to user's home directory
ls -l; this is used to contents of current directory in a long format
ls -al; this is used to display current directory contents, including hidden files
ls -lna this is used to current directory's content in a long format, user and group IDs displayed numerically
and hidden files.

mkdir; this is the command used to create a directory

mv; this command is used to move a file from one directory to another

rm; this is used to delete a file

rm -r; this ia command used to delete a directories with contents forcefully.
cd -; this is command is used to change the working directory to the previous one.
ls -al . ..; this command is used to list hidden files of the current directory and the directory before it, all in a long format
file; this command is used to print a file
cp -un *.filename ../;  script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [[:upper:]]*; this is command used for moving upper case files
rm *~; this is a command used to delete all files in the current working directory that end with the character ~.
mkdir -p, this is a command used to create directories with slash
ls -amvp; a command that lists all the files and directories of the current directory, separated by commas (,).



Directory names should end with a slash (/)

Files and directories starting with a dot (.) should be listed

The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning

Only digits and letters are used to sort; Digits should come first

You can assume that all the files we will test with will have at least one letter or one digit

The listing should end with a new line 
