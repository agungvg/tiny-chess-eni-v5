# tiny-chess v5

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/agungvg/tiny-chess-eni-v5/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/agungvg/tiny-chess-eni-v5/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01) — "Build the strongest chess engine in 4 KB of Python".

Fresh hand-written re-author (v5): 0x88 board, tapered piece-square evaluation with a bishop-pair bonus, PVS + late-move-reduction alpha-beta, null-move pruning, check extensions, mate-distance pruning, transposition table, killer + history ordering, and quiescence over captures, promotions and replies to checks. Fixed 60,000-node budget per move, no clock, fully deterministic. Plays the gauntlet over HTTP (`MAKEFUN_ENV_URL`).

## Files

- `main.py` — packed entrypoint (lzma payload, at most 4,096 bytes).
- `LICENSE` — MIT.

<sub>Entered on [make.fun](https://make.fun/?ref=p9r33tb4&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
