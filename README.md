# GitHub Tutorial

_by John Raffaele_

---
## Git vs. GitHub
#### Git:
###### - Versions Control: keeps "snapshots" of code.


#### Github:
###### - Visually tracks changes.
###### - Easily collarborates on the files that you make.
###### - [github.com](github.com) - your computer local machine. 

#### What is the difference between **Git** and **GitHub**?  
* Git doesn't require Github.
* GitHub requires Git.
* Git runs in the command line 
* GitHub is stored in the clouds
---
## Initial Setup
###### - Go to [github.com](github.com)
###### - Click on the top right and click on the profile icon.
###### - Click on settings.
###### - Look on the left sidebar and click on SSH and GPG keys.
###### - Click on New SSH Key
###### - Make the title cloud9
######  Key: 
###### - Switch to the cloud9 tab > top right gear icon
###### - Click on SSH key tabs then copy and paste the SSH key to github (starts with ssh-rsa)
###### - Add the SSH key.
---
## **Repository Setup**
#### **How to make a repository:**
###### - cd~/workspace
###### - Open the terminal in cloud9.
##### Type ALL of this:
###### - mkdir my-repo
###### - cd first-repo
###### - git init
###### - touch README.md
###### - open the README file and type in the README this is my repo.
###### - save it then add it 
###### - git commit -m "create readme"
#### - Go to [github.com](github.com)
###### - Click on the plus sign on the top right.
###### - Make the repository name my-repo.
###### - Click on Create Repository
###### - Then make sure your on the SSH part on the repository.
###### - Then copy and paste the second section of code that you see.
###### - DO IT ONE AT A TIME THOUGH!!!!!
---
## Workflow & Commands
###### - git init- it initializes git in our directory (now called a repository) for version control.
###### - git status- an optional command to see which files have been edited since the last command (they will be red)
###### - git add file.txt- add the file(s) to the stage to be committed (git add adds all the files that have changes)
###### - git log- shows your past commits.
###### - git diff- shows the difference between your current code and the previous commit.
###### - git pull- brings any changes from the remote repo down to the local repo.
###### - git push- pushes everything on the file on to a different file.
###### - git clone- copies an existing git repository.
###### - forking - makes a copy of someone elses project and sends if to you so you can edit things or help work on it.
###### - rm -rf- to uninitialize.
###### - git remote -v- allows you to track your local branch against almost any branch of a repository