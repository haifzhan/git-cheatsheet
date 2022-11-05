# stash

Stash staged files with a message

```git
git stash push -m "This is a message for the stash" -- $(git diff --staged --name-only)
```
