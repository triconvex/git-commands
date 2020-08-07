# git-commands
## 명령어

### Getting and Creating Projects
```
git init
```
```
git clone {remote url}
```
### Basic Snapshotting
```
git status
```
```
git add .
```
```
git commit -m "{commit message}"
```
```
git commit --amend
```
```
git reset --hard HEAD
git reset --hard HEAD^
git reset --hard HEAD~{the number of commits}
```
### Branching and Merging
```
git branch -m {new branch name}
```
```
git checkout {branch name}
```
```
git checkout -t {remote name}/{branch name}
```
```
git checkout -b {branch name}
```
```
git checkout -D {branch name}
```
```
git log
```
```diff
- git stash save (deprecated)
+ git stash push
```
```
git stash pop
```
```
git stash apply
```
### Sharing and Updating Projects
```
git fetch
```
```
git pull
```
```
git push -u {remote name} HEAD
```
```
git push {remote name} --delete {branch name}
```
```
git remote -v
```
```
git remote add {remote name} {remote url}
```
```
git remote set-url {remote name} {new remote url}
```
### Inspection and Comparison
```
git log
```
### Patching
```
git rebase {branch name}
```
```
git rebase -i HEAD~{the number of commits}
```
```
git revert {commit ID}
```
---

## 참고 
- [@jeonghwan-kim](https://github.com/jeonghwan-kim)님의 리포지토리(https://github.com/jeonghwan-kim/git-usage)를 보고 생성해봤습니다.
- https://git-scm.com/docs
