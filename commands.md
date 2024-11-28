# Git Commands

## Basic Terminal Commands
- Clear screen: `clear`
- Print current working directory: `pwd`
- List files in a directory: `ls -a`, `ls -ltr`

## Git Installation
- Install Git: `yum install git`
- Install Git with sudo: `sudo yum install git`
- Check Git version: `git --version`

## Directory Management
- Create a directory: `mkdir git`
- Rename or move a directory: `mv git git-for-devops`
- Navigate to a directory: `cd git-for-devops/`

## Git Initialization
- Initialize a Git repository: `git init`
- Check repository status: `git status`

## File Operations
- Create a file: `touch test01.txt`, `touch test02.txt`, `touch test03.txt`
- Edit a file: `vi test02.txt`
- Delete a file: `rm test02.txt`

## Staging and Committing Changes
- Add files to the staging area: `git add test01.txt`, `git add test02.txt`, `git add .`
- Remove files from the staging area: `git rm --cached test02.txt`
- Commit changes: 
  - `git commit -m "adding Test01 and Test02"`
  - `git commit -m "edited Test02"`
  - `git commit -m "Added Test03"`

## Configuring Git
- Set global username: `git config --global user.name "AK76"`
- Set global email: `git config --global user.email "aneelkhan76@hotmail.com"`

## Branch Management
- List branches: `git branch`
- Create a new branch: `git checkout -b dev`
- Switch between branches: `git checkout master`, `git checkout dev`

## Log Viewing
- View commit logs: `git log`
- View compact commit logs: `git log --oneline`

## Restoring Files
- Restore a deleted file: `git restore test02.txt`

## Additional Commands
- View command history: `history`
