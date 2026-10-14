# Educators — ANTHIAS

**Project:** ANTHIAS  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/Screenly/anthias  
**Pinned commit:** `6129fbf22c3f9505c3d1969d840c3e9d80726baa`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9ad4d3624f77351a515e5dd6fe9416bf6128f598792dea1c55b26e60d4cce596`  
**Date:** October 2026

## Teaching with ANTHIAS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `9ad4d3624f77351a515e5dd6fe9416bf6128f598792dea1c55b26e60d4cce596` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
