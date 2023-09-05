# Git manual
## Main commands
* git init - Initialized empty git repository
* git add path_to_file - Update the index with the contents of a new or modified file
* git commit - m "massage" - Create a new commit with your "massage"
* git commit -a -m "massage" - Shortcut to updating the index with a modified file and creating a new commit with your "massage"

## Other commands
* git status - a brief summary of changes
* git diff - difference between the index file and your working directory; changes that would not be included if you ran "commit" now.
* git log - Shows a list of commits

## Branches

* git checkout branch_name - Switch to branch_name branch
* git checkout -b branch_name Create a new branch with branch_name and switch to it
* git branch - List of branches
* git branch branch_name - Create a branch with branch_name
* git merge branch_name - Merges branch_name into current branch
* git branch -d branch_name - Delete branch with branch_name