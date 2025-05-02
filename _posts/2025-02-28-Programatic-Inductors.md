---
title: "Programatic Inductors"
date: 2025-02-28
---



Say a certain file is created on a main branch on github as well as a test branch. 
I then delete the file from the main branch.
If merge a pull request from the test branch to the main branch, will the main branch have the certain file again or not?

Every branch consists of a chain of commits or updates.
Therefore, despite the test branch having more content (the file in question) when compared to the main, the main has more commits which can be thought of a blockchain. 
In other words the main has both the commit to create the file and the commit to delete it. 
Therefore I can make a pull request from main to test (base test < compare main) to delete the file in the test branch.
But I cannot make a pull request from test to main (base main < compare test) to re-add the file to the main branch.

https://drive.google.com/file/d/1eC4eOhP9MKdzQVdu4ZsE486uPrYvSdPq/view
