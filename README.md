pwd-navigate to ur desired directory
git init-initializing a new empty git repo
git config -- global usrnm "---"
git congig --global usremail "email"
git config --list to view config of the usr
git remote -v -to chk remote repo w the local repo
git remote add origin https://------ >to add new remote in the dir where repo is stored at
ls - list all files n dir
cat - to view the file wout opening
echo "---" >> abcd.txt - to add txt in file wout opening it
git status - to chk status
git add abcd.txt - to tat files to staging area
git add . - to add all the changes to staging area
git log - to view commit history
git log --oneline - to voew cmt history in 1line
git push origin main - to push changes to remote 
git push -u origin main - to set origin main as default so tat we can give only git push command
git log -p - to display the commit history w patch diff
git diff master origin master - to show the diff btwn the local master branch nd remote origin master branch
git commit -m "----"-commit the staged changes w msg
git fetch origin master - fetch the latest changes frm the remote origin repo's master branch wout merging them into local master branch
git push origin master - push the local master branch changes to the remote origin repo
git pull origin master - pull the local master branch changes to the remote origin repo
git branch - to chk the branch
git branch dev - to create new branch called dev
git switch dev - switch btwn branches
git switch -c (or)git checkout -b - to create nd switch branch
git diff master dev - to show diff btwn master nd dev branch
git checkout master - to swap master branch
git merge dev - merge dev into master
git branch - to view all branches
git branch -d dev - to delete dev branch
git cherry-pick +cmtID - to merge selected commit to another branch (commit ID should be taken independent)
git tag V-.- - to create tag 
git tag - to all tags
git show V-.- - to view tat particular tag w tat ID
git push origin V-.- - to push origin V-.- to remote repo
git tag -d V-.- - to del tat tag 
vi .gitignore - to add git ignore file in repo
git reset abcd.txt - unstage abcd.txt but keep its changes in the wrking dir
git reset -- hard HEAD~1 - it create new commit tat reverse the old commit
git reset --soft HEAD~1 - it removes the commit but keeps ur changes staged
git revert cmtID - to revert the changes
git commit --amend --no-edit - modify my previous commit using the current staged changes keeping the same cmt msg
