# gitCommand
commands used in git

-- for creating repo in remote
git init
git config --local user.name "<user_name>"
git config --local user.eamil "<user_email>"

-- for adding remote url in local repo
git remote add origin <url_for_remote_repo>

-- for cloning repo to local
git clone <repo name>

-- for adding chages from local repo to remote repo
git add --all
<OR> git add .

-- to check status
git status

-- for log
git log

-- for commit
git commit -m "<message for commit>"

-- for pushing to remote url
git push <remote_name> <branch_name>

generally <remote_name> is origin

-- for pulling from specific branch
git pull <remote_name> <branch_name>

-- for creating brach
git branch <branch_name>

-- for moving to another branch
git checkout <branch_name>

-- for mergin one branch to another
-- first checkout to branch where you want to merge
-- so lets say you want to merge in branch1 from branch2
git checkout branch1

git merge brach2

-- now we need to delete branch2 from local and remote repo
-- from remote repo
git push --delete orign branch2

-- from local repo
git branch -d branch2

-- for fetching all branches from remote repo
git fetch --all
<OR> git fetch <remote_name> <branch_name>

-- if you want to fetch branch that is only in remote repo and not in local repo then
git fetch <remote_name>
git checkout --track <remote_name> <branch_name>

-- for merging specific commit from one branch to another
git cherry-pick <commit hash>

-- if had a conflict for files in local repo
git add --all
git commit -m "<message for conflict"
git pull origin


