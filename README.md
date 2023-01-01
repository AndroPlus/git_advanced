# git_advanced

# Git Squasing - REBASE with Interactive

git rebase -i HEAD~1
git rebase -i <COMMIT ID>
git rebase <source branch> <target branch>

# Git recent commit log modification
git commit --ammend -m <log message>
git commit --ammend

# Git checkout or create branchname
git checkout -b <branch name>

# Git checkout move to branch
git checkout <branchname> 

# Git push force on branch
git push -f origin <branch name>

# Git push to current branch to top of HEAD
git push origin HEAD

# Git pull origin
git pull origin <branch name>

#Git Stash
git stash
git stash pop 
git stash pop <0,1,2>
git stash list

#Git Cherry pick (cherry picking particular commit from a branch)
git checkout <branch>
git cherry-pick <commit id>


