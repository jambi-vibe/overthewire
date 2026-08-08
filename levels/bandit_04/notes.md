## Level progressions
#Example header lvl_1 -> lvl_2

#lvl_4 -> lvl_5

Objective: Find the password stored in the only human-readable file in the 'inhere' directory

Commands used: for x in {00..09}; do file ./-file$x; done, cat ./-file07

I used a for loop to iterate over file to check its file contents. Then i displayed the only human readable file(-file07)
