# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repo purpose

This is a GitHub profile README repo (repo name matches username `CloudNinjaDev`). Its content renders on the owner's GitHub profile page. There is no application code, build system, test suite, or CI pipeline — the repo is markdown and static image assets only.

## Structure

- `README.md` — the profile page content (source of truth, rendered on github.com/CloudNinjaDev).
- `some.md` — near-duplicate draft/scratch copy of the README content, missing the horizontal-rule section dividers present in `README.md`.
- `images/` — badge/certification images referenced by absolute GitHub URLs in `README.md`.

## Working in this repo

- Edits are markdown/HTML edits to `README.md`. There is nothing to build, lint, or test.
- Image references use full `https://github.com/CloudNinjaDev/CloudNinjaDev/blob/main/...` URLs (not relative paths) so they render correctly on the rendered profile page and in embeds.
- Several sections embed third-party badge/stat services (`skillicons.dev`, `github-readme-stats.vercel.app`, `github-profile-trophy.vercel.app`, `komarev.com`, `images.credly.com`) keyed off the `cloudninjadev` username — keep the username consistent if editing these.
