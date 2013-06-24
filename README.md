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

run a.out
OR 
run a.out 10

The second run command executes the program for 10 seconds. This is useful when 
the program requires user input and takes longer than 5 seconds to execute.


To go back to the top level home directory we utilize an aliased command "home".

home
