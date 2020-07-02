Get started by creating a new file or uploading an existing file. 

(We recommend every repository include a README, LICENSE, and .gitignore.)

Using the command line to create a new repository

1. Create local Repo with ReadMe
2. Create `remote-Repo` without a ReadMe
3. Use the command line to link to remote repository:
   
        git init
        git add .
        git commit -m "first commit"
        git remote add origin https://github.com/Carole-Ouedraogo/remote-Repo.git
        git pull origin master --allow-unrelated-histories
        git push -u origin master
