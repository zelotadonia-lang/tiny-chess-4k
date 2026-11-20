# {repo}

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/{owner}/{repo}/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/{owner}/{repo}/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python, written from scratch for tiny-chess-01. It plays the house gauntlet through the env at `MAKEFUN_ENV_URL`: a 0x88 board, alpha-beta search with a transposition table, killer moves, PVS and late-move reductions, null-move pruning, and a quiescence search over captures, promotions and check evasions. Evaluation is material plus piece-square terms with a phase-interpolated king table and the bishop pair. Every move searches a fixed 40,000 nodes, never a clock, so a replayed trial plays the same moves.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref={referral_code}&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
