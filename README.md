# Hello, this repo intend to help me to practice git

## Notes from Git and GitHub Master Class By Shubham Londhe

### Commands

1. ```git init```
This command is to create an empty git repository

2. ```git remote add origin https://github.com/virginiabrioso/repoName.git```
Create a new repository on the command line or connect folder to an existing repository

3. ```git add .``` or ```git add specificFile.txt```
It add files/file into a commit

4. ```git commit -m "message"```
The comment that goes to explain why/what you are changing.
For commits there are common patterns that most of developers are using. You can read more about this [here](https://github.com/helderberto/dotfiles/blob/main/git/.gittemplates/commitrkf)

5. ```git branch develop```
Create new branch locally

#### Note

Branch &rarr; Is a ramification from a certain point of code. For general idea, imagine that git is a tree. The trunk would be the base code and braches are the ramifications based on this (note that not necessary every branch has to have the same base code).

6. ```git push -u https://github.com/virginiabrioso/repoName.git develop```
Push the new branch into the remote repository

7. ```git push```
or ```git push origin main```
or ```git push origin HEAD:refs/for/develop```
Publish your commit

#### Note

The first time you push to your remote do it like so:

```git push -u origin develop```

The -u flag stands for ```--set-upstream```.  After the first time you only need to do it like this:

```git push```

8. ```git branch -M main```
Current Branch will be renamed Main, even if this Branch already exists

9. ```git branch -d develop```
Delete branch

10. ```git checkout -b develop```
Create change to branch develop, it create if not exist

11. ```git pull```
Get updates from the remote repo and brings those changes from the remote.

12. ```git pull origin master --rebase```
Update the base code of your commit to the most recent version of base code

13. ```git fetch```
Retrieve the latest meta-data info from the original (but doesn’t do any file transferring)

14. ```git merge develop```
Merge your feature branch into branch base

15. ```git status```
It show to the user which branch and commit are they, also
show track/untrack files

16. ```git cherry-pick commitSha```
Move a commit from one branch to another.

17. ```git stash```
Saves uncommitted changes

18. ```git stash apply```
Take the changes you have stored in a stash and apply them to the working directory

19. ```git stash pop```
Same as above, but it delete the stash after the changes have been applied

20. ```git stash clear```
Delete all saved stash
