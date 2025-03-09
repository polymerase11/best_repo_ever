# Git Commands Cheat Sheet

## Repository Setup
- `git init` → Initialize a new Git repository
- `git clone <repo-url>` → Clone an existing repository

## Staging & Committing
- `git status` → Check the status of changes
- `git add <file>` → Stage a specific file
- `git add -A` → Stage all changes
- `git commit -m "message"` → Commit staged changes
- `git commit -a -m "message"` → Stage and commit modified files (excluding untracked ones)

## Branching & Merging
- `git branch` → List branches
- `git branch <branch-name>` → Create a new branch
- `git checkout <branch-name>` → Switch to a branch
- `git merge <branch-name>` → Merge a branch into the current branch

## Remote Repositories
- `git remote -v` → Show remote repositories
- `git push origin <branch>` → Push changes to GitHub
- `git pull origin <branch>` → Pull latest changes from GitHub
