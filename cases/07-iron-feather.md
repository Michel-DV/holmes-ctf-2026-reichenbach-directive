# 07 — Iron Feather

**Status:** 17/17 validated  
**Primary focus:** PX4 UAV · Custom KDF · AES-GCM · Flight reconstruction

[Repository overview](../README.md) · [Case index](README.md) · [Master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) · [Publication PDF](../reports/HOLMES_2026_The_Reichenbach_Directive_PUBLICATION_FINAL_RELEASE.pdf)

## Case summary

Encrypted PX4 evidence was decrypted through firmware reverse engineering, allowing the planned mission and actual flight to be reconstructed separately.

## Investigation areas

- PX4 firmware reverse engineering;
- custom KDF and AES-256-GCM recovery;
- dataman mission intent and ULog flight reconstruction;

## Key findings

- The recovered key authenticated both encrypted evidence containers.
- The real flight diverged from the planned mission after an injected failure command.

## Cross-case relevance

Shares the Pavilion Road operational area with Silent Passenger.

## Validation state

All 17 tasks were validated on the competition platform.

> The [master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) is the canonical public analysis and contains the evidence narrative, task-level findings, detection opportunities and unified cross-case reconstruction.

---

[← 06 — Silent Passenger](06-silent-passenger.md) · [08 — Borrowed Name →](08-borrowed-name.md)
