# Rebasing
*Rebase feature branch onto main (to incorporate new changes made to main). Prevents unnecessary merge commits into feature, keeping history clean*
```bash
$ git checkout feature
$ git rebase main
```
*Interatively clean up a branches commits before rebasing onto main*  
```bash
$ git rebase -i main
```
*Interatively rebase the last 3 commits on current branch*
```bash
$ git rebase -i Head~3
```