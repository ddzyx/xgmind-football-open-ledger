# XG Mind — Open Football Forecast Ledger & Audit

[![Website](https://img.shields.io/badge/Terminal-xgmind.com-10b981)](https://xgmind.com/)
[![Public Ledger](https://img.shields.io/badge/Settled%20Matches-3,808-blue)](https://xgmind.com/performance/)
[![MCP Endpoint](https://img.shields.io/badge/MCP-Streamable%20HTTP-purple)](https://xgmind.com/mcp)

> **Compiled from pre-match timestamped briefings and post-match official results by [XG Mind](https://xgmind.com/).**

This repository is updated daily with XG Mind's public, non-retrospective match forecast verification ledger across 30+ football competitions. Pre-match reports are locked before kickoff and automatically settled after full-time without selective deletion.

- **Last Updated (UTC)**: 2026-11-24 22:30 UTC
- **Total Settled Matches**: **3,808**
- **Cumulative 1X2 Hit Rate**: **67.8%**
- **Cumulative Over/Under 2.5 Hit Rate**: **53.4%**
- **Cumulative Exact Score Hit Rate**: **20.0%**

## Monthly Verification Breakdown

| Month | Settled Matches | 1X2 Hit Rate | O/U 2.5 Hit Rate | Exact Score Rate |
| :--- | ---: | ---: | ---: | ---: |
| 2026-11 | 1,730 | 69.5% | 53.1% | 20.8% |
| 2026-10 | 2,046 | 66.1% | 53.7% | 19.0% |
| 2026-09 | 32 | 84.4% | 50.0% | 43.8% |

## Latest 15 Settled Fixtures

| Date | Competition | Matchup | FT Score | 1X2 | O/U | Briefing |
| :--- | :--- | :--- | :---: | :---: | :---: | :--- |
| 2026-11-24 | Premiership | Rangers vs Aberdeen | `3-2` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261124-rangers-vs-aberdeen/) |
| 2026-11-24 | Championship | Wolves vs Derby | `3-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261124-wolves-vs-derby/) |
| 2026-11-24 | UEFA Champions League | Slovan Bratislava vs Real Betis | `0-2` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261124-slovan-bratislava-vs-real-betis/) |
| 2026-11-24 | UEFA Champions League | RB Leipzig vs Lens | `3-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261124-rb-leipzig-vs-lens/) |
| 2026-11-24 | UEFA Champions League | Manchester City vs Napoli | `2-2` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261124-manchester-city-vs-napoli/) |
| 2026-11-24 | UEFA Champions League | Feyenoord vs FC Porto | `0-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261124-feyenoord-vs-fc-porto/) |
| 2026-11-24 | UEFA Champions League | Como vs AEK Athens FC | `1-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261124-como-vs-aek-athens-fc/) |
| 2026-11-24 | UEFA Champions League | Arsenal vs Borussia Dortmund | `1-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261124-arsenal-vs-borussia-dortmund/) |
| 2026-11-24 | Championship | Sheffield Utd vs Southampton | `1-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261124-sheffield-utd-vs-southampton/) |
| 2026-11-24 | Championship | Portsmouth vs West Ham | `1-0` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261124-portsmouth-vs-west-ham/) |
| 2026-11-24 | Championship | Norwich vs QPR | `1-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261124-norwich-vs-qpr/) |
| 2026-11-24 | Championship | Middlesbrough vs Swansea | `2-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261124-middlesbrough-vs-swansea/) |
| 2026-11-24 | Championship | Charlton vs Lincoln | `4-0` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261124-charlton-vs-lincoln/) |
| 2026-11-24 | Championship | Cardiff vs Preston | `0-4` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261124-cardiff-vs-preston/) |
| 2026-11-24 | Championship | Bristol City vs Wrexham | `1-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261124-bristol-city-vs-wrexham/) |

## Repository Files

- [`ledger/settled_predictions.csv`](ledger/settled_predictions.csv) — Full settled verification ledger in UTF-8 CSV format.
- [`ledger/summary.json`](ledger/summary.json) — Machine-readable summary metrics.
- `YYYY/MM/DD/en/*.json` & `*.md` — Individual pre-match briefings and post-match settlements synced in real time.

## Official Resources

- **Live Terminal**: https://xgmind.com/
- **Interactive Public Performance Ledger**: https://xgmind.com/performance/
- **Quantitative Methodology & Poisson Modeling**: https://xgmind.com/methodology/
- **Empirical Research Blog**: https://xgmind.com/blog/
- **Public Read-Only MCP Endpoint**: `https://xgmind.com/mcp`
