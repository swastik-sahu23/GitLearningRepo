# GitLearningRepo
This repo is a part git learning.
Below are basic understanding and commands to learn git and github.
GIT:- version control tool

What is git?
Ans:- Git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people.

Git is a "distributed version control system". So git doesnt necessarily rely on a central server to store all the versions of a project's files. Instead every user "clones" a copy of a repositoy(a collection of files) and has the full history of the project on their own hard drive. 

This clone has all of the metadata of the original while the original itself is stored on a self hosted server or a third party hosting service like github.

why use git?

1) undo mistakes ---> you can undo mistakes ---> can have checkpoints 
2) distributed developement --> multiple people can work on multiple features in a single project, later it can be merged
3) Dn't mix things up(branching and merging)
4) community support ---> aquired by microsoft, more than 15 millions developers use now.

installing git:-

https://git-scm.com/downloads

commands
1)git verson

ceate a folder in desktop - LearnGitRepo
2) cd ..
3) cd LearnGitRepo
4) git init #to initialise a git repository for a new or existing project, it initialise a master branch
5) git add <file_name> # add one or more file to staging (index) 
6) git status # List the files you have changed and those you still need to add or commit:
7) clear #to clear the terminal
8) git commit -m "commit message" #commit changes to head

git log # to see where the head is
git config --global user.name "swastik-sahu23"
git config --global user.email "swastik.dgh@gmail.com"
git rm --cached <filename> #unstaging files from staging area   
git branch <branchname> #creating a new branch from master branch to make clean to project
git checkout <branchname> #navigating new brach from master branch, here new branch has a copy of master branch.
git commit -am "dev branch changed one" # -am represents add and commit 
git merge dev #it will merge dev branch to master



GITHUB:- Thirt party hosting server

https://github.com/swastik-sahu23/ML_With_Python_Edureka.git
git remote add origin https://github.com/swastik-sahu23/GitLearningRepo.git
git remote -v
   origin  https://github.com/swastik-sahu23/GitLearningRepo.git (fetch)
   origin  https://github.com/swastik-sahu23/GitLearningRepo.git (push)
git push -u origin master #local to remote(github)
git checkout dev
git push -u origin dev

git pull #remote(origin mASTER to local local master)

git add .

git log --name-only # to check files committed to git branch

we can do 'git pull' and 'git push' directly for master branch. REDME file is for details of the project. in '.gitignore' we can mentioned filenames which we dnt want to push to remote.

fork:- This is a option in github to replicate the repo from a different account to our account.

suggestion for youtube link to learn:- https://www.youtube.com/watch?v=iR5WIknxdkY
