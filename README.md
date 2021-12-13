## Git Cheat Sheet

History of Git commands.

### Basic Commands
* `git init` - Initialize local Git repository
* `git add .` - Add all files in and under ci
cuurent directory to git index, staging them for commit
* `git commit -m "Message"`- Commit changes to local repo with commit message "Message"

### Information Commands
* `git status` - display current status of local working directory/repository
* `git log` - list commit history
* `git log --oneline` - list commit history, compact format


### Branching Commands
* `git branch` - List local git branches
* `git branch newBranch` - Create local branches `newBranch`
* `git checkout newBranch` - Check out local branch `newBranch`
* `git branch -M otherBranch` - Rename current branch to `otherBranch`

### Remote Commands
* `git remote add origin remoteURL` - Add alias "origin" for remote repository URL "remoteURL"
* `git push origin main` - Push locally-committed changes to `main` branch on remote repository
* `git push -u origin main` - Same, setting "origin main" as default for subsequent `git push`
