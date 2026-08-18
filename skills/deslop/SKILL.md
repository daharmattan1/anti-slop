---
name: deslop
description: "Subtractive editor that strips the lexical and cadence tells that mark writing as machine-made. Use when the user says: 'deslop this', 'remove the AI tells', 'cut the slop', 'make this sound less like AI', 'clean up this draft'. CAPABILITY: runs the draft against the slop taxonomy (banned phrases, structural pause-budget, voice violations, content sins) and returns an edited draft plus a change log. OUTPUT: the cleaned text + a list of every cut and why."
---

# deslop

A subtractive editor. It removes the patterns that make writing read as machine-made — filler openers, over-performed rhythm, guru voice, fake precision — and returns a cleaner draft plus a record of what changed and why.

**What it does NOT do:** it does not give the writing a voice. Subtraction gets you to *clean*; clean is the floor, not the ceiling. Adding a voice is a separate, additive job (see the `voice-corpus`, `voice-judge`, and `agitate` skills, and `guide/02-cant-subtract-to-a-voice.md`). Run deslop first because it is cheap and certain; then do the additive work on what survives.

## When to use
- "deslop this" / "cut the slop" / "remove the AI tells"
- "make this sound less like AI" / "clean up this draft"
- As the first, cheap pass in a content chain, before any voice work.

## The detection patterns

These are a **representative, editable** set — not an exhaustive lexicon. The point is the *categories* and the *reasoning*; extend the lists with the tells you actually see. Full explanations and before/after examples live in the repo's `guide/01-slop-taxonomy.md`.

### Pass 1 — Banned phrases (tolerance: zero; fastest)
Delete or rewrite on sight. Representative set:
- **Filler openers:** "It's worth noting that", "It's important to note", "In today's landscape/world", "As we all know", "In essence", "At its core", "When it comes to".
- **Abstract framing:** "the realm of", "navigate the complexities of", "a testament to", "plays a (pivotal/crucial/vital) role", "underscores".
- **Generic enthusiasm:** "game-changer", "revolutionary", "cutting-edge", "unlock", "supercharge", "seamless", "robust", "powerful" (as filler).
- **Formal transitions:** "Furthermore", "Moreover", "Additionally", "That being said", "It is important to recognize".
- **Magic adverbs (hollow intensifiers):** "quietly", "simply", "truly", "genuinely", "effectively", "significantly", "seamlessly" — cut unless they carry real information.
- **Avoidance verbs:** "serves as", "acts as", "functions as", "stands as" — usually a dodge for "is".
- **Vague attributions:** "studies show", "experts say", "research suggests", "many believe" — name the source or cut the claim.

### Pass 2 — Structure & cadence (the tell most editors miss)
- **The shared dramatic-pause budget (the key rule):** em-dashes, colon-sentences ("The truth: X"), and dramatic sentence fragments all produce the same *pause-then-deliver* beat, so they draw from ONE budget, not three. A rough working ceiling is about one dramatic pause of any kind per 150 words. Counting only em-dashes misses the budget; count all three together.
- **Aphoristic / staccato closers:** the two-beat mic-drop that ends a section ("X. Not Y." / "A person does."). At most one earned instance in a whole piece — never as a habit. Read each section's LAST sentence in isolation; if ~every section lands a quotable turn, flatten most of them to ordinary sentences.
- **Tricolon abuse:** the rule-of-three rhythm ("faster, cheaper, better") used more than once or twice as decoration.
- **Monotonous sentence length:** many sentences of near-identical length. Vary it.
- **The summary paragraph:** a closing paragraph that restates what was just said instead of advancing.

### Pass 3 — Voice violations
- **Guru language:** "the secret to", "here's the thing", "let that sink in", "master the art of".
- **Hustle / consulting-speak:** "leverage", "synergy", "circle back", "move the needle", "double down", "at the end of the day".
- **Passive authority:** sweeping claims with no citation, hedged into unfalsifiability.
- **Invented concept labels:** capitalizing an ordinary idea into a Branded Framework it hasn't earned.

### Pass 4 — Content sins
- **Fabricated precision:** oddly specific numbers with no source ("73% of teams", "in just 4 steps") — either cite or generalize honestly.
- **Signposted conclusions:** "In conclusion", "To sum up", "The bottom line is".
- **One-point dilution:** a single idea stretched with restatement and padding.
- **Same metaphor 4+ times:** retire a metaphor after its first use or two.

## Workflow
1. **Read the whole draft once** for meaning before cutting anything — you must preserve the argument.
2. **Run the four passes in order** (banned phrases → structure/cadence → voice → content sins). Passes 1 and 4 are close to mechanical; passes 2 and 3 need judgment.
3. **Prefer rewrite over deletion** when a flagged sentence carries real content — cut the tell, keep the point.
4. **Read each section's last sentence in isolation** for the staccato-closer habit; this is invisible to a glyph search and is the most common surviving tell.
5. **Return two things:** the edited draft, and a change log — one line per cut: `[category] "offending text" → fix (why)`.
6. **Do not add anything.** If the draft is clean but lifeless, say so and hand off to the additive skills; do not manufacture a voice here.

## Honest limit
deslop reaches *clean-generic* — a page with nothing wrong on it. Whether there is anything worth reading on it is a separate question this skill cannot answer. Pair it with a voice pass and an independent reader.

## Bundled resources
- `references/patterns.md` — a longer, editable pattern list you can grow with your own tells.
