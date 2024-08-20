## Creating a new repository
git init <br>
git add .  <br>
git commit -m "message"  <br>
git remote add origin <url>  <br>
git branch -M main  <br>
git push -u origin main  <br>

## Wokring with local changes
git status  <br>
git add .  <br>
git add -p <file>  <br>
git commit -m "mess"  <br>

## Viewing History
git log  <br>
git log -p <file>  <br>
git blame <file>  <br>

## Branching and Merging
git branch -av  <br>
git branch <new-branch>  <br>
git checkout <branch>  <br>
git merge <branch>  <br>

## Undoing Changes
git reset --hard HEAD  <br>
git checkout HEAD <file>  <br>
git revert <commitId>  <br>

## Additional Essential Commands

### Cloning a repository

git clone <url>  <br>

### Pulling Changes from remote
git pull origin main  <br>

### Stashing Changes

git stash  <br>
git stash list  <br>
git stash apply  <br>
git stash drop  <br>

### Tagging
git tag <tag-name> <br>
git tag <br>
git push origin <tag-name> <br>

### Viewing Differences <br>
git diff <br>
git diff HEAD <br>

### Deleting branches
git branch -d <branch> <br>
git branch -D <branch> <br>

### Working with remotes
git remote -v <br>
git remote add <name> <url> <br>
git remote remove <name> <br>

