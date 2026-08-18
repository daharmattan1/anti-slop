---
name: compress
description: "Structural subtraction gate that catches document-level padding a word-level editor misses. Use when the user says: 'compress this', 'cut the padding', 'tighten this structurally', 'this is too long', 'make it shorter without losing substance'. CAPABILITY: audits a draft for self-narration, restated points, metaphor twins, false-confidence hedging, and over-engineered structure, and returns a reversible kill-list. OUTPUT: a kill-list of proposed cuts and demotions the author accepts, rejects, or reverses — substance preserved."
---

# compress

A structural editor. Where a lexical pass (`deslop`) removes bad *words*, compress removes bad *volume* — the padding that survives every word-level check because it is made of clean sentences. It returns a **reversible kill-list**, not a rewritten file, so the author stays in control of every cut.

Verbosity is the one defect that *grows* with each revision, and no banned-word scan fires on "too much." A draft can pass every lexical gate and still be bloated past the point of saying anything.

## When to use
- "compress this" / "cut the padding" / "tighten this structurally"
- "this is too long" / "make it shorter without losing substance"
- On any long-form piece (≈1,500+ words) as a standard step before publishing.

## The rule: guilty until proven load-bearing
Every paragraph must earn its place. For each unit, ask: **if I delete this, what does the reader lose?** If the answer is "nothing they didn't already have," it is padding. Default to cut; keep only what carries weight the rest of the piece doesn't.

## What compress hunts for

1. **Self-narration / scaffolding.** Sentences about the piece instead of about the subject: "In this section we'll explore…", "Before we dive in…", "As mentioned above…", "It's worth taking a moment to…". The reader can see the structure; don't narrate it.
2. **Restated points.** The same claim made two or three times in different clothes. Keep the sharpest instance; cut the twins. (This includes a conclusion that restates the body.)
3. **Metaphor-restatement twins.** A point made plainly, then re-made as a metaphor that adds no new information — or the same metaphor farmed across many paragraphs. Keep one.
4. **False-confidence hedging.** "It could be argued that", "in many ways", "to some extent", "arguably" — words that inflate a sentence while lowering its claim. Cut the hedge or commit to the claim.
5. **Over-engineered structure.** Headers, numbered frameworks, and sub-sections imposed on material that is really one straight argument. Collapse the scaffolding.
6. **Padded lists.** A list where half the items are the same idea or exist to hit a round number. Cut to the ones that carry distinct weight.
7. **Throat-clearing openers and windup.** Paragraphs of context before the actual point. Start where the argument starts.

## Demote, don't (always) delete
Not every flagged unit should be cut. Three dispositions:
- **CUT** — pure padding; the reader loses nothing.
- **DEMOTE** — real but over-weighted: a paragraph that should be a sentence, a section that should be a clause, a framework that should be a list. Compress it in place instead of removing it.
- **KEEP** — flagged but load-bearing on a second look. Mark it so a later pass doesn't re-flag it.

## Workflow
1. **Read the whole draft** and hold the argument in mind — you are protecting substance, cutting volume.
2. **Walk it unit by unit** (paragraph, list item, section). For each, assign CUT / DEMOTE / KEEP with a one-line reason.
3. **Return a kill-list, not an edited file.** Format each entry so the author can act on it and reverse it:
   ```
   [CUT]    ¶4 "In this section we'll walk through…"  — self-narration; the header already says this.
   [DEMOTE] ¶7 (5 sentences) → 1  — restates ¶3's point; keep only the new example.
   [KEEP]   ¶9  — flagged as hedged, but the caveat is real and load-bearing.
   ```
4. **State the substance guarantee:** confirm that applying every CUT/DEMOTE removes no argument, example, or claim the piece needs — only repetition and scaffolding.
5. **Let the author accept, reject, or reverse each item.** The kill-list is a proposal; the author is the terminal gate.

## Self-contained
This skill needs nothing but the draft. It reads no external files and runs no scripts. If you want a mechanical word-count delta, count before and after applying the accepted cuts — but the judgment is the point, not the number.

## Honest limit
compress makes a piece shorter and denser. It does not make a boring argument interesting or a wrong one right. It removes what shouldn't be there; it cannot supply what isn't.
