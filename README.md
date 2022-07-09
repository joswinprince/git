# git

## git commands
***

### git reset command

```
$ git reset --hard HEAD       (going back to HEAD) 
//  The purpose of the “git reset” command is to move the current HEAD to the commit specified

$ git reset --hard HEAD^      (going back to the commit before HEAD)
$ git reset --hard HEAD~1     (equivalent to "^")

$ git reset --hard HEAD~2     (going back two commits before HEAD)
```
### Stage all files into git
```
git add .
```
### Undo Git Add using restore
```
git restore --staged <file>
```
