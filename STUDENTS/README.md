# Students — AI_FOR_BEGINNERS

**Project:** AI_FOR_BEGINNERS  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/microsoft/AI-For-Beginners  
**Pinned commit:** `392d0df1b2647cbee104942390551f1ed9e072c8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1745055cab9925ca16c2669b9944ef25c0d2f364e7ee9cf37ab2497a1742ae09`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `392d0df1b2647cbee104942390551f1ed9e072c8`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `1745055cab9925ca16c2669b9944ef25c0d2f364e7ee9cf37ab2497a1742ae09`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
