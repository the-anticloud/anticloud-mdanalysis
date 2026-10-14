# Ethics — MDANALYSIS

**Project:** MDANALYSIS  
**Category:** CHEMICAL_MANUFACTURING  
**Upstream:** https://github.com/MDAnalysis/mdanalysis  
**Pinned commit:** `2666cf1a6df1f22a3aefaa7ff740769bc06f237b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `89344775599bc8f57831437ab7098e7a7664923d1f4ad4614f5fc00bcc4abf7b`  
**Date:** October 2026

## Position

MDANALYSIS is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
