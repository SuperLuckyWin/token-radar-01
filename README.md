# token-radar-01

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/SuperLuckyWin/token-radar-01/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/SuperLuckyWin/token-radar-01/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar (radar-2): a ranked board of pre-token protocols by implied value, built from the sealed DefiLlama snapshot. The model prices each protocol from the snapshot's own figures — TVL times a category multiple taken from the median market-cap / TVL of live-token protocols in the same category in this snapshot, times a growth multiplier (upside and downside weighted differently), times an inverted-U launch-readiness curve over age with no token, times a multi-chain breadth factor — and covers all 226 rankable pre-token protocols (the 40-protocol watchlist plus every rankable protocol below the floor), each with a seven-step farm plan. The dashboard is a static, offline page with a sortable, filterable board, a detail view per protocol, and a live-token view set aside with market caps.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts --input <path-to-snapshot.json>
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=bmwyyzmm&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
