Git Basics | Add | Commit | Push


First make changes in the file or add a new file

Do git status to get the status. New files will be displayed under untracked file

We can do git add . (for all the changes) or git add ### (specific file) 

Do git status again and see that the changes are tracked

Next do git commit -m “message” (with a valid message) - This will save the changes locally. Commit is not live in GitHub

Do git push to push the changes to remote GitHub repository


To add a new repository

2 ways: 

First way:

Go to GitHub GUI create a new repo (name: aaa)
Create a folder in visual studio locally copy (name: aaa)
Do git init
We have a file (README.md) in the locally copy and we want to check into master. Go inside the folder and Do git add README_1.md 
Do git commit git commit -m "new_repo"
Do git branch -M main (specify the branch)
Do specify the repo path (ssh path which we can fiddle in the GitHub repository on web)git remote add origin git@github.com:Sreekanth0706/demofile_repo_1.git 
Do git push to main branch git push -u origin main
