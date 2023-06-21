# FileManagerA1
README
This program is a longer version and more indepth version of Assignemnt1Part1. It differs as it takes a user input as opposed to a command line system arguemnts yet does
the same thing was part 1 with the exception of adding 3 new commands. It adds the commands R,D,C which all do different things. The R commands take a user inputted path and reads the contents
inside of the file. If the file doesn't have anything inside of it, it print("EMPTY") showing that the contents of the file are empty. The C commands creates a file and takes another use input
with the name of the file that wants to be created along with the path or directory which the user wants to put in there. The last new function is the D function which deletes the file with the extension
.dsu that is given by the user. Similarly it does the same things as part1. At the moment the code takes a directory given by the user and gives many options in order to specify what the user wants. The simple option is "L" which prints the contents of the directory 
given by the user. With the L command you are able to take 4 different options -r, -f, -s, -e. The -r sub-command prints every fire and directory recursively. This is the area I had trouble with
as I was not able to pair -r with other commands without having errors. This will be fixed in part 2 of the assigement. the -f function gives all the files excluding the directories from the given file path.
The -s function takes another user parameter with a full example.exe file path and prints all the matches with that file path in a full directory. The -e function lets you give an extension
to which it prints all the files in a directory with that extension.
