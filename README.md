# Global Gitignore

A version-controlled global `.gitignore` file for use across all Git repositories.

## Setup

### 1. Symlink to `~/.gitignore`

```sh
ln -sf $PATH_TO_REPO/.gitignore ~/.gitignore
```

### 2. Configure Git to use it

Tell Git to use `~/.gitignore` as the global excludes file:

```sh
git config --global core.excludesFile ~/.gitignore
```

### Verify

```sh
git config --global core.excludesFile
# should output: ~/.gitignore
```

## Updating

Edit the `.gitignore` in this repository, commit, and push. Because `~/.gitignore` is a symlink, all repos on your machine pick up the changes immediately.
