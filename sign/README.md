# Sign

## Generate a GPG key
```bash
gpg --full-generate-key
```

## List GPG keys
```bash
gpg --list-secret-keys --keyid-format=long
```

## Set your signing key
```bash
git config --global user.signingkey <your-key-id>
```

## Sign a commit
```bash
git commit -S -m "message"
```

## Sign a tag
```bash
git tag -s v1.0 -m "version 1.0"
```

## Enable signing by default
```bash
git config --global commit.gpgSign true
```

## Check commit signatures
```bash
git log --show-signature
```