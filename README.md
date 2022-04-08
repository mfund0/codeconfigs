## codeconfigs
My VS Code config backups

### Backup extentions to file `extensions.txt`
```bash
code --list-extensions >> extensions.txt
```

### Install from file `extensions.txt`
```bash
cat extensions.txt | xargs -n 1 code --install-extension
```
