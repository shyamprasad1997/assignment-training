##Github Commands
###git config
This command sets the author name and email address respectively to be used with your commits.
**Usage:**
- git config –global user.name “[name]” 
- git config –global user.email “[email address]”

###git init

This command is used to start a new repository.
**Usage:**
- git init [repository name]

###git clone
This command is used to obtain a repository from an existing URL.
**Usage:**
 - git clone [url]
 
###git add
This command adds a file to the staging area.
**Usage:**
- git add [file]
- git add *

###git commit
This command records or snapshots the file permanently in the version history.
**Usage:**
- git commit -m “[ Type in the commit message]” 
- git commit -a 

###git diff
This command shows the file differences which are not yet staged.
**Usage:**
- git diff –staged
- git diff [first branch] [second branch] 

###git reset
This command undoes all the commits after the specified commit and preserves the changes locally.
**Usage:**
- git reset [commit]
-  git reset [file] 
- git reset –hard [commit]

###git status
This command lists all the files that have to be committed.
**Usage:**
- git status

###git log
This command is used to list the version history for the current branch.
**Usage:**
- git log 

###git tag
This command is used to give tags to the specified commit.
**Usage:**
- git tag [commitID] 

###git branch 
This command lists all the local branches in the current repository.
**Usage:**
- git branch

###git checkout
This command is used to switch from one branch to another.
**Usage:**
- git checkout [branch name]
- git checkout -b [branch name]

###git merge
This command merges the specified branch’s history into the current branch.
**Usage:**
- git merge [branch name]

###git remote
This command is used to connect your local repository to the remote server.
**Usage:**
- git remote add [variable name] [Remote Server Link]

###git push
This command sends the committed changes of master branch to your remote repository.
**Usage:**
- git push [variable name] [branch]
- git push –all [variable name] 
###git pull
This command fetches and merges changes on the remote server to your working directory.
**Usage:**
- git pull [Repository Link] 
