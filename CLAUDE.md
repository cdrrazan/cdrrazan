# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

GitHub **profile README** repo — `cdrrazan/cdrrazan`. Because the repo name matches the username, `README.md` renders on <https://github.com/cdrrazan> as the profile landing page.

`README.md` is the only file. No build, no tests, no dependencies, no CI. "Deploying" = pushing to `main`; GitHub renders it immediately.

## Working on it

- Changes are content edits to `README.md`. Verify by rendering as GitHub-flavored Markdown — GitHub's profile renderer allows a limited HTML subset (`<h1>`, `<h4>`, `<p>`, `<a>`, `<img>`, `align` attributes are all in use); no CSS, no `<script>`, no `style` attributes.
- All images are hosted externally (imgur, shields.io, ko-fi). Check any new image URL resolves before committing — a dead link is a broken profile page.
- Book cover images link to `shop.digitonx.com` product pages. Cover image and shop link must be updated together.
- A profile-visit counter API was removed in `25d1ccb` — don't reintroduce tracking/counter badges.

## Repo-specific git convention

History is plain sentence-case subjects committed directly to `main` (`Update Book Cover`, `Add KOFI on github readme`) — not Conventional Commits, no branches. Match that here; it overrides the global conventional-commit / no-direct-to-main rules for this repo.
