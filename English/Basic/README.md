- [1. git config](#1-git-config)
- [2. git init](#2-git-init)
- [3. git add](#3-git-add)
- [4. git clone](#4-git-clone)
- [5. git commit](#5-git-commit)
- [6. git status](#6-git-status)
- [7. git push](#7-git-push)
- [8. git checkout](#8-git-checkout)
- [9. git remote](#9-git-remote)
- [10. git branch](#10-git-branch)
- [11. git pull](#11-git-pull)
- [12. git merge](#12-git-merge)
- [13. git log](#13-git-log)
- [14. git diff](#14-git-diff)
# 1. git config
One of the most used git commands, email, username and file format etc. git config, which can be used to set user-specific configuration.
```
git config --global user.name <username>
git config --global user.email <mailaddress>
```
# 2. git init
Create a new repo
```
git init
```

# 3. git add
Update all
```
git add .
```
Update all files in the format (ex: .c, .cpp, .css...).
```
git add *.<format name> 
```
Update file by name
```
git add <file name 1> [<file name 2> ... <file name n>]
```

# 4. git clone
Clone 1 repo on the server to the local
```
git clone <Link repository>
```

# 5. git commit
Use to commit changes to the head
```
git commit -m "<Message>"
```

# 6. git status
Displays a list of files that have not yet been added or that have been changed along with the committed files
```
git status
```

# 7. git push
`Git push` is another of the most used basic Git commands. With a simple push, it pushes the changes made to the master branch of the remote directory associated with the working directory
```
git push origin <Branch name>
```

# 8. git checkout
Create a new branch and switch that branch
```
git checkout -b <Branch name>
```
Switch brach
```
git checkout <Branch name>
```

# 9. git remote
Display lists remote
```
git remote -v
```
Connect your repo to server
```
git remote add origin <Link to repo>
```
Rename remote
```
git remote rename <Old repo name> <New repo name> 
```

# 10. git branch
Create a new branch
```
git branch <Tên nhánh>
```
Delete a branch
```
git branch -d <Tên nhánh>
```
Check current branch
```
git branch
```

# 11. git pull
Use to merge all the changes found in the remote repository into the local working directory
```
git pull
```

# 12. git merge
Use to merge a branch into the active branch
```
git merge <Tên nhánh>
```

# 13. git log
List of commits on a branch with the relevant details
```
git log
```
# 14. git diff
Used to list conflicts. To view conflicts with the base file
```
git diff --base
```
Use to view conflicts between branches to be merged before merging
```
git diff
```