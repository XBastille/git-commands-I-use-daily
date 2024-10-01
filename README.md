# git-commands-I-use-daily
---
A detailed collection of frequently used Git operations.
---

### Starting & Managing Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Start a Git repository in your current directory |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Make a local copy of a remote repository |

### Recording Changes & Updates

| Command | Description |
| ------- | ----------- |
| `git status` | View the current working state of your repository |
| `git add [file-name.txt]` | Add a file to be tracked in the next commit |
| `git add -A` | Stage every new and modified file for the next commit |
| `git commit -m "[commit message]"` | Commit all staged changes with a descriptive message |
| `git rm -r [file-name.txt]` | Remove a file or directory from the working directory and Git tracking |

### Working with Branches

| Command | Description |
| ------- | ----------- |
| `git branch` | List all local branches (the active one has an asterisk) |
| `git branch -a` | Show all branches, both local and remote |
| `git branch [branch name]` | Create a fresh branch |
| `git branch -d [branch name]` | Delete a branch locally |
| `git push origin --delete [branch name]` | Remove a branch from the remote repository |
| `git checkout -b [branch name]` | Make a new branch and immediately switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Create a local branch from a remote one and switch to it |
| `git branch -m [old branch name] [new branch name]` | Rename a branch in your local repo |
| `git checkout [branch name]` | Switch to a different branch |
| `git checkout -` | Switch back to the previously checked-out branch |
| `git checkout -- [file-name.txt]` | Revert a file’s changes back to the last commit |
| `git merge [branch name]` | Combine changes from the specified branch into your current one |
| `git merge [source branch] [target branch]` | Merge a source branch into the target branch |
| `git stash` | Save your uncommitted changes temporarily, keeping your working directory clean |
| `git stash clear` | Remove all stored stashes permanently |

### Synchronizing & Sharing Code

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Send your local branch to the remote repository |
| `git push -u origin [branch name]` | Push changes to the remote repository and link the branch for future use |
| `git push` | Push the latest changes from your local repo to the remote one (for the current branch) |
| `git push origin --delete [branch name]` | Permanently delete a branch from the remote repository |
| `git pull` | Fetch the latest changes from the remote repository and merge them into your current branch |
| `git pull origin [branch name]` | Retrieve and integrate changes from a remote branch |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Associate your local repository with a remote GitHub repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Change the URL of the remote repository, switching to SSH if needed |

### Investigating & Comparing Changes

| Command | Description |
| ------- | ----------- |
| `git log` | Show a log of commits in your repository’s history |
| `git log --summary` | View a detailed breakdown of the commit history |
| `git log --oneline` | Get a compact, single-line view of the commit history |
| `git diff [source branch] [target branch]` | Compare the differences between two branches before merging |

---
