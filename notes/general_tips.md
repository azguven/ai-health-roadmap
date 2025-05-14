# General Tips and Commands

This file contains miscellaneous but useful tips, commands, and reminders that don’t fit into any specific tutorial or project notebook. It includes CLI commands, Git operations and other quick references.

## Index

- [Kaggle CLI](#kaggle-cli)
- [Git](#git)

## Kaggle CLI
Download and unzip a dataset into a folder:
```bash
kaggle datasets download uciml/pima-indians-diabetes-database -p data --unzip
```

## Git
Unstage a file after running git add:
```bash
git reset HEAD <filename>
```

Change the message of the last commit (before pushing):
```bash
git commit --amend
```
