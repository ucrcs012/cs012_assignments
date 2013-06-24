cs010_assignments
=================

The CS010(v) assignments repository is used to set up a students Cloud 9 
private workspace.


Example commands to work on an assignment.

In the Terminal window, start by changing to the assignment directory. Linux 
gives us the "cd" command with the argument of the folder.

cd assignment00


Once in the directory, listing all the file in the folder can be done with the
"ls" command.

ls                                                         


In assignment00, a hello_world.cpp file exists. To compile this file, use the
following command.

g++ hello_world.cpp


The g++ compiler creates a new file called "a.out" by default. The file can be
executed by the following method:

run a.out
OR 
run a.out 10

The second run command executes the program for 10 seconds. This is useful when 
the program requires user input and takes longer than 5 seconds to execute.


To go back to the top level home directory we utilize an aliased command "home".

home