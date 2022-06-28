# git-cheatsheet
git note for self


### Rebase
```
git pull --rebase
```

### Combine n commits
```
git rebase -i HEAD~n
```
Change all `pick` to `fixup` except the most recent commit
From 

```
pick commit n
pick commit n-1
pick commit n-2
...
pick commit 1
```
To
```
pick commit n
fixup commit n-1
fixup commit n-2
...
fixup commit 1
```
The n commits will be combined into 1 commit and the commit message will be `commit n`

### Change commit message
```
git commit --amend
```





