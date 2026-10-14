# Ethics — PYCROSCOPY

**Project:** PYCROSCOPY  
**Category:** SCIENTIFIC_LAB  
**Upstream:** https://github.com/pycroscopy/pycroscopy  
**Pinned commit:** `90e2d232acc9da634131c1793f082a70a04a3297`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9199a1b01dcb7b5542a6f71bef5f2152c1e0a45fccf052967df2ffbdce17c776`  
**Date:** October 2026

## Position

PYCROSCOPY is packaged for offline deployment with a verifiable audit trail. The
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
