# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Repository Overview

This is a personal GitHub profile repository for **Marco Galicia** ([@mgaliciat](https://github.com/mgaliciat)). It contains a single `README.md` that serves as a public-facing professional introduction on the GitHub profile page.

There is no application code, build system, test suite, or CI/CD pipeline.

## Repository Structure

```
mgaliciat/
└── README.md   # GitHub profile README (displayed on github.com/mgaliciat)
```

## Purpose

The `README.md` is rendered directly on the GitHub profile page. Its goal is to give visitors a concise, professional snapshot of who Marco is, what he works on, and how to reach him.

## Content Conventions

- **Keep it short.** The current style is intentionally minimalist. Avoid adding large blocks of text or elaborate tables.
- **Use plain Markdown.** Standard GitHub-flavored Markdown only — headings, bullet lists, and links. Avoid HTML unless strictly necessary.
- **Accurate information only.** Only update contact links, employer/project names, or tech stack entries when reflecting a real change. Do not invent or speculate about details.
- **Tone:** Professional but approachable; first-person; present tense.

### Current Sections

| Section | Content |
|---|---|
| Intro paragraph | One-sentence professional summary |
| Tech Stack | Core languages and infrastructure |
| Contact | LinkedIn, Twitter, Email |

When editing, preserve this structure unless explicitly asked to restructure it.

## Development Workflow

Since this is a documentation-only repository, the only workflow is editing `README.md` in a feature branch and opening a pull request.

### Branching

Branch names observed in this repo follow the pattern:

```
<tool>/<short-description>-<id>
```

Example: `claude/add-claude-documentation-sjx4L`

### Making Changes

1. Work on the designated feature branch (never commit directly to `master`).
2. Edit `README.md` (or `CLAUDE.md`) with the requested change.
3. Commit with a clear, descriptive message.
4. Push with `git push -u origin <branch-name>`.
5. Open a pull request against `master`.

### Commit Style

Short, imperative commit messages:

```
Add CLAUDE.md with repository guidance
Update tech stack to include Kubernetes
Simplify contact section
```

## What AI Assistants Should NOT Do

- Do not add new source code files, configuration files, or directories unless explicitly requested.
- Do not modify contact URLs without explicit instruction — they belong to the repository owner.
- Do not expand the README beyond the current minimalist style without being asked.
- Do not create CI/CD workflows, `.github/` directories, or any tooling infrastructure.
