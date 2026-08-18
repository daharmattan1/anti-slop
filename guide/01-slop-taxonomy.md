---
title: The Slop Taxonomy
description: A working catalog of the AI writing patterns that erode credibility — banned phrases, structural tells, voice violations, content sins, outbound and conversion failures, and composition tropes — with before/after fixes.
type: reference
---

# The Slop Taxonomy

A working catalog of the writing patterns that mark text as machine-made and erode a reader's trust. It covers every content type: articles, emails, social posts, outbound sequences, conversion copy, and internal documents.

Each pattern comes with a tolerance (how many instances are acceptable), a detection method, and a fix. Most fixes include a before/after pair. The "before" cells deliberately contain slop — that is the point. They show you the pattern so you can recognize it in your own draft.

Run this on any piece before you publish. A full pass takes roughly eight to ten minutes per 2,000 words. Outbound and conversion copy get the additional checks in Sections 5 through 7.

**Scope note:** slop applies to all content, not just articles. Emails, chat messages, social posts, and internal documents ("workslop") are equally susceptible. Short-form is especially prone to the Category 1 patterns, because the ratio of filler to substance is higher when there are fewer words to hide in.

---

## The Meta-Question (Ask This First)

> **Does this content exhibit superficial competence?**
>
> Superficial competence means the writing sounds authoritative but says nothing specific. It has the *shape* of insight without the substance. If the answer is yes, individual pattern fixes will not save it. The piece needs rewriting, not editing.
>
> Three diagnostic properties (Kommers et al., 2026): Does it read as if produced with **asymmetric effort** — easy to generate, hard to verify? Could it be **mass-produced** with a different topic swapped in? Does it pass a quick skim but fail close reading?

If you answer yes to the meta-question, stop checking patterns and rewrite from scratch. Pattern-level fixes on a superficially competent piece only produce polished slop.

**Treat this as an answered gate, not a vibe.** Do not skim it as preamble. Answer each property in writing, with one line of evidence. And if the prose is yours — you drafted it — you are the worst judge of whether it says something. Route the answer to a fresh reviewer (a second pass with clean context, or a reader who has not seen the draft), rather than certifying it yourself.

Add a fourth property for anything a reader will see, especially after several revision rounds: **is it verbose or repetitive** — the same word or idea hammered, paired and listy phrasing, stacked abstractions? A yes there routes to a compression pass. Verbosity is the one defect that *grows* with iteration, and no lexical check fires on "too much." A draft can pass every banned-word scan and still be bloated past the point of saying anything, because the bloat is made of clean sentences.

---

## Category 1: Banned Phrases

**Tolerance:** Zero instances. **Detection:** Automated search-and-replace. **Time:** 2-3 minutes.

These are literal strings. If they appear, delete or rewrite on the spot.

### 1.1 Filler Openers

Remove on sight:

- "It's worth noting that..."
- "This represents..."
- "What this means is..."
- "In today's landscape..."
- "However, it's important to recognize that..."
- "The implications extend beyond..."
- "Organizations are responding by..."
- "The message is clear:"
- "Here's the critical distinction:"
- "As we all know..."
- "In essence..."
- "At the end of the day..."
- "When it comes to..."
- "In terms of..."
- "It's important to understand that..."

**Fix:** Delete the opener. Start with substance. "It's worth noting that revenue dropped 15%" becomes "Revenue dropped 15%."

### 1.2 Abstract Framing Words

Never use these conceptual labels:

- "Paradox" / "Collision" / "Tension" / "Dichotomy"
- "Validates" / "Represents" / "Demonstrates"

**Fix:** Replace with cause and effect. Show the shift; do not label it. "There are more X, Y can act on them faster, so we need to respond by Z."

### 1.3 Generic Enthusiasm

Never use these buzzwords:

- "Revolutionary" / "Game-changing" / "Transformative"
- "Cutting-edge" / "Best-in-class" / "Industry-leading"
- "World-class" / "Unprecedented" / "Groundbreaking"

**Fix:** Replace enthusiasm with a specific claim. "Game-changing analytics platform" becomes "Identifies at-risk deals 14 days before they go dark."

### 1.4 Formal Transitions

Never use:

- "Furthermore" / "Moreover" / "Subsequently"
- "Additionally" / "Consequently"
- "In addition..."

**Fix:** Use "Also," "And," "So," "Then," or just start the next sentence. If the connection is not clear without a formal transition, fix the logic instead of labeling it.

### 1.5 Magic Adverbs

Cut these immediately:

- "quietly" / "deeply" / "fundamentally"
- "increasingly" / "remarkably" / "simply" / "arguably"

**Fix:** Cut the adverb. If the verb needs help, pick a better verb. "Quietly reshaping" — if something is reshaping, say how. If it is not, cut the claim.

### 1.6 Avoidance Verbs (the "Serves As" Dodge)

Never use:

- "serves as" / "acts as" / "functions as"
- "stands as" / "marks a" / "represents a"

**Fix:** Use the direct verb. "X serves as a catalyst" becomes "X accelerates." "This serves as a reminder" becomes "This is a reminder," or just state the reminder.

### 1.7 Vague Attributions

Never use without specifics:

- "experts say" / "research shows" / "studies suggest"
- "many believe" / "industry reports indicate"
- "industry leaders believe"

**Fix:** Name the expert. Cite the study. Link the report. Or cut the claim. "Studies show content quality matters" becomes "A 2025 study of 1,250 firms found only 5% achieve AI value at scale."

### 1.8 Superficial -ing Analyses

Never use:

- "reshaping" / "reimagining" / "redefining"
- "revolutionizing" / "highlighting its importance" / "reflecting broader trends"

**Fix:** Describe what actually changed. "Reshaping" — what shape was it before, what shape is it now?

---

## Category 2: Structural Patterns

**Tolerance:** Count-based limits. **Detection:** Visual scan of document shape. **Time:** 3-4 minutes.

Read looking at shape, not content. Are the bullet points all in groups of three? Do sections end with platitudes? Are em-dashes everywhere?

### 2.0 The Combined Dramatic-Pause Budget (read this first)

**Budget:** em-dashes, colon-sentences, and dramatic fragments share **one** budget — collectively about one per 150 words. For a 2,400-word piece, that is roughly sixteen dramatic pauses of all three kinds combined.

This rule exists because the three tells were once budgeted *separately*, and that separation was gameable. A draft that overran the em-dash cap could be "fixed" by converting em-dashes to colons: the em-dash count drops, the colon count rises inside its own allowance, and the dramatic-pause rhythm is completely unchanged. The reader still hears the same throat-clear-then-deliver beat. Only the punctuation changed.

So the three draw from one shared pool. Converting an em-dash to a colon does not reduce the count. Converting either to a dramatic fragment does not reduce the count. They are the same move wearing three costumes.

**How to actually reduce the count:** remove the pause, do not relocate it. Restructure into ordinary connected prose — conjunctions, subordinate clauses, two plain sentences with no theatrical beat between them. If the pause is load-bearing, keep it and spend one unit of the budget. If it is there for drama, cut it. That is a real reduction.

A piece can pass the individual caps below and still blow this combined budget. The combined budget is the binding constraint; the per-tell caps are floors within it.

**Register note (personal essay):** this budget is tuned for the default register — newsletter, long-form, and client or conversion copy — and stays strict there. In a personal-essay register, bare *emphasis* fragments can be an established authorial signature rather than drama. Where that is genuinely true of a writer's voice, exclude the fragment sub-count from this pool while keeping em-dashes and colon-sentences strict against the same budget. Do not relax this for newsletter, long-form, or any client-facing copy — those keep the full combined budget, fragments included. When in doubt, trust the author's real voice over the raw number, but only after confirming the fragments carry emphasis and not manufactured weight.

### 2.1 Em-Dash Saturation

**Max:** 1-2 per article, and counts against the §2.0 combined budget.

AI uses em-dashes at three to five times the rate of human writers. It is the single most recognizable tell.

| AI Pattern | Human Alternative |
|------------|-------------------|
| "AI tools—including X and Y—generate issues" | "AI tools like X and Y generate issues" |
| "The attack surface—already massive—continues" | "The already massive attack surface continues" |

**Alternatives:** "whether via," "including," "from X to Y," parentheses, or two sentences. Converting an em-dash to a colon is not an alternative — it keeps the same pause and still spends a budget unit.

### 2.2 Colon-Sentence Construction

**Max:** 2-3 per article, and counts against the §2.0 combined budget.

| AI Pattern | Human Alternative |
|------------|-------------------|
| "The result: Generic solutions don't fit." | "Generic solutions don't fit." |
| "Here's the key insight: Purpose-built tools win." | "Purpose-built tools win." |

**Fix:** State the fact directly without preamble. Break into two sentences. Use a conjunction. Do not "fix" an em-dash overrun by converting it here — see §2.0.

### 2.3 Colon Lists Must Become Bullets

When "For example:" or "Consider:" is followed by three or more parallel items, use actual bullet points, not an inline list.

```markdown
BAD:  For example: First item. Second item. Third item.
GOOD: For example:
      - First item
      - Second item
      - Third item
```

### 2.4 Tricolon Abuse

**Max:** 2 tricolons per piece.

Everything comes in groups of three: "Speed, quality, and reliability." When everything is a tricolon, nothing has emphasis. The rhythm becomes monotonous. Readers sense the pattern even when they cannot name it.

**Fix:** Vary the groupings. Use two items, four items, or one. Save tricolons for moments where three is genuinely right, and make the third item surprising rather than predictable.

### 2.5 Aphorism Endings

**Max:** 0 per piece.

Sections close with fortune-cookie statements: "After all, the best content is content that connects," or "In the end, quality speaks for itself." These are vacuous — the reader believed them before reading.

**Fix:** End sections with your most specific point, not your most general one. End with earned insight, not platitude.

*Distinct from Signposted Conclusions (4.4), which cover "Despite..." and "In conclusion..." wrap-up language. Aphorism endings are vacuous wisdom, not summaries.*

### 2.6 False Drama Constructions

**Max:** 0-1 per article.

- "This isn't X—it's Y" (for example, "This isn't failure—it's strategic clarity")
- "But here's the critical difference:"
- "The question is no longer X? It's Y?"

**Fix:** Direct statements, without negation or rhetorical setup.

### 2.7 Artificial Revelation Phrases

**Max:** 0 per article.

- "The pattern is clear:"
- "This is where X [verb]s"
- "What does X look like in practice?"

**Fix:** State the pattern directly, without telegraphing it.

### 2.8 Repetitive Emphasis Structures

**Max:** 0 per article.

- "It means... It means... It means..." repetition
- "This is the [term]:" label construction
- "This is fundamentally different"

**Fix:** A single clear statement, no repetition for emphasis.

### 2.9 Colon + Punctuation Compounds

**Max:** 1-2 per article.

- "X: Y—Z" (a colon immediately followed by an em-dash clause)
- Multiple "X: [full sentence]" constructions in succession

**Fix:** Break into separate sentences, or use a different structure.

### 2.10 Meta-Commentary Setup

**Max:** 0 per article.

- "Think about what this means"
- "Here's what X looks like:"

**Fix:** Show it directly. Do not tell the reader to think.

### 2.11 "Not X. Not Y. Just Z." Escalation

**Max:** 0 per article.

Three-part negation building to a dramatic reveal: "Not faster. Not cheaper. Just better."

**Fix:** State Z directly. The runway adds nothing the reader did not already expect.

### 2.12 Monotonous Sentence Length

**Max:** No runs of 3+ similar-length sentences.

AI often generates sentences of uniform length, which creates a droning effect that disengages readers.

**Example (bad):**

> Our platform helps teams reduce their stale pipeline significantly. We use AI to automatically generate next-step actions for every deal. Teams can review these actions just like any other workflow. This approach saves time and reduces manual effort.

Four sentences, all 10 to 14 words. No variation. It reads like a stuck record.

**Fix:**

- Vary sentence length deliberately.
- Short sentences (5 to 12 words) for emphasis and punch.
- Longer ones (15 to 30+ words) for context and building energy.
- Read aloud to hear the rhythm.
- The no-more-than-three rule: avoid three or more similar-length sentences in a row.

### 2.13 The Summary Paragraph

**Max:** 0 per piece.

AI loves to summarize what it just said: "In summary, we've explored how AI is transforming operations, discussed the key benefits, and outlined the implementation steps."

**Fix:** Say it once, say it well, stop.

---

### 2.14 Cadence and Rhythm Tells (Over-Performed Rhythm)

Good rhythm varies sentence length and reads naturally aloud (see Gary Provost's read-aloud framework). Section 2.12 covers the *monotony* failure — uniform sentences that drone. This block covers the opposite failure: rhythm that is *over-performed*, where drama is manufactured through fragments, staccato, and reveal scaffolding. Section 2.12 is too flat. Section 2.14 is too theatrical. Both read as AI. They are siblings, not duplicates — a draft can pass 2.12 with good length variety and still fail 2.14 because every variation is deployed for drama.

This is the tell that survives a lexical scan. The vocabulary is clean, the sentence lengths vary, every banned phrase is gone, and the piece still reads as AI because the *rhythm* is performing. It keeps clearing its throat, announcing what is coming, landing on a punchy fragment, then doing it again.

#### 2.14a Fragment-for-Drama

**Max:** 0-1 per piece. A deliberate fragment is fine; a *habit* of them is the tell.

A sentence is amputated into a fragment to manufacture weight. The fragment adds no information — it only signals "this is important."

| AI Pattern (over-performed) | Human Alternative |
|------------------------------|-------------------|
| "Built, styled, shipped-ready." | "It came back built, styled, and ready to ship." |
| "That's it. That's the mechanism." | "That's the mechanism." (one statement, not a drumroll) |

#### 2.14b Self-Narrating Meta-Sentences

**Max:** 0 per piece.

The writer narrates their own essay — flagging that a point is hard, that they took a while to see it, that they are about to go somewhere. This is throat-clearing dressed as intimacy. Distinct from 2.10 (which tells the *reader* to think); here the writer narrates their *own* process.

| AI Pattern (over-performed) | Human Alternative |
|------------------------------|-------------------|
| "That's the moment worth sitting with." | (cut entirely — sit with it by writing the next sentence) |
| "Now the part that took me longest to see." | (cut — if it took you longest, show why it is hard, do not announce it) |
| "Here's where I want to take it somewhere they don't." | "The original stops at accountability. Two things it names don't transfer." |

#### 2.14c Reveal Scaffolding

**Max:** 0 per piece.

A runway is built before the point so the point lands as a "reveal." The scaffolding — "here's the thing," "the line I keep coming back to:" — is pure setup. Overlaps 2.7 but is specifically the *rhythmic* pause-then-deliver move.

| AI Pattern (over-performed) | Human Alternative |
|------------------------------|-------------------|
| "And here's the thing: it wasn't wrong, exactly." | "It wasn't wrong, exactly." |
| "The line I keep coming back to: teams ask AI to fix a problem they never instrumented." | "Teams keep asking AI to fix a problem they never instrumented." |

#### 2.14d Aphoristic Staccato Closers

**Max:** 0-1 per piece.

Paragraphs and sections close on a short, declarative, quasi-profound beat — often a two-part staccato ("The machine can't hold the bag. So the bag is still yours."). One earned punch is voice; closing *every* section this way is a tic. Related to 2.5 (vacuous wisdom); 2.14d is about the *staccato rhythm* of the closer even when the content is real.

| AI Pattern (over-performed) | Human Alternative |
|------------------------------|-------------------|
| "The machine can't hold the bag. So the bag is still yours." | "The machine can't hold the bag, so it's still yours." (one breath, not two beats) |
| "You have a measurement problem wearing an AI costume." | "That's a measurement problem, not an AI opportunity." (state it; do not perform it) |

#### 2.14e Structural Narration (the essay narrating its own argument)

**Max:** 0 per piece.

Distinct from 2.14b (narrating one's own *process*) and 2.10 (telling the *reader* to think): here the prose narrates **where you are in the argument** — recapping the section just finished, announcing the relationship between sections, or labeling a transition as a transition. It is the connective tissue announcing itself instead of connecting. Cut it; let the next point land and trust the reader to feel the join.

| AI Pattern (over-performed) | Human Alternative |
|------------------------------|-------------------|
| "That was the altitude view. This month two things sharpened it into something I hadn't seen before:" | "This month it got specific." |
| "Here's the catch, and it connects back to the earlier section." | "But you don't get to be a framer without first having built frames." (just make the point) |
| "All three sections circle the same unanswered question:" | (cut the meta-frame; ask the question) |
| "And here's why that's a problem and not just an inconvenience:" | "And the responsibility never moved with the work." |

#### 2.14f Performed Stance (announcing honesty, surprise, or generosity instead of having it)

**Max:** 0 per piece.

A sentence advertises the writer's emotional posture — candor, surprise, fairness, generosity toward a source — rather than demonstrating it. The hedge, surprise, or credit should be specific and embedded, not announced. Name the specific worry, not the clean hedge.

| AI Pattern (over-performed) | Human Alternative |
|------------------------------|-------------------|
| "Caveat worth saying out loud: it's a sample of postings, not a census." | "It's a sample of postings, not a census." |
| "The researcher did the work I wish more people would. They pulled the postings..." | "The researcher pulled the job postings..." (credit by citing the work, not by praising it) |
| "which is the part that surprised me" | (cut — if it is surprising, the fact carries the surprise) |
| "I'm not going to pretend that reconciles cleanly." | (cut — hold the two facts side by side) |

**The read-aloud test for 2.14:** Provost's read-aloud test catches monotony, where the prose drones. The 2.14 test is the inverse — read it aloud and ask whether it sounds like someone performing a TED talk to themselves. If every few sentences lands a mic-drop, the rhythm is manufactured. Real voice has stretches of flat, ordinary connective prose between the punches.

---

### 2.15 Competent Smoothness (the tell that survives all of Categories 1-4)

The hardest failure to catch: a draft with zero banned phrases, clean structure, no voice violations, and every number sourced — and it is *still* recognizably AI. It passes every lexical and structural gate and reads as machine-made anyway, because it is *evenly built*. This is what remains once every obvious slop token is gone: not slop, but smoothness.

It shows up as four architecture-and-register habits, none of which any pattern-match can see:

| Habit | AI default | Human alternative |
|---|---|---|
| **a. Aphorism over enumeration** | Land the paragraph on a quotable abstraction that names the *shape* of the idea ("the work most in need of a human is the work that arrives looking like it doesn't") | List the literal particulars the abstraction stands in for ("the hundred small calls about emphasis and structure and which capability claims were true enough to show a customer"). The fix for a faux-profound landing is often replace-with-concrete, not just delete. |
| **b. News-as-spine** | Open the section with the strongest available news hook, then append the take | Open with your own *causal model*; demote the news or data to evidence the model explains |
| **c. Takeaway-as-widget** | Package the actionable into a boxed checklist, numbered framework, or labeled callout | Land the same payload as one flat declarative sentence ("the human is still responsible for every facet of the delivery. Period.") |
| **d. Uniform finish** | Smooth every sentence to the same even, declarative polish | Leave the roughness real voice has: a bare interjection, a one-word sentence, caps for stress, an em-dash mid-thought. Stop one polish-pass short of uniform. |

**Why no gate catches it:** each sentence is locally clean, so Categories 1 and 2 pass; the voice is plausible, so Category 3 passes; the claims are sourced, so Category 4 passes. The tell lives in the *relationship between* sentences and in the choice of *what to land on* — above the altitude any pattern-match operates at. A structural compression pass sees padding but not register. Only a read-aloud against a real human voice catches it.

**The diagnostic question:** *"If I handed this to the author, would they rewrite the architecture, or just tweak words?"* If a competent writer would re-spine the section (lead with their own model), re-land the closers (concrete over aphorism), un-box the takeaways, and re-roughen the finish, the draft has competent smoothness even though it scored clean. In one documented case, an AI draft passed every lexical and structural gate and was still heavily rewritten by its author on voice grounds — the rewrite touched architecture, not vocabulary.

---

## Category 3: Voice Violations

**Tolerance:** Zero instances. **Detection:** Judgment-based reading. **Time:** 3-4 minutes (combined with Category 4).

Read with the question: "Would my most skeptical reader trust this paragraph?"

### 3.1 Guru Language

- "Unlock the secrets to..." / "Master the art of..."
- "Discover the hidden framework..." / "Transform your approach..."
- "The ultimate guide to..."

These position the writer above the reader and break practitioner solidarity.

**Fix:** Replace revelation with observation. "Unlock the secrets to better content" becomes "Here's what worked after testing 40 different editorial workflows."

### 3.2 Hustle-Culture Contamination

- "10x your content output" / "Crush your competitors"
- "Growth hack your editorial process" / "Level up your..."
- "Grind through your content calendar"

This alienates experienced operators who have been through enough hype cycles to be allergic to it.

**Fix:** Replace intensity with specificity. "10x your content output" becomes "We went from 4 posts a month to 12 by automating research and first drafts."

### 3.3 Consulting-Speak Contamination

- "Leverage your content assets" / "Optimize stakeholder alignment"
- "Synergize cross-functional inputs" / "Drive holistic content strategy"
- "Operationalize the framework"

This creates distance and makes prose read like a slide deck.

**Fix:** Use the verb a normal person would use. "Leverage your content assets" becomes "Reuse your best-performing posts."

### 3.4 Passive Authority Voice

- "Research suggests..." / "Studies have shown..."
- "It has been demonstrated that..." / "Experts agree..."

This communicates nothing without specifics.

**Fix:** Cite a specific source, or own the opinion. "Studies show content quality matters" becomes "A 2025 study found only 5% of firms achieve AI value at scale."

### 3.5 False Vulnerability

- "I'll be honest..." / "This keeps me up at night..."
- "And yes, I'm openly in love with..."
- "If I'm being transparent..."

Performative vulnerability is the opposite of trust-building. It signals you are about to sell, not share.

**Fix:** Show vulnerability through specifics; do not announce it. "We tried X and it failed" beats "I'll be honest, this was hard." The reader should feel it, not be told about it.

### 3.6 Invented Concept Labels

Ad-hoc compound terms presented as established concepts: "supervision paradox," "acceleration trap," "alignment gap," "workload creep."

This makes you sound like you are manufacturing thought leadership instead of sharing real insight. Readers sense the invention.

**Fix:** If the concept needs a label, cite who coined it. If you coined it, earn it with three or more paragraphs of supporting evidence, or at least three data points.

### 3.7 False Ranges

- "It's both X and Y" / "at once X and Y"
- "simultaneously X and Y" / "From X to Y" where the endpoints are not on a real scale

**Fix:** Pick the more important one. Or show the tension with actual evidence.

### 3.8 Historical Analogy Stacking

**Max:** 1 historical analogy per piece.

Three or more historical comparisons in one piece: "Like the printing press... Like the Industrial Revolution... Like electricity..."

**Fix:** Make the one analogy earn its place with specific parallels.

---

## Category 4: Content Sins

**Tolerance:** Zero instances. **Detection:** Editorial judgment. **Time:** Combined with Category 3.

These are deeper structural problems. They require rethinking sections, not rewriting sentences.

### 4.1 Fabricated Precision

Uncited metrics like "Companies see a 47% improvement" or "Teams report 3.2x faster production." No source, methodology, or sample size. This is the content version of hallucination.

**Fix:** Every number needs a source or an honest label. Unsupported claims become qualitative: "Teams that automate research consistently ship faster."

**Scholarslop warning:** for content that cites academic research, verify that the cited papers actually exist. AI-generated citations to nonexistent papers are a documented class of slop. If you cannot link to the original paper, do not cite it.

### 4.2 Stat Recycling

The same statistic appears three or four times with slightly different framing. AI anchors on a strong number and reuses it because it is the most relevant data in context.

- First use: the cited stat with source and full context.
- Later uses: a vivid image instead of repeating the number.

**Image bank (examples):** backlog problems become "debt spiral" or "triage paralysis"; trust erosion becomes "poisoned well" or "alert-fatigue doom loop"; manual work becomes "hamster wheel"; tool sprawl becomes "dashboard theater."

### 4.3 Section-Level Pitch-Slapping

An entire paragraph or section could be lifted directly into a sales deck. The problem framing sets up a product too perfectly.

**The sales-deck test:** copy the suspicious paragraph into a sales deck. If it fits without modification, rewrite it. Editorial content should analyze the problem without prescribing a specific solution category.

**Detection rules:**

- The paragraph focuses on what a product does, not on what the problem is.
- Language includes "market category failure," "paradigm shift," "fundamental limitation."
- It uses a company's exact category-positioning language.
- It ends with an implicit "you need [our solution category]" conclusion.

### 4.4 Signposted Conclusions

- "Despite its challenges, X remains..." / "While not without limitations..."
- "In conclusion..." / "To sum up..."

**Fix:** End with the strongest claim or the most interesting open question. No wrapping-up-the-essay language.

### 4.5 Listicle in a Trench Coat

Three or more consecutive one-sentence paragraphs masquerading as flowing prose: "The first... The second... The third..."

**Fix:** Vary paragraph length. Some short, some with two or three connected sentences building on each other.

### 4.6 One-Point Dilution

A single insight padded to article length by restating it in different words, adding examples that carry no new information, and elaborating on obvious implications.

**Fix:** If you have one point, write a short piece. Three tight paragraphs beat ten diluted ones.

### 4.7 Analogy Scarcity

If a powerful analogy appears twice, retire it after the first use.

- First: "AI agents operate at machine speed."
- Second: "Traditional processes can't keep pace with autonomous systems."
- Third: "Velocity mismatch between detection and response."

**Never:** the same metaphor repeated four or more times through a piece.

---

## Section 5: Outbound and Sales Copy — The Deadly Sins

These destroy outbound copy specifically. Adapted from Jordan Crawford's problem-validation-proposition methodology.

### 5.1 Empty Personalization

> "Congrats on your funding round!"
> "I saw you were hiring..."
> "Noticed you're in the [industry] space..."

**Why it fails:** it is not connected to a validated insight. It screams "template."

**The fix:** personalization must connect to a relevant insight about *their* situation, not a generic event.

### 5.2 The "About Us" Monologue

> "Hi, I'm [Name] from [Company]. We're a leading provider of..."

**Why it fails:** nobody cares about you until you prove relevance to them.

**The fix:** open with value for them. Earn the right to introduce yourself.

### 5.3 Feature Vomit

> "Our platform includes automated scanning, real-time alerts, integration with 40+ tools, customizable dashboards, and AI-powered analysis..."

**Why it fails:** features without context are noise. There is no connection to their pain.

**The fix:** one benefit that matters to them, with proof.

### 5.4 Robot-Speak

> "I hope this email finds you well."
> "I would like to inquire about..."
> "Per my previous correspondence..."
> "At your earliest convenience..."

**Why it fails:** it triggers instant "sales email" detection. It feels automated.

**The fix:** write like a human. Short sentences. Natural language.

### 5.5 Premature Calendar Grabs

> "Can I get 30 minutes on your calendar?"
> "Would you be open to a quick call?"
> "Let me know when you're free to chat."

**Why it fails:** you have not earned the right to ask for their time.

**The fix:** earn engagement first with a softer ask — "Curious if this resonates?" / "Want the full analysis?" / "Worth exploring?"

### 5.6 Contextless Name-Dropping

> "We work with Google, Microsoft, and Amazon."
> "Trusted by Fortune 500 companies."

**Why it fails:** without explaining relevance to them, it is just bragging.

**The fix:** connect social proof to their situation. "Teams like [a similar company in their space] used this to..."

### 5.7 Generic Check-Ins

> "Just checking in..."
> "Following up on my previous email..."
> "Wanted to circle back..."

**Why it fails:** it adds zero new value. Just noise.

**The fix:** each touchpoint delivers fresh insight or value.

---

## Section 6: Conversion Copy Auto-Fail Conditions

These flaws cap your copy at a maximum score. Fix them before anything else.

### 6.1 Zero Specificity

**Score cap:** max 6.5 if no specific numbers are present.

Vague claims with no numbers or evidence: "Significantly faster," "Dramatically improved results," "Many customers see great outcomes."

**The fix:** add specific numbers, percentages, timeframes. "71% faster." "From 8 hours to 40 minutes." "347 customers in the past quarter."

### 6.2 All Features, No Benefits

**Score cap:** max 6.0 if benefit translation is missing.

Describing what it *is* instead of what it *does* for them: "AI-powered automation platform," "Real-time analytics dashboard," "Cloud-native architecture with microservices."

**The fix:** translate every feature to an outcome. "Stop spending 8 hours on manual review." "See problems before your customers do." "Works from day one, scales as you grow."

### 6.3 Missing Clear CTA

**Score cap:** max 6.5 if the CTA is unclear or missing.

"Feel free to reach out if interested," "Learn more on our website," or no CTA at all.

**The fix:** a single, clear, low-friction action. "Reply 'yes' and I'll send the analysis." "Book 15 minutes: [link]."

### 6.4 Vendor-Language Dominance

**Score cap:** max 6.5 if jargon-heavy.

Words they would never use themselves: "Optimize operational efficiency," "Enable seamless collaboration," "Transform your digital landscape."

**The fix:** use their actual vocabulary. "Get more done with less hassle." "Work together without the email chaos."

### 6.5 Generic, Interchangeable Copy

**Score cap:** max 6.0 (differentiation below 4 is a poison pill).

Copy that could be any competitor's: "We help companies grow," "Best-in-class solutions," "Your trusted partner."

**The fix:** be specific to your differentiation. "The only platform that auto-generates fix PRs." "Built by practitioners, not consultants."

### 6.6 Premature Sell

**Score cap:** kills response rates completely.

Pitching before establishing relevance: opening with a company description, leading with features, asking for a meeting before providing value.

**The fix:** value first, pitch second. Lead with an insight about them. Establish relevance before asking. Earn the right to sell.

---

## Section 7: AI Composition Tropes

Subtler than the patterns in Categories 1 and 2, but equally damaging to credibility. Several overlap with Category 1 and 3 patterns; they are grouped here as a cross-cutting check specifically for AI-generated composition habits.

### 7.1 Invented Concept Labels

See 3.6. Ad-hoc compound terms presented as established concepts.

> "The supervision paradox means that..." / "What I call the acceleration trap..."

### 7.2 False Vulnerability

See 3.5. Announcing vulnerability instead of showing it.

> "I'll be honest..." / "If I'm being transparent..."

### 7.3 Magic Adverbs

See 1.5. Adverbs doing the heavy lifting instead of the verb.

> "quietly reshaping" / "fundamentally changing" / "increasingly important" / "deeply relevant"

### 7.4 Vague Attributions

See 1.7. Phantom sources that sound authoritative but say nothing.

> "Experts agree..." / "Research shows..." / "Industry leaders believe..."

### 7.5 "Serves As" and Avoidance Verbs

See 1.6. Pompous alternatives to direct verbs.

> "This serves as a reminder..." / "The platform acts as a bridge..."

### AI Composition Tropes Checklist

- [ ] Zero invented concept labels (unless attributed to a named source)
- [ ] Zero false-vulnerability announcements
- [ ] Zero magic adverbs (quietly, fundamentally, increasingly, remarkably, arguably)
- [ ] Zero vague attributions (experts say, research shows, studies suggest)
- [ ] Zero "serves as" / "acts as" / "functions as" constructions

---

## Newsletter-Specific Patterns

These apply to newsletter content in addition to the categories above.

**N1. Labeled "So What?" Sections (max: 0).** Fold the insight into the final one or two sentences of the section, naturally.

**N2. Repeated Hyperlinks to the Same URL (max: 1 per section).** One source-citation link in the header area. Remove the duplicate inline links.

**N3. Internal Cross-References and Inside Baseball (max: 0).** "More on that in section 3" — each section should stand alone.

**N4. Duplicate Contrarian Section (max: 0).** If a contrarian take covers the same topic as a main section, fold it into that section as a turn.

**N5. First-Person Over Third-Person.**

- Bad: "This is a buying-motion design challenge, not a headcount challenge."
- Good: "I've bought software for a decade. I fall in the 67% myself."

**N6. Conversational Hedging Over Declarative Certainty.**

- Bad: "AI is a multiplier, not a transformer."
- Good: "Basically, AI is a multiplier, not a transformer — to be simplistic about it."

---

## Earned Technique vs AI Pattern

Every device in this taxonomy (the fragment, the em-dash, the metaphor, the one-line closer) can be either voice or slop. The same sentence shape reads as craft in one draft and as a tell in another. The difference is not the device. It is whether the device is load-bearing.

An earned technique carries information or changes the reader's understanding. A fragment that lands a specific, surprising particular is earned. A fragment that only signals "this is important" is a tell. An em-dash that holds a genuine aside is earned; an em-dash that manufactures a dramatic pause is a tell. A metaphor that makes an abstract mechanism concrete is earned; the same metaphor on its fourth appearance is a tell.

Two tests separate them:

- **The information test.** Remove the device. If the sentence loses meaning, it was load-bearing — keep it. If it only loses drama, cut it.
- **The frequency test.** One earned fragment per piece is voice; a habit of them is a tic. The tell is rarely a single instance; it is the pattern.

This is why the counts in Category 2 are budgets, not bans. Zero em-dashes is not the goal; performed em-dashes are. Judge each device by what it does, not by what it is.

---

## A Representative Banned-Word List

This is a short, illustrative set, not an exhaustive lookup table. The point is to recognize the *class* of word, then extend the list with the tells specific to your own drafts. Tiered by severity.

**Tier 1 — always kill (any content type):** synergy, ecosystem, leverage (as a verb), holistic, robust, streamline, cutting-edge, best-in-class, thought leader, paradigm, disruptive, revolutionary, game-changing, transformative, unprecedented, world-class, delve, tapestry, landscape (as metaphor). Also kill the abstract-framing labels ("paradox," "collision," "dichotomy") and the superficial -ing words ("reshaping," "reimagining," "redefining," "revolutionizing").

**Tier 2 — kill in short-form, social, and outbound:** utilize, facilitate, methodology, strategize, incentivize, proactive, deliverable, learnings, touchpoint, journey (as marketing), pivot (as buzzword), bandwidth (non-technical), align (as corporate verb), harness, unpack. Also kill the avoidance verbs ("serves as," "acts as," "functions as," "stands as").

**Tier 3 — flag in long-form (may be acceptable with context):** furthermore, moreover, additionally, consequently, nevertheless, henceforth, aforementioned. These are not auto-kill in long-form, but flag them. If you need the transition, the logic between paragraphs is probably weak. Fix the logic instead.

---

## The 3-Tier Pre-Publish Workflow

### Tier 1: Automated Search (2-3 minutes)

Search-and-replace for Category 1 (banned phrases). If any match, delete or rewrite on the spot.

- [ ] Filler openers: zero
- [ ] Abstract framing words: zero
- [ ] Generic enthusiasm: zero
- [ ] Formal transitions: zero
- [ ] Magic adverbs: zero
- [ ] Avoidance verbs: zero
- [ ] Vague attributions: zero
- [ ] Superficial -ing words: zero
- [ ] Tier 1 banned words: zero

### Tier 2: Visual Scan (3-4 minutes)

Read for shape, not content. Count the structural patterns.

- [ ] **Combined dramatic-pause budget (§2.0): em-dashes + colon-sentences + dramatic fragments ≈1 per 150 words, one shared pool**
- [ ] Em-dashes: ≤2 per article (inside the §2.0 pool)
- [ ] Colon-sentences: ≤3 per article (inside the §2.0 pool)
- [ ] Tricolons: ≤2 per piece
- [ ] Aphorism endings: zero
- [ ] Colon lists: converted to bullets
- [ ] False drama, artificial revelation, meta-commentary: zero
- [ ] "Not X. Not Y. Just Z." escalation: zero
- [ ] Monotonous sentence length: no runs of 3+ similar-length sentences
- [ ] **Cadence tells (§2.14): no fragment-for-drama habit, no self-narrating meta-sentences, no reveal scaffolding, no per-section staccato closers**
- [ ] Summary paragraphs: zero

### Tier 3: Judgment Read (3-4 minutes)

Read with the question: "Would my most skeptical reader trust this paragraph?"

- [ ] Guru language: zero
- [ ] Hustle culture: zero
- [ ] Consulting-speak: zero
- [ ] Passive authority without citations: zero
- [ ] False vulnerability: zero
- [ ] Invented concept labels: zero (or attributed)
- [ ] Fabricated precision: zero (every number sourced)
- [ ] Stat recycling: later uses replaced with images
- [ ] Pitch-slapping: no paragraphs that fit in a sales deck
- [ ] One-point dilution: the piece earns its length
- [ ] Scholarslop: all cited papers verified to exist
- [ ] AI composition tropes: clean (see Section 7 checklist)

### Conversion and Outbound Add-On (if applicable)

Run after Tier 3 for any outbound sequence, sales email, or conversion copy.

- [ ] Auto-fail check: all six conditions passed (Section 6)
- [ ] Deadly-sins check: all seven absent (Section 5)
- [ ] Opens with them, not you
- [ ] Personalization connected to insight
- [ ] No feature vomit
- [ ] Human language, not robot-speak
- [ ] The ask matches the engagement earned
- [ ] Social proof has context
- [ ] Single clear CTA
- [ ] Contains specific numbers, not "significant" or "substantial"
- [ ] Benefits stated, not just features
- [ ] Uses language they would actually use
- [ ] Distinct from competitor copy

---

## The Ultimate Test

**Read it aloud.** Does it sound like a person talking? Would you send this to a smart friend?

If it sounds like marketing, rewrite it.
