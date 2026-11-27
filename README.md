# XG Mind — Open Football Forecast Ledger & Audit

[![Website](https://img.shields.io/badge/Terminal-xgmind.com-10b981)](https://xgmind.com/)
[![Public Ledger](https://img.shields.io/badge/Settled%20Matches-3,899-blue)](https://xgmind.com/performance/)
[![MCP Endpoint](https://img.shields.io/badge/MCP-Streamable%20HTTP-purple)](https://xgmind.com/mcp)
[![XG Mind MCP connector](https://glama.ai/mcp/connectors/com.xgmind/xg-mind-football-mcp/badges/score.svg)](https://glama.ai/mcp/connectors/com.xgmind/xg-mind-football-mcp)

> **Compiled from pre-match timestamped briefings and post-match official results by [XG Mind](https://xgmind.com/).**

This repository is updated daily with XG Mind's public, non-retrospective match forecast verification ledger across 30+ football competitions. Pre-match reports are locked before kickoff and automatically settled after full-time without selective deletion.

- **Last Updated (UTC)**: 2026-11-27 12:01 UTC
- **Total Settled Matches**: **3,899**
- **Cumulative 1X2 Hit Rate**: **68.0%**
- **Cumulative Over/Under 2.5 Hit Rate**: **53.4%**
- **Cumulative Exact Score Hit Rate**: **20.1%**

## Monthly Verification Breakdown

| Month | Settled Matches | 1X2 Hit Rate | O/U 2.5 Hit Rate | Exact Score Rate |
| :--- | ---: | ---: | ---: | ---: |
| 2026-11 | 1,821 | 69.7% | 53.1% | 20.9% |
| 2026-10 | 2,046 | 66.1% | 53.7% | 19.0% |
| 2026-09 | 32 | 84.4% | 50.0% | 43.8% |

## Latest 15 Settled Fixtures

| Date | Competition | Matchup | FT Score | 1X2 | O/U | Briefing |
| :--- | :--- | :--- | :---: | :---: | :---: | :--- |
| 2026-11-27 | A-League | Macarthur vs Melbourne City | `2-0` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261127-macarthur-vs-melbourne-city/) |
| 2026-11-27 | Liga MX | Leon vs Cruz Azul | `0-4` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261127-leon-vs-cruz-azul/) |
| 2026-11-27 | Liga MX | CF Pachuca vs Guadalajara Chivas | `2-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261127-cf-pachuca-vs-guadalajara-chivas/) |
| 2026-11-26 | Serie A | Sao Paulo vs Remo | `3-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261126-sao-paulo-vs-remo/) |
| 2026-11-26 | UEFA Europa Conference League | FC Nordsjaelland vs Panathinaikos | `3-2` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261126-fc-nordsjaelland-vs-panathinaikos/) |
| 2026-11-26 | UEFA Europa Conference League | Inter Club d'Escaldes vs FC Copenhagen | `2-0` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261126-inter-club-d-escaldes-vs-fc-copenhagen/) |
| 2026-11-26 | UEFA Europa Conference League | HNK Hajduk Split vs St. Truiden | `0-2` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261126-hnk-hajduk-split-vs-st-truiden/) |
| 2026-11-26 | UEFA Europa Conference League | Gent vs FK Crvena Zvezda | `1-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261126-gent-vs-fk-crvena-zvezda/) |
| 2026-11-26 | UEFA Europa Conference League | SC Freiburg vs Twente | `2-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261126-sc-freiburg-vs-twente/) |
| 2026-11-26 | UEFA Europa Conference League | CSKA Sofia vs Trabzonspor | `1-2` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261126-cska-sofia-vs-trabzonspor/) |
| 2026-11-26 | UEFA Europa Conference League | SC Braga vs KuPS | `4-0` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261126-sc-braga-vs-kups/) |
| 2026-11-26 | UEFA Europa Conference League | Borac Banja Luka vs Atalanta | `2-3` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261126-borac-banja-luka-vs-atalanta/) |
| 2026-11-26 | UEFA Europa League | Torreense vs Celtic | `1-2` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261126-torreense-vs-celtic/) |
| 2026-11-26 | UEFA Europa League | Sunderland vs Jagiellonia | `1-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261126-sunderland-vs-jagiellonia/) |
| 2026-11-26 | UEFA Europa League | Sparta Praha vs AZ Alkmaar | `2-4` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261126-sparta-praha-vs-az-alkmaar/) |

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
