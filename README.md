# gitCommand
commands used in git

__for creating repo in remote__      
git init   
git config --local user.name "(user_name)"   
git config --local user.eamil "(user_email)"   

__for adding remote url in local repo__     
git remote add origin (url_for_remote_repo)   

__for cloning repo to local__     
git clone (repo name)   

__for adding chages from local repo to remote repo__     
git add --all  
(OR) git add .  

__to check status__     
git status   

__for log__     
git log   
 
__for commit__     
git commit -m "(message for commit)"   

__for pushing to remote url__     
git push (remote_name) (branch_name)   

generally (remote_name) is origin   

__for pulling from specific branch__    
git pull (remote_name) (branch_name)   

__for creating brach__     
git branch (branch_name)   

__for moving to another branch__     
git checkout (branch_name)   

__for mergin one branch to another__     
__first checkout to branch where you want to merge__     
__so lets say you want to merge in branch1 from branch2__     
git checkout branch1   

git merge brach2    

__now we need to delete branch2 from local and remote repo__      
__from remote repo__     
git push --delete orign branch2   

__from local repo__      
git branch -d branch2   

__for fetching all branches from remote repo__     
git fetch --all   
(OR) git fetch (remote_name) (branch_name)    

__if you want to fetch branch that is only in remote repo and not in local repo then__     
git fetch (remote_name)   
git checkout --track (remote_name) (branch_name)   

__for merging specific commit from one branch to another__     
git cherry-pick (commit hash)   

__if had a conflict for files in local repo__    
git add --all   
git commit -m "(message)"  
git pull origin   


