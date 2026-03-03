This is a git laening series
Below are the Comments
nitial message

git user.name ""
git user.email ""

git clone
git cd subname --for changing directory
git status
git add "file name"
git commit -m "Comments"
git commit -am "Comments"--commits all changes 
git push origin main


Git LifeCycle

Insert/modify ->Add->Commit->Push

move to new repository

PS C:\$Noorudeen$\Git Practice\KRI dev> git remote add origin https://github.com/NoorudeenBI/KRI-dev.git
PS C:\$Noorudeen$\Git Practice\KRI dev> git branch

Git Branching

Create New Branch as per the team requirement

git branch -a
git checkout ccm ---- from main to created branch
git checkout main -- return to main branch
git diff ccm --- to comapre the difference
git merge ccm -- to merge the changes with main branch


git branch -M main   -----to change from master to main


GIt Revert

git log
git log --oneline
git revert with id
git push
git reset
git reflog
