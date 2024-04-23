# Branches  
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