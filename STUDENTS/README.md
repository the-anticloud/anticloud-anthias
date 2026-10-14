# Students — ANTHIAS

**Project:** ANTHIAS  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/Screenly/anthias  
**Pinned commit:** `6129fbf22c3f9505c3d1969d840c3e9d80726baa`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9ad4d3624f77351a515e5dd6fe9416bf6128f598792dea1c55b26e60d4cce596`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `6129fbf22c3f9505c3d1969d840c3e9d80726baa`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `9ad4d3624f77351a515e5dd6fe9416bf6128f598792dea1c55b26e60d4cce596`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
