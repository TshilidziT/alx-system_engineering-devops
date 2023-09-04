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
