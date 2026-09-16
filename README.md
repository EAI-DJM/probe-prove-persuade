# Probe-Prove-Persuade

> **Probe · Prove · Persuade** — a scientific narrative polishing skill based on Randy Olson's *Houston, We Have a Narrative*

[English](README.md) | [中文](README.zh-CN.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Language: EN/ZH](https://img.shields.io/badge/Language-EN%2FZH-blue.svg)](#)
[![Skill Type: AI Agent](https://img.shields.io/badge/Type-AI%20Agent%20Skill-purple.svg)](#)
[![Method: WSP Model](https://img.shields.io/badge/Method-WSP%20Model-teal.svg)](#)

Apply Hollywood narrative techniques systematically to scientific writing. Through the **WSP model** (Word-Sentence-Paragraph), restructure paper narratives at three levels — turning scientific writing from a "lab notebook" into "a compelling story".

**Why this name** — three alliterative P-verbs: a classic trio in science communication, and a faithful map of the skill's core workflow:

```
Probe     Diagnose the narrative spectrum, locate the AAA patterns
   │
   ▼
Prove     Restructure argument logic with WSP model tools
   │
   ▼
Persuade  Deliver polished text that convinces the reader
```

---

## Table of Contents

- [Background & Motivation](#background--motivation)
- [Core Methodology: The WSP Model](#core-methodology-the-wsp-model)
- [Three-Stage Workflow](#three-stage-workflow)
- [Installation & Usage](#installation--usage)
- [Examples](#examples)
- [IMRAD Section Guide](#imrad-section-guide)
- [Anti-Patterns & Common Mistakes](#anti-patterns--common-mistakes)
- [File Structure](#file-structure)
- [Acknowledgments & References](#acknowledgments--references)
- [License](#license)

---

## Background & Motivation

The biggest problem in scientific writing is not a lack of data, but a **lack of narrative structure**.

Most papers follow the **AAA pattern** (And-And-And): a flat sequence of facts with no tension, no direction, no turning point. Readers cannot identify the research gap, nor feel *why this research matters*.

Randy Olson — a cross-disciplinary scholar who moved from tenured marine biology professor to Hollywood filmmaker — argues in *Houston, We Have a Narrative: Why Science Needs Story*:

> **Science is a narrative process. Narrative is storytelling. Therefore, science needs story.**

This skill systematizes the book's core methodology into an actionable polishing tool.

### Intellectual Lineage

| Source | Contribution |
|--------|--------------|
| Aristotle | Three-act structure: beginning—middle—end |
| Hegel | Dialectics: thesis—antithesis—synthesis |
| Joseph Campbell | The Hero's Journey (monomyth) |
| Christopher Vogler | Adaptation of the Hero's Journey as a practical screenwriting tool |
| Theodosius Dobzhansky | "Nothing in biology makes sense except in the light of evolution" |
| Randy Olson | Formalized ABT template, WSP model, Narrative Spectrum |

---

## Core Methodology: The WSP Model

The WSP model operates at three levels; each level corresponds to one narrative tool:

```
WSP Model
  │
  ├── W (Word)        ──►  Dobzhansky Template     ──►  Theme anchoring
  │                                                       operates at word/phrase level
  │
  ├── S (Sentence)    ──►  ABT Template             ──►  Logic restructuring
  │                                                       operates at sentence level
  │
  └── P (Paragraph)   ──►  Hero's Journey /         ──►  Arc construction
                           Story Spine                    operates at multi-paragraph level
```

**Core principle**: the three layers must be applied in order. You cannot fix a sentence problem when the theme (word layer) is unclear; you cannot build a paragraph arc when sentences lack ABT structure.

### Layer 1: The Dobzhansky Template (Word layer — theme anchoring)

```
"Nothing in [research domain] makes sense except in the light of [key concept]."
```

**Purpose**: lock the core theme of the whole text, reduce aimless information piling, and ensure every paragraph serves the anchored theme.

### Layer 2: The ABT Template (Sentence layer — logic restructuring)

```
[Agreement/facts], AND [more context],
BUT [contradiction/problem/gap],
THEREFORE [conclusion/action].
```

**Three variants** to suit different audiences:

| Variant | Name | Length | Use cases |
|---------|------|--------|-----------|
| cABT | Concise | 1 short sentence | Elevator pitch, public talk, press release |
| kABT | Keeper | 2–4 sentences | Conference abstract, paper abstract, grant abstract |
| iABT | In-depth | Full paragraph | Introduction, detailed technical proposal |

### Layer 3: Story Spine / Hero's Journey (Paragraph layer — arc construction)

```
In an ordinary world, [background]...
A flawed protagonist [research problem]...
Encountered a catastrophic event [key challenge/gap]...
Which upended their world, but after assessment, [insight]...
The protagonist decided to act, [method]...
But with raised stakes, [difficulty]...
The protagonist had to learn a lesson, [finding]...
To confront the antagonist, [validation]...
And achieve the goal, [contribution]...
```

**The high-low principle** (Christopher Keane): good stories keep only the highest peak and the lowest valley — cut the useless transitions in between.

---

## Three-Stage Workflow

```
┌─────────────────────────────────────────────────────────┐
│                    Input: text to polish                  │
└─────────────────────────┬───────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────┐
│  PROBE: Diagnose — Narrative Spectrum assessment        │
│  Mark each paragraph AAA / ABT / mixed                  │
│  Fill in the Dobzhansky template to anchor the theme    │
└─────────────────────────┬───────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────┐
│  PROVE: Argue — WSP model restructuring                 │
│  Word layer:      Dobzhansky template checks theme      │
│  Sentence layer:  ABT template rebuilds sentence logic  │
│  Paragraph layer: Story Spine builds a narrative arc    │
└─────────────────────────┬───────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────┐
│  PERSUADE: Convince — verification & delivery           │
│  Read-aloud test, elevator test, "But" truth check      │
│  Output polished text + diagnosis report + change log   │
└─────────────────────────┬───────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────┐
│                  Output: polished text                   │
└─────────────────────────────────────────────────────────┘
```

---

## Installation & Usage

### As an AI Agent Skill

Copy `SKILL.md`, `REFERENCE.md`, and `EXAMPLES.md` from this repository into your AI agent's skill directory. For a DuMate / OpenCode-style agent:

```bash
cp SKILL.md REFERENCE.md EXAMPLES.md /path/to/skills/user/probe-prove-persuade/
```

After installation, describe your polishing need in conversation to trigger the skill:

```
User: Polish this abstract for me
User: Check the narrative structure of this introduction
User: Restructure this discussion with the ABT template
User: Is this paragraph AAA-structured?
User: Write a cABT elevator pitch for me
User: Anchor the paper's theme with the Dobzhansky template
```

### As Standalone Reference Documents

Even without an AI agent, these files constitute a complete manual of narrative-writing methodology:

| File | Content | Purpose |
|------|---------|---------|
| [SKILL.md](SKILL.md) | Main instruction: three-stage workflow + WSP overview | Quick workflow lookup |
| [REFERENCE.md](REFERENCE.md) | Methodology in depth: the book's 11-chapter theoretical system | Deep theoretical background |
| [EXAMPLES.md](EXAMPLES.md) | 8 before/after polishing comparisons + quick reference | Hands-on practice |

---

## Examples

### Before polishing (AAA — flat statement)

> We study multi-energy systems. We model electricity, heat, and gas networks. We use reinforcement learning. We train agents with PPO. We evaluate on benchmark datasets. We compare with baseline methods. We achieve 15% cost reduction. We conclude that our method is effective.

**Diagnosis**: severe AAA. No research gap, no tension, no "But". Readers cannot tell why this work matters.

### After polishing (ABT — tension and resolution)

> Multi-energy systems integrate electricity, heat, and gas networks, **AND** reinforcement learning has shown promise for their coordinated optimization. **BUT** existing approaches assume homogeneous agent capabilities, failing to capture the structural heterogeneity of real-world energy components. **THEREFORE**, we propose a heterogeneous graph reinforcement learning framework that explicitly models component diversity, achieving 15% cost reduction over state-of-the-art baselines.

> More examples: see [EXAMPLES.md](EXAMPLES.md).

---

## IMRAD Section Guide

| IMRAD Section | Narrative Tool | Goal |
|---------------|----------------|------|
| **I**ntroduction | ABT + Story Spine + Dobzhansky | Establish the gap, build tension, motivate the research |
| **M**ethods | Minimal narrative; focus on clarity | Accurate, reproducible description |
| **R**esults | Minimal narrative; focus on clarity | Present findings without embellishment |
| **A**nd **D**iscussion | ABT + Dobzhansky | Interpret findings, tie back to the theme |

---

## Anti-Patterns & Common Mistakes

| Anti-pattern | Symptom | Fix |
|--------------|---------|-----|
| **AAA listing** | "We did A. We did B. We did C. We found D." | Find the "But" — what is surprising? What gap exists? |
| **Fake ABT** | Fabricating a conflict that does not exist in the data | If there is no real "But", the research may be descriptive — do not force a narrative arc |
| **Over-dramatizing** | Writing the Methods section like a thriller | Keep Methods/Results factual; use narrative tools only for I and D |
| **Theme drift** | Every paragraph discusses a different topic with no unifying thread | Reapply the Dobzhansky template; every paragraph must serve the anchored theme |
| **Ignoring the audience** | Using the same ABT density for public talks and expert papers | Choose cABT / kABT / iABT according to the audience |

---

## File Structure

```
probe-prove-persuade/
├── README.md              # This file — project homepage (English)
├── README.zh-CN.md        # 中文项目主页 (Chinese version)
├── LICENSE                # MIT license
├── .gitignore             # Git ignore rules
├── CONTRIBUTING.md        # Contribution guide (English)
├── CONTRIBUTING.zh-CN.md  # 中文贡献指南 (Chinese version)
├── SKILL.md               # Main instruction: three-stage workflow + WSP overview
├── REFERENCE.md           # Methodology in depth: the book's 11-chapter theoretical system
└── EXAMPLES.md            # 8 before/after polishing comparisons + quick reference
```

---

## Acknowledgments & References

### Original book

```
Olson, Randy. Houston, We Have a Narrative: Why Science Needs Story.
Chicago: University of Chicago Press, 2015. ISBN: 978-0-226-27098-6
```

### Chinese translation

```
兰迪·奥尔森. 科学需要讲故事. 高爽 译. 重庆: 重庆大学出版社, 2018.
ISBN: 978-7-5689-0920-4
```

### Core theoretical sources

- **Dobzhansky template**: from the title of Theodosius Dobzhansky's classic 1973 paper
- **ABT template**: formalized by Olson in 2011; roots trace back to Aristotle's three-act structure and Hegel's dialectics
- **Story Spine**: developed by Dolly Barton (a collaborator of Olson's workshops)
- **Hero's Journey**: Joseph Campbell, *The Hero with a Thousand Faces* (1949), adapted as a screenwriting tool by Christopher Vogler

---

## License

This project is open-sourced under the [MIT License](LICENSE).

The methodology in the book is copyrighted by Randy Olson and the respective publishers. This project is a secondary distillation and tool-ization of the book's methods, provided for learning and research purposes only.