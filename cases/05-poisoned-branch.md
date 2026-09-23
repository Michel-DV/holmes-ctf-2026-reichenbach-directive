# 05 — Poisoned Branch

**Status:** 15/15 validated  
**Primary focus:** Software supply chain · Linux implant · Loot recovery

[Repository overview](../README.md) · [Case index](README.md) · [Master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) · [Publication PDF](../reports/HOLMES_2026_The_Reichenbach_Directive_PUBLICATION_FINAL_RELEASE.pdf)

## Case summary

A poisoned ticket-parser repository led to a Linux compromise, Mettle/Metasploit activity and encrypted loot recovery.

## Investigation areas

- supply-chain compromise reconstruction;
- Linux implant and operator-server analysis;
- ZipCrypto known-plaintext recovery of `LOOT.zip`;

## Key findings

- Victim and operator artifacts were tied together by matching binary identity.
- The investigation recovered both operator infrastructure and stolen personnel data.

## Cross-case relevance

Continues the Tom Ainsworth thread first exposed in Paper Ghost.

## Validation state

All 15 tasks were validated on the competition platform.

> The [master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) is the canonical public analysis and contains the evidence narrative, task-level findings, detection opportunities and unified cross-case reconstruction.

---

[← 04 — Paper Ghost](04-paper-ghost.md) · [06 — Silent Passenger →](06-silent-passenger.md)
