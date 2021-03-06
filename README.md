
![alt text](img/git.png)

## base
https://realpython.com/python-git-github-intro/

## advance
https://realpython.com/advanced-git-for-pythonistas/


## some commands …

```bash
git add my_new_file1.md
git status
git commit -a -m "modifiche fatte"
git push
git checkout master -b my_feature_one
git commit -a -m "modify new file with blablabla"
git branch
git checkout master
git branch
git merge --no-ff my_feature_one
```
to remove branch ( local and remote)

```
git branch -d my_feature_one
git push

git branch -d my_feature_two
git push
git branch -D my_feature_two
git push --delete origin my_feature_two
```

To delete a local branch
```
git branch -d the_local_branch
```

To remove a remote branch (if you know what you are doing!)
```
git push origin :the_remote_branch
```

or simply use the new syntax (v1.7.0)
```
git push origin --delete the_remote_branch
```

to seee HEAD and commit status and add TAG

```
git log
git tag -a messo_tag_001 8f3b60517d2d887f6a8a214f701039b1b320bcc7
git tag
git show
git push origin messo_tag_001
```

## Useful link reference ...

### Git add 
https://stackoverflow.com/questions/572549/difference-between-git-add-a-and-git-add

```
git add -A 	    stages all changes
git add . 		stages new files and modifications, without deletions
git add -u 	    stages modifications and deletions, without new files
```

### Git config
show all config parameters
```
git config -l
```
set *email*
```
git config --global user.email "email@example.com"
```

https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address


### GitFlow
https://jeffkreeftmeijer.com/git-flow/

### Resetting, Checking Out & Reverting
https://www.atlassian.com/git/tutorials/resetting-checking-out-and-reverting

### Git Tip of the Week: Understanding the Index
https://alblue.bandlem.com/2011/10/git-tip-of-week-understanding-index.html

### Git Tools - Revision Selection
https://git-scm.com/book/en/v2/Git-Tools-Revision-Selection

### Learning ...
https://learngitbranching.js.org/


