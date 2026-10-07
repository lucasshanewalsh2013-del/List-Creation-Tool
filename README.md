# List-Creation-Tool
Something I made in 2025 for a project. Originally on my old acc, but I am reuploading it here too. Enjoy!

Usage:

Hey there! Thanks for downloading my tool! Here's the docs for how to use the tool!
To begin, here are the list of commands:

create
append
display
quit

and here are the different list types:

int (integers)
float (floating point numbers)
bool (booleans)
enum (enumerates)
char (strings/text)
container (contains other lists)

to use the command "create", you write the command, then the type of list. 
create int
create float
create bool
create enum
create char
create container

to use append, write the command, and then the name of the list.
(never append to containers, not implemented yet)
append int
append float
append bool
append enum
append char

then you are asked: to what list do you want to append to and what value? you then write the list id (for example: list1, list25, etc), and the value.
(make sure you append the right value or you'll get an error!)
list1 <value>
list25 <value>
etc

display shows the entire hierarchy of the main container.
container([intlist([25, 56, 63])boollist([true, false, false])])

quit exits out of the program safely.

Have fun!
