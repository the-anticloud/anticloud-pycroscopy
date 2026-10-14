# Educators — PYCROSCOPY

**Project:** PYCROSCOPY  
**Category:** SCIENTIFIC_LAB  
**Upstream:** https://github.com/pycroscopy/pycroscopy  
**Pinned commit:** `90e2d232acc9da634131c1793f082a70a04a3297`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9199a1b01dcb7b5542a6f71bef5f2152c1e0a45fccf052967df2ffbdce17c776`  
**Date:** October 2026

## Teaching with PYCROSCOPY

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `9199a1b01dcb7b5542a6f71bef5f2152c1e0a45fccf052967df2ffbdce17c776` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
