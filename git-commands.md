This file will contain the git commands.

#BASIC GIT COMMNDS
>> git -v : to check is git is installed and its version
>> git init : Initializes a new Git repository.
>> git config user.name = "User Name" : Configures Git username
>> git config user.email = "Email" : Configures Git email
>> git config --list : View Config Values
>> git status : Lists which files are modified and not yet stage
>> git add : Stages files for commit
>> git commit -m "commit message" : Save staged changes with a message explaining what you changed
>> git log : Shows the history of commits in your repository who changed what,when. It  also shows Commit hash,Author name & email,Date,Commit message
>> git branch : Tell on which branch the things are being performed


#BRANCHES
>> git branch : tell on whih branch you are currently performing the things.
>> git branch <branch-name> : craete the new branch.
>> git switch <branch-name> : switchs to the mentioned branch.
>> git chechout -b <branch-name> : switched to the mentioned branch and also restore files too.


#PUSHING/PULLING things to/from GitHub
>> git remote -v : Shows where your code is being pushed/pulled from.
>> git remote add origin <url> : Connects your project to a remote repository.
>> git remote set-url origin <url> : Changes the remote repository link.
>> git push -u origin feature-1 : Uploads your branch and links it for future pushes.
>>git push origin feature-1 : Uploads your branch (no linking for future use).
>> git pull origin <branch> : Sync/downloads the data or info from GitHub repo to the local machine


#ADVANCED Git: MERGE, REBASE, STASH & CHERRY-PICK
>> git merege feature: takes the changes from the feature branch and combines them into your current branch
>> git merge --squash feature: takes all the changes from the feature branch and combines them into a single commit on your current branch
>> git stash : temporarily saves your uncommitted changes (both staged and unstaged) and reverts your working directory back to a clean state
   >> git stash list : shows saved stashes
   >> git stash pop : reapplies and removes the stash
>> git log : shows the commit history of your repository
>> git cherry-pick <commit-id> : copies a specific commit from one branch and applies it onto your current branch
>> git rebase feature : moves or replays your commits onto another base branch
