# 09 — Last Light

**Status:** 8/10 validated  
**Primary focus:** Memory forensics · Kerberos · Forged tickets · RBCD

[Repository overview](../README.md) · [Case index](README.md) · [Master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) · [Publication PDF](../reports/HOLMES_2026_The_Reichenbach_Directive_PUBLICATION_FINAL_RELEASE.pdf)

## Case summary

Domain Controller memory and event evidence reconstructed `svc_bkup`, token impersonation, forged Kerberos material, machine-account creation and RBCD abuse.

## Investigation areas

- DC02 memory forensics and artifact reconstruction;
- Kerberos ticket and PAC analysis;
- machine-account creation, S4U and Resource-Based Constrained Delegation;

## Key findings

- The `svc_bkup` artifact reconstructed from memory matched the file transferred in Borrowed Name.
- The post-compromise chain exposed token impersonation, forged ticket material and RBCD.

## Cross-case relevance

Provides artifact-level continuity with Borrowed Name through the same `svc_bkup` binary.

## Validation state

8 of 10 tasks were validated. Tasks 2 and 3 remain open because the relevant ticket/checksum evidence was identified but the validator's expected representation was unresolved.

> The [master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) is the canonical public analysis and contains the evidence narrative, task-level findings, detection opportunities and unified cross-case reconstruction.

---

[← 08 — Borrowed Name](08-borrowed-name.md) · End →
