## Creating a new repository
git init
git add .
git commit -m "message"
git remote add origin <url>
git branch -M main
git push -u origin main

## Wokring with local changes
git status
git add .
git add -p <file>
git commit -m "mess"

## Viewing History
git log 
git log -p <file>
git blame <file>

## Branching and Merging
git branch -av
git branch <new-branch>
git checkout <branch>
git merge <branch>

## Undoing Changes
git reset --hard HEAD
git checkout HEAD <file>
git revert <commitId>

## Additional Essential Commands

### Cloning a repository

git clone <url>

### Pulling Changes from remote
git pull origin main

### Stashing Changes

git stash
git stash list
git stash apply
git stash drop

### Tagging
git tag <tag-name>
git tag
git push origin <tag-name>

### Viewing Differences
git diff
git diff HEAD

### Deleting branches
git branch -d <branch>
git branch -D <branch>

### Working with remotes
git remote -v
git remote add <name> <url>
git remote remove <name>

