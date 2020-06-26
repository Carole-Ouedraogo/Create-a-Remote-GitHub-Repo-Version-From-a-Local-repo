Get started by creating a new file or uploading an existing file. 

(We recommend every repository include a README, LICENSE, and .gitignore.)

Using the command line to create a new repository

1. Create 'empty repo' without a ReadMe
2. Use the command line to create a new repository:
   
        echo "# Create-a-Remote-GitHub-Repo-Version-From-a-Local-repo" >> README.md
        git init
        git add README.md
        git commit -m "first commit"
        git remote add origin https://github.com/Carole-Ouedraogo/Create-a-Remote-GitHub-Repo-Version-From-a-Local-repo.git
        git pull origin master --allow-unrelated-histories
        git push -u origin master
