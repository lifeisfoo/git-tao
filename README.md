Git Tao ☯
=======

### Already moved files (without git mv)?
```
git add -u //will restore the peace
```

### Forgot to switch branch before editing your files?
```
git add .
git stash
git checkout 'branchname'
git stash pop
git commit
```

### Wrong remote tracked branch
```
git branch --set-upstream-to origin/my-default-fetch-branch
```

### Wrong commit (amend)
Make all the changes you need, then:
```
git add .
git commit --amend
```

### Wrong commit (already pushed)
Execute the _"Wrong commit"_ commands, then:
```
git push -f origin master
```
