# TINY CHESS 4K

The strongest chess engine that fits in 4 KB of Python, for the make.fun bounty [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01) ($500, 20 paid places).

> Placeholder README — the builder rewrites this file fully in its recorded session.

## What it does

- `main.py` (at most 4,096 bytes) plays chess against the house gauntlet through the trial env: alpha-beta search with move ordering, quiescence, transposition table and a tuned evaluation, packed with the kit's own compress command.
- Reads `/input/prompt.txt`, plays 8 games (one per house opponent), deterministic: same position and trial seed, same move.

## Entry

- Repo: https://github.com/Cube-666/tiny-chess-4k
- Bounty: https://make.fun/bounty/tiny-chess-01
- License: MIT
