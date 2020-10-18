## Basic Git Commands

### git init
Create a new local repository.
* git init [repository name]

### git config
This command sets the author name and email address respectively to be used with your commits.
* git config –global user.name “[name]”  
* git config –global user.email “[email address]”  

### git clone
Create a working copy of a repository.
* git clone [url]

### git add
Add one or more files to staging.
* git add [file]

### git commit
Commit changes to head (but not yet to the remote repository).
* git commit -m “[commit message]”
* git commit -a -m “[commit message]”

The above command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

### git push
Send changes to the master branch of your remote repository.

### git status
List the files you've changed and those you still need to add or commit.

### git remote
List all currently configured remote repositories.
* git remote add [remote name] [Remote Server Link]

### git branch
List all the branches in your repo, and also tell you what branch you're currently in.
* git branch [branch name]

### git checkout
Switch from one branch to another.
* git checkout [branch name]
* git checkout -b [branch name]

The above comment creates a new branch and also switches to it.

### git pull
Fetch and merge changes on the remote server to your working directory.

### git diff
View all the merge conflicts.

### git log
Lists the commits made in that repository in reverse chronological order.

### git rm 
Deletes the file from your working directory and stages the deletion.
* git rm [file]

### git tag
This command is used to give tags to the specified commit.
* git tag [commit ID] 