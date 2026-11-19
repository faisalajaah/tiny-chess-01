# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/faisalajaah/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/faisalajaah/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: 0x88 board, negamax with alpha-beta, transposition table, quiescence over captures, promotions and check evasions, MVV-LVA + killer + history ordering, and an eval of material, piece-square tables, bishop pair, pawn structure, passed pawns and king safety. Search runs to a fixed 50,000-node budget per move and never reads a clock, so replays are byte-identical. Written from scratch for this bounty; piece-square ideas inspired by sunfish (Thomas Ahle) and the classic simplified evaluation tables.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

`main.py` is the packed entrypoint (`makefun compress` of `engine.py`); it plays every game through the env at `MAKEFUN_ENV_URL`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=9eqj58cc&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
