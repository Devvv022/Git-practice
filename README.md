# Git-practice
# Git Learning Repository

This repository contains the Git commands that I practiced while learning version control.  
It includes basic operations like creating commits, managing branches, and working with remote repositories.

---

## 1. Repository Setup

- `git init`  
  Used to start a new Git repository in a folder.

- `git status`  
  Displays the current state of files and shows which files are staged or unstaged.

---

## 2. Tracking Changes

- `git add <file>`  
  Adds a particular file to the staging area.

- `git add .`  
  Adds all modified files to the staging area at once.

- `git commit -m "message"`  
  Saves the staged changes in the repository history with a message.

- `git log`  
  Shows the full history of commits.

- `git log --oneline`  
  Displays commit history in a shorter format.
  ## 3. Working with Branches

Branches allow multiple versions of a project to be developed independently.

- `git branch`  
  Lists all the branches present in the repository.

- `git branch <branch-name>`  
  Creates a new branch.

- `git checkout <branch-name>`  
  Moves the working directory to another branch.

- `git checkout -b <branch-name>`  
  Creates a new branch and switches to it immediately.

- `git branch -d <branch-name>`  
  Deletes a branch that is no longer needed.