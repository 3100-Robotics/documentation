# Git

## Status

View the local branches.

    git branch
    
View staged and unstaged files. Staged is in greed, unstaged in red

    git status
    
View commit history for branch

    git log --graph
    
View commit history for entire repo

    git log --graph --all
    
## Push, Fetch, Pull from remote
    
To push changes to a remote repo
 
    git push origin <branch name>
    
To pull changes from remote repo

    git pull origin <branch name>
    
To fetch the state of the remote repo (new branches, etc)

    git fetch origin
    
## Stage/Unstage

Stage all changes

    git add --all
    
or 

    git add .
    
Stage a specific file

    git add <file name>
    
Unstage a specific file

    git reset HEAD <name of file>
    
## Commiting 

To commit all staged changes

    git commit -m '<commit message>'
    
To commit all changes, staged and unstaged

    git commit -am '<commit message>'
    
To revert a commit

    git revert <commit id>
    
## Branching

To create a new branch from the current one

    git checkout -b <new branch name>
    
To checkout an existing branch

    git checkout <branch name>
    
To delete a local branch

    git branch -D <branch name>
    
To merge a branch into the current one

    git merge <branch name> -m '<commit message>'
