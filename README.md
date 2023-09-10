# Git-Task
# Git Commands 

This README provides Git Commands used in Git-Task.

```bash
# Initialize a Git Repository
git init

# Staging Changes
git add .
git add readme.md

# Committing Changes
git commit -m "<commit_message>"

# Managing Branches
git branch -M main

# Setting Up Remote
git remote add origin <repository_url>

# Viewing Remote Information
git remote -v

# Pushing Changes
git push -u origin main

# Pulling Changes
git pull origin master

# Checking Status
git status

# Amending the Last Commit Message
git commit --amend -m "<new_commit_message>"

# Committing All Changes
git commit -a -m "<commit_message>"

# Viewing Commit History
git log

# Viewing Unstaged Changes
git diff

# Viewing Staged Changes
git diff --staged

# Unstaging a File
git restore --staged <file_name>

# Undoing the Last Commit (Keep Changes)
git reset --soft HEAD^

# Undoing the Last Two Commits (Keep Changes)
git reset --soft HEAD^^

# Undoing the Last Commit (Discard Changes)
git reset --hard HEAD^

# Cloning a Repository
git clone <repository_url>
