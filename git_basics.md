git status

git init
  initialize a repository

git add <filename>
git add -A .
  add untracked files or changes to staging area

using wildcards
  git add '*.txt'

git reset <filename>
  remove file from staging area

git commit -m 'commit message'
  commit staging changes to repository -- get a snapshot

git log
git log --summary
  to see the history

git remote add origin http://github.com/zzmxleo/git-note.git
  add a remote name and remote url

git push -u origin master
  push local repository to remote repository

git pull origin master
  pulling from remote repository

git stash
  stash your changes before pulling
git stash apply
  re-apply your changes after pulling

git diff HEAD
  take a look at the differences with last commit

git diff --staged
  look at the differences between staged files and last commit

git reset <filename>
  unstaging files

git checkout -- <target>
  revert all the changes made to the target since last commit

git branch <branch_name>
  set up a new branch

git branch
  check all the branches

git checkout <branch_name>
  switch to the branch specified

git checkout -b <new_branch>
  create and checkout a new branch at the same time

git rm <filename>
git rm '*.txt'
git rm -r <folder>
  remove file from disk and stage the removal

git commit -am 'blahblah'
  autoremove deleted files from the working tree if you have deleted a file without using 'git rm'

git merge <branch_name>
  merge the branch specified to the current branch

git branch -d <branch_name>
  delete a branch

git branch -d -f <branch_name>
  force delete
