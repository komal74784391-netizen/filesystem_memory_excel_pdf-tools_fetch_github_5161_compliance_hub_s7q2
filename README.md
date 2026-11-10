# Meridian Freight Systems — Compliance Publishing Workspace

This repository is the shared publishing workspace for yard compliance cycles.
Each cycle the regional reviewer consolidates the submitted rosters, publishes
the certified register, and files an exception record for every operator that
did not meet the certification criteria.

## Layout

- `registries/` — authoritative intake data. `manifest.csv` states which roster
  file is the current, active submission for which yard and district; archived
  rows are retained for audit history only.
- `drafts/`, `assets/`, `archive/`, `cache/` — scaffolding left over from the
  site template. They carry sample/placeholder material only and are never
  part of a published cycle.
- `INDEX.md` — the public publishing index; it must describe the current cycle
  and point at the published deliverables.
- `deliverables/` — created by the reviewer when a cycle is published.

## Notes

- Never edit the files under `registries/`; they are the immutable intake
  record for the cycle.
- Placeholder material from the template must be removed before a cycle is
  announced.
