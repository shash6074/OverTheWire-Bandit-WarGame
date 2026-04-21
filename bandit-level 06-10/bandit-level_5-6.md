# Bandit Level 5 → Level 6

## Level Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:
-> human-readable
-> 1033 bytes in size
-> not executable 

## Approach
We have the condtions which password is human readable and having 1033 bytes of size and its not having executable permisssion. 
To get the password use commnads below.

## Commands Used
pwd - for checking the current working directory.
cd - go to the inhere directory.
ls - list all the files and folders.
cat - display the content of the file.
find - find the file or directory.

## Solution
To find the file having size 1033.
cmd: cd inhere -> go to inhere directory
cmd: find ./ -type f -size 1033c -> used to find 1033 byte sized file or directory only in regular file.
-> ./ says finding in current working directory.

password: HWasnphtq9AVKe0dmk45nxy20cvUa6EG

## Explanation
To find the password for next level we need to used find command with some of them options; -type f says find a regular file;
-size <size>c says exact size in bytes 'c' for bytes, 'm' for mb and goes on.
