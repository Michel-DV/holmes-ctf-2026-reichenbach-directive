# 04 — Paper Ghost

**Status:** 9/9 validated  
**Primary focus:** Removable-media intrusion · SRUM · Windows Search / ESENT

[Repository overview](../README.md) · [Case index](README.md) · [Master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) · [Publication PDF](../reports/HOLMES_2026_The_Reichenbach_Directive_PUBLICATION_FINAL_RELEASE.pdf)

## Case summary

A planted USB initiated endpoint surveillance; residual Windows artifacts and Search Index data exposed sensitive DIOGENES personnel information.

## Investigation areas

- removable-media execution and UserAssist / ConsentStore analysis;
- SRUM timeline reconstruction;
- Windows Search / ESENT long-value recovery;

## Key findings

- Secondary Windows artifacts preserved evidence after primary files were removed.
- Recovered DIOGENES records exposed Tom Ainsworth and ticketing credentials.

## Cross-case relevance

Provides the personnel and ticketing exposure that leads into Poisoned Branch.

## Validation state

All 9 tasks were validated on the competition platform.

> The [master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) is the canonical public analysis and contains the evidence narrative, task-level findings, detection opportunities and unified cross-case reconstruction.

---

[← 03 — Whisper Chain](03-whisper-chain.md) · [05 — Poisoned Branch →](05-poisoned-branch.md)
