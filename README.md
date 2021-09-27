# Demo

Some description!

## Subheader

$ ls -la => "list all the files and directories (including the hidden ones) in the current home directory and show their permissions"
That tell ls to show the permissions of each file/directory (-l) and include hidden files and directories in the list (-a).

$ ls cd - => back to previous folder

- Clone repository
  ../git_learning
  $ git clone git@github.com:dinhnhatdang/demo-repo.git

- Show all of the files that were updated or created or deleted, but haven't been saved in the commit yet.
  ../demo-repo
  $ git status

- Track all the file before commit (git add .) or track specific a file before commit (git add index.html as example)
  ../demo-repo
  $ git add .

- Commit = save your code (locally). -m = message
  ../demo-repo
  $ git commit -m "Added index.html" -m "some description"

- Push = push this file live to remote repository where my project is hosted (Github)
  ../demo-repo
  $ git push

- Create new branch (new name branch is: feature-readme-instructions)
  $ git checkout -b feature-readme-instructions

- See what branch you are standing in (you're standing at the branch with highlight)
  $ git branch

- Switch between branches
  $ git checkout <branch name>

- Check the difference between branches
  $ git diff feature-readme-instructions
