# Thesis Anchoring Map

A field guide for thesis writers (VT26) on drafting the **Introduction & Background** with proper anchoring. Synthesised from Grant & Pollock (2011), Sandberg & Alvesson (2010), Agee (2009), and Shepherd & Wiklund (2020).

**Live page:** https://mcmespinaa.github.io/thesis-anchoring-map/

## What's here

| File | Purpose |
|---|---|
| [`index.html`](index.html) | The Anchoring Map — visual single-page reference covering the 5 anchors (A–E), the 5-stage funnel, gap-spotting vs problematization, reviewer pitfalls, the RQ refinement cycle, and a 12-point pre-submission audit. |
| [`evaluator-prompt.md`](evaluator-prompt.md) | Universal prompt — paste into any LLM (ChatGPT, Claude, Gemini), then paste your intro draft. Returns a scorecard, funnel review, pitfall scan, and prioritised fixes. |
| [`SKILL.md`](SKILL.md) | Claude Code skill — same evaluator, invoked natively in Claude Code as `anchoring-map-evaluator`. |

## Using the evaluator (universal)

1. Open [`evaluator-prompt.md`](evaluator-prompt.md) and copy everything below the horizontal rule.
2. Paste into ChatGPT, Claude, Gemini, or any LLM.
3. When prompted, paste your full Introduction & Background draft.
4. Receive: anchor scorecard (X/10), funnel stage diagnosis, pitfall scan, 12-point audit, top 5 prioritised fixes.

## Using the evaluator (Claude Code)

```bash
mkdir -p ~/.claude/skills/anchoring-map-evaluator
curl -o ~/.claude/skills/anchoring-map-evaluator/SKILL.md \
  https://raw.githubusercontent.com/mcmespinaa/thesis-anchoring-map/main/SKILL.md
```

Then in Claude Code: ask it to evaluate your thesis intro and it'll trigger the skill.

## The five anchors at a glance

- **A · Empirical** — named phenomenon, dataset, vignette
- **B · Literature** — bounded, named conversation (≥2 streams)
- **C · Assumption** — articulated belief to support/refine/challenge
- **D · Scope** — setting, period, unit, exclusions
- **E · Contribution** — specific advance, traceable to discussion

Every paragraph in the intro should tie to ≥1 anchor. Paragraphs without an anchor letter in the margin are floating — cut them or re-tether them.

## License

Content is a synthesis of cited academic sources for educational use. The HTML/markdown scaffolding is free to fork, adapt, and remix.
