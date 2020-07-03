# GitUtils
Helpful cheat sheat for git commands

## Terminal Commands
Stage all changes (aka the step before commit):

    git add .

Commit your staged changes

    git commit -m "<a good commit message>"

Switch to a new branch: 

    git checkout <branch name>

Create a new branch (feature branch):

    git checkout -b <branch name>

Retrieve latest changes from master:  
Checkout master branch, then run the  following command

    git pull origin master

Push a local branch up to Github:

    git push origin <branch name>

Delete a branch:

    git branch -D <branch name>

Stashing changes:
Stashing temporarily stores any changes you haven't commited.

    git stash

Unstashing allows you to re-apply your changes to the current branch (does not affect other branches)

    git stash pop






