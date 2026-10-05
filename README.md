> **Portfolio showcase** — the complete implementation is kept private to protect intellectual property. This public repository intentionally contains documentation only. A live demo or private code review can be provided for a serious project discussion.

# Competitor Price Monitor

Production-style ecommerce price monitoring pipeline.

## Approach
Search-engine shopping prices can be stale or disconnected from the actual merchant page. The pipeline combines discovery with direct verification and only treats a price as actionable when the offer URL and current page price can be confirmed.

## Highlights
- multi-source offer discovery
- direct merchant-page price verification
- marketplace handling
- link discovery and persistence
- false-positive filtering
- email reports and watchdog alerts
- network and timeout guards
- historical price output
- tests for matching and alert rules

## Public snapshot
Live store catalogues, report recipients, API credentials, generated reports and production history are excluded. products.example.csv contains synthetic input.

Copy .env.example to .env and provide your own provider credentials before enabling external integrations.

## Source access

The complete implementation is kept in a private source archive. For serious commercial discussions, a live walkthrough, architecture review, or controlled private code review can be arranged.

## Usage and licensing

This repository is source-available for portfolio evaluation. You may inspect the code and run an unmodified local copy for evaluation, but commercial use, redistribution, republishing and derivative distribution are not permitted without written permission. See [PROPRIETARY-NOTICE.md](PROPRIETARY-NOTICE.md).
