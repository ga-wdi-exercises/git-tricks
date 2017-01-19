# git-tricks
Share your git tricks here.

## Branches
- `git push --delete  <branch_name>`: Delete remote branch.  see: http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely


The trick that I learned for today is:

git checkout -b <new_branch_name> - create a new branch and check it out in one step

Here's my whole cheat sheet:

Git Cheat Sheet

<br>git init <dir> (creates empty repo in dir) 
<br>git clone <repo> (clones from github; use SSH)
<br>git config user.name <name> (defines author)
<br>git add <dir> (stage changes for next commit)
<br>git commit  -m “message”
<br>git push origin master (pushes local up to remote rep)
<br>git status (lists staged files)
<br>git diff (show unstated changes between dir and index)
<br>git checkout -b <branch name> (creates and checks out new branch)
<br>git checkout <branch> (changes branch)
<br>git branch (displays branches)
<br>git revert <commit> (creates new commit that undoes all of changes in spec comm - enter commit ID from git log)
<br>git reset <file> (removes file from staging area, upstages without overwriting in changes)
