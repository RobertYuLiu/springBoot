# springBoot
practice spring boot applications

https://github.com/RobertYuLiu

github account:
username: RobertYuLiu
pw: liuyu1162

basic command

git status

git pull

git add .

git add file name here

git commit -m "something..."

git push


https://stackoverflow.com/questions/20568971/git-pull-keeps-telling-me-to-stash-local-changes-before-pulling

Firstly, stash your changes

git stash
Then, pull in the changes from origin.

git fetch origin && git rebase origin/(branch name)
Next, add the stash back in to your working directory:

git stash pop