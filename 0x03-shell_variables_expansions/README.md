#!/bin/bash
alias [name]='[value]'creating an alias
echo "Hello $(whoami)" printing Hello username
export PATH="$PATH:/action"Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
find $PATH -type d | wc -l Create a script that counts the number of directories in the PATH
set Create a script that lists all local variables and environment variables, and functions.
local var=value a script that creates a local variable
