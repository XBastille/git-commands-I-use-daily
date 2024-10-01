# git-commands-I-use-daily
---

## Git Operations Guide

_A summary of essential Git operations frequently utilized._

---

### Starting & Managing Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Set up a Git repository locally |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Clone an existing repository from a remote server |

### Recording Changes

| Command | Description |
| ------- | ----------- |
| `git status` | Display current repository status |
| `git add [file-name.txt]` | Stage a specific file for the next commit |
| `git add -A` | Stage all modified and new files for the next commit |
| `git commit -m "[commit message]"` | Save the staged changes with a message |
| `git rm -r [file-name.txt]` | Delete a file or directory from the repository |

### Managing Branches

| Command | Description |
| ------- | ----------- |
| `git branch` | Show a list of all branches (the current branch is marked with an asterisk) |
| `git branch -a` | Display both local and remote branches |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Remove a branch locally |
| `git push origin --delete [branch name]` | Remove a branch from the remote repository |
| `git checkout -b [branch name]` | Create a branch and switch to it immediately |
| `git checkout -b [branch name] origin/[branch name]` | Create and switch to a local copy of a remote branch |
| `git branch -m [old branch name] [new branch name]` | Rename an existing branch |
| `git checkout [branch name]` | Switch between branches |
| `git checkout -` | Switch to the previously active branch |
| `git checkout -- [file-name.txt]` | Undo changes in a file before committing |
| `git merge [branch name]` | Combine another branch into the active one |
| `git merge [source branch] [target branch]` | Merge the specified source branch into the target branch |
| `git stash` | Temporarily save changes that are not ready to commit |
| `git stash clear` | Clear all stashed changes |

### Syncing & Sharing Code

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Upload a branch to a remote repository |
| `git push -u origin [branch name]` | Upload changes to the remote repository and track the branch |
| `git push` | Push committed changes to the remote repository (for the current branch) |
| `git push origin --delete [branch name]` | Remove a remote branch |
| `git pull` | Synchronize the local repository with the latest changes from the remote |
| `git pull origin [branch name]` | Fetch and merge changes from a specific branch |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Link a local repository with a remote one |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Update the remote repository's URL to use SSH |

### Viewing Logs & Comparing Changes

| Command | Description |
| ------- | ----------- |
| `git log` | Show a history of changes |
| `git log --summary` | View a detailed log of changes |
| `git log --oneline` | Display a condensed log of changes |
| `git diff [source branch] [target branch]` | Compare changes between branches before merging |

--- 
