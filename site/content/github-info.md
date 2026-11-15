# GitHub Info

## Mona's editorial angle

Mona's website focuses on practical GitHub guidance backed by official references from:

- docs.github.com
- github.blog
- github.blog/changelog

## Current homepage themes

- GitHub collaboration basics: repositories, branches, pull requests, and merges.
- GitHub Copilot as an AI coding assistant across the IDE, CLI, and GitHub.
- GitHub Actions as the automation layer behind repository workflows.
- Recent GitHub Blog and Changelog stories worth watching.

## Recent highlights

### GitHub Copilot

- **Gemini 4 Hydrogen now available in Copilot** — Google's latest Flash model is generally available across Copilot Pro, Pro+, Max, Business, and Enterprise. It's optimized for fast agentic coding, tool use, and multistep workflows with improved instruction following over Gemini 3.8 Flash. Usage-based billing applies at provider list pricing.
  _Source: [GitHub Changelog, Nov 13 2026](https://github.blog/changelog/2026-11-13-gemini-4-hydrogen-in-github-copilot)_

- **GitHub Enterprise Server support in the Copilot app** — You can now add your GHES account to the GitHub Copilot app to work with remote repositories, issues, and pull requests. Generally available after an opt-in preview. Sign in with a GitHub.com or GHE.com account first, then add your GHES account under Settings > Accounts.
  _Source: [GitHub Changelog, Nov 13 2026](https://github.blog/changelog/2026-11-13-github-enterprise-server-support-in-the-github-copilot-app)_

- **Build once, run on any agent** — A practical guide to writing reusable agent skills that work across different Copilot agent surfaces. Useful if you want to standardize automation across your team.
  _Source: [GitHub Blog](https://github.blog/ai-and-ml/)_

### Secret scanning

- **Secret scanning now covers Actions workflow logs** — GitHub scans workflow run logs for exposed secrets (in addition to issues, wikis, discussions, and PRs). Findings surface in the repository's Security tab. Available in public preview.
  _Source: [GitHub Changelog, Nov 9 2026](https://github.blog/changelog/2026-11-09-secret-scanning-detects-secrets-in-github-actions-workflow-logs)_

### Issues & planning

- **Issue types and fields for personal accounts** — Issue types and issue fields (previously org-only) are now generally available on personal account repositories. Individual developers and open source maintainers can now standardize how they categorize and track work.
  _Source: [GitHub Changelog, Nov 11 2026](https://github.blog/changelog/2026-11-11-issue-types-and-fields-are-available-for-personal-accounts)_

- **More compact GitHub dashboard** — The dashboard now fits more information on screen: reduced padding, denser item lists, a pinnable Feed or Home tab, and "Agent sessions" hidden when not applicable.
  _Source: [GitHub Changelog, Nov 10 2026](https://github.blog/changelog/2026-11-10-a-more-informative-github-dashboard)_

### Awesome Copilot Workflows

Community-contributed Copilot workflow templates at [github/awesome-copilot](https://github.com/github/awesome-copilot/tree/main/workflows):

- **Daily Issues Report** — Runs on a weekday schedule and posts a summary of new, closed, and stale issues as a labeled GitHub issue. Good starting point for team standup automation.
  _Source: [Awesome Copilot Workflows](https://github.com/github/awesome-copilot/blob/main/workflows/daily-issues-report.md)_

- **Relevance Check** — A slash-command workflow (`/relevance-check`) that uses Copilot to evaluate whether an open issue or PR is still relevant, checking current code and recent history before posting a structured assessment.
  _Source: [Awesome Copilot Workflows](https://github.com/github/awesome-copilot/blob/main/workflows/relevance-check.md)_

- **Weekly Comment Sync** — Runs weekly to find stale inline comments and README snippets contradicted by current code, makes text-only fixes, and opens a draft PR. No logic changes — documentation only.
  _Source: [Awesome Copilot Workflows](https://github.com/github/awesome-copilot/blob/main/workflows/weekly-comment-sync.md)_
