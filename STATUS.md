# InsultGPT — Status
_Auto-updated by Status Brain on every push. Last change: Add Status Brain workflow to auto-update project status._

**Status:** In progress
**What it is:** An app that generates insults using GPT.
**Stack:** Node.js (mjs scripts), GitHub Actions.

## What works right now
- Status Brain automation (script + GitHub workflow) to track real project state
- Task tracking structure (CLAUDE.md + tasks/ folder) for organizing work
- GitHub Actions workflow to run status updates on every push

## Recent changes (newest first)
- 2026-07-20 — Added Status Brain workflow for automated status tracking
- 2026-07-20 — Added Status Brain script (status-brain.mjs) to generate this file
- 2026-01-29 — Set up HQ task tracking with CLAUDE.md and tasks/ directory structure

## Reusable parts (for other projects)
- **Status Brain** — Automated project status tracker that reads git history and code to generate plain-English status updates — status-brain.mjs + .github/workflows/status-brain.yml

## Not done / next
- Core app logic (no insult generation code exists yet)
- No package.json or dependencies defined
- No README with user-facing documentation
- Task list in tasks/01-core-features.md needs completion
- API integration or GPT model selection not yet specified
- No frontend, API endpoints, or entry point implemented
