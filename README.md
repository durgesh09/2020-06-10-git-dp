# 2020-10-06-git-dp

- `git init`: create git repository in current folder
- `git add`: to save the changes in staging area
- `git commit`: to save the changes in git repo
	-`git commit -m "<Message> `: oneline commit message without nano
- `git status`: to get the latest status of the changes

- `git log`: show you your log history
	- `git log --oneline`: one line version of your history

- `git diff`: to show difference in the file been edited
	- `git diff --staged`: show you differences in the staging area
	- `git diff HEAD~2`: diff 2 places back from HEAD
	- `git diff <HASH>`: diff 2 locations
- `git checkout <HASH> <FILE>`: revert file
- `git remote add origin <URL>`: add the url with the name 
- `git push origin master`: spends master branch on local computer
- `git pull origin master`: updates local with remote (master)
