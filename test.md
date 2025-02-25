# Git commands short reference
## Git commands for work with local repository
To create new repository, manage files and etc, please use the next commands:  
> **git init** - initialize new repository folder  
> **git add** - adds file into repository (**git add .** - adds all files from project folder into rpository)  
> **git commit** - sends changes of project files to repository  
> **git restore** 'file'... - discards changes in working directory  
> **git checkout** 'commit hash' - moves to the selected commit  
> **git checkout master** - sets to last commit  
> **git diff** - shows difference between currently saved file and last commit  
> **git status** - shows status of current working project  

> **git branch** - shows current branch of editing project  
>> **git branch** [new_branch_name] - creates new branch with given *new_branch_name* as parameter  
>> **git branch -d** <branch_name> - deletes branch with name given as parameter  

> **git merge** - merges two or more branches into one, suggesting to resolve conflicts if any appeared  
> **git log** - list commits  
>> **git log -graph** - list commits in tree view  

> **git fetch** - fetch object and references from repository  
>> **git fetch** --dry-run - show possible changes without making any of them  
>> **git fetch** --force - *git fetch* may refuse to update the local branch, this option override it.  
## Git commands for work with remote repository  
> **git pull** - pull changes from remote repository  
> **git push** - push changes to remote repository

*This document created using 'markdown' formatting.*  
![Official  markdown logo](./images/markdownlogo.jpg "Official  markdown logo")
