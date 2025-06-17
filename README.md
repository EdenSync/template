# GitHub Actions Template Repository

A starter template for GitHub Actions workflows, including reusable configurations for linting, issue/project automation, and changelog generation.

## Features

- 🧹 **Linting** with [Super-Linter](https://github.com/super-linter/super-linter)
- 📦 **Release Changelog** grouping via `release.yml`
- 📌 **Auto-assign issues to GitHub Projects** on open/reopen
- 🔄 **Auto-move linked issues** to "In review" when a PR is reviewed

## Included Workflows

- `.github/workflows/lint.yml` — Auto-fixes formatting with Super-Linter and commits results
- `.github/release.yml` — Categorizes PRs for changelogs
- `.github/workflows/add-to-project.yml` — Adds new issues to a GitHub Project (Org-level)
- `.github/workflows/move-to-review.yml` — Moves linked issues to "In review" when a PR is assigned reviewers

## License

[Apache 2.0](LICENSE)
