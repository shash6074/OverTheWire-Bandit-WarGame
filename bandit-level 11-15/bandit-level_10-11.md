# Bandit Level 10 → Level 11

## Level Goal
The password for the next level is stored in the file data.txt, which contains base64 encoded data.

## Approach
its simple to find the password use base64 command to option -d to decode the file content.

## Commands Used
all basic commads.
base64 -> it will converts the binary contents to human reabable content.

## Solution
to find password that is human readable.
use  cmd : base64 -d -> decodes the file contents to reable format.

password: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

## Explanation
Using the base64 command with -d its option will decode the contents of the file data.txt.
it will show the password.
