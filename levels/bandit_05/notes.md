## Level progressions
#Example header lvl_1 -> lvl_2

#lvl_5 -> lvl_6

Objective: Find the password in a file somewhere in the "inhere" directory with these properties: human-readable, 1033 bytes in size, not executable

Commands used: find ./inhere/ -type f -size 1033c ! -executable

Important Flags: -type f; sets it to only look for files ,-size xxxxc; filters by a specific size "c" means specifically bytes, !; means not, -executable; tests to see if the user has execution permissions
