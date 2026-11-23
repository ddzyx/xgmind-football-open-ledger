# XG Mind — Open Football Forecast Ledger & Audit

[![Website](https://img.shields.io/badge/Terminal-xgmind.com-10b981)](https://xgmind.com/)
[![Performance](https://img.shields.io/badge/Public%20Ledger-Verified-blue)](https://xgmind.com/performance/)
[![MCP Endpoint](https://img.shields.io/badge/MCP-Streamable%20HTTP-purple)](https://xgmind.com/mcp)

> **Compiled from publicly available sports statistics and processed by [XG Mind](https://xgmind.com/) Data Engine.**

This repository publishes **daily transparent football forecast tracking**, pre-match briefing archives, and post-match verified settlement records across 30+ leagues. Every match is timestamped before kickoff and automatically settled after full-time without cherry-picking or post-hoc editing.

## What Is Inside

- `ledger/settled_predictions.csv` — Daily updated post-match settlement ledger (kickoff UTC, league, matchup, direction, fulltime score, half-time score, outcome flags, and canonical report link).
- `ledger/summary.json` — Aggregated monthly and overall settlement metrics.
- `YYYY/MM/DD/en/*.json` & `*.md` — Daily pre-match briefing snapshots and post-match result audits.

## Links & Standards

- **Official Terminal**: https://xgmind.com/
- **Verified Public Performance Ledger**: https://xgmind.com/performance/
- **Methodology & Calibration**: https://xgmind.com/methodology/
- **Research Blog**: https://xgmind.com/blog/
- **Public Read-Only MCP Server**: `https://xgmind.com/mcp`

## Disclaimer & Compliance

All records are strictly objective sports analytics and statistical audit artifacts for research and quantitative modeling.
