# Combine n commits

Before doing any of the combine commands, make sure all changes have been commited.

```git
git rebase -i HEAD~n
```

Change all `pick` to `fixup` except the most recent commit

From

```git
pick commit n
pick commit n-1
pick commit n-2
...
pick commit 1
```

To

```git
pick commit n
fixup commit n-1
fixup commit n-2
...
fixup commit 1
```

The n commits will be combined into 1 commit and the commit message will be `commit n`
