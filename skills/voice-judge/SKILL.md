---
name: voice-judge
description: "Positive discriminator that scores a draft against real samples of a specific writer's voice and returns the closest real passage as a rewrite target. Use when the user says: 'does this sound like me', 'voice check', 'judge the voice', 'score this against my writing', 'is this in my voice'. CAPABILITY: reads a draft beside a voice corpus, scores 0-100 with PASS/REVISE/REWORK bands, and flags the sentences that read generic with the nearest real-voice counter-example. OUTPUT: a score, per-sentence flags, and a rewrite target for each — plus a graceful first-run path when no corpus exists yet."
---

# voice-judge

A *positive* discriminator. Where `deslop` subtracts known slop (and reaches clean-generic), voice-judge measures the opposite thing: does this draft read like it came from **your** hand? It scores a draft against real samples of your writing and, for every sentence that reads generic, hands back the closest real passage as the target to write toward.

This is the additive half of the method. You cannot subtract your way to a voice — see `guide/02-cant-subtract-to-a-voice.md`. A banned-phrase list tells you what is wrong; voice-judge tells you whether a clean sentence is actually yours.

## When to use
- "does this sound like me" / "is this in my voice" / "voice check"
- "score this against my writing" / "judge the voice"
- After `deslop` and `compress`, as the voice gate before publishing.

## Requires a corpus (and fails gracefully without one)
voice-judge scores against **real samples of a specific author's voice**, kept in a voice
corpus. On the FIRST run, before any corpus exists, do NOT fabricate a score:

> **No voice corpus found.** voice-judge needs real samples of your writing to score against —
> without them it can only compare a draft to the generic average, which is the exact thing this
> method rejects. Build a corpus first with the `voice-corpus` skill (it takes about ten minutes
> and a handful of passages you already wrote), then run voice-judge again. To see how the
> scoring works before you have your own corpus, point it at the bundled sample corpus in
> `examples/sample-corpus/`.

Only score once at least ~3 register-matched samples are available. A judge with no real
counter-examples cannot emit a valid verdict — refuse rather than guess.

## The bands
Score each draft 0-100 for how closely it reads as the same hand as the corpus samples:
- **85-100 — PASS.** Reads as the author's voice. Ship (subject to a human read).
- **70-84 — REVISE.** Mostly there; specific sentences fall to generic. Return the flags.
- **Below 70 — REWORK.** The draft reads as clean-generic, not as this author. Don't polish it —
  re-draft it against the corpus (imitation-first).

## Workflow
1. **Load the corpus.** Read the author's samples. If the corpus tags samples by register (a
   punchy short-form voice vs. a reflective long-form voice, etc.), select the 2-3 samples whose
   register matches the draft — scoring long-form prose against a corpus of one-line social posts
   is a category error.
2. **Read the draft beside those samples.** Judge the same hand: diction, rhythm, how it opens and
   lands, what it is willing to claim, where it takes a position.
3. **Score 0-100** and assign the band. Be honest — a judge that never says REWORK is a rubber
   stamp (see `guide/07-verify-the-verifier.md`).
4. **Flag every sentence that reads generic**, and for each, quote the **closest real passage** from
   the corpus as the rewrite target. The instruction is never "cut this sentence" — it is "pull it
   toward this real one."
5. **Return** the score, the band, and the per-sentence flags with counter-examples.

## Independence note
voice-judge is most trustworthy when it did not write the draft it is scoring — an author scoring
their own draft shares its blind spots. Run it as a separate pass (fresh context, or a different
person), and periodically **verify the verifier**: hand it a passage you know is off-voice and
confirm it catches it. See `guide/07-verify-the-verifier.md`.

## Honest limit
voice-judge measures *fidelity to a voice*, not *quality of thought*. A draft can sound exactly
like you and still say nothing worth saying. It is one gate in a chain, not the whole verdict.

## Bundled resources
- The repo ships a synthetic sample corpus at `examples/sample-corpus/` so the scoring works out of
  the box before you have built your own.
