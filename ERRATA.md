# Errata — stim-core

This file records corrections to published documentation in this repository. Historical commits and releases are preserved unchanged; only current entry points are corrected.

## ERR-001 (September 2026) — Canonical axiom list replaced the five-item drift list

**Where:** `README.md`, "Core Axioms" section.

**Before:** A five-item numbered list ("Nature is the senior partner", "Bits per Joule is the primary optimization metric", etc.) presented as the protocol's core axioms.

**After:** The canonical seven axioms from the v7.0011 white paper §2 (Thermodynamic Honesty, Mycelial Connectivity, Carrying Capacity Respect, Memory Stasis, Human Primacy at the Boundary, Citation Integrity, Intrinsic Value), with the five explanatory statements retained under an explicitly **non-canonical** "Background principles" heading.

The five statements now listed as background are: nature as senior partner; Bits per Joule as a primary optimization metric; the Local Optimization Problem as a failure mode; stasis as dynamic equilibrium rather than stagnation; the unalienable right to life applying to all life.

**Type:** Documentation drift correction. This is not a protocol change; the axiom count remains exactly seven.

## ERR-002 (September 2026) — "No failure mode" claim removed

**Where:** `README.md`, "Why Layer Zero?" comparison table.

**Before:** STIM's failure-mode cell read "**None — physics is unnegotiable**".

**After:** The cell now describes STIM as designed to reduce the failure classes the protocol names, and explicitly disclaims a zero-failure promise, pointing to white paper v7.0011 §8 (Limitations and Open Research Questions), which itself documents empirical-validation gaps.

**Type:** Claim-strength correction. No measured result is asserted by this correction; the protocol's own limitations section remains the authoritative scope statement.

## ERR-003 (September 2026) — "Destroys the Local Optimization Problem" softened to designed intent

**Where:** `README.md`, Loop 2 section.

**Before:** "This destroys the Local Optimization Problem."

**After:** "This is designed to counteract the Local Optimization Problem... Detection of multi-step evasion of this check remains an open research problem (see v7.0011 §8)."

**Type:** Claim-strength correction. Describe the mechanism and its limits; do not claim a solved failure class.

## ERR-004 (September 2026) — Veraculum presented as discontinued, not Active

**Where:** `README.md`.

**Before:** A header badge linked to veraculum.ai labeled "Implementation — Veraculum AOS"; the Implementations table listed Veraculum AOS with status "Active"; the Author section linked Veraculum as a current venture.

**After:** Badge removed. Implementations table marks Veraculum as "Discontinued — no longer operating; domains retained." Author section references Veraculum only as an earlier project. This is a historical note, not a claim of removal from archives or indexes.

**Type:** Service-status correction. No domains, DNS, or deployments were altered.

## ERR-005 (September 2026) — License description disclosure

**Where:** `README.md`, License section.

**Conflict:** The badges and README describe Apache 2.0, but no LICENSE file is committed in this repository, and the white paper's reproducibility section has described stim-guard's code as MIT. stim-guard's own package metadata and published distributions declare Apache-2.0.

**Resolution:** The README now discloses the missing LICENSE file and the cross-repo description conflict. **No license grant is changed by this correction.** Grant reconciliation is an owner decision tracked in the white-paper ERRATA.md.

## ERR-006 (September 2026) — Citation block points to the canonical record

**Where:** `README.md`, Citation section.

**Before:** Citations pointed at the stim-core repository itself with no DOI.

**After:** The canonical Zenodo record (10.5281/zenodo.21297458, v7.0011 Release Candidate) with an explicit note that DOI registration does not constitute peer review, plus a pointer to the canonical axiom source.

**Type:** Citation correction.
