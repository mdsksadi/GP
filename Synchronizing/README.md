# Synchronizing
*Add a remote repo*
```bash
$ git remote add <alias> <url>
```
*View all remote connections. Add -v flag to view urls.*
```bash
$ git remote
```
*Remove a connection*
```bash
$ git remote remove <alias>
```
*Rename a connection*
```bash
$ git remote rename <old> <new>
```
*Fetch all branches from remote repo (no merge)*
```bash
$ git fetch <alias>
```
*Fetch a specific branch*
```bash
$ git fetch <alias> <branch>
```
*Fetch the remote repo's copy of the current branch, then merge*
```bash
$ git pull
```
*Move (rebase) your local changes onto the top of new changes made to the remote repo (for clean, linear history)*
```bash
$ git pull -rebase <alias>
```
*Upload local content to remote repo*
```bash
$ git push <alias>
```
*Upload to a branch (can then pull request)*
```bash
$ git push <alias> <branch>
```