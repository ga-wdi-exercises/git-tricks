# git-tricks
Share your git tricks here.

git reset
Resets your index and working directory to the state of your last commit. Example: git reset --hard HEAD

git fetch
Fetches all the objects from the remote repository that are not present in the local one. Example: git fetch origin

git grep
Lets you search through your trees of content for words and phrases. Example: git grep "www.siteground.com" -- *.php

## Branches
- `git push --delete  <branch_name>`: Delete remote branch.  see: http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely
- `git checkout -b <new_branch_name>`: Create a new branch and check it out in one step
