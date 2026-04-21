# Bandit Level 2 → Level 3

## Level Goal
The password for the next level is stored in a file called --spaces in this filename-- located in the home directory.

## Approach
The Password for next level is stored in home directory with spaces in filename. 

## Commands Used
pwd - for checking the current working directory.
cd - go to the home directory.
ls - list all the files and folders.
cat - display the content of the file.

## Solution
I found the filename called "--spaces in this filename--" in the current working directory.
used cmd: cat "./--spaces in this filename--" to display the password written in that file.
we can also use the command cmd: cat --"--spaces in this filename--".

password: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

## Explanation
The filename as spaces in it, to find the content of that file.
simply type cat "./--spaces in this filename--" it displayes the password in the present working directory for the next level.
cmd: cat "./--spaces in this filename--" will display the content forcefully.
and cmd: cat --"--spaces in this filename--" will stop using options or it does not recognize it is option.

