delete history

git checkout --orphan temp_branch
git add -A
git commit -m "hide history"
git branch -D master
git branch -m master
git push -f origin master

edit github repo settings to "derekdai.com" as default
