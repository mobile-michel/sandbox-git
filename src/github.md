---
title: Collaborate
description: Collaborating with Git & GitHub
layout: base
tags: primary
date: 2023-09-10
---

## Working with remote repos

* ```git remote add origin https://github.com/user/repo.git```
* ```git push origin main```
* ```git pull origin main```

## Creating & merging pull requests

### create the pull request

1. push your changes to a separate branch in the remote repository: ```git push origin new-feature```
2. navigate to the repository on GitHub and clock the "Compare & pull request" button
3. select the branch you want to merge and the branch you want to merge into
4. review the changes that will be included in the pull request
5. enter a title and description for the pull request
6. click the "Create pull request" button to create the pull request

### merge the pull request

1. navigate to the pull request on GitHub
2. review the changes included in the pull request
3. if the pull request is ready to be merge, click the "Merge pull request" button
4. enter a commit message for the merge & click the "Confirm merge" button