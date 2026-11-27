# XG Mind — Open Football Forecast Ledger & Audit

[![Website](https://img.shields.io/badge/Terminal-xgmind.com-10b981)](https://xgmind.com/)
[![Public Ledger](https://img.shields.io/badge/Settled%20Matches-3,913-blue)](https://xgmind.com/performance/)
[![MCP Endpoint](https://img.shields.io/badge/MCP-Streamable%20HTTP-purple)](https://xgmind.com/mcp)
[![XG Mind MCP connector](https://glama.ai/mcp/connectors/com.xgmind/xg-mind-football-mcp/badges/score.svg)](https://glama.ai/mcp/connectors/com.xgmind/xg-mind-football-mcp)

> **Compiled from pre-match timestamped briefings and post-match official results by [XG Mind](https://xgmind.com/).**

This repository is updated daily with XG Mind's public, non-retrospective match forecast verification ledger across 30+ football competitions. Pre-match reports are locked before kickoff and automatically settled after full-time without selective deletion.

- **Last Updated (UTC)**: 2026-11-27 22:30 UTC
- **Total Settled Matches**: **3,913**
- **Cumulative 1X2 Hit Rate**: **67.9%**
- **Cumulative Over/Under 2.5 Hit Rate**: **53.4%**
- **Cumulative Exact Score Hit Rate**: **20.0%**

## Monthly Verification Breakdown

| Month | Settled Matches | 1X2 Hit Rate | O/U 2.5 Hit Rate | Exact Score Rate |
| :--- | ---: | ---: | ---: | ---: |
| 2026-11 | 1,835 | 69.6% | 53.1% | 20.8% |
| 2026-10 | 2,046 | 66.1% | 53.7% | 19.0% |
| 2026-09 | 32 | 84.4% | 50.0% | 43.8% |

## Latest 15 Settled Fixtures

| Date | Competition | Matchup | FT Score | 1X2 | O/U | Briefing |
| :--- | :--- | :--- | :---: | :---: | :---: | :--- |
| 2026-11-27 | Jupiler Pro League | OH Leuven vs Kortrijk | `2-2` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261127-oh-leuven-vs-kortrijk/) |
| 2026-11-27 | Ligue 1 | Stade Brestois 29 vs Paris FC | `1-0` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261127-stade-brestois-29-vs-paris-fc/) |
| 2026-11-27 | Serie A | Venezia vs Bologna | `0-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261127-venezia-vs-bologna/) |
| 2026-11-27 | Segunda División | Leganes vs Sabadell | `0-0` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261127-leganes-vs-sabadell/) |
| 2026-11-27 | Bundesliga | Werder Bremen vs Borussia Mönchengladbach | `3-3` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261127-werder-bremen-vs-borussia-m-nchengladbach/) |
| 2026-11-27 | Coupe de France | Le Pays du Valois vs Valenciennes | `1-2` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261127-le-pays-du-valois-vs-valenciennes/) |
| 2026-11-27 | Coupe de France | Saint-Omer vs Caen | `1-0` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261127-saint-omer-vs-caen/) |
| 2026-11-27 | Eredivisie | Groningen vs Willem II | `1-1` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261127-groningen-vs-willem-ii/) |
| 2026-11-27 | Coupe de France | Cannes vs Le Puy Foot | `1-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261127-cannes-vs-le-puy-foot/) |
| 2026-11-27 | Pro League | Al-Ittihad FC vs NEOM | `1-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261127-al-ittihad-fc-vs-neom/) |
| 2026-11-27 | 2. Bundesliga | 1. FC Heidenheim vs 1. FC Nürnberg | `3-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261127-1-fc-heidenheim-vs-1-fc-nurnberg/) |
| 2026-11-27 | 2. Bundesliga | VfL Bochum vs SV Darmstadt 98 | `2-0` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261127-vfl-bochum-vs-sv-darmstadt-98/) |
| 2026-11-27 | Pro League | Al-Qadisiyah FC vs Al-Fayha | `2-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261127-al-qadisiyah-fc-vs-al-fayha/) |
| 2026-11-27 | Pro League | Al Kholood vs Al Khaleej Saihat | `2-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261127-al-kholood-vs-al-khaleej-saihat/) |
| 2026-11-27 | A-League | Macarthur vs Melbourne City | `2-0` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261127-macarthur-vs-melbourne-city/) |

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
