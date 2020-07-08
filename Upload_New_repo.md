Get started by creating a new file or uploading an existing file. 

(We recommend every repository include a README, LICENSE, and .gitignore.)

Using the command line to create a new repository

1. Create local Repo with ReadMe
2. Create `remote-Repo` without a ReadMe
3. Use the command line to link to remote repository:

```
  git init
  git add .
  git commit -m "first commit"
  git remote add origin https://github.com/Carole-Ouedraogo/remote-Repo.git
  git pull origin master --allow-unrelated-histories
  git push -u origin master
```       
[Mastering Markdown](https://guides.github.com/features/mastering-markdown/)


Git
typical process
git add .
git status
git commit -m ‘my solution’
git push origin master
 
create branch
git checkout -b “branch name”
 
list branches
git branch
 
checkout a branch
git checkout “branch name”
 
Sync local to repo
git pull
 
Merge branches
git merge “branch”
 
