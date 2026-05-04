# niches.md — Niche Playbooks

Every niche has its own set of myths, its own sacred cows, its own forbidden truths.
This file gives you the exact rules for each one.

---

## AI / DEVELOPER / TECH

### What everyone repeats (never say this):
- "AI is changing everything"
- "This model is incredibly powerful"
- "The future of [X] is AI"

### What creates real tension in this niche:
- Specific failure modes (when does the model/tool actually break?)
- Version regression (when did an update make things worse?)
- What the docs don't tell you (the thing you only find out from the issue tracker)
- The abstraction cost (what do you lose by using the high-level API instead of building lower?)
- Benchmark vs. real performance (MMLU scores vs. what happens in your actual prod environment)

### Required in every AI/tech carousel:
- At least one real failure mode with conditions
- At least one comparison ("GPT handles this by X. Claude handles it by Y. Here's where each breaks.")
- At least one thing that contradicts the marketing

### Forbidden phrases:
- "state-of-the-art"
- "cutting-edge"
- "revolutionary"
- "game-changing"

### Preferred language:
- Specific version numbers
- Latency figures
- Token costs
- GitHub repo names, not product names when possible
- "In production" or "at scale" as qualifiers

### Gold mine sources:
- GitHub issue trackers (where real failure modes are documented)
- CHANGELOG files (where regressions are buried)
- Twitter/X threads from staff engineers building on top of these models
- `lm-evaluation-harness` results, not company benchmarks

---

## BUSINESS / FOUNDERS / STARTUPS

### What everyone repeats (never say this):
- "Product-market fit is everything"
- "Focus on the customer"
- "Move fast and break things"
- "Culture eats strategy"

### What creates real tension in this niche:
- Stage-specificity (advice that works at seed that kills you at Series A)
- Survivor bias (the strategies you hear about are from winners — what did losers do that looked identical?)
- The advice that worked once, in one context, that people universalize
- What the "conventional wisdom" costs you if you follow it exactly

### Required in every business carousel:
- A stage qualifier (at what company size / funding stage / market condition does this apply?)
- A failure mode (when does this advice break?)
- One concrete example — a named company, not "a startup I know"

### Forbidden phrases:
- "authentic leadership"
- "servant leadership"
- "just ship it"
- "trust your gut"
- "the best founders..."

### The tension that always works in this niche:
The thing that sounds like good advice but contains a hidden assumption that fails at scale.
> "Hire slowly, fire quickly" — works when you have time. Kills you when you're racing a competitor to market.

---

## CREATOR / CONTENT / MARKETING

### What everyone repeats (never say this):
- "Value first"
- "Be authentic"
- "Consistency is key"
- "Know your audience"

### What creates real tension in this niche:
- Platform-specific data that contradicts general advice
- The thing that works at 1k followers that stops working at 100k
- Engagement that doesn't convert vs. engagement that does
- The difference between what creators say works and what their analytics actually show

### Required in every creator carousel:
- Platform qualifier (what works on LinkedIn fails on Instagram — always specify)
- Time-range qualifier (the algorithm changes; when was this true?)
- At least one number that contradicts expectation

### Forbidden phrases:
- "the algorithm loves this"
- "blow up your account"
- "go viral"
- "this one trick"

### The most dangerous creator advice to perpetuate:
"Post daily" — without specifying: daily what? Daily filler? Daily reposts?
The quantity-before-quality trap has destroyed more accounts than any algorithm change.

### What actually creates tension in this niche:
> The carousel that performs worst on the day you post is often the one that compounds the most over 90 days. Virality and compounding are different games. Most creators play the wrong one.

---

## FINANCE / INVESTING

### What everyone repeats (never say this):
- "Time in the market beats timing the market"
- "Diversification reduces risk"
- "Buy what you know"
- "Think long term"

### What creates real tension in this niche:
- The conditions under which conventional wisdom fails
- Risk metrics that sound safe but aren't (volatility ≠ risk for a long-horizon investor)
- The specific historical case that breaks the rule
- Tax implications that wipe out the strategy advantage

### Required in every finance carousel:
- Time horizon (this changes everything — never give financial insight without it)
- Risk profile qualifier
- At least one historical counterexample
- The assumption the advice rests on — stated explicitly

### Absolute rules for this niche:
- Never state or imply a specific return
- Never give advice that could be read as "do this" — always frame as "here's the mechanism / here's the decision framework"
- Always note what conditions the insight requires

### The tension that always works:
The strategy that sounds conservative but contains hidden risk.
The strategy that sounds aggressive but contains hidden stability.
The difference between what the metric measures and what you actually need to know.

---

## HEALTH / WELLNESS / PERFORMANCE

### What everyone repeats (never say this):
- "Sleep is the most important thing"
- "You are what you eat"
- "Listen to your body"
- "Stress is bad for you"

### What creates real tension in this niche:
- The dose-response relationship (almost everything in health is a U-curve, not a linear line)
- The difference between population-level advice and individual-level application
- What the study actually showed vs. how it was reported
- The intervention that helps one biomarker while harming another

### Required in every health carousel:
- Population qualifier (this was studied in X — may not apply to Y)
- Effect size (statistical significance ≠ meaningful effect)
- Duration qualifier (works acutely / chronically / in a specific window)

### The permanent gold seam in this niche:
Things that are good in doses and harmful in excess — and most people are taking them in excess.
Recovery, sunlight, social connection, caloric restriction. All U-curves.

---

## PHILOSOPHY / IDEAS / THINKING

### What everyone repeats (never say this):
- "Think outside the box"
- "Question everything"
- "First principles thinking"
- "The map is not the territory"

### What creates real tension in this niche:
- The idea that sounds profound but is actually circular
- The philosophy that works as an individual practice but breaks as a social policy
- The thinker who was right for the wrong reasons
- The framework that solves one class of problems by creating a different one

### Required in every philosophy carousel:
- The specific context where the idea originated (most ideas travel badly)
- What the idea costs — every mental model has a shadow
- At least one case where applying the idea leads to a bad outcome

### What makes this niche uniquely hard:
Ideas can sound true without being useful. They can be useful without being true.
The best philosophy carousel gives you a thinking tool — not a true fact, not a motivational line. A tool.

### The permanent gold seam here:
Widely celebrated ideas that contradict each other, both with strong evidence.
> "Opposites attract" vs. "Birds of a feather flock together."
Both are supported by research. Both are used as common wisdom. Most people have never asked: under what conditions does each one apply?
