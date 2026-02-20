# Auto Commit for GitHub Activity

This repository uses a GitHub Actions workflow to automatically commit once per day, keeping my GitHub contribution streak active.

## How it works

- A scheduled workflow runs daily at **12:00 UTC**
- It writes the current timestamp to `last_updated.txt`
- The commit is authored as `dhivagar29` so it counts on the contribution graph
- Can also be triggered manually via `workflow_dispatch`

The workflow is defined in `.github/workflows/autocommit.yml`.
