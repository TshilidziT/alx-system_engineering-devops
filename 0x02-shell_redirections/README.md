#!/bin/bash
echo is a command used to print something in linux
cat displays content of a file
tail -n 10 displays last 10 lines of a file
head -n 10 displays first 10 lines of a file
head -3 filename | tail -1 displays third line of a file
echo -e contents > filename creates file with content inside
ls -la > filename writes results of command into a file
tail -n 1 filename >> filename
find . -type f -name "*.js" -delete removes specific file types
find . -mindepth 1 -type d | wc -l number of directories in current directories
ls -t -A | head -n 10 displays 10 newest files in current directory from new to old
sort | uniq -u Create a script that takes a list of words as input and prints only words that appear exactly once
grep "root" /etc/passwd Display lines containing the pattern “root” from the file /etc/passwd
grep -c 'bin' /etc/passwd Display the number of lines that contain the pattern “bin” in the file /etc/passwd
grep -A 3 root /etc/passwd Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
grep -v "bin" /etc/passwd Display all the lines in the file /etc/passwd that do not contain the pattern “bin”
grep "^[a-zA-Z]" /etc/ssh/sshd_config Display all lines of the file /etc/ssh/sshd_config starting with a letter including capital letters
echo "input" | perl -pe "s/A/Z/g; s/c/e/g"  Replace all characters A and c from input to Z and e respectively
