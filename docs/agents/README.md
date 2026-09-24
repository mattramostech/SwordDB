# Agent Instructions

## Consult the documentation first

Before starting any task, read the root [README](../../README.md), these instructions, the [roadmap overview](../roadmap/README.md), and the [specifications overview](../specs/README.md). Then read any roadmap entries and specifications relevant to the task.

Always consult and respect this documentation structure:

- `docs/roadmap/` contains planned milestones, priorities, and progress.
- `docs/specs/` contains all project decisions and business rules.
- `docs/agents/` contains instructions for agents working on the project.

## Document decisions and business rules

Record every project decision and business rule in `docs/specs/`, including architectural and technical decisions. Create or update the relevant specification before implementing a decision or changing behavior. Keep documentation and implementation consistent.

Use roadmap entries to organize work and agent instructions to describe how agents should work. Link to specifications whenever these documents reference project decisions or business rules.

## Never commit directly

Agents must never create commits or run `git commit`. Leave changes uncommitted for the project owner to review and commit.

## Use English throughout

All project content must be in English, including documentation, specifications, code identifiers, comments, and user-facing text.
