## Level progressions
#Example header lvl_1 -> lvl_2

#Lvl_0

Objective: Log into bandit0 machine as bandit0@bandit.labs.overthewire.org on port 2220

Commands used: ssh -p 2220 bandit0@bandit.labs.overthewire.org

Important Flags: -p; allows you to specify the port number you want to connect through.
Why -p is important: If you have a service listening on a specific port, you can connect directly to that service through that port. Changing the port from the default can be used to hide a service from basic automated scripts that search for common open ports(443, 80, 22, etc.)

#lvl_0 -> lvl_1

Objective: Find the password stored in a file called 'readme' on the home directory

Commands used: ls -a -h -l, file readme, cat readme

Important Flags: ls {-a; lists all files, including hidden files with ., -h; makes the listing more easily readable by a human, -l; is long listing format which includes file/directory permissions and owners}

