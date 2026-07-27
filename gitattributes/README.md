# .gitattributes

## Use cases
- Keep consistent line endings across platforms
- Mark files as binary
- Enable Git LFS for large files
- Set custom diff or merge rules

## Force LF line endings
```text
*.sh text eol=lf
```

## Mark a file as binary
```text
*.png binary
```

## Enable LFS for a file type
```text
*.psd filter=lfs diff=lfs merge=lfs -text
```

## Use a custom diff driver
```text
*.md diff=markdown
```

## Check attributes
```bash
git check-attr --all README.md
```

