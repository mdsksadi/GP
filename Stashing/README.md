# Stashing
*Store modified & staged changes. To include untracked files, add -u flag. For untracked & ignored files, add -a flag.
```bash
$ git stash
```
*As above, but add a comment.*
```bash
$ git stash save "comment"
```
*Partial stash. Stash just a single file, a collection of files, or individual changes from within files*
```bash
git stash -p
```
*List all stashes*
```bash
$ git stash list
```
*Re-apply the stash without deleting it*
```bash
$ git stash apply
```
*Re-apply the stash at index 2, then delete it from the stash list. Omit stash@{n} to pop the most recent stash*
```bash
$ git stash pop stash@{2}
```
*Show the diff summery of stash 1. Pass the -p flag to see the full diff.*
```bash
$ git stash show stash@{1}
```
*Delete stash at index 1. Omit stash@{n} to delete last stash made*
```bash
$ git stash drop stash@{1}
```
*Delete all stashes*
```bash
$ git stash clear
```