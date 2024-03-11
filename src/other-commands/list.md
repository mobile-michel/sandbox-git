---
title: List
description: List of Git commands
date: 2023-09-10
---

## Git States

* git --version
* git init
* git status
* git log

## Synchronise Changes

Working Directory > [add] > Staging Area > [commit] > Local Repository > [push] > Remote Repository  
Working Directory > [commit -a] > Local Repository  
Working Directory < [checkout] < Staging Area  
Working Directory < [checkout HEAD] < Local Repository < [fetch] < Remote Repository  
Working Directory < [pull] < Remote Repository  

* git add (add a file to the staging area)
* git commit (commit files from the staging area to the local repository)
* git push (send files to the remote repository)
* git commit -a (directly commit modified and deleted files into the local repository without new files)
* git checkout (get a file from the staging area)
* git checkout HEAD (get a file from the local repository)
* git fetch (get files from the remote repository)
* git pull (get files from the remote repository and put a copy in the working directory)

## Make Changes

* git show
* git diff
* git log

## Branches

* git branch
* git switch
* git merge