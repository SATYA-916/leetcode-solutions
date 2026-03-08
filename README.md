# Git & GitHub Quick Guide (Beginner Workflow)

This repository is used to store my **DSA practice solutions** and to remember the **basic Git workflow**.

---

## Folder Structure

DSA/
   hello.py
   README.md

More files will be added as I solve problems.

---

## First Time Setup (Only Once)

Initialize Git in the project folder:

git init

Add files to Git tracking:

git add .

Create the first commit (save snapshot):

git commit -m "first commit"

Connect the project to the GitHub repository:

git remote add origin https://github.com/SATYA-916/leetcode-solutions.git

Set the main branch name:

git branch -M main

Upload the code to GitHub:

git push -u origin main

After this step the **local project and GitHub repository are connected**.

---

## Daily Workflow

Whenever I add or modify code:

1. Add changes

git add .

2. Save the changes

git commit -m "describe what changed"

3. Upload to GitHub

git push

Example:

git add .
git commit -m "added two sum solution"
git push

---

## Checking Changes (Optional)

To see which files changed:

git status

---

## Summary

First time setup → multiple commands.

Daily use → only 3 commands:

git add .
git commit -m "message"
git push

This workflow will be used to upload all future DSA solutions to GitHub.
