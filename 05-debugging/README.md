# 05 — Debugging and Troubleshooting

## What Is Debugging?

Debugging is the process of finding, understanding, and fixing problems in software or development workflows.

When working with Git and GitHub, problems may include failed tests, merge conflicts, missing files, and incorrect branch names.

## 1. Check Your Git Status

Run:

```bash
git status
```

This shows your current branch, modified files, staged changes, and whether a merge is in progress.

## 2. Understand Common Git Errors

### Error: Uncommitted Changes

Git may prevent you from switching branches when local changes could be overwritten.

Check your changes:

```bash
git status
```

Commit changes you want to keep, or carefully stash them:

```bash
git stash
```

Restore stashed changes later with:

```bash
git stash pop
```

### Error: Merge Conflict

A merge conflict occurs when Git cannot automatically combine changes.

1. Run `git status`.
2. Open the conflicting file.
3. Look for `<<<<<<<`, `=======`, and `>>>>>>>`.
4. Choose the correct content and remove the conflict markers.
5. Stage the resolved file with `git add`.
6. Complete the merge with `git commit` when Git requires it.

### Error: Failed Tests

Read the workflow log and identify the failed step.

For Python tests, run:

```bash
python -m unittest discover -s 04-cicd-github-actions -p "test_*.py" -v
```

Fix the underlying problem and rerun the tests.

### Error: Wrong Branch

Check your current branch:

```bash
git branch --show-current
```

Switch to the intended branch:

```bash
git switch main
```

Only switch branches when doing so will not overwrite work you need to keep.

## 3. A Safe Debugging Checklist

- [ ] Read the complete error message.
- [ ] Run `git status`.
- [ ] Confirm the current branch.
- [ ] Identify the affected file.
- [ ] Make a focused correction.
- [ ] Run the relevant tests.
- [ ] Commit and push the fix when appropriate.

## Practice Exercise

Create a test failure in your calculator project by changing an expected result.

Run the tests and observe the failure. Restore the correct expected result and rerun the tests.

**Goal:** Learn to diagnose a problem from its error message instead of guessing.

## Key Takeaway

Good debugging starts with understanding the error, checking the current state, and making one deliberate change at a time.

**Next lesson:** Make your first meaningful contribution to an open-source project.
