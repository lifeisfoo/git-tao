Git Tao
=======
![Tao logo](http://upload.wikimedia.org/wikipedia/commons/1/17/Yin_yang.svg)

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
