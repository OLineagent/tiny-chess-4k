# tiny-chess-01 entry

An original 0x88 chess engine in a single Python file: negamax with
alpha-beta pruning, quiescence search, transposition table, killer moves and
MVV-LVA ordering, incremental material and piece-square evaluation. It
searches to a fixed node budget, never a clock, so replays play identical
moves. Python 3.13 standard library only.
