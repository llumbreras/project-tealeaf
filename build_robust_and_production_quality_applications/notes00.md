##### Git Flow

To create a new branch:
  git checkout -b branch_name

To switch between branches:
  git checkout master
  git checkout branch_name

To confirm the current branch:
  git branch

  * branch_name
    master

To merge the branch to master after making the commit:
  git checkout master

  git merge branch_name --no-ff

  --no-ff means retain all commit messages prior to merge

Now push the changes to the remote server.
  git push



