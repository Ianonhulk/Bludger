## Creating new repositories
Creating new repositories is a piece of cake:
```bash
./bludger.py -n {repository_name}
```

## Cloning any repository
Cloning new/existent repositories is also simple, except you need to explicitly mention a slug or create a new repository.
```bash
./bludger.py -n {repository_name} --clone
```
or
```bash
./bludger.py -s {username}/{repository} --clone
```