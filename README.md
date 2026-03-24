# convexfaith

A repository for experimenting with AI-assisted long-form text authoring workflows.

## Purpose

This repo is structured so a human + AI agents can iteratively improve long-form prose using:
- markdown as the canonical manuscript format
- git for version control and diffs
- companion state documents for outline, voice, summaries, and revision queues
- patch-oriented editing rather than uncontrolled whole-document rewrites

## Core structure

- `manuscript/` — canonical manuscript files
- `chapters/` — chapter-level working files or split source files
- `notes/` — outline, voice guide, summaries, revision queue, open questions
- `reviews/` — integration reviews, audits, and evaluation passes
- `prompts/` — reusable agent prompts/workflows
- `scripts/` — helper scripts for future tooling

## Recommended workflow

1. Update the outline and chapter summaries before major revisions.
2. Ask agents for scoped changes, not whole-book rewrites.
3. Review patch-like edits at the section/chapter level.
4. Periodically run integration reviews to assess whether the whole manuscript improved.
5. Commit meaningful revisions in small logical units.
