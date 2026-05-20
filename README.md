# .github

## Organization workflow: close linked issues on non-default branches

This repository provides a reusable GitHub Actions workflow that closes issues linked to merged pull requests.

- Reusable workflow: `.github/workflows/close-linked-issues-on-target-branch.yml`
- Starter caller workflow (for `dev`): `.github/examples/close-linked-issues-on-dev-merge.yml`

### How to use in another repository

1. Copy `.github/examples/close-linked-issues-on-dev-merge.yml` into the target repository as:
   `.github/workflows/close-linked-issues-on-dev-merge.yml`. This can also be done through the UI.
2. Commit the workflow file.
