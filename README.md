# tooplate.com
https://www.tooplate.com/

git config --global user.email ""
git config --global user.name "name"
git init
git add .
git commit -m " " (local commit)
git branch -M main
git push -u origin main

Clone repo to local-
git clone url

Local to remote-
cd local_repo
git remote add origin repor_url
git push -u origin main
git pull (fetch latest changes)

git checkout -B branch_name (create branch)

git pull origin master/branch_name --allow-unrelated-histories

git branch new-branch-name
git checkout new-branch-name
cd new-branch-name
git push -u origin new-branch-name

git log --oneline
git show commit_id

git fetch --all (fetch remote branches)
git branch -a (local and remote branch)

git branch -c sprint1
git checkout sprint1
