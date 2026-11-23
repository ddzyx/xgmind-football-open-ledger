# XG Mind — Open Football Forecast Ledger & Audit

[![Website](https://img.shields.io/badge/Terminal-xgmind.com-10b981)](https://xgmind.com/)
[![Public Ledger](https://img.shields.io/badge/Settled%20Matches-3,769-blue)](https://xgmind.com/performance/)
[![MCP Endpoint](https://img.shields.io/badge/MCP-Streamable%20HTTP-purple)](https://xgmind.com/mcp)

> **Compiled from pre-match timestamped briefings and post-match official results by [XG Mind](https://xgmind.com/).**

This repository is updated daily with XG Mind's public, non-retrospective match forecast verification ledger across 30+ football competitions. Pre-match reports are locked before kickoff and automatically settled after full-time without selective deletion.

- **Last Updated (UTC)**: 2026-11-23 22:30 UTC
- **Total Settled Matches**: **3,769**
- **Cumulative 1X2 Hit Rate**: **67.9%**
- **Cumulative Over/Under 2.5 Hit Rate**: **53.5%**
- **Cumulative Exact Score Hit Rate**: **19.9%**

## Monthly Verification Breakdown

| Month | Settled Matches | 1X2 Hit Rate | O/U 2.5 Hit Rate | Exact Score Rate |
| :--- | ---: | ---: | ---: | ---: |
| 2026-11 | 1,691 | 69.7% | 53.4% | 20.6% |
| 2026-10 | 2,046 | 66.1% | 53.7% | 19.0% |
| 2026-09 | 32 | 84.4% | 50.0% | 43.8% |

## Latest 15 Settled Fixtures

| Date | Competition | Matchup | FT Score | 1X2 | O/U | Briefing |
| :--- | :--- | :--- | :---: | :---: | :---: | :--- |
| 2026-11-23 | La Liga | Levante vs Elche | `1-1` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261123-levante-vs-elche/) |
| 2026-11-23 | Premier League | Brentford vs Everton | `4-0` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261123-brentford-vs-everton/) |
| 2026-11-23 | Serie A | Monza vs Fiorentina | `3-0` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261123-monza-vs-fiorentina/) |
| 2026-11-23 | Ligue 2 | Sochaux vs Dunkerque | `2-3` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261120-sochaux-vs-dunkerque/) |
| 2026-11-23 | Ligue 2 | Nantes vs Grenoble | `1-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261120-nantes-vs-grenoble/) |
| 2026-11-23 | Segunda División | AD Ceuta FC vs Almeria | `2-3` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261123-ad-ceuta-fc-vs-almeria/) |
| 2026-11-23 | AFC Champions League Elite | Al Quwa Al Jawiya vs Al-Gharafa | `2-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261123-al-quwa-al-jawiya-vs-al-gharafa/) |
| 2026-11-23 | AFC Champions League Elite | Al-Ittihad FC vs Pakhtakor | `2-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261123-al-ittihad-fc-vs-pakhtakor/) |
| 2026-11-23 | Allsvenskan | Orgryte IS vs Kalmar FF | `3-2` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261123-orgryte-is-vs-kalmar-ff/) |
| 2026-11-23 | Allsvenskan | Hammarby FF vs IFK Goteborg | `3-1` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261123-hammarby-ff-vs-ifk-goteborg/) |
| 2026-11-23 | AFC Champions League Elite | Tractor Sazi vs Al-Wasl FC | `1-5` | ✅ | ✅ | [Audit](https://xgmind.com/matches/20261123-tractor-sazi-vs-al-wasl-fc/) |
| 2026-11-23 | AFC Champions League Elite | Al Shamal vs Al-Ahli Jeddah | `3-2` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261123-al-shamal-vs-al-ahli-jeddah/) |
| 2026-11-23 | AFC Champions League Elite | Al Ain vs Esteghlal FC | `1-1` | ❌ | ❌ | [Audit](https://xgmind.com/matches/20261123-al-ain-vs-esteghlal-fc/) |
| 2026-11-23 | AFC Champions League Elite | Neftchi vs Al-Hilal Saudi FC | `2-2` | ❌ | ✅ | [Audit](https://xgmind.com/matches/20261123-neftchi-vs-al-hilal-saudi-fc/) |
| 2026-11-23 | Major League Soccer | Vancouver Whitecaps vs Real Salt Lake | `2-0` | ✅ | ❌ | [Audit](https://xgmind.com/matches/20261123-vancouver-whitecaps-vs-real-salt-lake/) |

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
