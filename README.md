# Plugin-cvim
Plugin for those who use the vim text editor, which automates filling with the standard libraries (stdio.h) and (stdlib.h)


After downloading the file vim enter the directory where the file is to make it executable with the command:

chmod +x cvim

ready after that it will be executable, you can perform a test running command:

./cvim test.c

If it works, and it opens a vim with the libraries already, you can finish the process by adding cvim to the default directory folder:

sudo mv cvim /usr/bin/
