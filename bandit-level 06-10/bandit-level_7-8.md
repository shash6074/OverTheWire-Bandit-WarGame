# Bandit Level 7 → Level 8

## Level Goal
The password for the next level is stored in the file data.txt next to the word millionth

## Approach
To find here with having millionth word in it, here we have to use new command grep.

## Commands Used
all basic commads.
cat - display the content of the file.
find - finding the  file or directory using conditions.
grep - display the file which mathes the given pattern (word).

## Solution
To find the password use find commands with pattern given "millionth".
cmd: grep "millionth" data.txt -> used to find the password with pattern or starting word.

password: dfwvzFQL4mU0wfNbF0e9RoWskMLg7eEc

## Explanation
For this problem we have to use grep command which is used to  get the content of the file which as pattern given.
It uses Regular Expression to find the pattern or word.
grep -> stands for Global Regular Expression Print.
