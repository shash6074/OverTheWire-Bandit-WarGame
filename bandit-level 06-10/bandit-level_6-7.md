# Bandit Level 6 → Level 7

## Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties:
-> owned by user bandit7
-> owned by group bandit6
-> 33 bytes in size

## Approach
The Password for next level is stored somewhere in host server and the filename as some conditions.
using below commands we can get the password same as previous one.

## Commands Used
pwd - for checking the current working directory.
cd - go to any directory.
ls - list all the files and folders.
cat - display the content of the file.
find - finding the  file or directory using conditions.

## Solution
To find the password use find commands with condition size as 33 bytes.
cmd: find -type f -size 33c -user bandit7 -group bandit6 -> for specific size, user and group.

password: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

## Explanation
Finding the file which as 33 bytes of size using find commands with size conditions.
The file is stored somewhere in root using find command with above contions can get the password easily.
There are many files which contains above three same conditions and having permission denied for all except the password file.
