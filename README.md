# git-tricks
Share your git tricks here.

## Branches
- `git push --delete  <branch_name>`: Delete remote branch.  see: http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely


The trick that I learned for today is:

git checkout -b <new_branch_name> - create a new branch and check it out in one step

Here's my whole cheat sheet:

Git Cheat Sheet

git init <dir> (creates empty repo in dir)
git clone <repo> (clones from github; use SSH)
git config user.name <name> (defines author)
git add <dir> (stage changes for next commit)
git commit  -m “message”
git push origin master (pushes local up to remote rep)
git status (lists staged files)
git diff (show unstated changes between dir and index)
git checkout -b <branch name> (creates and checks out new branch)
git checkout <branch> (changes branch)
git branch (displays branches)
git revert <commit> (creates new commit that undoes all of changes in spec comm - enter commit ID from git log)
git reset <file> (removes file from staging area, upstages without overwriting in changes)
