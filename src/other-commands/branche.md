---
title: Branches
description: Create & merge branches
layout: base
tags: secondary
date: 2023-09-06
---

## Create a new branch

* git branch my-branch (create a new branch to store any new changes)
* git checkout my-branch (switch to that branch, line of development)
* git add --all (stage the changed files)
* git commit -m "my snapshot" (take a snapshot of the staging area, anything that's been added)
* git push --set-upstream origin my-branch (push changes to GitHub)

## Merge the branch

* git checkout main (switch to the main branch)
* git merge my-branch (merge "my-branch" with the "main" branch)