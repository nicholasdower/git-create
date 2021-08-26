# git-create

```
Creates a new branch based on the repo's default branch. The branch name will
have the format: <git-email-username>/<name>

To install, add this script to your PATH, then run one of the following:

    git config --global alias.create '!git-create' # All repos
    git config alias.create '!git-create'          # Current repo only

Usage: git create <name>

Options:
    -h                               Print this message (Don't use --help).
```
