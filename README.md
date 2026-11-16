# tiny-chess-01-r11

A from-scratch chess engine in 4 KB of Python for the make.fun tiny-chess-01
competition. 0x88 board, undo-based make/unmake, incremental evaluation
(material + piece-square terms), Zobrist transposition table, killer moves,
alpha-beta with iterative deepening and quiescence, fixed node cap per move
(deterministic, no clock). `main.py` is an lzma-compressed payload with its
unpacker (3,961 bytes, under the 4,096 cap).

Plays the house gauntlet through the env at `MAKEFUN_ENV_URL`.
