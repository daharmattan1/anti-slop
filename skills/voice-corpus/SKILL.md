---
name: voice-corpus
description: "Builds and grows a personal voice corpus — the real writing samples that imitation-first drafting and voice-judge run on. Use when the user says: 'build a voice corpus', 'set up my corpus', 'add a voice sample', 'start a voice corpus', 'capture my edits'. CAPABILITY: sets up a corpus file with register tags, signature passages, and captured edit-pairs, and defines the workflow for growing it over time. OUTPUT: a corpus file (from a copy-paste template) plus a repeatable seed-adding routine."
---

# voice-corpus

The raw material the additive method runs on. Imitation-first drafting and `voice-judge` both need real samples of **your** writing; this skill builds that collection and keeps it growing. Nobody can hand you their corpus — a voice corpus is yours by definition. Full rationale: `guide/06-build-a-voice-corpus.md`.

## When to use
- "build a voice corpus" / "start a voice corpus" / "set up my corpus"
- "add a voice sample" / "capture my edits"
- Before the first useful run of `voice-judge` or any imitation-first drafting.

## The three kinds of entry

1. **Register samples.** You do not write in one voice — you write in a few. A punchy short-form
   register, a reflective long-form register, a plain instructional register. Collect a few real
   passages in EACH register you actually use, and tag them, so a drafting or judging pass can match
   the register to the job.
2. **Signature passages.** The passages that could only be you — an odd word choice, a rhythm you
   return to, a flat unresolved line you left on purpose. Keep them exactly as written, typos and
   all. Do not sand them smooth; the roughness is the fingerprint.
3. **Edit-pairs (the highest-value entries).** When you rewrite a machine draft by hand, that diff
   is a training pair: the generic *before* and your *after*. Save both. The pair shows the
   *direction* of the correction, not just the destination — which is exactly what an imitation pass
   needs to learn from.

## Copy-paste template

Start your corpus by copying this block into a file (e.g. `voice-corpus.md`) and filling it in:

```markdown
# Voice corpus — <your name>

## Registers
# List the distinct registers you write in. Tag every sample below with one.
- R1: <e.g. punchy / short-form / social>
- R2: <e.g. reflective / long-form / essay>
- R3: <e.g. plain / instructional / how-to>

## Seeds
# Real passages you wrote. Keep them verbatim — roughness included.
### seed-001
register: R2
source: <where it's from / date>
text: |
  <paste a real passage of your own writing, unedited>

### seed-002
register: R1
source: <...>
text: |
  <another real passage, a different register>

## Signature passages
# The lines that could only be you. Keep exactly as written.
- id: sig-001
  register: R2
  text: "<the exact words — do not clean them up>"

## Edit-pairs
# A machine/generic BEFORE and your hand-edited AFTER.
- id: pair-001
  register: R2
  before: "<the generic draft sentence>"
  after:  "<how you actually rewrote it>"
  note:   "<optional: what you changed and why>"
```

## Workflow
1. **Seed it now.** Do not wait for a perfect set. Paste three real passages you already have,
   tagged by register. Three is enough to start `voice-judge`.
2. **Grow it from real work.** Every time you hand-edit a machine draft, capture the before/after as
   an edit-pair. This is the cheapest, richest signal and it accumulates on its own if you make it a
   habit.
3. **Keep it rough.** Never polish a seed to make it "better." A sanded-smooth seed teaches a
   sanded-smooth voice. Copy passages byte-for-byte.
4. **Tag every entry with a register** so downstream passes can match register to task.
5. **Mark sacred lines** (optional): if a passage contains words that must never be auto-edited,
   note it so your subtractive passes skip it. A subtractive gate removes known-slop tokens, not
   your signature lines — and if a gate ever flags a real signature line, the line wins.

## Honest limit
The corpus is only as honest as the samples in it. If you fill it with writing you wish were yours
rather than writing that is yours, every downstream pass inherits the lie. Use real passages.

## Related
- `guide/06-build-a-voice-corpus.md` — the full method.
- `voice-judge` — scores drafts against this corpus.
- `agitate` — surfaces the registers and lived specifics a corpus alone can't.
