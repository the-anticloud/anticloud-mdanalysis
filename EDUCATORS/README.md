# Educators — MDANALYSIS

**Project:** MDANALYSIS  
**Category:** CHEMICAL_MANUFACTURING  
**Upstream:** https://github.com/MDAnalysis/mdanalysis  
**Pinned commit:** `2666cf1a6df1f22a3aefaa7ff740769bc06f237b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `89344775599bc8f57831437ab7098e7a7664923d1f4ad4614f5fc00bcc4abf7b`  
**Date:** October 2026

## Teaching with MDANALYSIS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `89344775599bc8f57831437ab7098e7a7664923d1f4ad4614f5fc00bcc4abf7b` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
