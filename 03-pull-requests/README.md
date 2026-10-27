# 03 — Forks and Pull Requests

## What Is a Fork?

A fork is your own GitHub copy of another repository. It lets you experiment and propose changes without directly modifying the original project.

## What Is a Pull Request?

A pull request (PR) proposes changes from one branch to another. Maintainers can review the changes, discuss improvements, and decide whether to merge them.

## Branch vs Fork

| Branch | Fork |
|---|---|
| Exists inside a repository | Is a separate repository |
| Useful for organizing work | Useful when contributing without write access |
| Shares repository settings | Has its own repository settings |
| Changes can be proposed through a PR | Changes can be proposed to the original through a PR |

## Open-Source Contribution Workflow

1. Find a project that interests you.
2. Read its README and contribution guidelines.
3. Look for issues labeled `good first issue` or `help wanted`.
4. Fork the repository.
5. Create a feature branch.
6. Make a small, useful change.
7. Test your changes.
8. Commit and push your branch.
9. Open a pull request to the original repository.
10. Respond respectfully to review feedback.

## Example Branch Names

- `docs/fix-installation-guide`
- `fix/incorrect-example`
- `feature/add-beginner-tutorial`

## Pull Request Checklist

- [ ] I understand the purpose of my change.
- [ ] I followed the project's contribution guidelines.
- [ ] My changes are focused and clearly explained.
- [ ] I checked for spelling mistakes and broken links.
- [ ] I ran relevant tests when applicable.
- [ ] My pull request describes what changed and why.

## Important Terms

- **Upstream:** The original repository you want to contribute to.
- **Origin:** Commonly the remote pointing to your fork.
- **Review:** Feedback from maintainers or other contributors.
- **Merge conflict:** A situation where Git cannot automatically reconcile changes.

## Practice Exercise

Fork a practice repository, create a branch, update its documentation, and prepare a pull request.

## Next Lesson

Learn how GitHub Actions runs automated checks on pushes and pull requests.