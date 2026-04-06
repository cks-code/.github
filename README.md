# .github

This repository contains the organization-wide default community health files and workflow templates for **cks-code**.

GitHub uses files in this repository as defaults for all repositories in the organization that do not define their own.

## Files

| File | Purpose |
|------|---------|
| [`profile/README.md`](profile/README.md) | Organization profile displayed on the cks-code GitHub page |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Default code of conduct for all repositories |
| [`SECURITY.md`](SECURITY.md) | Default security and responsible disclosure policy |
| [`FUNDING.yml`](FUNDING.yml) | Funding/sponsorship configuration |
| [`workflow-templates/`](workflow-templates/) | Reusable GitHub Actions workflow templates |

## Workflow Templates

The [`workflow-templates/`](workflow-templates/) directory contains the following reusable workflows:

- **[`build-lint-test.yml`](workflow-templates/build-lint-test.yml)** — Build, lint, and test pipeline for Node.js projects
- **[`create-release-pr.yml`](workflow-templates/create-release-pr.yml)** — Workflow to create a release pull request
- **[`publish-release.yml`](workflow-templates/publish-release.yml)** — Workflow to publish a release when a release PR is merged

## Usage

Community health files (e.g. `CODE_OF_CONDUCT.md`, `SECURITY.md`) stored here will automatically apply to all repositories in the `cks-code` organization that do not have their own copy.

Workflow templates stored in `workflow-templates/` can be used by any repository in the organization via the **Actions** tab → **New workflow**.
