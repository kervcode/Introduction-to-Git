# Introcduction to Git

### Introduction

- To run git : git example = > `git --help`

- `git clone` and `git init` used to setup new repositories.

- `git add`, `git status` and `git commit`: used to when commiting new versions of files

- `git log` view a list of old commits
`git mv` for git move and `git rm` for git remove are used repectively to move and remove files tracked by Git.

- `git push` and `git pull` are used to synchronize commits with remote repositories.

### Initializing a repository

- Their are two ways to get a new repository on a computer

1. is to clone it
    
2. Create a repository 
  steps to create new repo
    - `git init`
      this will initialize the repository in the current directory
      Every file goes through three states in a git repository
        - Modified
        - Staged
        - Commited
    - `git status` can be used to check which state a file in a repo is
    
    - `git commit` uses the `-m` flag. m for message
    
    - `git config --global user.email "example@email.com"
    
    - `git config --global user.name "Kervintz Noel"
    
    - `git log` reveal commits
    
### Viewing changes to a file

  - `git diff` To view change files in the stage area.
  
  - `git diff --staged` To compare staged changes against the previous commit
  
### Removing Files

- `git rm` to remove files in repositories

- `git mv` can be used to rename files or move them
    - ex: `git mv index.txt index.html`
    
### Unstaging Changes

- `git reset HEAD filename` to unstage`

### Discarding File Modifications

- `git checkout -- filename` to discard changes in working directory

### Undoing File Deletions

 Same comment for discarding file
 
### Commit Shas and Undoing commits

  #### shas
      - DEF: Simple Hashing Algorithm
      
 - `git revert xxxxx` x represent 5 first characters in the commit
 
 - `git revert HEAD` in this command, HEAD means the most recent commit
 
### Cloning a Repository



### Pulling changes

- `git pull` or `git pull origin`







