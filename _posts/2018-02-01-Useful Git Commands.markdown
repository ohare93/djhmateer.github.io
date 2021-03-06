---
layout: post
title:  Useful Git Commands
categories: Git
published: true 
redirect_from: git/2018/02/01/Useful-Git-Commands.html 
sitemap: true
---

I use Git every day. Here are my favourite commands, which I frequently forget, therefore I've published here. 

```
git reset --hard head
git clean -dfx

git push -u origin textChanges

--working on OS projects
git checkout master
git fetch upstream
git merge upstream/master
git checkout 2204
git rebase master
git push origin 2204 -f  

git stash
git apply

git branch -d 2204 (delete local branch)
git branch -D 2204 (force delete if hasn't been merged)
git push origin --delete 2204 (delete remote branch)

git branch -u origin/masterDemoMoneyMinded (sets upstream branch)

git push -u origin davem/1234 (shortcut to set upstream branch only need to do once)

git tag -a v1.0.4 -m "adding a tag
git push --tags
```