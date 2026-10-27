# 06 — Your First Open-Source Contribution

## What Is Open Source?

Open-source software is software whose source code is available under a license that allows people to use, study, modify, and share it under specified conditions.

Contributors help improve projects by fixing bugs, improving documentation, writing tests, and adding useful features.

## Why Contribute to Open Source?

- Practise real-world development workflows.
- Improve your Git and GitHub skills.
- Learn how to read unfamiliar code.
- Receive feedback from other developers.
- Build a portfolio of meaningful contributions.

## Step 1: Find a Project

Explore beginner-friendly opportunities at:

- [GitHub Contribute](https://github.com/contribute)
- [GitHub Docs](https://github.com/github/docs)

Choose a project that interests you. Read its README, contribution guidelines, and code of conduct if available.

Look for issues labelled `good first issue` or `help wanted`.

## Step 2: Choose a Useful Issue

Before starting work:

1. Read the issue carefully.
2. Check whether someone is already working on it.
3. Review the project's contribution guidelines.
4. Ask a question or comment on the issue if clarification is needed.
5. Make sure your proposed change addresses a real need.

Do not submit unrelated or unnecessary changes just to create a pull request.

## Step 3: Fork the Repository

A fork is your own GitHub copy of another repository.

1. Open the original project on GitHub.
2. Click **Fork**.
3. Choose your GitHub account.
4. Create the fork.

You can experiment in your fork without directly changing the original repository.

## Step 4: Clone Your Fork

Copy the URL of your fork and run:

```bash
git clone YOUR_FORK_URL
cd REPOSITORY_NAME
```

Replace `YOUR_FORK_URL` and `REPOSITORY_NAME` with the actual values.

## Step 5: Create a Branch

Create a separate branch for your contribution:

```bash
git switch -c docs/improve-installation-guide
```

Use a descriptive branch name that reflects the change you intend to make.

## Step 6: Make and Test Your Changes

Make a small, useful change that addresses the issue.

Before committing:

- Review the changed files.
- Check spelling and formatting.
- Run the relevant tests.
- Follow the project's contribution guidelines.

Inspect your changes with:

```bash
git status
git diff
```

## Step 7: Commit and Push

Stage the intended changes:

```bash
git add .
git commit -m "Improve installation documentation"
git push -u origin docs/improve-installation-guide
```

Use a commit message that accurately describes your actual change.

## Step 8: Open a Pull Request

1. Open your fork on GitHub.
2. Select **Compare & pull request** or open a new pull request.
3. Set the base repository to the original project.
4. Set the base branch to the project's intended target branch.
5. Set the head repository to your fork and the compare branch to your feature branch.
6. Explain what you changed and why.
7. Submit the pull request.

The maintainers may ask questions, request changes, or approve your contribution.

## Step 9: Respond to Review Feedback

Read review comments carefully. Make any necessary corrections on the same branch, commit them, and push the updates. GitHub will update the existing pull request automatically.

A pull request is a proposal; acceptance and merging are decided by the project's maintainers.

## Important Git Terms

- **Fork:** Your copy of another repository on GitHub.
- **Clone:** A local copy of a repository on your computer.
- **Branch:** An independent line of development within a repository.
- **Commit:** A recorded set of changes.
- **Pull request:** A proposal to merge changes into another branch or repository.
- **Upstream:** Commonly the original repository from which your fork was created.
- **Origin:** Commonly the remote URL of your own fork.

## Practice Exercise

1. Find a real issue that matches your skills.
2. Read the project's contribution guidelines.
3. Fork the repository.
4. Create a feature branch.
5. Make and test a useful change.
6. Commit and push your changes.
7. Open a pull request to the original repository.

## Key Takeaway

Successful open-source contributions start with understanding the project, making a focused improvement, testing it, and communicating clearly with maintainers.

**Congratulations!** You have learned the main Git and GitHub workflow needed to begin contributing to open-source projects.