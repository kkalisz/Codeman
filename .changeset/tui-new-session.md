---
'aicodeman': patch
---

`codeman tui <name> --new [-m <mode>] [-d <folder>]` starts a session with that exact name in the current folder (or `--dir`) when no live session has it, then attaches; with a live one it just attaches. No case is created, an implicit home folder and digits-only names are refused, and nothing is created without a terminal or a running server.
