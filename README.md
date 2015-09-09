# HW

### Git basics
##### Introduction Sequence
##### Level 1 : Introduction to Git Commits
```
git commit
git commit
```

##### Level 2 : Branching in Git
```
git branch bugFix
git checkout bugFix
```

##### Level 3 : Merging in Git
```
git branch bugFix
git checkout bugFix
git commit
git checkout master
git commit
git merge bugFix
```

##### Level 4 : Rebase Introduction
```
git checkout -b bugFix
git commit
git checkout master
git commit
git checkout bugFix
git rebase master
```

### Git bonus
##### Ramping Up
##### Level 5 : Detach yo' HEAD
```
git checkout bugFix
git checkout C4
```

##### Level 6 : Relative Refs (^)
```
git checkout bugFix^
```

##### Level 7 : Relative Refs #2 (~)
```
git checkout master
git branch -f master C6
git checkout bugFix
git branch -f bugFix HEAD~3
git checkout master
git checkout HEAD~3
```

##### Level 8 : Reversing Changes in Git
```
git reset HEAD~1
git checkout pushed
git revert HEAD
```

### Screenshot
![image](https://cloud.githubusercontent.com/assets/11006675/9763214/5bc9c24a-56d6-11e5-9140-4f0b1e72a2bf.png)

