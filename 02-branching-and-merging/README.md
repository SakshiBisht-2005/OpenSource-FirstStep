# 02 — Branching and Merging

## What Is a Git Branch?

A branch is an independent line of development. It lets developers work on features or fixes without directly changing the main branch.

## Why Use Branches?

- Develop new features safely.
- Fix bugs without disturbing other work.
- Collaborate with other developers.
- Review changes before merging them.

## Common Branch Names

- `main` — the stable primary branch.
- `feature/branching-basics` — a new feature or lesson.
- `fix/readme-typo` — a bug fix or documentation correction.

## Useful Git Commands

```bash
git branch
git switch -c feature/my-feature
git switch main
git merge feature/my-feature
```

### What These Commands Do

- `git branch` lists local branches.
- `git switch -c` creates and switches to a new branch.
- `git switch main` switches back to the main branch.
- `git merge` integrates changes from another branch into your current branch.

## Practice Exercise

1. Create a branch named `feature/my-first-change`.
2. Add a new example to this lesson.
3. Commit your change.
4. Open a pull request into `main`.
5. Review and merge your pull request.

## What Is a Merge Conflict?

A merge conflict happens when Git cannot automatically reconcile overlapping changes. Developers must review the conflicting content and decide what the final version should be.

## Summary

Branches make collaboration safer and help developers organize their work. Pull requests provide a place to discuss and review changes before merging.

Next, learn how pull requests work and how to resolve merge conflicts.
