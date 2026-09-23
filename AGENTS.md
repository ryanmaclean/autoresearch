# AGENTS.md

## Role

Experimental-method baseline.

## Owns

- fixed-budget experiment loop
- keep/discard measurement pattern

## Do not duplicate

- runtime/orchestration ownership

## Sibling repos to consult first

- ryanmaclean/smolfire

## Cross-project context

Read `docs/CROSS-PROJECT-LESSONS-2026-09.md` before making architectural changes.

## Agent delegation

- Primary GitHub coding agent: Copilot when assignable/available.
- Fallback: delegate the issue or PR to Codex with `@codex`.
- Do not treat Copilot/Codex state as canonical project state; keep canonical work in repo issues/BOP/filesystem state.
