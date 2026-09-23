# 02 — Bottle Out

**Status:** 10/10 validated  
**Primary focus:** Windows endpoint forensics · XMPP · Anti-forensics

[Repository overview](../README.md) · [Case index](README.md) · [Master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) · [Publication PDF](../reports/HOLMES_2026_The_Reichenbach_Directive_PUBLICATION_FINAL_RELEASE.pdf)

## Case summary

A seized Windows endpoint exposed VPN access, Tactical RMM, Gajim/XMPP artifacts and the Operation Vanish cleanup sequence.

## Investigation areas

- OpenVPN and Tactical RMM artifact recovery;
- Gajim / XMPP account reconstruction;
- deleted-file and anti-forensics timeline analysis;

## Key findings

- Deleted application data remained recoverable through surviving endpoint artifacts.
- The endpoint identified the operator context around `spur` and the jailer Abel Stokes.

## Cross-case relevance

Connects directly to Whisper Chain through Murknet and the `spur` custody context.

## Validation state

All 10 tasks were validated on the competition platform.

> The [master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) is the canonical public analysis and contains the evidence narrative, task-level findings, detection opportunities and unified cross-case reconstruction.

---

[← 01 — Silent Dividend](01-silent-dividend.md) · [03 — Whisper Chain →](03-whisper-chain.md)
