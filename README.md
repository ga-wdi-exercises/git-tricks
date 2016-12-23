# git-tricks
Share your git tricks here.

## Branches
- `git push --delete  <branch_name>`: Delete remote branch.  see: http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely

- git is awesome!!!!!


# J's additions below 

Alias git to ‘g’

I also alias git to g, saving me 66% on typing time! Also, I’m lazy. Add the following to your .bashrc or .zshrc:

alias g='git'
Now, you’ll probably also want to have the Git Autocompletion when you’re using g as well. Add this to your .bashrc or .zshrc:

# Autocomplete for 'g' as well
complete -o default -o nospace -F _git g
