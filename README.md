# makefun-chess-4kb-20261124

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/gom92/makefun-chess-4kb-20261124/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/gom92/makefun-chess-4kb-20261124/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python: a 0x88 board, negamax with alpha-beta pruning, quiescence search over captures, a transposition table with killer-move ordering, and iterative deepening on a fixed 50,000-node budget per move. It plays the make.fun house gauntlet through the trial env (HTTP, UCI moves), fully deterministic — no clock, no unseeded randomness.

## Run it

```sh
python3 main.py
```

(The trial harness sets `MAKEFUN_ENV_URL`; the engine talks to the env there.)

---

<sub>Entered on [make.fun](https://make.fun/?ref=radjee14&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
