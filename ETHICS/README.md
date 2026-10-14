# Ethics — ANTHIAS

**Project:** ANTHIAS  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/Screenly/anthias  
**Pinned commit:** `6129fbf22c3f9505c3d1969d840c3e9d80726baa`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9ad4d3624f77351a515e5dd6fe9416bf6128f598792dea1c55b26e60d4cce596`  
**Date:** October 2026

## Position

ANTHIAS is packaged for offline deployment with a verifiable audit trail. The
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
