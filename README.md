# Git

## What is git?
git is a version control system. That keep track our changes. This helps to do colaboration in the projects.

## Lists of *version control system*
- GitHub
- GitLab
- Beanstalk
- PerForce
- Bitbucket

*Note* : 70% of developers use *git*

## How git works:

## Setup
*Set the name and email that will be attached to my commits and tags*  
```bash
$ git config --global user.name "myUserName"
$ git config --global user.emal myUserEmail@gmail.com
```
## Start a Project
*Create a local repo to initialise the current directory as a git repo*  
```bash
$ git init <directory>
```
*Download a remote repo*
```bash
$ gti clone <url>
```
## Make a Change
*Add a file to staging*
```bash
$ git add <file>
```
*Stage all files*
```bash
$ git add .
```
*Commit all staged files to git*
```bash
$ git commit -m "commit massage"
```
*Add all changes made to tracked files & commit*
```bash
$ git commit -am "commit message"
```
## Basic Concepts
**main:** default development branch  
**origin:** default upstream repo  
**HEAD:** current branch  
**HEAD^:** parent of HEAD  
**HEAD~4:** great-great grandparent of HEAD

## Branches  
*List all local branches. Add -r flag to show all remote branches. -a flag for all branches.* 
```bash
$ git branch
```
*Create a new branch*
```bash
$ git branch <new-branch>
```
*Switch to a branch & update the working directory*
```bash
$ git checkout <branch>
```
*Create a new branch and switch to it*
```bash
$ git checkout -b <new-branch>
```
*Delete a marged branch*
```bash
git branch -d <branch>
```
*Delete a branch, wheather marged or not*
```bash
$ git branch -D <branch>
```
*Add a tag to current commit (often used for new version releases)*
```bash
$ git tag <tag-name>
```
## Marging
*Merge branch a into branch b. Add -- no-ff option for no-fast-forward merge*
```bash
$ git checkout b
$ git merge a
```
*Merge & squash all commits into one new commit*
```bash
$ git merge --squash a
```
## Rebasing
*Rebase feature branch onto main (to incorporate new changes made to main). Prevents unnecessary merge commits into feature, keeping history clean*
```base
$ git checkout feature
$ git rebase main
```
*Interatively clean up a branches commits before rebasing onto main*  
```base
$ git rebase -i main
```
*Interatively rebase the last 3 commits on current branch*
```bash
$ git rebase -i Head~3
```

