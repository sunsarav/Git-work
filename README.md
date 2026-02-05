###### **Git commands used in this Project**



This repository was used to practice basic and intermediate Git commands.

Below are a lists of all Git commands I used during the work, along with a short explanation of what each command does.



**Adding and committing changes**



git add .

This command stages all modified and new files



git commit -m "message"

This command saves the staged changes as commit with a message



**Checking status and history and ignore**



git status

This command shows which files are modified, staged or untracked



git log

This command displays the commit history of the repository



.gitignore

This command tells Git which files and folders or directories to ignore and not to track them



**Pushing changes**



git push

This command uploads local commits to the remote GitHub repository



git push -u origin main

This command pushes the changes and sets the main branch as the default branch



**Cloning and Repo setup**



git clone

This command was used to copy an existing GitHub repository to my local computer



git remote -v

This command shows the current remote repo URLs



git remote set-url origin <new-url>

This command was used to change the remote connection so the project points to my own GitHub account



**Restoring and Discarding changes**



git restore <file>

This command discards changes in working directory and restores the file to the last committed version



git restore --staged <file>

This command removes a file from the staging area and moves it back to the working directory



git restore.



This command restores all files in the working directory to their previous state

These restore commands were used to fix bugs, undo mistakes and move files between different stages.



**Branching and Merging**



git branch

This command lists all branches



git branch <branch-name>

This command creates a new branch



git checkout <branch-name>

This command switches to another branch



git merge <branch-name>

This command merges changes from  one branch into another



**Summary**



During this project, I cloned a repository, changed the remote to my own GitHub account, made multiple edits, committed changes, restored files to previous versions, experimented with branching and merging, re-published the project to my own repository.



