# anti-slop

You can't subtract your way to a voice. Anti-slop gates get you to clean, and clean is a floor, not a voice. This repo gives you both halves: the subtractive tools that reach clean, and the additive method that gets you past it.

---

**Before** (nothing here trips a banned-phrase filter, and nothing here would survive a good editor)
> AI has changed how content gets made, and the teams that adapt to it will have an advantage over the teams that don't.

**After** (same claim, from someone who actually holds a position)
> AI drafts to the average of everyone who ever wrote about your topic. You can clean that draft until it is spotless and it will still read like the average. Sounding like you is a separate job, and it's the part almost everyone skips.

The "before" passes a banned-phrase scanner and a quick skim, and a reader still keeps nothing from it. That distance, between a draft that is clean and a draft worth reading, is what this repo is built to close.

---

## What this is

anti-slop is two things at once: a field guide and an installable toolchain for keeping AI-assisted writing from reading like a machine made it. The utility layer is drop-in `rules/` files and installable `skills/` you run against a draft. The authority layer is the `guide/`, the essays and principles that explain why the tools cut what they cut, so you can make the calls a tool can't.

## Quickstart (about 60 seconds)

Two ways in. Pick one.

**A. Drop in a rules file.** Copy one file from `rules/` into wherever your assistant reads its instructions:
- Claude Code: append `rules/anti-slop.claude.md` to your `CLAUDE.md`, or a file it imports.
- Cursor: paste `rules/anti-slop.cursorrules` into your project's `.cursorrules`.
- Copilot: add `rules/anti-slop.copilot.md` to your instructions file.
- Anything else: paste `rules/anti-slop.system-prompt.md` into the system prompt.

Now ask it to write. The banned-phrase baseline applies to every draft it hands you.

**B. Install the skills.** Copy the folders you want from `skills/` into your agent's skills directory, then run them on a draft in order: `deslop` to strip the tells, `compress` to cut the padding, `voice-corpus` once to set up your samples, `voice-judge` to score a draft against them, and `agitate` when a clean draft still reads flat.

## The map

- **`rules/`** holds four drop-in files, one per home: `anti-slop.claude.md`, `anti-slop.cursorrules`, `anti-slop.copilot.md`, and `anti-slop.system-prompt.md`. Same standard, formatted for where it lives.
- **`skills/`** holds five installable skills:
  - **`deslop`** strips the lexical and cadence tells and returns a cleaned draft plus a log of every cut.
  - **`compress`** catches document-level padding a word scan can't see and returns a reversible kill-list.
  - **`voice-judge`** scores a draft against your real samples and hands back the closest passage to write toward.
  - **`voice-corpus`** builds and grows the sample set the previous two run on.
  - **`agitate`** is the additive pass for a draft that is clean and still dead; it mines you for the specific detail that revives it.
- **`guide/`** is the authority layer. Start at `00-start-here.md` for the map and the fast method, then `01-slop-taxonomy.md` for the named tells so you can point at what's wrong instead of just feeling it. `02-cant-subtract-to-a-voice.md` through `08-enforcement-honesty.md` work the thesis out in full: why subtraction stops at clean, stance versus cadence, moving between altitudes inside one piece, the draft-check-edit-compress chain, building a corpus, verifying the verifier, and an honest account of what the tooling catches and misses. `principles/` is the working reference the essays draw on.
- **`examples/before-after.md`** shows the taxonomy in action on invented pairs you can swap for your own.

## The honest limit

These tools are honest about their reach. The rules and `deslop` remove the tells a filter can see, which gets you to clean. Clean is the floor. Nothing here decides whether the draft is worth reading, whether the argument holds, or whether it sounds like you rather than everyone. That work lives in the `guide/`, and most of it is yours to do. The tooling makes the cheap part fast so you have room for the part that counts.

## License

Code, meaning the `rules/` files and the `skills/`, is MIT. Content, meaning the `guide/` and `examples/`, is CC BY 4.0.

Built by Victor Sowers, who writes about the craft at [STEEPWORKS](https://steepworks.io). Released under the licenses in LICENSE (code, MIT) and LICENSE-CONTENT (content, CC BY 4.0).
