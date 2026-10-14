# Students — MDANALYSIS

**Project:** MDANALYSIS  
**Category:** CHEMICAL_MANUFACTURING  
**Upstream:** https://github.com/MDAnalysis/mdanalysis  
**Pinned commit:** `2666cf1a6df1f22a3aefaa7ff740769bc06f237b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `89344775599bc8f57831437ab7098e7a7664923d1f4ad4614f5fc00bcc4abf7b`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `2666cf1a6df1f22a3aefaa7ff740769bc06f237b`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `89344775599bc8f57831437ab7098e7a7664923d1f4ad4614f5fc00bcc4abf7b`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
