# Undoing Things
*Move (&/or rename) a file & stage move*  
```bash
$ git mv <existing_path> <new_path>
```
*Remove a file from working directory & staging area, then stage the removal  
```bash
$ git rm <file>
```
*Remove from staging area only  
```bash
$ git rm --cashed <file>
```
*View a previous commit (READ only)*
```bash
$ git checkout <commit_ID>
```
*Create a new commit, reverting the changes from a specified commit*
```bash
$ git revert <commit_ID>
```
*Go back to a previous commit & delete all commits ahead of it (revert is safer). Add --hard flag to also delete workspace changes (BE VERY CAREFUL)*
```bash
$ git reset <commit_ID>
```