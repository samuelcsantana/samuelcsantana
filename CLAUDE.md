# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is Samuel Santana's GitHub **profile README** repository (repo name matches the GitHub username `samuelcsantana`), a special-cased repo that GitHub renders as the profile page at github.com/samuelcsantana. It contains a single file, `README.md`, written in Portuguese, with badges and stats widgets.

There is no application code, no package manager, and no build/lint/test tooling in this repository — do not assume Node.js, Python, or any other stack is present. Do not invent `package.json`, CI config, or test setups; none exist here.

## Working with this repo

- The only file that matters is `README.md`. Changes here directly change what is displayed on the GitHub profile page.
- Content is in Portuguese (pt-BR); keep additions consistent with the existing language and tone unless asked otherwise.
- The README uses `shields.io` badge images and a `streak-stats.demolab.com` widget for GitHub stats — these are external image URLs embedded via raw HTML (`<img>`, `<p align="center">`), not markdown image syntax, because it's rendered as GitHub-flavored HTML/Markdown.
- Sections in the current README: intro/tagline, contact badges (LinkedIn/Email/Blog), a summary of technical focus areas, a "Projetos em Destaque" section linking out to the author's actual projects (Pyxis: pyxis-api, pyxis-sdk, pyxis-web; BolsoVerde, linked only by its domain bolsoverde.com because its repositories are private; Ninho: cygnus, cygnus-api; Vertex: vertex-web, vertex-api; rx-state-bridge; and Vela in a short "Outros" line — these live in separate repositories, not here), a tech-stack badge grid, GitHub streak stats, and a closing personal-interests blurb.
- There is nothing to build, lint, or test. Verifying a change means re-reading the rendered Markdown/HTML for correctness (valid links, matching badge syntax, no broken HTML tags).
