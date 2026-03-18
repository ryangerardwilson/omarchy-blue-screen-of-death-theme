# AGENTS.md

## Scope

This repo owns the `blue-screen-of-death` Omarchy theme.

## Source Of Truth

- The repo contents are the source of truth.
- The installed copy under
  `~/.config/omarchy/themes/blue-screen-of-death` is only a deployed theme
  copy.

## Editing Workflow

- Make durable theme edits in this repo first.
- Direct edits in the installed theme directory are allowed only for quick
  local testing.
- Once a direct config edit is validated, port it back into this repo before
  finishing the task.
- Do not leave the repo and the installed theme intentionally diverged.

## Release Workflow

- When a change should become the real theme, commit and push this repo first.
- Then install or refresh the theme via Omarchy from the GitHub repo.
- If the theme should become active immediately after install, run
  `omarchy-theme-set blue-screen-of-death`.
