# Git Cheatsheet

### Download
---
Visit the [Downloads](https://git-scm.com/downloads) page and select your operating system. 

Mac already has git preinstalled. Windows and others can also get it. Pretty straight forward installation. No hidden ways. Just plain out standard shit. 


### Linking local git to a remote one/Config
---
**Username**
`git config --global user.name “[firstname lastname]”`

**Email**
`git config --global user.email “[valid-email]”`

**Colour**
`git config --global color.ui auto`


### Starting the work
---
**Initialising** a local repository 
`git init`

**Starting** off from a remote repository
`git clone [url]`


### Saving local changes 
---
**Check** the status. Where you are, what's left to commit, which files were edited.
`git status`

See the **difference**. What's new. 
`git diff`

Getting **changes** ready for saving.  
`git add .`

Committing **last** added changes
`git commit -m "message for commit"`

Checking the commmit **history**
`git log`


### Dealing with remote 
---
Checking all the **existing** remotes
`git remote -v`

Show **information** on remotes
`git remote show <remote's name>`

**Adding** a remote 
`git add remote <remote's name - usually named origin> <url>`

**Removing** a remote 
`git remove rm <remote's name>`

**Pulling** changes from a remote i.e. bringing the remote git to local system
`git pull <remote's name> <branch's name>`

**Pushing** changes to a remote i.e. sending local git to remote
`git push <remote's name> <branch's name>`

### Branches
---



### Merge
---


### Undo
---


