# Git Cheat Sheet

## Git Installation

1. Download git from here : https://git-scm.com/downloads (download the file follow simple steps and install)
2. Official Docs : https://git-scm.com/docs

## Creating a GitHub Account and creating first Repository

3. GitHub : https://github.com/ (simply follow the steps and create a profile)
4. Creating your first github repository : After creating a github account it'll land the home page / profile page , find repository option/logo there and click create a repository , keep everything as it is (default) if you are a beginner, give your repository name and description (if possible) and create your repository. (Or just do a youtube search and follow the steps)

## Setup

### If you have successfully installed Git on your machine search for GitBash and open it (for windows just right click inside the project folder or the folder you are using and click GitBash) then, follow the commands.

1. git config --list : To see all the details
2. git config --global user.name "username here": To set the username
3. git config --global user.email "email address here" : To set the email
4. git config user.name : To see the username
5. git config user.email : To see the email

## Basics

6. git status : To see the current status of the project/folder
7. git init : To initialize the project/folder, it also makes a hidden file named '.git'
8. git add <filename> : To track that file/include in what will be committed
9. git add . : To track all the untracked file
10. git commit -m "commit message" : To commit the files
11. git branch -M < branch name > : To change the branch
12. git remote add origin https://github.com/github_username/repo_name.git : To add the files/changes to your new repo (no need to use it if you are pushing changes to your existing repo)
13. git push -u origin < the branch u want to push in > : To push it inside your repo
14. git log : To Check all your commits

### For the first time use it'll ask for authentication , just follow the steps it's asking to follow, it'll take just 1-2 mins.
