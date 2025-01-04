# git Initialization 

to set `main` as the default branch name   
`git config --global init.defaultBranch main`		

To set your name  
`git config --global user.name "Ahmad Romman"`

To set your email  
`git config --global user.email "Rommaneus@hotmail.com"`

To check the user.name  
`git config user.name`					

To list all the config settings  
`git config --list`					

## git help ##

For manual Page  
`git help <verb>` or 
`git <verb> --help` or
`man git-<verb>`

Quick CLI manual  
`git <verb> -h`

## git Repo ##

to initiate the git repo  
`git init`

to add a file to the staging area  
`git add <file_name>`

To commit the changes  
`git commit -m "message"`

to skip the staging area  
`git commit -a`

To redo a commit  
`git commit --amend`

to clone a repo  
`git clone <url>`

to remove a file from the staged and working directory  
`git rm <file>`

to remove a file from the staged only  
`git rm --cached <file>`

to rename a file  
`git mv <file_a> <file_b>`

## Checking Status ##

To show if there is untracked files or uncommited  
`git status`

to show a shorter status   
`git status -s`

to show the difference between the working directory and staged  
`git diff`


To show the difference between the staged and last commited  
`git diff --staged`

to list the commits amde in the repo  
`git log`

shows the difference introduced in each commit. -2 means last two patches  
`git log -p -2`

to see abbreviated stats for each commit  
`git log --stat`

to see the commit and the message  
`git log --pretty=oneline` 

## Undo Repo ##
To unstage a file  
`git restore --staged <file>`

To restore a file to its last commit  
`git restore <file>`

## Remote Repositories

To get the current remote repos
`git remote`

To add a remote repo
`git remote add <alias> <url>`

