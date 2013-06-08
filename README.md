cs010_assignments
=================

The CS010(v) assignments repository is used to set up your Cloud 9 
**private** workspace 
*(you may never collaborate on programming assignments, so this workspace has to be private!)*


**Here are some commands you'll need to work on your assignments:**

In the Terminal window, start by changing to the assignment directory. 
Linux gives us the "cd" command *(meaning "change directory to folder_name")*:

cd assignment00

Once in the directory, you can list all the files in the folder with the "ls" command *("list")*:

ls                                                         

In assignment00, you'll find the file hello_world.cpp, which is a plain text file containg C++ source code.
To compile it into an "executable" (a binary file that is a "runnable" program), launch the compiler with the
following command:

g++ hello_world.cpp

The g++ compiler creates a new file, the executable, called "a.out" by default.
Note that to run it, you must use the initial "./" as follows 
*(this tells the system to look for a.out in the current directory, rather than among the system files)*:

./a.out

