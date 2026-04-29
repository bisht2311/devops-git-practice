This file will contain the git commands.

>> git -v : to check is git is installed and its version
>> git init : Initializes a new Git repository.
>> git config user.name = "User Name" : Configures Git username
>> git config user.email = "Email" : Configures Git email
>> git config --list : View Config Values
>> git status : Lists which files are modified and not yet stage
>> git add : Stages files for commit

>> git commit -m "commit message" : Save staged changes with a message explaining what you changed

>> git log : Shows the history of commits in your repository who changed what,when,and why                                           It  also shows Commit hash,Author name & email,Date,Commit message

>> git branch : Tell on which branch the things are being performed


#BRANCHES

>> git branch : tell on whih branch you are currently performing the things.
>> git branch <branch-name> : craete the new branch.
>> git switch <branch-name> : switchs to the mentioned branch.
>> git chechout -b <branch-name> : switched to the mentioned branch and also restore files too.

#PUSHING things to GitHub

>> git remote -v : Shows where your code is being pushed/pulled from.
>> git remote add origin <url> : Connects your project to a remote repository.
>> git remote set-url origin <url> : Changes the remote repository link.
>> git push -u origin feature-1 : Uploads your branch and links it for future pushes.
>>git push origin feature-1 : Uploads your branch (no linking for future use).


