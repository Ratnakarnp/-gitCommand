# gitCommand
commands used in git

_for creating repo in remote   
git init   
git config --local user.name "<user_name>"   
git config --local user.eamil "<user_email>"   

_for adding remote url in local repo   
git remote add origin <url_for_remote_repo>   

_for cloning repo to local   
git clone <repo name>   

_for adding chages from local repo to remote repo   
git add --all  
<OR> git add .  

_to check status   
git status   

_for log   
git log   
 
_for commit   
git commit -m "<message for commit>"   

_for pushing to remote url   
git push <remote_name> <branch_name>   

generally <remote_name> is origin   

_for pulling from specific branch   
git pull <remote_name> <branch_name>   

_for creating brach   
git branch <branch_name>   

_for moving to another branch   
git checkout <branch_name>   

_for mergin one branch to another   
_first checkout to branch where you want to merge   
_so lets say you want to merge in branch1 from branch2   
git checkout branch1   

git merge brach2    

_now we need to delete branch2 from local and remote repo    
_from remote repo   
git push --delete orign branch2   

_from local repo    
git branch -d branch2   

_for fetching all branches from remote repo   
git fetch --all   
<OR> git fetch <remote_name> <branch_name>    

_if you want to fetch branch that is only in remote repo and not in local repo then   
git fetch <remote_name>   
git checkout --track <remote_name> <branch_name>   

_for merging specific commit from one branch to another   
git cherry-pick <commit hash>   

_if had a conflict for files in local repo  
git add --all   
git commit -m "<message>"  
git pull origin   


