---
description: Strip unneeded, drift-prone, and meta comments from the code in scope
---

Clean up the comments in the code in scope (files mentioned above, otherwise the current diff).

- Remove comments not needed for maintenance.
- Remove specifics that can drift (line numbers, counts, values, file paths, names of things that move).
- Remove meta-commentary (what the change is, why it was made, what was there before, notes to the reader).
- Keep what remains minimal, concise, declarative. Lean.

Do not change code behavior.
