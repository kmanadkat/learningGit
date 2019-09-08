## Git Tutorial
---


### BASIC COMMANDS
----------------------------------------------------------
```bash
git init	                // Initialize Local Git Repo
git add <file>	          // Add File(s) to Index
git add .                 // Adds Everything to git stage
git rm --cached <file>    // Removes File from git stage
git status	              // Check status of Working tree
git commit	              // Commit Changes in Index
git commit -m 'msg'       // Commit quickly with msg
git push 	                // Push to Remote Repo
git pull	                // Pull Latest From Remote Repo
git clone	                // Clone Repo into a new folder
```


### GETTING STARTED
--------------------------------------------------------
```bash
git config --global user.name 'Krupesh'
git config --global user.email 'kmanadkat@gmail.com'
```


### GIT IGNORE
--------------------------------------------------------
Add <file names> and </directories> which git should not
commit or track



### GIT Branches
--------------------------------------------------------
Make copies/branches of project and work in them 
individually to implement features, without disturbing
the initially coded project.After the branch job -> 
new feature creation, is completed merge it with "master" 
branch

Files and State of one branch will be invisble to another.
All branches work independently. After completion of branch task, merge master to that branch

```bash
git branch <name>             // Create Branch
git checkout <name>           // Switch to branch
git branch -d <name>          // Delete Branch
git merge <name>              // Run from master to merge
git remote add origin <url>   // Add Remote Repo Ref
git push -u origin master     // First Push to Remote
git push                      // Next push changes
```