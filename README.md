# Git Practice Repository :arrows_counterclockwise:

This repository serves as a way for me to practice using Git and GitHub. 
It contains notes from the 
[Git and GitHub Master Class by Shubham Londhe](https://www.youtube.com/watch?v=AT1uxOLsCdk&list=PLlfy9GnSVerRqYJgVYO0UiExj5byjrW8u&index=2), 
as well as some commands that I have been practicing.

## Commands :computer:

Here are some of the Git commands and its descriptions:

- `git init`: Creates an empty Git repository
- `git remote add origin https://github.com/virginiabrioso/repoName.git`: Creates a new repository on the command line or connects a folder to an existing repository
- `git add .` or `git add specificFile.txt`: Adds files to a commit
- `git commit -m "message"`: Adds a comment that explains why/what you are changing
- `git branch develop`: Creates a new branch locally
- `git push -u https://github.com/virginiabrioso/repoName.git develop`: Pushes the new branch into the remote repository
- `git push` or `git push origin main` or `git push origin HEAD:refs/for/develop`: Publishes your commit
- `git branch -M main`: Renames the current branch to main, even if this branch already exists
- `git branch -d develop`: Deletes a branch
- `git checkout -b develop`: Creates a change to the develop branch, creating it if it doesn't exist
- `git pull`: Gets updates from the remote repo and brings those changes from the remote
- `git pull origin master --rebase`: Updates the base code of your commit to the most recent version of base code
- `git fetch`: Retrieves the latest metadata info from the original (but doesn’t transfer any files)
- `git merge develop`: Merges your feature branch into the base branch
- `git status`: Shows the user which branch and commit they are on, as well as tracked/untracked files
- `git cherry-pick commitSha`: Moves a commit from one branch to another
- `git stash`: Saves uncommitted changes
- `git stash apply`: Takes the changes you have stored in a stash and applies them to the working directory
- `git stash pop`: Same as above, but deletes the stash after the changes have been applied
- `git stash clear`: Deletes all saved stashes

## Notes :pencil2:

- Branch: A ramification from a certain point of code. For a general idea, imagine that Git is a tree. The trunk would be the base code, and branches are the ramifications based on this (note that not every branch has to have the same base code).
- For commits, there are common patterns that most developers use. You can read more about this [here](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53).
- The first time you push to your remote, do it like this: `git push -u origin develop`. The `-u` flag stands for `--set-upstream`. After the first time, you only need to do it like this: `git push`.
