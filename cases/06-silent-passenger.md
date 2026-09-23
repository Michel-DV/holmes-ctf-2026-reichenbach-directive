# 06 — Silent Passenger

**Status:** 16/20 validated  
**Primary focus:** Android firmware · Staged malware · Mobile proxy infrastructure

[Repository overview](../README.md) · [Case index](README.md) · [Master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) · [Publication PDF](../reports/HOLMES_2026_The_Reichenbach_Directive_PUBLICATION_FINAL_RELEASE.pdf)

## Case summary

Android head-unit firmware analysis reconstructed MQTT delivery, staged payloads and a native module that converted the vehicle into a mobile proxy relay.

## Investigation areas

- Allwinner T3 / TOPWAY firmware and privileged-app analysis;
- MQTT tasking and staged JAR / DEX reconstruction;
- native relay protocol and mobile proxy behavior;

## Key findings

- The compromise progressed through multiple dynamically retrieved stages.
- The vehicle's operational context converged on Pavilion Road.

## Cross-case relevance

The Pavilion Road location provides the geographic pivot into Iron Feather.

## Validation state

16 of 20 tasks were validated. Tasks 13, 14, 19 and 20 remain open because runtime-dependent canonical values were not fully recoverable.

> The [master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) is the canonical public analysis and contains the evidence narrative, task-level findings, detection opportunities and unified cross-case reconstruction.

---

[← 05 — Poisoned Branch](05-poisoned-branch.md) · [07 — Iron Feather →](07-iron-feather.md)
