# Issue Events

Shows two things: reacting to a new issue and running a simple multi‑stage pipeline on push.

## Workflows

1. Issue workflow: triggers on `issues` (opened) and prints useful fields + the raw JSON
2. Deployment workflow: build → lint → test → deploy with `needs` links

## What you learn

- Basic event payload usage (`github.event`)
- Filtering by issue action
- Printing JSON for quick inspection
- Simple “stop deploy if tests fail” chain

## Why it exists

Highlights how to react to repo activity and combine it with a normal build pipeline.

## Next

See `event-triggers` for multiple events and filters.