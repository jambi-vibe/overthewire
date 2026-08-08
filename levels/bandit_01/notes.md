## Level progressions
#Example header lvl_1 -> lvl_2

#lvl_1 -> lvl_2

Objective: Find the password in a file named '-' store on the home directory

Commands used: ls -a, cat ./-

Important FLags: -a; used to list all files/directories in the current directory, even ones hidden with .

*Notes: '-' is an uncommon naming convention. You cannot use cat <filename> with this as cat read '-' as a command flag. Using ./- specifies its a filename with a specific path. Alternative: -- <filename>; '--' tells cat to stop reading the following as command options
