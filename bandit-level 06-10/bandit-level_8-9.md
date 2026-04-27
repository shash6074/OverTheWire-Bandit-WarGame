# Bandit Level 8 → Level 9

## Level Goal
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

## Approach
To find, here we can use new commamds : uniq -> it will find the unique content, with sort commands.

## Commands Used
all basic commads.
uniq -> it will find unique  contents in file with its -u options.
sort -> it sorts the all the contents of the file accordingly.

## Solution
to find password that is occured only once.
use  cmd : sort data.txt | uniq -u
this uniq works if first command works 

password: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

## Explanation
Finding the password content that apperars only once in file contents, the file data.txt has many passwards in it and some are occured 2 or more times but the 
actual password occurs only once that we need to find.
command called uniq -u help to find the unique contents sort command will prints the sorted content of file.
