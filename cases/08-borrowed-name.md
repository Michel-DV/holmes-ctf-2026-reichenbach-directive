# 08 — Borrowed Name

**Status:** 12/12 validated  
**Primary focus:** AdaptixC2 · Active Directory abuse · Lateral movement

[Repository overview](../README.md) · [Case index](README.md) · [Master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) · [Publication PDF](../reports/HOLMES_2026_The_Reichenbach_Directive_PUBLICATION_FINAL_RELEASE.pdf)

## Case summary

A removable-media intrusion progressed through DLL side-loading, AdaptixC2, credential access and Active Directory abuse before reaching DC02.

## Investigation areas

- AdaptixC2 and endpoint execution reconstruction;
- credential access and Active Directory discovery;
- lateral movement and service-path abuse on DC02;

## Key findings

- The attacker transferred `svc_bkup` to DC02 through `ADMIN$`.
- The binary was executed through temporary service configuration abuse.

## Cross-case relevance

Hands the exact `svc_bkup` artifact directly into the Last Light investigation.

## Validation state

All 12 tasks were validated on the competition platform.

> The [master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) is the canonical public analysis and contains the evidence narrative, task-level findings, detection opportunities and unified cross-case reconstruction.

---

[← 07 — Iron Feather](07-iron-feather.md) · [09 — Last Light →](09-last-light.md)
