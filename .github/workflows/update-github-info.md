---
name: update-github-info
description: Update the GitHub info page with latest GitHub Blog and Changelog highlights for Mona.
on:
  workflow_dispatch:
  schedule: daily
permissions:
  contents: read
  issues: read
  pull-requests: read
engine:
  id: copilot
  copilot-sdk: true
tools:
  edit: true
  web-fetch: {}
safe-outputs:
  create-pull-request:
    title-prefix: "[update-github-info] "
    draft: true
    allowed-files:
      - site/content/github-info.md
network:
  allowed:
    - defaults
    - github.blog
    - github.com
---

Read `notes/mona-notes.md` and follow those editorial notes when writing updates.

Use `web-fetch` to read:
- https://github.blog/latest/
- https://github.blog/changelog/

Update `site/content/github-info.md` with concise, practical highlights for developers. Include source references to GitHub Blog and/or Changelog entries used for each update.

When changes are ready, use `create-pull-request` to open a draft PR proposing only `site/content/github-info.md`. In the PR description, explicitly request Mona's review.
