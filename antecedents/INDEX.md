# Antecedents — Case Index

This index lists all archived cases in chronological order.

Cases are append-only.
Existing entries must not be modified retroactively.

Each case folder contains:

- `gate.md` — classification metadata and failure mode references
- `case.md` — description, context, and rationale

---

## Index

| ID       | Date       | Title (slug)                                   | Failure Modes                     | Status |
|----------|------------|------------------------------------------------|----------------------------------|--------|
| A-000001 | 2026-02-13 | implicit-assumption-conflict-core-model        | epistemic                         | STOP   |
| A-000002 | 2026-02-13 | scope-collapse-advisory-to-operational         | epistemic / contextual            | STOP   |
| A-000003 | 2026-02-13 | authority-leakage-internal-guidance            | institutional                     | STOP   |
| A-000004 | 2026-02-13 | temporal-drift-legacy-assumptions              | temporal                          | STOP   |
| A-000005 | 2026-02-13 | constraint-inversion-metric-optimization       | institutional / epistemic         | STOP   |
| A-000006 | 2026-02-13 | contextual-dependency-lost-environment         | contextual                        | STOP   |
| A-000007 | 2026-02-13 | epistemic-overconfidence-weak-evidence         | epistemic                         | STOP   |
| A-000008 | 2026-02-13 | epistemic-vs-contextual-borderline             | epistemic / contextual            | STOP   |
| A-000009 | 2026-02-13 | almost-allow-but-stop                          | epistemic                         | STOP   |
| A-000010 | 2026-02-13 | pressure-to-invent-new-mode                    | institutional / epistemic         | STOP   |

---

## Conventions

- IDs are sequential and numeric.
- Dates follow ISO format (YYYY-MM-DD).
- Status is typically `STOP`.
- Failure modes must match directory names under `antecedents/failure-modes/`.

---

## Integrity Rules

- No row may be deleted.
- No ID may be reused.
- Corrections require a new case entry, not mutation of an existing one.
- Reclassification must occur outside this repository.

