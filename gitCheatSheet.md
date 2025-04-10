# Git Cheat Sheet

## Basic Commands
- `git init` - Initialize a new Git repository.
- `git clone <url>` - Clone a repository from a remote source.
- `git status` - Check the status of your working directory.
- `git add <file>` - Stage a file for commit.
- `git add .` - Stage all changes in the current directory.
- `git commit -m "message"` - Commit staged changes with a message.
- `git log` - View commit history.

## Branching
- `git branch` - List all branches.
- `git branch <branch-name>` - Create a new branch.
- `git checkout <branch-name>` - Switch to a branch.
- `git checkout -b <branch-name>` - Create and switch to a new branch.
- `git merge <branch-name>` - Merge a branch into the current branch.

## Remote Repositories
- `git remote add origin <url>` - Add a remote repository.
- `git push -u origin <branch-name>` - Push changes to a remote branch.
- `git pull` - Fetch and merge changes from the remote repository.
- `git fetch` - Fetch changes from the remote repository without merging.

## Undo Changes
- `git reset <file>` - Unstage a file.
- `git reset --hard` - Reset the working directory and staging area to the last commit.
- `git revert <commit-hash>` - Revert a specific commit.

## Stashing
- `git stash` - Save changes for later.
- `git stash apply` - Reapply stashed changes.
- `git stash list` - List all stashes.

## Tagging
- `git tag <tag-name>` - Create a new tag.
- `git tag` - List all tags.
- `git push origin <tag-name>` - Push a tag to the remote repository.

## Miscellaneous
- `git config --global user.name "Your Name"` - Set your Git username.
- `git config --global user.email "you@example.com"` - Set your Git email.
- `git diff` - Show changes between commits, branches, or the working directory.
- `git rm <file>` - Remove a file from the repository.
