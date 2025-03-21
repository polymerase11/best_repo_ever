# Git Commands Cheat Sheet

## Repository Setup
- `git init` -> Initialize a new Git repository
- `git clone <repo-url>` -> Clone an existing repository
- `touch "filename.txt"` -> Creates a new file 
- `nano "filename.txt` -> Edit the file

## Staging & Committing
- `git status` -> Check the status of changes
- `git add <file>` -> Stage a specific file in the staging area
- `git add -A` -> Stage all changes
- `git commit -m "message"` -> Commit staged changes
- `git commit -a -m "message"` -> Stage and commit modified files (excluding untracked ones)
- `git remote -v`-> shows the server adress where git thinks you want to push to
- `git remote set-url origin <remot-url>` -> sets up the repo you want to push to 

## Branching & Merging
- `git branch` -> List branches
- `git branch <branch-name>` -> Create a new branch
- `git checkout <branch-name>` → Switch to a branch
- `git checkout -- .` -> Restores every file 
- `git merge <branch-name>` → Merge a branch into the current branch

## Remote Repositories
- `git remote -v` → Show remote repositories
- `git push origin <branch>` → Push changes to GitHub
- `git pull origin <branch>` → Pull latest changes from GitHub
