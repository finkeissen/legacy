# Failure Modes

This directory defines the structural reasons why legacy material is classified
as inadmissible.

A failure mode is not an error, mistake, or false statement.
It is a recurring structural condition that invalidates material for
operational, analytical, or decision-making use.

Failure modes explain *why* material is stopped — not *how* to fix it.

---

## Purpose

Failure modes serve three functions:

1. To make inadmissibility decisions explicit and reproducible
2. To prevent silent reuse of structurally compromised material
3. To identify recurring patterns across otherwise unrelated cases

They are intentionally conservative and coarse-grained.

---

## What failure modes are not

Failure modes are:

- Not bug reports
- Not quality issues
- Not factual corrections
- Not lessons learned
- Not improvement suggestions

A failure mode does not imply that material is “wrong” in a narrow sense.
It implies that the material is unsafe, unstable, or unfit for reuse
given its structure, assumptions, or context.

---

## Structure

Each failure mode is documented in its own directory.

A failure mode definition may include:

- A short description of the structural condition
- Typical trigger characteristics
- Clear non-examples (what does *not* fall under this mode)
- Heuristics for recognition

Not all failure modes are equally detailed.
Some exist primarily as placeholders until sufficient cases accumulate.

---

## Usage

When archiving a case:

- At least one failure mode **must** be referenced in `gate.md`
- Multiple failure modes may apply to a single case
- Failure modes should be reused whenever possible

If no existing failure mode fits,
a new one may be introduced — but only if it describes a
structural condition, not a one-off issue.

---

## Stability

Failure modes are intended to be relatively stable over time.

Definitions may be clarified or expanded,
but their meaning should not drift.
Reclassification of past cases should not be required
when failure modes evolve.

---

## Relationship to patterns

Failure modes explain *why* material is inadmissible.

Structural patterns (see `/patterns/`) describe
*how* such failures tend to manifest across domains.

The two are related but not interchangeable.

