# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is a GitHub **profile README** repository. The repo name (`aaronboysen/aaronboysen`) matches the owner's username, so GitHub renders `README.md` from the default branch at the top of https://github.com/aaronboysen.

Practical implications for any work here:

- The primary (and likely only) deliverable is `README.md` at the repo root. Edits to that file are what become visible on the profile.
- There is no build system, no test suite, and no application code. Do not invent one. If asked to "run tests" or "build," clarify with the user — there is nothing to run.
- Rendering is GitHub-flavored Markdown with the usual profile-README features: shields.io badges, GitHub stats cards, mermaid diagrams, and a small set of allowed raw HTML tags (`<img>`, `<a>`, `<details>`, `<picture>`, etc.). JavaScript and most inline styles are stripped by GitHub's sanitizer — don't rely on them.
- Assets (images, GIFs) should live in the repo (e.g. an `assets/` directory) and be referenced by relative path, or hosted externally. Do not commit large binaries without confirming with the user.

## Current state

As of this file's creation the repository is empty — no commits, no `README.md`, no other files. Anything beyond this `CLAUDE.md` is yet to be authored.

## Workflow

- Develop on the branch specified by the task (currently `claude/add-claude-documentation-9LUWw`); do not push directly to `main`.
- Open a draft pull request after the first push.
- Because the audience for every change is "anyone viewing the GitHub profile," treat `README.md` edits as user-visible content changes and preview the Markdown before committing when possible.
