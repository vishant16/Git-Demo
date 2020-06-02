# Git-Demo

## Lifecycle of Git
    1. Local
    2. Remote



### 1.Local
  #### 1. Working directory
   When we create new file, file will be in "working directory".
  
  #### 2. Staging area
  When we add "git add" file goes to staging area
  
  #### 3. .git folder
   When we commit "git commit" file goes to .git folder.

### 2.Remote
Local repo changes will be in remote repo by git push

  
## commands
 ### git init
 ### git status
 ### git add .
 ### git commit -m "messages."
 ### git push origin master
 
 ### git pull origin master (to push down the remote changes to our local repository)
 ### git ls-files (to track all files)
 ### git reset HEAD filename
    It unstage the file means put back to working directory from staging area or undo git add
 ### git checkout -- filename
    It undo the changes we have done or to discard changes in working directory

 ## git push origin master -f
    If fail to push or failed to push some refs to https://github.com/xyz.git
    
 ## create branch
    git checkout -b branchname
  ## change branch
    git checkout branchname
  ## delete branch
    git checkout -d branchname
   ## all branch
    git branch -a
   ## current branch
    git branch
 ## Linux commands
  ### mkdir -p folder_name/folder_name 
    to make tree structured directories



