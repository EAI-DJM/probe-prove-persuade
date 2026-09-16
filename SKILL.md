---
name: probe-prove-persuade
description: >-
  Probe-Prove-Persuade: a scientific narrative polishing skill based on Randy
  Olson's "Houston, We Have a Narrative". Probes the Narrative Spectrum to
  diagnose AAA vs ABT structures, Proves arguments through the WSP model
  (Dobzhansky Template, ABT, Story Spine), and Persuades readers with
  restructured scientific writing. Use when user wants to polish, revise, or
  improve scientific papers, academic abstracts, research proposals, thesis
  introductions, discussion sections, or any scholarly text to enhance narrative
  clarity, logical flow, and reader engagement. Triggers: polish my paper, revise
  my abstract, improve scientific writing, ABT, narrative structure, scientific
  storytelling, 润色论文, 润色摘要, 科学写作, 科研写作, 叙事结构, 学术润色.
---

# Probe-Prove-Persuade

**Probe · Prove · Persuade** — a science text polishing skill built on Randy
Olson's *Houston, We Have a Narrative: Why Science Needs Story*. The core
thesis: **science is a narrative process, and narrative is storytelling --
therefore science needs story**.

The name captures the three-stage workflow:
- **Probe** — diagnose the text's narrative health (AAA vs ABT)
- **Prove** — restructure arguments with WSP model tools
- **Persuade** — deliver polished text that convinces the reader

## Quick Start

```
User: "Help me polish this abstract:"
> "We studied X. We measured Y. We found Z. We conclude W."

Assistant applies ABT:
> "X is widely studied AND Y has been measured, BUT Z was unexpected,
> THEREFORE we conclude W."
```

## Core Philosophy

1. **Shape first, style later** -- Narrative structure (the "essence") must
   precede stylistic elements (humor, metaphor, tone). IMRAD already forces
   scientists to shape information; this skill makes that shaping conscious.
2. **Replace AAA with ABT** -- Most scientific writing suffers from the
   "And-And-And" (AAA) pattern: a flat sequence of facts with no tension or
   resolution. ABT (And-But-Therefore) injects conflict and consequence.
3. **Match tool to IMRAD section** -- Different parts of a paper need different
   narrative tools (see Workflow below).
4. **Do not fear templates** -- Science communication's biggest problem is
   *lack* of narrative structure, not excess of it. Templates are starting
   points, not cages.

## The WSP Model

The skill operates across three layers, mirroring the WSP (Word, Sentence,
Paragraph) model:

| Layer | Tool | Scope | IMRAD Section |
|-------|------|-------|---------------|
| **W**ord | Dobzhansky Template | Theme / core message | All sections |
| **S**entence | ABT Template | Single-sentence logic | I & D (subjective) |
| **P**aragraph | Hero's Journey / Story Spine | Multi-paragraph arc | I & D (subjective) |

For Methods and Results (objective sections), focus on clarity and accuracy
rather than narrative transformation.

## Workflow

### Step 1: Diagnose -- Narrative Spectrum Assessment

Before polishing, classify the input text on the Narrative Spectrum:

- **AAA (And-And-And)**: Flat listing of facts. No tension, no direction.
  *Symptom*: reader cannot identify the research gap or why it matters.
- **ABT (And-But-Therefore)**: Has agreement, contradiction, and consequence.
  *Symptom*: reader immediately grasps the story.
- **Mixed / partial**: Some sections have ABT, others are AAA.

**Action**: Tag each paragraph as AAA, ABT, or mixed. Prioritize AAA
paragraphs for restructuring.

### Step 2: Anchor -- Dobzhansky Template (Word Layer)

Fill in the Dobzhansky Template to identify the single core theme:

```
"Nothing in [research domain] makes sense except in the light of [key concept]."
```

Chinese:
```
"如果不从 [关键概念] 的角度思考问题，[研究领域] 的一切都毫无道理。"
```

**Rules**:
- The first blank is the *perspective* (the "light").
- The second blank is the *subject domain*.
- If you cannot fill both blanks cleanly, the text lacks a unifying theme --
  fix this before any sentence-level work.
- This template reduces "purposeless information gathering" -- every paragraph
  should eventually serve the anchored theme.

### Step 3: Restructure -- ABT Template (Sentence Layer)

Transform key sentences (especially in abstracts, introductions, and
discussions) into ABT form:

```
[Agreement/facts], AND [more agreement/context],
BUT [contradiction/problem/gap],
THEREFORE [conclusion/action/finding].
```

Chinese:
```
______而且______，但是______，因此______。
```

**ABT vocabulary**:

| Function | English | Chinese |
|----------|---------|---------|
| Agreement | AND | 并且 / 而且 |
| Contradiction | BUT | 但是 / 然而 |
| Consequence | THEREFORE | 因此 / 所以 |

**Three ABT variants** (adapt to audience):

| Variant | Name | Length | Audience |
|---------|------|--------|----------|
| cABT | Concise | 1 short sentence | General public |
| kABT | Keeper (final product) | 2-4 sentences | Mixed / elevator pitch |
| iABT | In-depth | Full paragraph | Specialist peers |

**ABT construction process**:
1. List the facts you need to convey (the "And" material).
2. Identify the gap, problem, or unexpected result (the "But").
3. State what follows logically (the "Therefore").
4. If you cannot find a "But", the text is likely AAA -- dig deeper for the
   real tension or research gap.

**Self-check**: After rewriting, read the sentence aloud. If it sounds like a
flat list (no emotional shift at "But"), the ABT is weak -- strengthen the
contradiction.

### Step 4: Build Arc -- Hero's Journey / Story Spine (Paragraph Layer)

For multi-paragraph sections (introduction, discussion), use the Story Spine
template (developed by Dolly Barton):

```
In an ordinary world, [background context]...
A flawed protagonist [the research problem/question]...
Encountered a catastrophic event [the key challenge/gap]...
Which upended their world, but after assessment, [realization]...
The protagonist decided to act, [methodology/approach]...
But with raised stakes, [complication/difficulty]...
The protagonist had to learn a lesson, [insight/finding]...
To confront the antagonist, [resolution/analysis]...
And achieve the goal, [conclusion/contribution]...
```

Chinese:
```
在一个平凡的世界里，______
一位有缺陷的主角______
遇到灾难性的事件______
这件事颠覆了他/她的世界，但是在作出评估之后，______
主角决定采取行动，______
但是由于增加了风险______
主角必须学到教训______
为了对抗反派______
实现目标______
```

**Key principle** (from playwright Christopher Keane): *Good stories omit the
middle transitions and keep only the highest highs and lowest lows.* When
polishing, cut intermediate steps that do not serve the dramatic arc.

**Caveat**: The Hero's Journey is powerful but easily misused. Apply it to
*introductions and discussions* (where argument and persuasion live), not to
*methods and results* (where factual accuracy must dominate).

### Step 5: Verify -- Narrative Intuition Check

After polishing, perform a final read-through guided by "narrative intuition":

- **Does the text move?** The audience craves forward motion ("development
  narrative"), not repetition.
- **Is the "But" genuine?** It must reflect a real research gap or
  contradiction, not a manufactured one.
- **Does "Therefore" follow logically?** No over-reaching beyond what the data
  supports.
- **Can you tell it in an elevator?** If you cannot deliver the core ABT in
  under 30 seconds, the narrative is still too complex.

## IMRAD Section Guide

| IMRAD Section | Narrative Tool | Goal |
|---------------|----------------|------|
| **I**ntroduction | ABT + Story Spine | Establish gap, create tension, motivate study |
| **M**ethods | Minimal narrative; focus on clarity | Accurate, reproducible description |
| **R**esults | Minimal narrative; focus on clarity | Present findings without spin |
| **A**nd **D**iscussion | ABT + Dobzhansky | Interpret findings, connect back to theme |

## Anti-Patterns

1. **AAA listing**: "We did A. We did B. We did C. We found D."
   -> Fix: Identify the "But" -- what was unexpected? What gap existed?
2. **False ABT**: Manufacturing a conflict that does not exist in the data.
   -> Fix: If there is no real "But", the study may be descriptive -- that is
   fine, but do not force a narrative arc.
3. **Over-dramatization**: Turning a methods section into a thriller.
   -> Fix: Keep methods and results factual. Narrative tools are for I and D.
4. **Theme drift**: Each paragraph discusses a different topic with no unifying
   thread.
   -> Fix: Re-apply the Dobzhansky Template. Every paragraph must serve the
   anchored theme.
5. **Ignoring the audience**: Using the same ABT density for a public talk and
   a specialist paper.
   -> Fix: Choose cABT / kABT / iABT based on the target reader.

## Output Format

When polishing, provide:

1. **Diagnosis**: Tag each paragraph as AAA / ABT / mixed, with a one-line
   explanation.
2. **Dobzhansky anchor**: State the identified core theme.
3. **Polished text**: The revised version with ABT/Story Spine applied.
4. **Change log**: Key modifications and why (e.g., "Added 'But' clause to
   highlight research gap that was implicit in original").
5. **Narrative Spectrum score**: Rate the before/after on a simple scale
   (AAA-heavy -> ABT-balanced).

## Advanced Topics

For detailed templates, worked examples, case studies from the book, and
LaTeX-specific guidance, see:

- [REFERENCE.md](REFERENCE.md) -- Full methodology deep-dive
- [EXAMPLES.md](EXAMPLES.md) -- Before/after polishing examples
