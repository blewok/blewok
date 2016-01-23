---
layout: post
title: "Pluralsight's Advanced Git"
date: 2016-01-01
---

```
git add -p # add lines interactively
# Have git branch and commit id in zsh prompt
git reflog
tree dir
# Aliases rule
git status --short
grep -r '====' * # search for unresolved merge conflicts
git checkout -b branch-name commit-id # creates branch for commit
git log -S'text to search for' # searches text in git repository, including history
```

Branches are just labels. These can be freely moved, because commits history stays immutable.