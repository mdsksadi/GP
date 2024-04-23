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