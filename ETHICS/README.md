# Ethics — AI_FOR_BEGINNERS

**Project:** AI_FOR_BEGINNERS  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/microsoft/AI-For-Beginners  
**Pinned commit:** `392d0df1b2647cbee104942390551f1ed9e072c8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1745055cab9925ca16c2669b9944ef25c0d2f364e7ee9cf37ab2497a1742ae09`  
**Date:** October 2026

## Position

AI_FOR_BEGINNERS is packaged for offline deployment with a verifiable audit trail. The
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
