# Git commands
*This repo contains all the common and necessary git commands*
## Git set up commands
> configuration of git to git hub
```
git config --global user.email "someone@gmail.com"
git config --global user.name "Rejoice Doe"
```
## checking status
```
git status
```
> The status commands is use to check if a directory is git enable and also to check the status of our files whether stage, committed or push
## initializing a repo
```
git init
```
> git init is use to initialize a directory into a git repo

## staging changes
```
git add filename
git add . 
```
> The `git add filename` is use to stage a single file while `git add .` is use to stage multiple file.
## committing changes
```
git commit -m "commit message"
git commit -a -m "commit message" 
```
> The first command in the code block above is use to commit a file that has been recently stage, while the second command is use to add and commit a file that git is alrerady tracking.
## Secting up a remote collection
- checking if a connection already exist
```
git remote -v
```
> This command is use to check if a remote connection exist and active
- Adding a remote connection
```
git remote add "connection name" "connection url" remote
git remote add origin https://github.com/username
```
> The above command is use to create a remote connection
- Removing a remote connection
```
git remote remove "connection name" 
git remote remove origin 
```
> This command is use to remove connection to your git hub
## Pushing to remote repository
```
git push
git push -u connection-name branch-name
(eg git push -u origin master)
```
> The first command is use to push to a remote repository when you already have an upstream set up while the second command is use to set an upstream and push to a remote repository 