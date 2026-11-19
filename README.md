# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Cube-666/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Cube-666/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Tiny Chess 4K — a deterministic alpha-beta chess engine in 4,096 bytes of Python. 0x88 board, transposition table, quiescence search (captures, promotions, check evasions), null-move pruning, late move reductions, MVV-LVA + killer + history move ordering, and a tuned evaluation (material, piece-square tables, bishop pair, tapered king table). No clock, no randomness: a fixed 60,000-node budget per move, so a replay makes the same moves byte for byte. It plays the house gauntlet over HTTP and scores about 1,300 Elo in practice (floor 1,154).

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=k11s2hyb&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
