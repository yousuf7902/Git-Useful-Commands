﻿# Git-Useful-Commands
## Create a new repository on the 

``` 
git init 
git add .  
git commit -m "first commit"  
git branch -M main    
git remote add origin "url"  
git push -u origin main
```

 ## For daily usage

 ``` 
git add . 
git commit -m "message here"  
git push
```

## Status

### Check the status of working directory and staging area

```
git status
```

### Show changes between HEAD and working directory

```
git diff
```

## Branching, Merge , Checkout

### Show the branch list
```
git branch 
```

### Create new branch
```
git branch "branch name"
```

### Switching the branch
```
git checkout “branch name”
```

### Merge 2 branches codes
```
git merge “branch name” -m “merge message”
```



## Push and Pull
### Send codes local repository to remote 
```
git push -u origin "branch name"
```

### Fetches and merges changes from a remote repository to the local repository

```
git pull
```
    
## Log , Reset, Restore

### Displays the commit history
```
git log
```

### Shows the differences between the working directory and the repository
```
git diff
```

### Restore the changes
```
git restore
```

### Reset the staging or anything
```
git reset
```

### It will give the changes and file back together
```
git reset --hard
```

### After committing if you want to reset then  it will back the changes and also give the files back also
```
git reset HEAD~ 
```







