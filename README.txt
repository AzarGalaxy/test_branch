create a new repository on the command line
===========================================
git init
git add README.txt
git commit -m "first commit"
git remote add origin https://github.com/AzarGalaxy/test_branch.git
git push -u origin master


or push an existing repository from the command line
====================================================
git remote add origin https://github.com/AzarGalaxy/test_branch.git
git push -u origin master

Add a file
==========
git add README.txt

Add all file under current folder
=================================
git add .

Add all files and folders
==========================
git add --all
or
git add -A

Remove file from stage
=======================
git rm --cached README.txt

Commit all file after stage
===========================
git commit -m "first commit"

Commit specific file
====================
//No need to stage
git commit README.txt -m "test"

Add and commit
===============
git -am "message"

See changes for tracked and untracked files
===========================================
git status

Push all changes to git
======================
git push

Store credential
================
git config credential.helper store


==============
*** BRANCH ***
==============
Show all branches
==================
git branch -a

Create new branch
=================
git branch develop

Create new branch with checkout with specific branch
====================================================
git checkout -b staging master

Switch default branch
=====================
//this is will checkout from the current branch
git checkout develop

Merge two branch
================
git merge develop

Delete branch
=============
//can't delete current branch from currently selected branch
git branch -d test

Get last commits
=================
git branch -v

Get branches that are merged with current branch
================================================
git branch --merged

Get branches that are not merged with current branch
=====================================================
git branch --no-merged

Local branch to remote branch
=============================
git push -u origin develop
