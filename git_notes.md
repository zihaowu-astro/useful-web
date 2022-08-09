# Only Merge part of the branch
1. create a temperate branch 

```
git checkout -b A_temp
```

2. 
```
git merge B 
```

3. go back to branch A and cover them 
```
git checkout A
git checkout A_temp [files]
```

4. delete 
```
git branch -d A_temp
```
