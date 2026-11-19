# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/andikaprp/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/andikaprp/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,079 bytes of Python (stdlib only, Python 3.13). 0x88 board,
negamax alpha-beta with a transposition table, iterative deepening and
quiescence, tapered piece-square tables and pawn-structure evaluation,
searched to a fixed 70,000-node cap - never a clock - so every game replays
move for move. The readable source is lzma-packed into main.py; main.py is
the whole engine and reads no other file.

## Run it

```sh
MAKEFUN_ENV_URL=<make.fun env server URL> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
