# Git Cheat Sheet
This document provides a list of common Git commands and their descriptions. Use these commands to work with Git in your projects.

## Configuration
- **Set User Information:**

  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"


- **View Git Configuration:**
  git config --list
  
## Repository Setup

- **Initialize a New Repository:**
  git init
  

- **Clone a Repository:**
  
  git clone <repository-url>


## Basic Workflow

- **Check Repository Status:**
  git status
  

- **Stage Changes:**
  git add <file(s)>
  

- **Commit Changes:**
  git commit -m "Your commit message here"
  

- **View Commit History:**
  git log
  

## Branches

- **Create a New Branch:**
  git branch <branch-name>
  

- **Switch Branch:**
  git checkout <branch-name>
  

- **Create and Switch to a New Branch:**
  git checkout -b <branch-name>
  

- **List Branches:**
  git branch
  

- **Merge a Branch:**
  git merge <branch-name>
  

- **Delete a Branch:**
  git branch -d <branch-name>
  

## Remote Repositories

- **Add a Remote Repository:**
  git remote add <remote-name> <repository-url>


- **Fetch Changes from a Remote Repository:**
  git fetch <remote-name>
  

- **Pull Changes from a Remote Repository:**
  git pull <remote-name> <branch-name>
  

- **Push Changes to a Remote Repository:**
  git push <remote-name> <branch-name>
  

## Undoing Changes

- **Discard Changes in Working Directory:**
  git restore <file>
  

- **Undo Staging:**
  git reset <file>


- **Revert to a Specific Commit:**
  git revert <commit-hash>


## Collaboration

- **Create a Pull Request:**
  - Fork the repository on GitHub.
  - Make changes in your forked repository.
  - Create a Pull Request from your fork to the original repository.

- **Review and Merge a Pull Request:**
  - Review the changes in the Pull Request.
  - Merge the Pull Request if changes are approved.

Use this cheat sheet to perform common Git operations in your projects. Remember to adapt these commands as needed for your specific use cases.
