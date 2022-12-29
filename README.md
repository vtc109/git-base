# git-base
# Add remote repo 
git remote add <repo-name> <link-url-of-repo>

#Delete branch 
git branch -d <branch-name>

#Recover deleted branch
git checkout -b <branch-name> <sha>

#Rebase (change root)
(in sub-main)
git rebase main