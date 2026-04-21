# Bandit Level 3 → Level 4

## Level Goal
The password for the next level is stored in a hidden file in the inhere directory.

## Approach
The Password for next level is stored in inhere directory and the file is hidden. 

## Commands Used
pwd - for checking the current working directory.
cd - go to the inhere directory.
ls - list all the files and folders.
cat - display the content of the file.

## Solution
To find the hidden file in any directory we need to use option called -a in ls command.
cmd: ls -l -a -> list the all the files and directories in detatils including hidden files.
cmd: cat "...Hiding-From-You" -> display the content from that file.

password: 2WmrDFRmJIq3IPxneAaMGhap@pFhF3NJ

## Explanation
In the inhere directory there will be only one file that is hidden and the filename is "...Hiding-From-You".
Used the simple commands to get the password.

