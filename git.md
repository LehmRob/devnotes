# Useful GIT commands

- Add all unstaged files

```
for i in $(git status -s | grep "??" | cut -d " " -f 2); do git add $i; done
```
