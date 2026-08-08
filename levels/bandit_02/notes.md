## Level progressions
#Example header lvl_1 -> lvl_2

#lvl_2 -> lvl_3

Objective: Find the password in the file named '--spaces in this filename--' in the home directory

Commands used: cat ./--spaces\ in\ this\ filename--

*Notes: The important concept here is called character escaping. \ lets BASH know to treat the next character as a normal char instead of assigning its usual special meaning, useful for bypassing spaces which are seen as argument seperators.
