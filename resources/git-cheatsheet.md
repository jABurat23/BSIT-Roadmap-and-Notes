# 🧰 Git Cheatsheet

> Quick reference for managing this repo and future projects.

---

## 🚀 The Big 3 (Use These Every Day)

| Command | What it does |
|---------|--------------|
| `git add .` | Stages all changes (puts files in the box) |
| `git commit -m "message"` | Saves a snapshot with a label |
| `git push` | Sends your commits up to GitHub |

## 📁 Starting a Repo

| Command | What it does |
|---------|--------------|
| `git init` | Turns a normal folder into a Git repo |
| `git clone <url>` | Downloads a repo from GitHub to your computer |

## 👀 Checking Status

| Command | What it does |
|---------|--------------|
| `git status` | Shows what files have changed or are staged |
| `git log` | Shows the history of all your commits |
| `git log --oneline` | Same but cleaner, one line per commit |

## 🌿 Branches

| Command | What it does |
|---------|--------------|
| `git branch` | Lists all branches |
| `git branch <name>` | Creates a new branch |
| `git checkout <name>` | Switches to that branch |
| `git checkout -b <name>` | Creates AND switches in one step |
| `git merge <name>` | Merges a branch into your current one |

## ⏪ Undoing Things

| Command | What it does |
|---------|--------------|
| `git restore <file>` | Discards unsaved changes in a file |
| `git reset HEAD~1` | Undoes your last commit (keeps the files) |
| `git stash` | Temporarily shelves changes to use later |
| `git stash pop` | Brings those shelved changes back |