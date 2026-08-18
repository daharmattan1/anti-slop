# Quote Inventory (threshold >= 40 consecutive words)

Regenerated mechanically by `_tools/quote_inventory.py`. Every flagged run is
deep-checked to confirm it is original prose, not a verbatim third-party passage.

Flagged runs (mechanical ≥40-word verbatim): 14 — **all original repo prose, zero in-copyright**.
Every long run is a skill description, a guide blockquote, the sample-corpus disclaimer, the scrubbed
real-hand-edit excerpt (from the author's own already-published essay), or an original
sentence-rhythm demonstration. None reproduces a third-party book, article, or advertisement. Deep-
check verdict: 0 verbatim in-copyright passages ship. Re-run `quote_inventory.py` after any change.

| File | Kind | Words | What it is |
|------|------|-------|-----------|
| guide/01-slop-taxonomy.md | blockquote | 87 | own "superficial competence" meta-question block |
| skills/voice-judge/SKILL.md | blockquote | 81 | own empty-corpus message |
| skills/{voice-corpus,deslop,compress}/SKILL.md | description | 71-79 | own skill descriptions |
| examples/sample-corpus/voice-corpus.md | blockquote | 76 | own synthetic-author disclaimer |
| examples/real-hand-edit.md | blockquote | 64-65 | author's own (published, scrubbed) essay excerpt |
| guide/03-stance-vs-cadence.md | blockquote | 41-64 | own worked demo sentences |
| guide/principles/sentence-rhythm.md | blockquote | 54-61 | own original rhythm demonstrations |
| README.md | blockquote | 44 | own above-fold "after" example |

## Fair-use paraphrase log (attributed, NON-verbatim)

`guide/principles/masters-as-lenses.md` and `copywriting-methodology.md` name real advertising
writers and describe their techniques and campaigns. Every reference is an **attributed paraphrase
in original words** — no advertisement, headline, or book passage is reproduced verbatim; famous
copy is *described*, not quoted; books appear as further-reading pointers, not excerpts. This is
attributed critical commentary on ideas/methods (fair use), not redistribution of protected copy.

| Doc | Reference | Treatment |
|-----|-----------|-----------|
| masters-as-lenses | Ogilvy (luxury-car ad) | Described the "one quiet concrete detail" technique; ad line NOT quoted |
| masters-as-lenses | Hopkins (toothpaste / process-vividness) | Described the reader-confirms-it technique; no ad text reproduced |
| masters-as-lenses | Caples (famous headline arc) | Described structure (embarrassment→triumph); headline NOT quoted |
| masters-as-lenses | Kennedy (maxim) | Short attributed paraphrase of an idea |
| copywriting-methodology | Hopkins (reader self-interest) | Attributed short paraphrase, flagged inline |
| sentence-rhythm + masters | Provost (rhythm passage) | Provost's famous passage deliberately NOT reproduced; a fresh original demonstration written; idea attributed by name |

Batch A docs (`00-start-here`, `content-principles`, `productive-tensions`): no third-party quotes
retained; all example strings are original invented illustrations.

## How to re-verify

```bash
python _tools/quote_inventory.py staging --threshold 40
```
