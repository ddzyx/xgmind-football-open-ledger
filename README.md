# XG Mind — Open Football Forecast Ledger & Audit

[![Website](https://img.shields.io/badge/Terminal-xgmind.com-10b981)](https://xgmind.com/)
[![Public Ledger](https://img.shields.io/badge/Settled%20Matches-3,845-blue)](https://xgmind.com/performance/)
[![MCP Endpoint](https://img.shields.io/badge/MCP-Streamable%20HTTP-purple)](https://xgmind.com/mcp)

> **Compiled from pre-match timestamped briefings and post-match official results by [XG Mind](https://xgmind.com/).**

This repository is updated daily with XG Mind's public, non-retrospective match forecast verification ledger across 30+ football competitions. Pre-match reports are locked before kickoff and automatically settled after full-time without selective deletion.

- **Last Updated (UTC)**: 2026-11-25 22:30 UTC
- **Total Settled Matches**: **3,845**
- **Cumulative 1X2 Hit Rate**: **67.9%**
- **Cumulative Over/Under 2.5 Hit Rate**: **53.4%**
- **Cumulative Exact Score Hit Rate**: **20.0%**

## Monthly Verification Breakdown

| Month | Settled Matches | 1X2 Hit Rate | O/U 2.5 Hit Rate | Exact Score Rate |
| :--- | ---: | ---: | ---: | ---: |
| 2026-11 | 1,767 | 69.7% | 53.1% | 20.8% |
| 2026-10 | 2,046 | 66.1% | 53.7% | 19.0% |
| 2026-09 | 32 | 84.4% | 50.0% | 43.8% |

## Latest 15 Settled Fixtures

| Date | Competition | Matchup | FT Score | 1X2 | O/U | Briefing |
| :--- | :--- | :--- | :---: | :---: | :---: | :--- |
| 2026-11-25 | Championship | Stoke City vs Millwall | `2-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261125-stoke-city-vs-millwall/) |
| 2026-11-25 | UEFA Champions League | Sporting CP vs Manchester United | `2-2` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261125-sporting-cp-vs-manchester-united/) |
| 2026-11-25 | UEFA Champions League | Paris Saint Germain vs AS Roma | `2-2` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261125-paris-saint-germain-vs-as-roma/) |
| 2026-11-25 | UEFA Champions League | Lille vs Bayern München | `2-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261125-lille-vs-bayern-m-nchen/) |
| 2026-11-25 | UEFA Champions League | Inter vs VfB Stuttgart | `2-0` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261125-inter-vs-vfb-stuttgart/) |
| 2026-11-25 | UEFA Champions League | Club Brugge KV vs Liverpool | `0-3` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261125-club-brugge-kv-vs-liverpool/) |
| 2026-11-25 | UEFA Champions League | Atletico Madrid vs Viking | `2-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261125-atletico-madrid-vs-viking/) |
| 2026-11-25 | Championship | Watford vs Blackburn | `0-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261125-watford-vs-blackburn/) |
| 2026-11-25 | Championship | Burnley vs Birmingham | `0-2` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261125-burnley-vs-birmingham/) |
| 2026-11-25 | Championship | Bolton vs West Brom | `1-3` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261125-bolton-vs-west-brom/) |
| 2026-11-25 | Serie B | Pisa vs Modena | `1-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261125-pisa-vs-modena/) |
| 2026-11-25 | Serie B | Padova vs Sampdoria | `1-2` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261125-padova-vs-sampdoria/) |
| 2026-11-25 | Serie B | Mantova vs Arezzo | `3-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261125-mantova-vs-arezzo/) |
| 2026-11-25 | AFC Champions League Two | Al Taawon vs Al-Nahda | `0-0` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261125-al-taawon-vs-al-nahda/) |
| 2026-11-25 | Serie B | Cremonese vs Avellino | `0-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261125-cremonese-vs-avellino/) |

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
