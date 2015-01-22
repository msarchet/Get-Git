![Git Logo](images/logo.png)

Learning a Distributed Version Control

---

## Installation 

https://git-scm.com

  - Use from Command Line
  - Use line endings Windows style, Unix Style

---

## Setup

    git config --global user.name (username)
    git config --global user.email (useremail)

---

## Create a repository

    git init

---
## Getting an existing repository

    git clone (url) (directoryname)

create a local copy of the repository at the given url

directoryName is optional

---
## See What Is Up

    git status

---

## Branching

### Create

    git branch (branchname)

### Switching Branches

    git checkout (branchname)

Shortcut

    git checkout -b (branchname)

---
## Add Something

    git add <filename>

---

## Add Everything

    git add .

---

## Add Multiple Items 

    git add (glob | filenames)

---

## Commit It!

    git commit

or

    git commit -m "message"

---
## See History

    git log

---

## See some history

    git log -n (count)

count is how many commits you want to see back

---

## Push It!

    git push (remote) (branch)

branch is optional - will push all branches

remote is optional - defaults to origin

---

## Getting Latest

    git fetch

---

## Incorporate Changes

    git merge

---

## Pull It!

    git pull (remote) (branch)

branch is optional - will get all branches

remote is optional - defaults to origin

  
---

## Merging
  
    git merge (branchname)

---

## Ignoring Files

    .gitignore

---

## Add a Remote

    git add remote (remote) (url)

remote - name of the remote

url - location of the remote

---

## Non CLI

- Visual Studio ( ¯\_('')_/¯ )
- [Github for Windows](https://windows.github.com)
- [Tortoise Git](http://code.google.com/p/tortoisegit)
- [SourceTree](http://www.sourcetreeapp.com)
