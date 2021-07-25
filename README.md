# git-cheatsheet

Handy git commands that are too niche to remember.

## Show diff of staged (but not commited) changes

```shell
git diff --cached
```

## Make changes to last commit

**[Source](https://stackoverflow.com/a/927386)**

```shell
git reset HEAD~
# Make some changes
git add .
git commit -c ORIG_HEAD
```
