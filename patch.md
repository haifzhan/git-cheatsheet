# Patch

Both **staged** and **unstage** changes:

```git
git diff HEAD > patch_name.txt
```

For **unstaged** changes:

```git
git diff > patch_name.txt
```

For **staged** changes:

```git
git diff --cached > patch_name.txt
```
