# Students — PYCROSCOPY

**Project:** PYCROSCOPY  
**Category:** SCIENTIFIC_LAB  
**Upstream:** https://github.com/pycroscopy/pycroscopy  
**Pinned commit:** `90e2d232acc9da634131c1793f082a70a04a3297`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9199a1b01dcb7b5542a6f71bef5f2152c1e0a45fccf052967df2ffbdce17c776`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `90e2d232acc9da634131c1793f082a70a04a3297`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `9199a1b01dcb7b5542a6f71bef5f2152c1e0a45fccf052967df2ffbdce17c776`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
