## Introduction to Git and GitHub for Python Developers

https://realpython.com/python-git-github-intro/


## Basic Usage

### Creating a New Repo
To work with Git, you first need to tell it who you are. You can set your username with the git config command:

```
$ git config --global user.name "your name goes here"
```

```
$ mkdir example
$ cd example
$ git init
Initialized empty Git repository in /home/jima/tmp/example/.git/
```

```
$ git status
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
```

### Adding a New File

```python
# hello.py
print('hello Git!')
```

```
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	hello.py

nothing added to commit but untracked files present (use "git add" to track)
```

```
git add hello.py 
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   hello.py
```

```
git restore --staged hello.py 
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	hello.py
```

