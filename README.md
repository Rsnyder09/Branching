# Git Cheat Sheet and Branching Practice


## Overview

Common command reference, and practicing with commits and branches

## Basic Commands
* `git init` - initialize local Git repo
* `git add fileName` - stage changed file `fileName`
for commit
* `git commit -m"message"` - commit staged changes, with commit message "message"

## Info commands
* `git status` -show status of working directory
* `git log` - list local commit history
* `git log --oneline` - list local commit history in compact format

## Branching Commands
* `git branch` - list local branches
* ` git branch -m newName` - rename current branch to `newName`
* `git branch branchName` - create local branch `branchName`
* `git checkout branchName` - switch to local branch `branchName`

## Remote
* `git remote add origin url` - configure `url` as a remote repo, with alias `origin`
* `git push origin branchName` - push local commits to remote repo `origin` on branch `branchName`