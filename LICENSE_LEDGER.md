# License Ledger — anti-slop

This ledger shows the repo ships **no in-copyright full text**. Every source class
below is enumerated, and a mechanical quote sweep (`_tools/quote_inventory.py`,
threshold ≥ 40 consecutive words) confirms the only long runs are original prose —
not verbatim third-party passages.

## Source classes

| Class | What it is | Redistribution basis |
|-------|-----------|----------------------|
| **Original prose** | The guide essays (`guide/`), the README, the worked examples (`examples/`), and every skill and rules file — written from scratch for this repo. | Original work → MIT (code) / CC BY 4.0 (content). |
| **Paraphrase-with-attribution** | Short, attributed restatements of the methods of named writers and copywriters in `guide/principles/`, always in our own words and cited — never a reproduced passage. | Fair use — short, transformative, attributed, non-substitutive. |
| **Resolvable links** | Citation URLs to source articles and books. Links only — no copied article text. | Linking is not redistribution. |
| **Public-domain / permissive** | Method *names* and *structures* (editorial rules, rhetorical moves) are ideas/methods, not copyrightable expression. | Not copyrightable as ideas. |

## Mechanical quote sweep

`python _tools/quote_inventory.py staging --threshold 40` flags every quoted or
blockquoted run ≥ 40 consecutive words. Deep-check any flagged run to confirm it is
original prose. See `QUOTE_INVENTORY.md` for the current result.

## How to re-verify

```bash
python _tools/quote_inventory.py staging --threshold 40
```

Re-run after any content change and deep-check any newly flagged run.
