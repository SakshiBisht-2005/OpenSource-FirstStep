# 01 — Git and GitHub Basics

Welcome to the first lesson of OpenSource-FirstStep!

In this lesson, you'll learn what Git and GitHub are and how developers use them to collaborate on projects.

## 1. What is Git?

Git is a version control system that tracks changes in files over time.

With Git, you can:
- Track changes to your code.
- Save snapshots using commits.
- Create branches to work on new features.
- Compare changes and resolve conflicts.
- Restore earlier versions of your work.

## 2. What is GitHub?

GitHub is an online platform for hosting Git repositories and collaborating with other developers.

It provides tools such as:
- Repositories
- Issues
- Pull requests
- Code reviews
- GitHub Actions for automation

## 3. Git vs GitHub

| Git | GitHub |
|---|---|
| A version control system | An online collaboration platform |
| Can work locally on your computer | Hosts repositories online |
| Tracks changes through commits | Supports pull requests and code reviews |
| Supports branching and merging | Adds collaboration and automation features |

## 4. Important Git Commands

```bash
git status
git add README.md
git commit -m "Add my first lesson"
git log
git branch
```

- `git status` shows the state of your working directory.
- `git add` stages changes for the next commit.
- `git commit` records staged changes.
- `git log` displays commit history.
- `git branch` lists your local branches.

## 5. Practice Exercise

1. Create a text file named `hello.txt`.
2. Write a short introduction to yourself as a learner.
3. Check your changes using `git status`.
4. Stage the file using `git add hello.txt`.
5. Commit it using `git commit -m "Add first practice file"`.

## 6. What You Learned

- Git tracks file changes.
- GitHub helps developers collaborate.
- Commits record changes.
- Staging lets you select which changes go into a commit.

## Next Lesson

In the next module, we'll learn how to create branches, switch between them, merge changes, and resolve merge conflicts.

Happy learning! 