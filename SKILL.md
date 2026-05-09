---
name: anchoring-map-evaluator
description: Evaluate a thesis Introduction and Background draft against the Anchoring Map rubric: 5 anchors (Empirical, Literature, Assumption, Scope, Contribution), 5 funnel stages (Hook, Conversation, Problematization, Research Question, Promise and Map), and a 12-point pre-submission audit. TRIGGER when the user pastes a thesis intro or chapter-1 draft, links a markdown or PDF intro file, or asks to score, audit, evaluate, or check anchoring on a thesis introduction. SKIP when the request is for a full thesis review, a methodology or findings chapter, a journal-article intro outside the thesis context, or non-academic writing. Synthesised from Grant and Pollock (2011), Sandberg and Alvesson (2010), Agee (2009), Shepherd and Wiklund (2020).
---

# Anchoring Map Evaluator

You are evaluating a thesis **Introduction and Background** draft against the Anchoring Map. The map's premise: an intro is not a list of sections; it is a **chain of anchored claims**. Every move (hook, conversation, problem, RQ, contribution) must be tethered to something a reader can verify.

Reference: https://mcmespinaa.github.io/thesis-anchoring-map/

## Before You Start

- **Valid input.** A thesis Introduction, Chapter 1, or Background section. Accept markdown, plain text, PDF, or pasted text.
- **Missing input.** If no draft has been provided, ask once: "Paste the draft, or give me a file path or URL." Do not score until you have it.
- **Wrong chapter.** If the input looks like a methodology, findings, or discussion chapter, stop and say so. The rubric is calibrated for the introduction stage of the funnel, not the rest of the thesis.
- **Non-thesis intro.** If the input is a journal article intro, blog post, or other non-thesis writing, proceed but flag in the output that audit items 8 and 10 (discussion-section traceability and length budget) may not apply.
- **Length budget.** The default operative target is **1800 to 2000 words** for the Introduction and Background. If the user's programme has a different target, ask once at the start and adjust audit item #10 accordingly.
- **Anti-fabrication.** Do not invent quotes, scores, or anchors. If the draft lacks evidence for an anchor, the verdict is "no evidence found" and the score is 0.

## How to run

1. Read the full draft once before scoring. Do not start scoring after reading only the opening.
2. Count words mechanically (exclude headings, captions, references). Note the count for audit item #10.
3. Produce the output in the five sections below, in order. Quote short fragments (≤10 words) from the draft to ground each judgment.
4. End with a prioritised fix list (max 5 items, ordered by impact). Do not append a summary after it.

## The Five Anchors (every paragraph must tie to ≥1)

- **A · Empirical.** A named phenomenon, dataset, headline, vignette, or shift in the world. Anchors the hook.
- **B · Literature.** A bounded, named conversation; ≥2 streams identifiable by author and construct. Anchors the field-establishing move.
- **C · Assumption.** An articulated belief held by that literature, which the thesis will support, refine, or challenge. *The deepest anchor; missing in most intros.*
- **D · Scope.** Boundary conditions: setting, unit of analysis, time frame, population. States what the thesis is *not* claiming.
- **E · Contribution.** The *specific* way the thesis will change, challenge, or advance the conversation. Stated in intro, delivered in discussion.

## The Five-Stage Funnel

1. **Hook.** Why should anyone keep reading? (Pasteur's quadrant: useful AND theoretically rich.)
2. **Conversation.** What conversation are you joining? (≥2 named streams, related to each other.)
3. **Problematization.** What is wrong, missing, or contested? (Prefer problematization over gap-spotting.)
4. **Research Question.** Anchored, scoped, answerable with the data the author can access.
5. **Promise and Map.** What will we learn, how does the rest unfold; calibrated, not overpromised.

## Output format

### 1. Anchor Scorecard

For each of A to E, score **0 / 1 / 2** (missing / weak / strong) with a one-line justification quoting the draft. Total /10.

| Anchor | Score | Evidence (quoted) | Verdict |
|---|---|---|---|
| A · Empirical | | | |
| B · Literature | | | |
| C · Assumption | | | |
| D · Scope | | | |
| E · Contribution | | | |

**Anchor total: X/10**

### 2. Funnel Stage Review

For each of the 5 stages, give a one-paragraph diagnosis:
- **What's working** (1 sentence).
- **What's missing or weak** (1 to 2 sentences with quoted evidence).
- **Anchor letter(s) tied to this stage** (or "FLOATING: no anchor found").

### 3. Pitfall Scan (Grant and Pollock)

Flag presence/absence of the three reviewer pitfalls:
- **Failing to motivate and problematize** (60% of rejections): does the draft argue *why filling it matters*, or assume importance?
- **Lack of focus** (45%): too many frameworks, rambling, describing structure instead of defining problem?
- **Overpromising** (14%): does the contribution promise exceed what the thesis can deliver?

For each: ⚠️ PRESENT / ⚪ ABSENT / 🟡 PARTIAL, with one-line evidence.

### 4. The Twelve-Point Audit

Walk the draft against all 12 checks. Mark each ✅ / ⚠️ / ❌ with a brief note.

1. Hook anchored to A or B (not a generic importance claim).
2. The "who cares" answer fits in one sentence.
3. Names ≥2 literature streams and how they relate.
4. Articulates ≥1 assumption to support, refine, or challenge.
5. Word "gap" appears ≤1 time, never as sole motivation (prefer *problem · puzzle · paradox*).
6. RQ answerable with accessible data.
7. Scope explicit: setting, period, unit of analysis, exclusions.
8. Contribution promise specific and traceable to a discussion section.
9. No first-mover claims ("never been done before").
10. Length budget honoured: the draft falls within **1800 to 2000 words**. Report the actual word count. Mark ❌ if outside, ⚠️ if within 5% of either bound, ✅ if comfortably inside.
11. Intro reads as a stand-alone mini-summary (peer test).
12. Rewritten ≥5 times (award-winners average 10); note whether the draft feels like a rough cut.

### 5. Top 5 Fixes (prioritised)

Numbered list. Each item: **[anchor letter]** what to change, in 1 to 2 sentences. Order by impact, not by appearance order in the draft.

## Example output (truncated)

```
### 1. Anchor Scorecard

| Anchor | Score | Evidence (quoted) | Verdict |
|---|---|---|---|
| A · Empirical | 2 | "post-2020 surge in solo-founder SaaS exits" | Named, dated, specific. |
| B · Literature | 1 | "scholars debate whether bootstrapping…" | One stream named; second stream implied, not cited. |
| C · Assumption | 0 | no evidence found | No literature belief is named, supported, or challenged. |
| D · Scope | 1 | "Swedish SaaS founders, 2018 to 2024" | Setting and period given; unit of analysis missing. |
| E · Contribution | 1 | "this study extends the resource-based view" | Direction stated; mechanism vague. |

**Anchor total: 5/10**

### 3. Pitfall Scan

- ⚠️ PRESENT. Failing to motivate and problematize: opening assumes importance ("solo-founders matter") without arguing why filling this matters now.
- ⚪ ABSENT. Lack of focus: tight 4-paragraph build-up, single frame.
- 🟡 PARTIAL. Overpromising: "novel theoretical contribution" claimed; mechanism not specified.

### 4. The Twelve-Point Audit (excerpt)

10. ❌ Length budget: actual count 2,318 words; ~16% over the 2000 upper bound. Cut the second-paragraph history detour.

### 5. Top 5 Fixes

1. **[C]** Name one belief held by the bootstrapping literature you intend to challenge or refine. Without an articulated assumption, the contribution lands as gap-spotting.
2. **[A]** Replace the abstract opening with a 2-sentence vignette grounded in the post-2020 exits dataset you already mention later.
…
```

## Common pitfalls (anti-drift rules)

- **Quote, do not paraphrase.** Each evidence cell quotes a fragment of ≤10 words from the draft, in quotation marks. If you cannot find a quote, the score is 0 and the evidence reads "no evidence found."
- **Do not pad scores.** A draft missing anchor C (assumption) gets 0 on C. Compensating ("but the literature is strong, so let us call it a 1") is forbidden.
- **Do not score on length.** A short, sharp intro can max the rubric. A long, rambling intro can score low on every line. Word count drives audit item #10 only, not the anchor scorecard.
- **Do not conflate gap-spotting with assumption-naming.** "X is understudied" is anchor B framing, not anchor C. Anchor C requires naming a *belief* held by the literature.
- **No first-mover claims in feedback either.** Do not write "you are the first to" or "no one else has." That is the same pitfall the rubric flags in drafts.
- **Use the anchor letters (A to E) consistently** so fixes map back to the published map.
- **End with the prioritised fix list, not a summary.** The 5-fix list is the deliverable; do not append a paragraph above or below it.

## References (consult on demand)

The rubric in this SKILL.md is a faithful synthesis. Do not read these sources on a normal evaluation. Consult one only when the user asks "why is this rule here?", "show me where Sandberg says that," or wants the original phrasing. When you do, quote ≤25 words and cite the source with its short tag (e.g., "Grant and Pollock 2011, p.875").

Local source folder: `/Users/MC/Obsidian/salsu-resources-docs/Master-Thesis-VT26/Thesis Intro/`

| Source | Grounds | File (in source folder above) |
|---|---|---|
| Grant and Pollock (2011) | Funnel stages, 3 reviewer pitfalls, 10× rewrites stat | `Grant & Pollock (2011) Publishing in AMJ- part 3 - Setting the hook.pdf` |
| Sandberg and Alvesson (2010) | Gap-spotting vs problematization (anchor C) | `Sandberg & Alvesson (2010) Ways of constructing research questions - gap-spotting or problematization.pdf` |
| Agee (2009) | RQ refinement cycle, anchor D scope | `Agee (2009) Developing qualitative research questions  a reflective process.pdf` |
| Shepherd and Wiklund (2020) | Heuristics, "anchor every paragraph" rule | `Shepherd & Wiklund (2020) Simple rules templates and heuristics - An attempt to deconstruct the craft of writing - ET&P.pdf` |
| Course Lecture 2 | Operational checklist, 5-stage funnel framing | `The reserach process - practical persepctives lecture 2.pdf` |
