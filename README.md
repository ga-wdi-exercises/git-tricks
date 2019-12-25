# git-tricks
Share your git tricks here.
- Figuring out if something is a merge is easy. That's all commits with more than one parent. To check for that, you can do, for example;
$ git cat-file -p $commit_id

## Branches
- `git push --delete  <branch_name>`: Delete remote branch.  see: http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely
- `git checkout -b <new_branch_name>`: Create a new branch and check it out in one step
- `git stash save`: Save your local modifications to a stash and roll your working directory back to HEAD
- `git stash list`: Show all stashed changes
- 'git stash apply': <commit>


