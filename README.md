# VS Code Customizations

This repository contains my Visual Studio Code backup configuration files and extension list.

## Included Files

-`settings.json`  → VS Code settings

-`extensions.txt`  → Installed Extensions List

## Backup Extensions

Export Installed Extensions:


```bash
code --list-extensions > extensions.txt
```

## Restore Extensions

Installed extensions from backups:
```bash
cat extensions.txt | xargs -L 1 Code install extension
```
