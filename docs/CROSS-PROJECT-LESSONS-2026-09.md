# Cross-project lessons — 2026-09

Autoresearch provides a useful **experimental-method template** for the lower-bound runtime/storage work.

## Reuse

- fixed time budget per experiment
- one changing variable at a time
- machine-readable metric
- autonomous keep/discard loop
- overnight repeated experiments

## Apply to smolFire/storage matrix

Experiments should vary one substrate/filesystem/tuning knob at a time and record:
- boot time
- RSS
- artifact size
- write amplification
- rename/fsync latency
- crash recovery
- retained history/GiB
- lineage reconstruction cost

The experiment harness belongs here as methodology; canonical runtime state remains in BOP/filesystem.

## Agent assignment

Copilot primary; `@codex` fallback.
