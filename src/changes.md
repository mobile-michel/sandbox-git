---
title: Changes
description: Making & tracking changes with Git
layout: base
tags: primary
date: 2023-09-12
---

## Adding & committing changes

* ```git add .```
* ```git commit -m "Added new feature"```

## Viewing the repo history

- ```git log```
- ```git log --oneline```
- ```git log --graph```
- ```git show abcdef``` (hash of the commit)

## Undoing changes

### not been committed yet

- ```git checkout .```

### undo a commit

- ```git revert abcdef``` (hash of the commit)