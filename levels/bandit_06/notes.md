## Level progressions
#Example header lvl_1 -> lvl_2

#lvl_6 -> lvl_7

Objective: Find the password on a file somewhere in the server with a size of 33bytes, is owed by user "bandit7", and onwer by group "bandit6"

Commands used:cd /, find ./ -size 33c -user bandit7 -group bandit6 2> /dev/null

Important Flags: 2>/dev/null; the 2 stand for stderr, the > is a redirect operator, /dev/null is n "abyss" file that throws out any input.(Still not 100 percent sure WHAT it is, just know what it DOES.)

Why use it: I used 2>/dev/null because I didnt want to manually search through all the error outputs. It helped reduce clutter in the terminal so i can more easily find what I needed.
