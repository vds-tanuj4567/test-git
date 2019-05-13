# Git in action: CLI

### Plan
1. Explain what is Working directory,Staged Area and Local Repository  addressing and it's importance and explain  how the work flow is being taken place.
![ git workflow ]( https://github.com/vds-tanuj4567/test-git/tree/master/images/git1.png )
#### Example
``` 
git init gittest  //
cd gittest
vi f1.txt 
git status  
git add f1.txt
git status
git commit f1.txt
```
2. Explain what is branch and it's importance.
#### Example
``` 
git checkout -b branchname
```

3. Explain what is commit and need of commit and when it is to be done  with  live examples 
#### Example
```
git commit f1.txt
```
4. Explain what is diff and when it is used with a live examples
#### Example
```
git checkout -b m1
vi f1.txt
git checkout -b m2
vi f2.txt
git diff
```

5. Explain the need of **.gitignore** with a live examples.
6. Explain how stashing works and how we can stash untracked files.
```
vi f12.txt
git add f12.txt
git stash
```
###### to stash untracked files
```
git stash -u 
```
7. Explaining the need of merging and pros and cons of doing it.

![ merge ]( https://github.com/vds-tanuj4567/test-git/tree/master/images/git2.png )

```
git merge branch1 branch2
```
8. Explain the need of rebase, pros and cons and compare merge and rebase.

![ rebase ]( https://github.com/vds-tanuj4567/test-git/tree/master/images/rebase.png )

```
git rebase source target
```
9. Explain the need of Master branch and how it is considered different from others and it's importance.

> Master is a state of code where the entire source code is safe to deploy in production.
> It is the main branch where all the changes get merged back in.


