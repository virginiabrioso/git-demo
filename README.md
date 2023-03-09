# Notes from Git and GitHub Master Class By Shubham Londhe

Hello,
this repo intend to help me to practice git

## Commands:

1. ```git init```
This command is to create an empty git repository
2. ```git status```
It show to the user which branch and commit are they, also
show track/untrack files
---
**NOTE**

Branch &rarr; Is a ramification from a certain point of code. For general idea, imagine that git is a tree. The trunk would be the base code and braches are the ramifications based on this (note that not necessary every branch has to have the same base code).

---
3. ```git add . ``` or ```git add specificFile.txt```
It add files/file into a commit

4. ```git commit -m "message"```
The comment that goes to explain why/what you are changing.
For commits there are common patterns that most of developers are using. You can read more about this [here](https://github.com/helderberto/dotfiles/blob/main/git/.gittemplates/commitrkf)

5. ```git checkout -b develop```
Create a new branch named example