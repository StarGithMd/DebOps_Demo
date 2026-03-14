These are common Git commands used in various situations

## Setup & Config
- **git config --global user.name "Your Name"**
- **git config --global user.name "Your Name"**
- **git --version**

## Basic Workflow   >>> Basic Workflow
- **init    >>> Create an empty Git repository or reinitialize an existing one**
- **git add git-commands.md**    >> Stages a file for commit
- **git add .**     >> Stages all changes in the current directory

- **git commit -m "message"**   >> Commits staged changes with a message

## Viewing Changes and status
- **git status**    >> Shows the status of files (staged, modified, untracked)

## Main Porcelain Commands
- **git add .**     >>> Add file contents to the index
- **git commit**    >>> Record changes to the repository
- **git  branch**     >>> List, create, or delete branches
- ** git checkout**     >>> Switch branches or restore working tree files
- ** git switch**       >>> Switch branches

## The most common Git branching commands
- **git branch**        >>> List all local branches
- **git branch -a**     >>> List all local and remote ranches
- **git branch**    >>> List all local branches
- **git branch <branch-name>**  >>> Create a new branch
- **git branch -d <branch-name>**   >>> Delete a branch (safe delete, prevents deleting if not merged)
- **git branch -D <branch-name>**   >>> Force delete a branch
- **git branch -m <new-name>**      >>> Rename the current branch
- **git branch -m <old-name> <new-name>**   >>> Rename a specific branc

##  Switching & Creating
- **git checkout <branch-name>**    >>> Switch to a branch
- **git checkout -b <branch-name>** >>> Create and switch to a new branch
- **git switch <branch-name>**      >>> Switch to a branch (modern alternative to checkout)
- **git switch -c <branch-name>**   >>> Create and switch to a new branch

## Remote Branches
- **git branch -r**     >>> List remote branches
- **git branch -a**     >>> List all branches (local + remote)
- **git push origin <branch-name>**     >>> Push a branch to remote
- **git push origin --delete <branch-name>**    >>> Delete a remote branch

## Tracking & Info
- **git branch -vv**        >>> Show branches with tracking info and last commit
- **git branch --merged**   >>> Show branches already merged into current branch
- **git branch --no-merged** >>> Show branches not yet merged

