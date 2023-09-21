# Git Cheat Sheet and Branching Practice

## Overview

Common command reference, and practicing with commits and branches.

## Basic Commands
* `git init` - initialize local Git repo
* `git add fileName` - stage changed file `fileName`
for commit
* `git commit -m"message"` - commit staged changes, with commit message "message"

## Info commands
* `git status` -show status of working directory
* `git log` - list local commit history
* `git log --oneline` - list local commit history in compact format
* `git config --list` - show config settings for local repo

## Branching Commands
* `git branch` - list local branches
* ` git branch -m newName` - rename current branch to `newName`
* `git branch branchName` - create local branch `branchName`
* `git checkout branchName` - switch to local branch `branchName`
* `git checkout -b branchName` - create and switch to `branchName`

## Remote Commands
* `git remote add origin url` - configure `url` as a remote repo, with alias `origin`
* `git push origin branchName` - push local commits to remote repo `origin` on branch `branchName`
* `git push -u origin branchName` - push and make `origin` the default remote for futher `git push`
* `git pull origin branchName` - pull and attempt to merge remote `branchName` into current local branch


