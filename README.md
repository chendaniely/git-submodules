# git-submodules
Notes on using git submodules (nested git repositories)

## New submodules

### Cloning a repo with submodules

```bash
git clone --recursive <URL>
```

### Add a repo as submodule

```bash
git submodule add <URL>
# git submodule update --remote
```

## Updating submodules

### update and clone new submodules
```bash
git submodule update --init --recursive
```
