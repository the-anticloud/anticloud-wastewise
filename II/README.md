# Independent Insurance — WASTEWISE

**Project:** WASTEWISE  
**Category:** WASTE_MANAGEMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `5cdfa2ae5ed8ec04d97fc93cc24161bb9c880de5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `662bc71d4cf4fdadc8a104653cfb8733707e390de7a6df45f21f93e916e9e6ca`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | WASTEWISE with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `662bc71d4cf4fdadc8a104653cfb8733707e390de7a6df45f21f93e916e9e6ca`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
