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

Commit
======
git commit -m "first commit"

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

Switch default branch
=====================
git checkout develop