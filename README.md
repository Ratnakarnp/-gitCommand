# gitCommand
commands used in git

__for creating repo in remote   
git init   
git config --local user.name "<user_name>"   
git config --local user.eamil "<user_email>"   

__for adding remote url in local repo   
git remote add origin <url_for_remote_repo>   

__for cloning repo to local   
git clone <repo name>   

__for adding chages from local repo to remote repo   
git add --all  
<OR> git add .  

_to check status   
git status   

__for log   
git log   
 
__for commit   
git commit -m "<message for commit>"   

__for pushing to remote url   
git push <remote_name> <branch_name>   

generally <remote_name> is origin   

__for pulling from specific branch   
git pull <remote_name> <branch_name>   

__for creating brach   
git branch <branch_name>   

__for moving to another branch   
git checkout <branch_name>   

__for mergin one branch to another   
__first checkout to branch where you want to merge   
__so lets say you want to merge in branch1 from branch2   
git checkout branch1   

git merge brach2    

__now we need to delete branch2 from local and remote repo    
__from remote repo   
git push --delete orign branch2   

__from local repo    
git branch -d branch2   

__for fetching all branches from remote repo   
git fetch --all   
<OR> git fetch <remote_name> <branch_name>    

__if you want to fetch branch that is only in remote repo and not in local repo then   
git fetch <remote_name>   
git checkout --track <remote_name> <branch_name>   

__for merging specific commit from one branch to another   
git cherry-pick <commit hash>   

__if had a conflict for files in local repo  
git add --all   
git commit -m "<message>"  
git pull origin   


