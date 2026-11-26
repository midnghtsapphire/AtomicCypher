# Contributing

Thank you for helping. A few rules keep this repository trustworthy.

## Fact-check everything

Every claim is fact-checked, including the author's own ideas, papers and drafts. A fact-check reports what the published sources say, with citations and page numbers, and marks each claim as supported, wrong, or not confirmed. It never silently rewrites the work; it sits alongside it. To report a factual problem, open a **Fact-check report** issue.

## Keep it public-safe

This repository is public. Do not add:

- copyrighted source material (edition scans, plates, purchased books, corpus files under restrictive or unknown licences);
- private research data;
- credentials, tokens or keys;
- analytics, telemetry, tracking pixels, link tagging, or affiliate or referral code;
- vendor or tool branding ("built with …" lines, badges, logos).

Link to a source instead of copying it.

## Never delete history

Do not delete files, rules or changelog entries. To retire something, comment it out or mark it superseded in place, with the date, who, and why. Changelogs are append-only.

## How changes land

1. Open an issue first (a work request, bug report, or fact-check report).
2. Make changes on a branch and open a **draft** pull request that links the issue.
3. Use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages and PR titles (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`).
4. The repository owner reviews and merges. Authors do not merge their own pull requests.

Automated agents also start every commit message, PR description and comment with their name in bold and end with `— <name>`.

## Adding a tool

Copy `tools/_template/` to `tools/<tool-name>/` (lowercase, hyphenated), fill in its README and CHANGELOG, and add a row to the tools table in the top-level README. Releases follow [`docs/RELEASES.md`](docs/RELEASES.md).

## Continuous integration

This repository does not use hosted GitHub Actions. Run each tool's tests locally before opening a pull request, and paste the command and its result into the PR.
