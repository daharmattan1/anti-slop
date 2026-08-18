# Voice corpus — Dana Okafor (SAMPLE, synthetic author)

> This is a **fictional** author, invented so the `voice-judge` skill has a real voice to score
> against out of the box. Dana is a former line cook turned product manager; the voice is plain,
> concrete, impatient with abstraction, and reaches for the kitchen when explaining anything.
> Replace this whole file with your OWN corpus (see the `voice-corpus` skill) — this one exists only
> as a working demo. Nothing here is drawn from any real person's writing.

## Registers
- R1: punchy / short-form (posts, replies)
- R2: reflective / long-form (essays, memos)
- R3: plain / instructional (how-to, docs)

## Seeds

### seed-001
register: R1
source: fictional social post, 2026
text: |
  A roadmap nobody cooked from is just a menu. Pretty, and nobody eats.

### seed-002
register: R2
source: fictional team memo, 2026
text: |
  The first kitchen I worked in had a rule: you clean as you go, or you drown at eight o'clock.
  I didn't believe it until my first Friday, standing in a pile of my own pans with forty tickets
  up. Nobody drowns because they can't cook. They drown because they let the small mess sit.
  Product work is the same. The bug you don't write down at ten in the morning is the outage you
  explain to the whole company at six.

### seed-003
register: R2
source: fictional essay, 2026
text: |
  Everyone wants the recipe. Almost nobody wants to spend the four hours making the stock the
  recipe assumes you already have. So they buy the boxed stuff, and the soup is fine, and fine is
  the ceiling now, and they can't taste why. Most strategy decks are boxed stock. The real work is
  the thing that got skipped before the deck.

### seed-004
register: R3
source: fictional how-to doc, 2026
text: |
  Before you write the spec, do the prep. List every input the feature needs and where it comes
  from. If you can't name where an input comes from, that's not a spec problem, that's a missing
  ingredient, and no amount of writing fixes a missing ingredient.

### seed-005
register: R1
source: fictional reply, 2026
text: |
  "Move fast" and "don't clean up" are two different sentences. People keep saying the first one
  and meaning the second.

## Signature passages
- id: sig-001
  register: R2
  text: "Nobody drowns because they can't cook. They drown because they let the small mess sit."
- id: sig-002
  register: R2
  text: "fine is the ceiling now, and they can't taste why"

## Edit-pairs
- id: pair-001
  register: R2
  before: "It is important to establish robust processes early in order to avoid technical debt down the line."
  after:  "Clean as you go, or you drown at eight o'clock. The mess you skip at ten is the outage at six."
  note:   "Cut the abstract framing; replace with the kitchen rule and the concrete before/after. Same point, but it's mine and you can picture it."
