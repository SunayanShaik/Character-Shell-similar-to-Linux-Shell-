# Character-Shell-similar-to-Linux-Shell

Character-based Shell implementation using Facade design pattern. 

# Shell Application #

 ![Shell Demo](https://github.com/SunayanShaik/Character-Shell-similar-to-Linux-Shell-/blob/master/CUIShell.gif?raw=true)

# Shell Commands

Shell accepts the following commands:

• pwd - Print the current working directory.

• cd <dir name> - Change the current directory to the specified directory. 
                  Accept a relative (not absolute) directory name. 
                  Accept ".." (move to the parent directory of the current directory.)

• cd - Change the current directory to the root directory.

• ls - Print the name of every file, directory and link in the current directory.

• dir - Print the information (i.e., kind, name, size and owner) of every file, directory and link in the current directory.

• dir <dir/file name> - Print the specified directory’s/file’s information. Accept relative (not absolute) directory name. Accept ".."

• mkdir <dir name> - Make the specified directory in the current directory.

• rmdir <dir name> - Remove the specified directory in the current directory.

• ln <target (real) dir/file> <link (alias) dir/file> - Make a link

• mv <dir/file> <destination dir> - Move a directory/file to the detonation directory

• cp <dir/file> <destination dir> - Copy a directory/file to the destination directory

• chown - Change the owner of a file/directory

• history - Print a sequence of previously-executed commands.

• redo - Redo the most recently-executed command.

• sort - Sort directories and files in the current directory
