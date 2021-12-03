# This documentation is to describe the git commands used

## Configure terminal
`git config credential.helper store` --> store password

`git config --global user.name "John Doe"`

`git config --global user.email johndoe@example.com`

`git config --global core.editor vim` --> choose vim as default text editor

`git config --global push.default simple` --> to push only the current branch

`git config --global color.ui auto`	

## Create branch
Terminal :  
`git checkout -b {branch_name}` --> create new branch locally

`git push -u origin {branch_name} `--> push the new branch to the server

## Delete branch
Local :
`git branch -d {branch_name}` --> delete local branch

Server :
`git push --delete origin {branch_name}`--> delete branch on server

## Checkout branch
`git checkout {branch_name}` --> go on the branch

`git checkout [file_name] `--> remove changes made to the files

## Pull branch
`git pull` --> update branch

## Commit
`git add [file_name]` --> add file to the commit

`git rm [file_name]` --> remove file

`git commit -m "Commit message"`--> commit changes

## Rebase
`git checkout develop` --> branch on which you want to rebase on

`git pull`

`git checkout {branch_to_rebase}` --> branch to rebase

`git rebase develop`

## Reset branch
`git reset --hard origin/{branch_name}` --> reset local branch to branch on the server

`git clean -f -d` --> to have local file sys = remote file sys

`git pull`

