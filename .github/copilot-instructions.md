# Copilot instructions (Profile README repo)

## What this repo is
- This workspace is a **GitHub profile README** content repo (no application code).
- The primary deliverables are the Markdown/HTML documents:
  - `README.md`
  - `parisafauzan/README.md`

## Editing rules (keep existing style)
- Preserve the current **HTML-first layout** (e.g., `<h1 align="center">`, `<p align="center">`, badge `<img>` tags).
- Keep section structure and separators (`---`) consistent; avoid large rewrites unless explicitly requested.
- Prefer **small, targeted edits** (text, links, badges, dates, project rows) over reformatting.
- Do not introduce new tooling files (CI, build configs, package managers) unless the user asks.

## Duplication / source of truth
- The same profile content exists in **two files** (`README.md` and `parisafauzan/README.md`).
- When making content updates, **apply the same change to both** unless the user specifies a single canonical README.

## Common safe updates
- Update personal info (education, dates, locations) and ensure consistency across both READMEs.
- Update links in the centered badges block (Gmail/LinkedIn/Portfolio).
- Update the “Featured Projects” table by editing rows only (keep 3 columns: Project / Description / Tech).

## External embeds & placeholders
- The GitHub Stats images use a placeholder username: `YOUR_GITHUB_USERNAME`.
  - If the username is known/confirmed, replace it consistently in both stats URLs.
  - Otherwise, leave the placeholder unchanged (don’t guess).

## Verification checklist for PRs
- Markdown renders correctly on GitHub (tables align, HTML blocks closed).
- No broken Markdown table pipes (`|`) or unescaped special characters.
- Links are valid and use `https://`.
