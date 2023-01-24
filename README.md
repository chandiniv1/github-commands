# GIT COMMANDS

## $ git clone <repo>
    Git clone is a command for downloading existing source code from a remote repository (like Github, for example). In other words, Git clone basically makes an identical copy of the latest version of a project in a repository and saves it to your computer.

## $ git branch <branch_name>
    We can use the git branch command for creating, listing and deleting branches.By using branches, several developers are able to work in parallel on the same project simultaneously. 

## $ git push -u <remote><branch-name>
    To push the new branch into the remote repository git push 
    
## $ git branch --list
    this command is used to view the list of branches

## $ git branch -d <branch-name>
    this is used to delete a branch
    
    
## $ git checkout git branch -d <branch-name>
    Git checkout is mostly used for switching from one branch to another. We can also use it for checking out files and commits.
 
    
## $ git checkout -b <name-of-your-branch>
    This command allows us to create and switch to a branch at the same time
    
## $ git status
    The Git status command gives us all the necessary information about the current branch.This includes :
    Whether the current branch is up to date
    Whether there is anything to commit, push or pull
    Whether there are files staged, unstaged or untracked
    Whether there are files created, modified or deleted
    
    
## $ git add <file>
    When we create, modify or delete a file, these changes will happen in our local and won't be included in the next commit (unless we change the configurations).We need to use the git add command to include the changes of a file(s) into our next commit. 
    
## $ git add -A
    This command is used to add all the changes at once
    
## $ git commit -m "commit message"
    Git commit is used to save the changes when we reached the pparticular point of development.It is like setting a checkpoint in the development process which you can go back to later if needed.

## $ git push <remote> <branch-name>
    After committing your changes, the next thing you want to do is send your changes to the remote server. Git push uploads your commits to the remote repository.

## $ git push -u origin <branch_name>
    This command is used to push our code to the newly created branch
    
## $ git pull <remote>
    The git pull command is used to get updates from the remote repo. This command is a combination of git fetch and git merge which means that, when we use git pull, it gets the updates from remote repository (git fetch) and immediately applies the latest changes in your local (git merge).

## $ git revert
    This command is used to undo the commits.In other words it revert back the changes that we made locally or remotely
    
## $ git log -- oneline
    this command is used  to see the commit history
    
## $ git stash
    This command is used to temporarily save changes that you have made in your working directory, but have not yet committed, to a new stash. This allows you to switch to a different branch or to return to a clean state without losing your changes.
    
## $ git stash [name]
    name: The name of the stash. If no name is specified, a default name will be used.

## $ git stash list
    This command lists all the stashes that you have created.

## $ git stash apply [name]
    name: The name of the stash you want to apply.

## $ git stash drop [name]
    name: The name of the stash you want to delete.
    
## $ git merge <branch-name>
    This command is used to merge the another branch with the current branch. The code present in the current branch and merged branch will be merged.
    
## $ git init
    This command is used to create an empty git repository or to initialize and existing repository.

## $ git config
    This command is used to configure the username and email of the person working on the local repository.

## $ git config --global user.name = <name>
    This command is used to configure the username
    
## $ git config --global user.email = <email>
    This command is used to configure the email
    
## $ git log
    This command is used to get the total history of the repository. It provides the list of all the commits and for each commit it provides the username, date of commit, commit title and commit-hash.
    
## $ git log --oneline
    To get each commit details in oneline
    
## $ git log --stat
    To get the list of files modified and no. of lines modified in each commit
    
## $ git log --patch
    To get the list of files modified and also the location of the lines removed of added in the file
    
## $ git log --graph
    To get the graph of the commits made Each node of graph represents a commit

## $ git log -n
    To view last n commit details
    
## $ git diff
    This command is used to view the difference between the files in the one commit and another commit.

## $ git diff <commit1-hashkey> <commit2-hashkey>
    To view the changes between two different commits
    
## $ git diff <branch1-name> <branch2-name>
    To view the changes between two different branches
    
## $ git fetch
    This command will download the changes from the remote repository to the local repository. This will get the updates that are made to the remote repository into the local repository. This will only download the change and does not merge the changes.
    
## $ git fetch <remote-url>
    This command is used to fetch a remote repo
    
## $ git fetch <remote-url> <branch-name>
    This command is used to fetch a specific remote branch

## $ git fetch -all
    This command is used to fetch all the branches

## $ git reset <commit id>
    This command is used to undo the changes. This will reset the current state of the HEAD to any specific state.
    
## $ git rm <file-name>
    This command is used to used to delete a file or files from the repo
    
## $ git rm --cached
    This command is used to delete the file form git, but to preserve the file in the local system
    
## $ git tag
    This command is used to tag a commit and tag can be refered in future. A branch can have any number of tags. Tags can be names of the versions.

## $ git tag <tag-name>
    This command is used to create a tag

## $ git show <tag-name>
    This command is used to list the tag names
    
## $ git push origin <tag-name>
    This command is used to push a specific tag to remote repo

 

