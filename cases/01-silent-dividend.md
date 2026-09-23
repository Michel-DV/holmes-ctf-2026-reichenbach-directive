# 01 — Silent Dividend

**Status:** 10/10 validated  
**Primary focus:** Electron malware · LuaJIT · Ethereum / Sepolia

[Repository overview](../README.md) · [Case index](README.md) · [Master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) · [Publication PDF](../reports/HOLMES_2026_The_Reichenbach_Directive_PUBLICATION_FINAL_RELEASE.pdf)

## Case summary

A malicious Electron application combined a LuaJIT implant with wallet-secret collection and on-chain state to support an ERC-20 draining flow.

## Investigation areas

- Electron application and LuaJIT implant analysis;
- wallet-secret collection and WinHTTP behavior;
- Sepolia smart-contract state and on-chain key retrieval;

## Key findings

- The malware chain connected local wallet theft to an on-chain control path.
- The recovered settlement data exposed the Silvertown geographic pivot at `51.5049,0.0348`.

## Cross-case relevance

Introduces the NAPOLEON naming and Silvertown pivot that recur in the wider investigation.

## Validation state

All 10 tasks were validated on the competition platform.

> The [master investigation](../reports/HOLMES_2026_The_Reichenbach_Directive.md) is the canonical public analysis and contains the evidence narrative, task-level findings, detection opportunities and unified cross-case reconstruction.

---

← Start · [02 — Bottle Out →](02-bottle-out.md)
