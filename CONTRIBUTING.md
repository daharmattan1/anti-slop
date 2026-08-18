# Contributing

This repo gets better when people who actually fight slop for a living add what they've caught.
The most useful contribution is not code — it's a **slop pattern** you've seen in the wild that the
taxonomy misses.

## Submit a slop pattern

Open an issue (or a PR against `guide/01-slop-taxonomy.md` and `skills/deslop/references/patterns.md`)
with:

1. **The tell** — the phrase, structure, or move, named plainly.
2. **A before/after** — a short synthetic example showing the slop and a fix. Invent it; don't paste
   anyone's real copy.
3. **The category** — which of the taxonomy's groups it belongs to (banned phrase, structure/cadence,
   voice, content sin), or propose a new one.
4. **Why it's a tell** — one line on what makes it read as machine-made.

Good patterns are specific and testable. "AI writing is generic" is not a pattern; "every section
ends on a two-beat 'X. Not Y.' closer" is.

## What makes a pattern land here

- It survives a banned-word scan (the interesting tells always do).
- It generalizes past one topic or author.
- It comes with a fix, not just a complaint.

## Docs and skills

- Prose changes: keep the repo's own standard. A contribution to an anti-slop guide that reads as slop
  won't merge — run your text through `deslop` first.
- Skill changes: keep them self-contained (no external dependencies, no private data) and add a smoke
  test showing the behavior.

## Ground rules

- No real third-party copy, no private/identifying data in examples — synthetic or your own only.
- MIT for code (`rules/`, `skills/`), CC BY 4.0 for content (`guide/`, `examples/`). By contributing
  you agree your contribution ships under those licenses.
