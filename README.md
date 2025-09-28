# Issue Events

Two workflows: one reacts to a new issue, one is a multi‑stage pipeline on push.

## Purpose
Demonstrate event payload usage alongside a standard build → lint → test → deploy chain.

## Highlights
- `issues` trigger (opened)
- Title/body extraction & raw JSON dump
- Lint/test gating before deploy
- `needs` chain for ordered stages

## Notes
Keeps logic minimal; focus is on event context access.

## Next
`event-triggers`