# git-tricks
Share your git tricks here.

## Branches
- `git push --delete  <branch_name>`: Delete remote branch.  see: http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely


The trick that I learned for today is:

git checkout -b <new_branch_name> - create a new branch and check it out in one step
git revert (commit SHA) - this will allow you to revert a commit based on the SHA hash of the specific commit. The SHA can be found in git log.
