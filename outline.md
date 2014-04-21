![Git Logo](images/logo.png)

Learning a Distributed Version Control


---

## Installation 

https://git-scm.com

  - Use from Command Line
  - Use line endings Windows style, Unix Style

---

## Setup

    git config --global user.name <username>
    git config --global user.email <useremail>

---

## Create a repository

    git init

---

## See What Is Up

    git status

---
## See History

    git log

---

## See some history

    git log -n <count>

count is how many commits you want to see back

---

## Add Something

    git add test.txt

---

## Add Everything

    git add .

---

## Add Somethings

    git add *.txt

---

## Commit It!

    git commit

or

    git commit -m "message"

---

## Ignoring Files

    .gitignore

---

## Add a Remote

    git add remote <remote> <url>

remote - name of the remote

url - location of the remote

---

## Push It!

    git push <remote> <branch>

branch is optional - will push all branches

remote is optional - defaults to origin

---

## Getting Changes

    git pull <remote> <branch>

branch is optional - will get all branches

remote is optional - defaults to origin
---

## Pull Explained

    git fetch && git merge 
  
---

## Getting an existing repository

    git clone <url> <directoryname>

create a local copy of the repository at the given url

directoryName is optional
---

## Branching

### Create

    git branch <branchname>

### Switching Branches

    git checkout <branchname>

Shortcut

    git checkout -b <branchname>

creates and moves to the given branch
---

## Merging
  
    git merge <branchname>

---

## Non CLI

- [Github for Windows](windows.github.com)
- gitk - included
- [Tortoise Git](http://code.google.com/p/tortoisegit)
- [SourceTree](http://www.sourcetreeapp.com)
