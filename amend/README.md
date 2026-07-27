# Amend

## Amend the last commit
```bash
git add <file>
git commit --amend
```

## Remove a file from the last commit
```bash
git reset HEAD^ -- <file>
git commit --amend
```