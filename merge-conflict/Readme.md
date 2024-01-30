# Merge Conflict

## Task:

1. Create a new branch called `merge-conflict` from `master` branch.
2. Create a new file called `the-conflict.txt` and add the following text to it:
```
This file will cause a merge conflict
```
3. Commit the changes to the `merge-conflict` branch. Make sure you add a meaningful commit message.
4. Switch back to `master` branch.
5. Create a new file called `the-conflict.txt` and add the following text to it:
```
Peace not conflict is the way forward
```
6. Commit the changes to the `master` branch. Make sure you add a meaningful commit message.
7. Merge the `merge-conflict` branch into the `master` branch.
8. Resolve the merge conflict by keeping the following text in the file:
```
Peace not conflict is the way forward
```
9. Commit the changes to the `master` branch. Make sure you add a meaningful commit message.

## Useful commands

- `git checkout -b <branch-name>` - creates a new branch and switches to it
- `git checkout <branch-name>` - switches to the specified branch
- `git merge <branch-name>` - merges the specified branch into the current branch
- `git status` - shows the status of the current branch
- `git add <file-name>` - adds the specified file to the staging area
- `git commit -m "<commit-message>"` - commits the staged changes with the specified commit message
- `git log` - shows the commit history
- `git log --oneline` - shows the commit history with each commit on a single line
- `git log --oneline --graph` - shows the commit history with each commit on a single line and the branches graph


