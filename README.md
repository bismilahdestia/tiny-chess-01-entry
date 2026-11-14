# Tiny Chess — v4 engine

A 4 KB Python chess engine for the make.fun tiny-chess-01 bounty:
alpha-beta search with aspiration windows, futility pruning, king tropism
and a pawn shield. Packed with lzma (4,063 bytes); it unpacks to the engine
source at runtime. Practice trial-3: Elo 1253.

The pack is built from the engine source with lzma preset 9 + base85
(pack3.py): the submitted bytes are a deterministic transform of that
source, verified by decompressing byte-for-byte before submitting.
