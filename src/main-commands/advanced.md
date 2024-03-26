---
title: Advanced
description: Advanced Git techniques
date: 2023-09-10
---

## Resolving merge conflicts

### example:

```
<<<<<<<<HEAD
This is the version in the current branch
======
This is the version in the incoming branch
>>>>>>>>incoming-branch
```

1. you need to delete the conflict markers and the unwanted lines
2. save the file
3. mark the file as resolved: ```git add file.txt```
4. continue the merge: ```git merge --continue``` 
5. repeate the process for each file with merge conflict
6. complete the merge by commiting the changes: ```git commit```

## Using Git stash to temporarily store changes

- switch branches without committing the changes
- restore a previous version of your code without committing
- save to the stash and restore the previous version: ```git stash```
- view the list of stashed changes: ```git stash list```
- restore the stash and leave the stash list: ```git stash apply stash@{0}```
- restore the stash & remove from stash list: ```git stash pop stash@{0}```
- remove a stash from the stash list: ```git stash drop stash@{0}```