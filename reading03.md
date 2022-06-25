### Reading 3 - Git the Basics

Please let me share one warning for new Git users - Git owns and controls all tracked files, as if an OS file manager - 
so if you attempt to remove Git from a working directory by deleting the .Git folder - it will be removed, but it will also remove 
all tracked files along with it.  This wasn't obvious to me until I tried it once on a local repo, and luckily, the working directory had backups.

Moving on - this reading was a review of Git fundamentals, which I was familiar with, but the review did reinforce core concepts and syntax.

Below are some of the reading topics covered so far.  Also, please forgive the quick note-taking style, as I attempt to finish this review soon and delve into new Full Stack material.

Git File Status 

Two primary Git status types:  
1. Untracked file  
2. Tracked file  

Tracked files have 3 kinds of status:  
1. Modified
2. Staged 
3. Comitted 

Install Git on Ubuntu via:  
_sudo apt-get install git_

Configure Git  
_git config [--global] user.name "My Name"_  
_git config [--global] user.email "MyEmail@<area>email.com"_

Call git config without arguments to confirm, as below:  
_git config user.name_

Configure a Default Text Editor

Check Settings via:  
_git config --list_

Find Help Docs via:  
_git help [command]  
git [command] --help  
man git-command_  

To make any directory into a new repo, use:  
_git init_  

Then stage and commit, via:  
_git add [file-specifiers]_  
Stage all via:  
_git add ._  
Commit via:  
_git commit -m "Message describing commit."  
git commimt -a // Commits all, will be prompted for message._  

A new local repo can also be made by cloning  
_git clone [target] <area>[new-repo]_

3 Primary Parts of a Git Repo:  
1. Working directory (may have modified files)  
2. Index (staged changes)  
3. Head (the most recent commit)  

Check repo status, via:  
_git status_

Push changes to a remote via:  
_git push origin main // This sends to target, from source._

To temporarily cache local changes to a stack and revert, use:  
_git stash_    
Restore changes via:  
_git stash apply_  

See any upstream remote repo via:  
_git remote [-v] // Option includes url_

[Back to Home](https://stephen-montague.github.io/reading-notes/)
