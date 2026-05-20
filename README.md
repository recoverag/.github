# .github

## Organization workflow template: close linked issues on non-default branches

This repository provides a reusable GitHub Actions workflow and a workflow template to close issues linked to pull requests merging into non-default branches.

### How to use in another repository

1. In the target repository, go to **Actions**.
2. Select **New workflow**.
3. Choose **Close linked issues on target branch merge**.
4. Commit the generated workflow file.

### Configuration

In the generated workflow file, set:

- `target_branches`: comma-separated target branches that should trigger closing (example: `dev`).
