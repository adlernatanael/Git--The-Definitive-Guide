# Git Definitive Guide - Summary

**Git-Definitive.pdf** is a visual and practical guide to the essential Git commands and workflows.  
Perfect for beginners, intermediate users, and professionals who need a quick and efficient reference.

Git is a fundamental tool for version control and collaboration in software projects. This guide is designed to be your companion in daily development work.

---

## Table of Contents

- [Setup & Init](#1-setup--init)
- [Stage & Snapshot](#2-stage--snapshot)
- [Branch & Merge](#3-branch--merge)
- [Inspect & Compare](#4-inspect--compare)
- [Tracking Path Changes & Ignoring Patterns](#5-tracking-path-changes--ignoring-patterns)
- [Share & Update](#6-share--update)
- [Rewrite History](#7-rewrite-history)
- [Temporary Commits (Stash)](#8-temporary-commits-stash)
- [Target Audience](#target-audience)
- [Benefits of the Guide](#benefits-of-the-guide)
- [Why Learn and Use Git?](#why-learn-and-use-git)

---

## 1. Setup & Init

- Configure user information (`git config`)
- Initialize local repositories (`git init`)
- Clone remote repositories (`git clone`)

## 2. Stage & Snapshot

- Add files to staging (`git add`)
- View differences (`git diff`, `git diff --staged`)
- Unstage files (`git reset`)
- Commit changes (`git commit`)

## 3. Branch & Merge

- Create and manage branches (`git branch`)
- Switch between branches (`git checkout`)
- Perform merges (`git merge`)
- Inspect commit history (`git log`)

## 4. Inspect & Compare

- Compare branches (`git diff branchB...branchA`)
- Inspect specific commits (`git show SHA`)
- Track file changes across renames (`git log --follow [file]`)

## 5. Tracking Path Changes & Ignoring Patterns

- Move and delete versioned files (`git mv`, `git rm`)
- Configure ignore patterns with `.gitignore`

## 6. Share & Update

- Add remote repositories (`git remote add`)
- Fetch and merge updates (`git fetch`, `git merge`)
- Push commits to remote repositories (`git push`)

## 7. Rewrite History

- Rebase and rewrite commit history (`git rebase`)
- Reset commits (`git reset --hard`)

## 8. Temporary Commits (Stash)

- Temporarily store changes (`git stash`)
- Restore changes (`git stash pop`)
- Clean up the stash (`git stash drop`, `git stash list`)

---

## Target Audience

- Beginner developers learning Git
- Intermediate users who want to refresh essential commands
- Professionals looking for a quick visual reference
- Teams in need of practical documentation for daily workflows

## Benefits of the Guide

- Straight to the point
- Visually organized
- Covers real-world team collaboration scenarios
- Includes advanced inspection and comparison commands
- Perfect for everyday development use

---

## Why Learn and Use Git?

Git is the most widely used version control system in the world. It enables developers and teams to:

- **Version code safely** — every change is tracked with a clear, traceable history.
- **Collaborate effectively** — with branches and merges, multiple people can work in parallel without conflicts.
- **Experiment freely** — branches and stash allow testing ideas without impacting main code.
- **Automate processes** — integrates with CI/CD tools, pipelines, and modern workflows.
- **Increase productivity and quality** — mastering Git is a highly valuable skill in today’s software industry.

Learning Git it’s about mastering a workflow that enables you to deliver software more efficiently, professionally, and reliably.
