# learngit
This is just for learning basic git commands and getting familiar to it
Try below commands in LINUX box

mkdir demo
cd demo
git init (dev pc)
ls -la
------------------
git clone https://.....
-------------------
nano 1.txt
nano 2.txt
ls
git status
git add . (staging area)
git status 
git commit -m "firstcommit" (local repo)
git status
git log
git remote -v
git remote add origin url reference
git push origin master
--------------
git fetch origin master
git log origin/master (^master)
git pull origin master
----------------
git checkout -d branchname
-----
git log
---
git config --global merge.tool genometools
git mergetool

git config --global user.name "saurabh"
git config --global user.email "saurabh@xyz.com"
---
git show 'commitid'
---
To stage and commit multiple files at once we use -a flag with the
commit command
Syntax: git commit -a -m ‘message’
