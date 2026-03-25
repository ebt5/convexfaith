# Editing Workflow

## Principle
`manuscript/book.md` is the canonical manuscript. Proposed changes are drafted and reviewed in `proposals/` before any integration.

## Proposal file format
Each proposal should include:
- TITLE
- TARGET_ANCHOR
- CHANGE_TYPE
- EDITOR_NOTE
- OLD_TEXT
- NEW_TEXT

## Allowed change types
- INSERT_AFTER
- INSERT_BEFORE
- REPLACE
- DELETE
- REWRITE_BLOCK

## Review flow
1. Draft proposal in `proposals/`.
2. Author reviews/edits the proposal file or preview file.
3. Author explicitly approves integration.
4. Only then is `manuscript/book.md` changed.

## Preview files
A matching file in `proposals/previews/` may show how the passage reads after the proposed change, without changing the canonical manuscript.
