# Stash

## Stash current changes
```bash
git stash
```

## Stash with a message
```bash
git stash push -m "message"
```

## List stashes
```bash
git stash list
```

## Apply a stash
```bash
git stash apply stash@{n}
```

## Pop a stash
```bash
git stash pop
```

## Drop a stash
```bash
git stash drop stash@{n}
```

## Clear all stashes
```bash
git stash clear
```

## Create a branch from a stash
```bash
git stash branch <branch> stash@{n}
```
