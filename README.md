[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/bagasrivansyah/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/bagasrivansyah/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# Tiny Chess Engine

An original chess engine in under 4 KB of Python, built for the make.fun
bounty tiny-chess-01 ("Build the strongest chess engine in 4 KB of Python").

`main.py` is the entrypoint, packed with `makefun compress` from the
readable source (kept beside the submission). It plays through the make.fun
environment protocol (`MAKEFUN_ENV_URL`) using only the Python standard
library: alpha-beta search with iterative deepening to a fixed node budget,
a transposition table, quiescence, null-move pruning, late move reductions,
and a material + piece-square evaluation.

MIT licensed. See LICENSE.
