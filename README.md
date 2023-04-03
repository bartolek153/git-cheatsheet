
# Git Commands Cheatsheet

## Remote repositories

```bash
git commit -m <message> -a --amend
```


```bash
git remote add origin <repo_url>
git branch -M main
git push -u origin main
```

## Logging

```bash
git log --oneline --graph --all
```

## Tagging

```bash
git tag -a <tag> -m message
git push --tags
git fetch --tags
```
