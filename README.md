# XG Mind — Open Football Forecast Ledger & Audit

[![Website](https://img.shields.io/badge/Terminal-xgmind.com-10b981)](https://xgmind.com/)
[![Public Ledger](https://img.shields.io/badge/Settled%20Matches-3,755-blue)](https://xgmind.com/performance/)
[![MCP Endpoint](https://img.shields.io/badge/MCP-Streamable%20HTTP-purple)](https://xgmind.com/mcp)

> **Compiled from pre-match timestamped briefings and post-match official results by [XG Mind](https://xgmind.com/).**

This repository is updated daily with XG Mind's public, non-retrospective match forecast verification ledger across 30+ football competitions. Pre-match reports are locked before kickoff and automatically settled after full-time without selective deletion.

- **Last Updated (UTC)**: 2026-11-23 11:46 UTC
- **Total Settled Matches**: **3,755**
- **Cumulative 1X2 Hit Rate**: **67.9%**
- **Cumulative Over/Under 2.5 Hit Rate**: **53.6%**
- **Cumulative Exact Score Hit Rate**: **19.9%**

## Monthly Verification Breakdown

| Month | Settled Matches | 1X2 Hit Rate | O/U 2.5 Hit Rate | Exact Score Rate |
| :--- | ---: | ---: | ---: | ---: |
| 2026-11 | 1,677 | 69.8% | 53.5% | 20.6% |
| 2026-10 | 2,046 | 66.1% | 53.7% | 19.0% |
| 2026-09 | 32 | 84.4% | 50.0% | 43.8% |

## Latest 15 Settled Fixtures

| Date | Competition | Matchup | FT Score | 1X2 | O/U | Briefing |
| :--- | :--- | :--- | :---: | :---: | :---: | :--- |
| 2026-11-23 | Major League Soccer | Vancouver Whitecaps vs Real Salt Lake | `2-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261123-vancouver-whitecaps-vs-real-salt-lake/) |
| 2026-11-23 | Liga MX | Club Queretaro vs Necaxa | `2-2` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261123-club-queretaro-vs-necaxa/) |
| 2026-11-23 | Liga Profesional Argentina | Instituto Cordoba vs Huracan | `2-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261123-instituto-cordoba-vs-huracan/) |
| 2026-11-22 | Major League Soccer | Chicago Fire vs Charlotte | `1-2` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261122-chicago-fire-vs-charlotte/) |
| 2026-11-22 | Liga MX | Guadalajara Chivas vs Cruz Azul | `1-0` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261122-guadalajara-chivas-vs-cruz-azul/) |
| 2026-11-22 | Serie A | RB Bragantino vs Vasco DA Gama | `1-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261122-rb-bragantino-vs-vasco-da-gama/) |
| 2026-11-22 | Liga Profesional Argentina | River Plate vs Lanus | `3-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261122-river-plate-vs-lanus/) |
| 2026-11-22 | Serie A | Fluminense vs Mirassol | `1-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261122-fluminense-vs-mirassol/) |
| 2026-11-22 | Major League Soccer | Nashville SC vs FC Cincinnati | `0-1` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261122-nashville-sc-vs-fc-cincinnati/) |
| 2026-11-22 | Segunda División | Burgos vs Albacete | `1-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261122-burgos-vs-albacete/) |
| 2026-11-22 | La Liga | Getafe vs Atletico Madrid | `0-3` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261122-getafe-vs-atletico-madrid/) |
| 2026-11-22 | Primera División | Sporting Cristal vs Cienciano | `4-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261114-sporting-cristal-vs-cienciano/) |
| 2026-11-22 | Primera División | Sport Huancayo vs Universitario | `4-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261114-sport-huancayo-vs-universitario/) |
| 2026-11-22 | Ligue 1 | Marseille vs Le Mans | `2-3` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261122-marseille-vs-le-mans/) |
| 2026-11-22 | Serie A | Atalanta vs Inter | `4-4` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261122-atalanta-vs-inter/) |

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
