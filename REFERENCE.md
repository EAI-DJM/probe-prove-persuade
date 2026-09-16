# REFERENCE.md -- Scientific Narrative Polisher: Full Methodology

This document provides the complete theoretical foundation and operational
detail for the sci-narrative-polisher skill, derived from Randy Olson's
*Houston, We Have a Narrative: Why Science Needs Story* (2015, Chinese
translation 2018 by Gao Shuang, Chongqing University Press).

---

## Table of Contents

1. [Book Overview](#1-book-overview)
2. [The Narrative Problem in Science](#2-the-narrative-problem-in-science)
3. [WSP Model: Three Layers of Narrative Tools](#3-wsp-model-three-layers-of-narrative-tools)
4. [Dobzhansky Template (Word Layer)](#4-dobzhansky-template-word-layer)
5. [ABT Template (Sentence Layer)](#5-abt-template-sentence-layer)
6. [Hero's Journey / Story Spine (Paragraph Layer)](#6-heros-journey--story-spine-paragraph-layer)
7. [Narrative Spectrum](#7-narrative-spectrum)
8. [IMRAD Integration](#8-imrad-integration)
9. [Narrative Intuition](#9-narrative-intuition)
10. [Hegel's Dialectic and Book Structure](#10-hegels-dialectic-and-book-structure)
11. [LaTeX-Specific Guidance](#11-latex-specific-guidance)

---

## 1. Book Overview

| Field | Value |
|-------|-------|
| Title | Houston, We Have a Narrative: Why Science Needs Story |
| Chinese Title | 科学需要讲故事 |
| Author | Randy Olson (兰迪·奥尔森) |
| Translator | Gao Shuang (高爽) |
| Publisher | Chongqing University Press (重庆大学出版社) |
| Year | 2018 (Chinese edition) |
| ISBN | 978-7-5689-0920-4 |

**Author background**: Randy Olson was a tenured marine biology professor at
the University of New Hampshire before leaving academia for Hollywood. He
became a filmmaker, writer, and science communication consultant. This
dual perspective -- scientist and storyteller -- gives the book its unique
authority.

**Core thesis**: Science is a narrative process. Narrative is storytelling.
Therefore, science needs storytelling. The biggest problem in science
communication is not lack of data but lack of narrative structure.

---

## 2. The Narrative Problem in Science

### 2.1 The AAA Pattern (And-And-And)

Most scientific writing follows the AAA pattern: a flat sequence of facts
connected by "and" with no tension, conflict, or resolution.

**Example (AAA)**:
> "We collected samples AND we measured temperature AND we analyzed the data
> AND we found a correlation AND we wrote this paper."

**Symptoms**:
- Reader cannot identify the research gap
- No emotional shift or intellectual surprise
- Feels like a lab notebook, not a story
- Audience loses attention

### 2.2 Why Scientists Resist Narrative

- Scientists equate "story" with "fiction" or "distortion"
- IMRAD template already forces *some* information shaping, but scientists
  do this unconsciously rather than strategically
- The academic reward system (tenure) does not punish poor communication
- "Style" is dismissed as superficial; "substance" is valued above all

### 2.3 The Hollywood Insight

Olson argues that Hollywood has spent a century perfecting narrative
techniques for mass audiences. Scientists should borrow these tools, not to
entertain, but to communicate more effectively. The key transferable skill is
**structuring information to maintain attention**.

**Quote**: "You are only as good as your last movie." (Hollywood maxim) --
in science, every paper, every talk, every grant is a "performance" that
should engage its audience.

---

## 3. WSP Model: Three Layers of Narrative Tools

The WSP model is the organizing framework for all narrative tools in this
skill:

```
WSP Model
  |
  +-- W (Word)        --> Dobzhansky Template    --> Theme anchoring
  |                                                Works at the level of
  |                                                a single word/phrase
  |
  +-- S (Sentence)    --> ABT Template           --> Logic structuring
  |                                                Works at the level of
  |                                                a single sentence
  |
  +-- P (Paragraph)   --> Hero's Journey /       --> Arc building
                         Story Spine                Works at the level of
                                                    multiple paragraphs
```

**Key insight**: The three layers are applied in order. You cannot fix
sentence-level problems if the theme (word level) is unclear. You cannot
build a paragraph arc if the sentences within it lack ABT structure.

**Megan's three-stage process** (referenced in the book):
1. See it (observe the information)
2. Shape it (apply narrative structure -- this is where WSP operates)
3. Say it (deliver with style)

WSP operates at stage 2. Style (stage 3) comes only after shaping is complete.

---

## 4. Dobzhansky Template (Word Layer)

### 4.1 Origin

Theodosius Dobzhansky (1900-1975) was one of the most important geneticists
of the 20th century. He emigrated from the Soviet Union to the United States
and published *Genetics and the Origin of Species* (1937), which became the
foundation of the modern evolutionary synthesis.

His famous 1973 essay title:
> "Nothing in biology makes sense except in the light of evolution."

### 4.2 Template

```
English:
"Nothing in [domain] makes sense except in the light of [key concept]."

Chinese:
"如果不从 [关键概念] 的角度思考问题，[研究领域] 的一切都毫无道理。"
```

### 4.3 How to Use

1. **Identify the domain** (second blank): What is the broad field your paper
   addresses? (e.g., "power system optimization", "reinforcement learning",
   "multi-energy systems")

2. **Identify the key concept** (first blank): What single idea or perspective
   makes everything in your paper coherent? (e.g., "heterogeneous graph
   structure", "multi-agent coordination", "carbon-aware scheduling")

3. **Test the anchor**: Read the filled template. Does it accurately capture
   the paper's unique contribution? If the template could apply to many
   papers in the field, your anchor is too generic -- sharpen it.

### 4.4 Purpose

- **Reduces information waste**: The book cites Fasher's "chaos in the
  brickyard" (1963) -- science suffers from purposeless information
  gathering. The Dobzhansky Template forces you to state your purpose
  before gathering more material.
- **Theme consistency check**: Every paragraph in the paper should
  eventually serve the anchored theme. If a paragraph does not connect to
  the anchor, it may be tangential -- consider cutting or repositioning it.
- **Title generation**: A strong Dobzhansky anchor often suggests a
  compelling paper title.

### 4.5 Example

For a paper on heterogeneous graph reinforcement learning for multi-energy
systems:

```
"Nothing in multi-energy system optimization makes sense except in the
light of heterogeneous graph structure."
```

This anchor tells the reader: the paper's unique contribution is applying
heterogeneous graph structure to energy system optimization, and without
this perspective, the field's problems remain intractable.

---

## 5. ABT Template (Sentence Layer)

### 5.1 Definition

ABT stands for **And-But-Therefore**. It is a single-sentence narrative
structure that captures the essence of a story:

```
[Agreement/facts] AND [more context],
BUT [contradiction/problem/gap],
THEREFORE [conclusion/action].
```

### 5.2 Theoretical Foundation

ABT traces directly to two traditions:

1. **Aristotle's three-act structure**: Beginning (And), Middle (But), End
   (Therefore)
2. **Hegel's dialectic**: Thesis (And), Antithesis (But), Synthesis
   (Therefore)

Olson formalized ABT in 2011, though the underlying pattern has existed
for millennia (as old as the Epic of Gilgamesh).

### 5.3 Neural Basis

The book references Uri Hasson's neuroscience research: ABT structure
activates the narrative-processing regions of the brain. When a listener
hears "But", their brain lights up -- this is where the story truly begins.
The "But" functions as an "inciting incident" in screenwriting terms,
transitioning the audience from the ordinary world to the special world.

### 5.4 ABT vs AAA

| Feature | AAA (And-And-And) | ABT (And-But-Therefore) |
|---------|--------------------|-----------------------|
| Structure | Flat list of facts | Agreement -> Conflict -> Resolution |
| Tension | None | Peaks at "But" |
| Direction | Aimless | Forward-moving |
| Audience engagement | Low (boredom) | High (curiosity) |
| Memorability | Low | High |
| Typical length | Rambling | Concise |

### 5.5 The "But" as Inciting Incident

In screenwriting, the "inciting incident" is the event that disrupts the
ordinary world and sets the story in motion. In scientific writing, the
"But" serves this function:

- It signals the research gap
- It creates intellectual tension
- It motivates the "Therefore" (the study's contribution)

**Without a genuine "But", there is no story.** If you cannot find a real
contradiction or gap, your study may be purely descriptive -- which is
acceptable, but you should not force a false narrative arc.

### 5.6 Three ABT Variants

Olson defines three versions of ABT for different audiences:

#### cABT (Concise ABT)
- **Length**: One short sentence
- **Audience**: General public, non-specialists
- **Use case**: Elevator pitch, public talk, press release
- **Example**: "Energy systems are getting more complex AND we need better
  optimization, BUT current methods can't handle heterogeneous components,
  THEREFORE we developed a new graph-based approach."

#### kABT (Keeper ABT)
- **Length**: 2-4 sentences
- **Audience**: Mixed (e.g., conference attendees from related fields)
- **Use case**: Conference abstract, paper abstract, grant summary
- **Balance**: Concise enough to deliver orally, detailed enough to convey
  substance
- **Example**: "In my lab, we study multi-energy system optimization using
  reinforcement learning. We initially focused on homogeneous agent
  coordination, AND we achieved good results on standard benchmarks. BUT we
  realized that real-world energy systems have heterogeneous components that
  homogeneous models cannot capture. THEREFORE, we developed a heterogeneous
  graph reinforcement learning framework that explicitly models component
  diversity."

#### iABT (In-depth ABT)
- **Length**: Full paragraph or more
- **Audience**: Specialist peers in the same field
- **Use case**: Introduction section, detailed technical proposal
- **Detail level**: Includes technical terminology, specific method names,
  quantitative results
- **Example**: Multi-paragraph introduction with embedded ABT structure,
  where the "But" is a detailed literature gap analysis and the "Therefore"
  is the proposed methodology with expected contributions.

### 5.7 ABT Construction Process

1. **Gather the "And" material**: List all background facts and context
   the reader needs. These are things the audience already agrees with.
2. **Find the "But"**: Identify the gap, contradiction, or unexpected
   result. This is the most important step -- a weak "But" means a weak
   paper.
3. **State the "Therefore"**: What follows logically from the contradiction?
   This is your contribution.
4. **Test by reading aloud**: If the sentence flows naturally and creates
   a sense of "aha" at the "Therefore", the ABT is working.
5. **Adjust length by intuition**: There is no fixed word count. The right
   length depends on audience and context. Develop "narrative intuition"
   through practice.

### 5.8 ABT for Different IMRAD Sections

| Section | And | But | Therefore |
|---------|-----|-----|-----------|
| Abstract | Background + existing work | Research gap | This paper's contribution |
| Introduction | Field context + progress | Unsolved problem | Proposed approach |
| Discussion | Main findings | Unexpected results / limitations | Implications + future work |
| Conclusion | Summary of contribution | Remaining challenges | Broader impact |

### 5.9 Common ABT Mistakes

1. **Fake "But"**: "We studied X, BUT we also studied Y, THEREFORE we
   published this." -- Y is not a contradiction to X; this is still AAA
   wearing an ABT mask.
2. **Missing "Therefore"**: "We found A AND we found B BUT we found C."
   -- Without a "Therefore", the story has no resolution.
3. **Overstated "Therefore"**: "BUT current methods are completely useless,
   THEREFORE our method is the only solution." -- Exaggeration undermines
   credibility.
4. **ABT in Methods**: Do not force ABT into methods sections. "We used
   method A AND we used method B BUT method C was better THEREFORE we chose
   C." -- This is unnecessary dramatization of a technical choice. State it
   factually.

---

## 6. Hero's Journey / Story Spine (Paragraph Layer)

### 6.1 Origin

The Hero's Journey (monomyth) was articulated by Joseph Campbell in *The
Hero with a Thousand Faces* (1949). George Lucas applied it to *Star Wars*,
demonstrating its commercial power. Christopher Vogler adapted it for
screenwriters in *The Writer's Journey: Mythic Structure for Writers*
(1998), making it accessible to Hollywood.

### 6.2 The Story Spine Template

The Story Spine was developed by Dolly Barton (Olson's workshop collaborator)
as a simplified, fill-in-the-blank version of the Hero's Journey:

```
In an ordinary world, _______________________________
A flawed protagonist ___________________________________
Encountered a catastrophic event _______________________
Which upended their world, but after assessment, _______
The protagonist decided to act, _________________________
But with raised stakes, _________________________________
The protagonist had to learn a lesson, _________________
To confront the antagonist, _____________________________
And achieve the goal, ___________________________________
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

### 6.3 Application to Scientific Writing

Map the Story Spine elements to research narrative:

| Story Spine Element | Scientific Equivalent |
|---------------------|-----------------------|
| Ordinary world | Established field / current state of the art |
| Flawed protagonist | The research problem (which is "flawed" = unsolved) |
| Catastrophic event | The key challenge / gap that disrupts the status quo |
| Assessment | Literature review / analysis of the gap |
| Decision to act | Proposed methodology / research design |
| Raised stakes | Complications / unexpected difficulties |
| Lesson learned | Key finding / insight |
| Confront antagonist | Addressing the challenge / experimental validation |
| Achieve goal | Contribution / resolution / impact |

### 6.4 The "High-Low" Principle

From playwright Christopher Keane: *All great stories are about the
contrast between highs and lows.* When polishing:

- **Identify the highest point** (the breakthrough finding, the moment of
  insight)
- **Identify the lowest point** (the failed approach, the dead end, the
  moment of doubt)
- **Cut the middle transitions** that do not serve the dramatic arc
- **Accelerate through routine steps**, **slow down for dramatic/emotional
  moments**

**Analogy**: A baseball batter swings and misses two slow pitches, then
hits a home run. The drama is in the miss-then-hit contrast, not in the
detailed mechanics of each swing.

### 6.5 When to Use (and When Not to)

**Use for**:
- Introduction sections (establish the research journey)
- Discussion sections (interpret findings as a narrative of discovery)
- Grant proposals (persuade reviewers that the research story matters)
- Conference talks (engage the audience)

**Do NOT use for**:
- Methods sections (factual, procedural)
- Results sections (data presentation)
- Equations and derivations (mathematical rigor)

### 6.6 Caution

Olson explicitly warns: the Hero's Journey is "powerful but easily misused."
It can lead to over-dramatization or forced narratives. Use it as a
*diagnostic tool* (does your introduction have the right beats?) rather than
a *rigid template* (you must fill every blank).

---

## 7. Narrative Spectrum

### 7.1 Definition

The Narrative Spectrum is a diagnostic tool for evaluating where a text falls
on the AAA-to-ABT continuum. It is not a polishing tool itself, but a
*measurement* tool that guides polishing decisions.

### 7.2 Five-Element Analysis

Following Anna Ripple et al. (2011), scientific abstracts can be decomposed
into five structural elements:

| Element | Narrative Function | ABT Role |
|---------|--------------------|----------|
| Background | Sets the scene | AND |
| Objective | States the goal / gap | BUT |
| Methods | Describes the approach | (factual) |
| Results | Reports findings | (factual) |
| Conclusion | Interprets meaning | THEREFORE |

This maps to Hegel's dialectic:
- Background = Thesis (the established order)
- Objective = Antithesis (the contradiction / gap)
- Conclusion = Synthesis (the resolution)

### 7.3 Spectrum Classification

| Classification | Description | Example Pattern |
|----------------|-------------|-----------------|
| **AAA-heavy** | All facts, no tension | "We did A and B and C and found D" |
| **Weak ABT** | Has a "But" but it is minor or unclear | "We did A and B, but C was different, so D" |
| **Strong ABT** | Clear agreement, genuine conflict, logical resolution | "A is known AND B extends it, BUT gap G exists, THEREFORE we propose M" |
| **ABT + Story Spine** | Full narrative arc across paragraphs | Introduction follows Story Spine beats |

### 7.4 How to Apply

1. Tag each paragraph with its narrative function (AND/BUT/THEREFORE/factual)
2. Count the ratio of AND paragraphs to BUT paragraphs
3. If > 70% AND with no clear BUT, the text is AAA-heavy
4. If there is a clear BUT but the THEREFORE is weak, focus on strengthening
   the conclusion
5. Use this assessment to prioritize which sections to polish first

### 7.5 The "Boring World" Test

From the book: if you remove the "But" from your text, does it still read
the same? If yes, your "But" is not doing any work. A real "But" changes the
direction of the narrative -- without it, the story falls apart.

---

## 8. IMRAD Integration

### 8.1 IMRAD Overview

IMRAD = Introduction, Methods, Results, And Discussion. It is the dominant
structure for scientific papers, adopted over the past 50+ years.

### 8.2 Narrative Tool Selection by Section

```
Introduction     --> ABT + Story Spine + Dobzhansky
                   (Subjective, argumentative, needs narrative)

Methods          --> Minimal narrative; focus on clarity
                   (Objective, procedural, needs accuracy)

Results          --> Minimal narrative; focus on clarity
                   (Objective, factual, needs precision)

Discussion       --> ABT + Dobzhansky
                   (Subjective, interpretive, needs narrative)
```

### 8.3 Why Methods and Results Don't Need ABT

Olson explicitly states: "In this part [Methods/Results], I no longer use
the ABT structure. ABT is effective for the Introduction and Discussion
[parts], which are more subjective and full of argument. But in the middle
part, we will unfold specific details, about the journey's material, which
is more objective -- needs to directly state what happened."

**Practical rule**: If a section describes *what you did* or *what you
found*, keep it factual. If a section argues *why it matters* or *what it
means*, apply narrative tools.

### 8.4 Structured Abstracts

The trend toward structured abstracts (Background, Objective, Methods,
Results, Conclusion) is accelerating:
- 1992: 2.5% of journals required structured abstracts
- 2005: 20.3%
- Projected 2050: ~100%

This trend aligns with ABT: Background (AND) + Objective (BUT) + Conclusion
(THEREFORE), with Methods and Results as factual support.

---

## 9. Narrative Intuition

### 9.1 Definition

Narrative intuition is the trained ability to "feel" whether a narrative is
working -- without conscious analysis. It is the goal of long-term practice
with ABT and the Story Spine.

### 9.2 Developing Narrative Intuition

1. **Practice ABT daily**: Convert any research summary into a single ABT
   sentence. Do this for your own work and for papers you read.
2. **Read aloud**: If you stumble or feel bored while reading your own text,
   the narrative is not working.
3. **The elevator test**: Can you tell your research story in 30 seconds?
   If not, the narrative is too complex.
4. **The "But" hunt**: For every paper you read, identify the "But". If you
   cannot find it, the paper may be AAA.
5. **Story Circle**: Olson's recommended practice -- gather 3-5 colleagues,
   each presents their research as an ABT, and the group provides feedback.
   This collective sharpening builds intuition faster than solo practice.

### 9.3 The ABT Timing Experiment

In the book, Olson describes an experiment:
- Volunteers looked at an Edward Hopper painting and described what they saw
- Without ABT: average 30 seconds, rambling, no clear endpoint
- With ABT: average 13 seconds, structured, confident, complete

**Lesson**: ABT does not make stories longer or more complex. It makes them
*shorter and more effective* by providing a natural endpoint (the
"Therefore").

---

## 10. Hegel's Dialectic and Book Structure

### 10.1 The Book's Own ABT Structure

Olson structures the entire book as a Hegelian dialectic:

```
Thesis (Part II):     Science needs storytelling
                       AND: Science is helpless in the narrative world
                       BUT: Humanities should help... but can't
                       THEREFORE: Hollywood rescues science

Antithesis (Part III): The tools (WSP model)
                        Methods: Word, Sentence, Paragraph
                        Results: Narrative Spectrum, case studies

Synthesis (Part IV):   Science needs storytelling (revisited)
                        AND: Hollywood can help
                        BUT: Narrative training needs different thinking
                        THEREFORE: I recommend Story Circles
```

### 10.2 Why This Matters for Polishing

When polishing a full paper, consider its macro-structure:
- Does the Introduction function as a "Thesis" (establishing the status quo)?
- Does the gap analysis function as an "Antithesis" (the contradiction)?
- Does the Discussion function as a "Synthesis" (resolving the tension)?

If the paper lacks this dialectic movement, it may be a collection of facts
rather than an argument.

---

## 11. LaTeX-Specific Guidance

For users writing papers in LaTeX (common in CS, engineering, physics):

### 11.1 Abstract

```latex
\begin{abstract}
% Apply ABT here
% AND: [domain context] is important and [existing approaches] have been studied.
% BUT: [specific gap] remains unsolved.
% THEREFORE: We propose [method] and demonstrate [result].
\end{abstract}
```

### 11.2 Introduction

Structure the introduction as Story Spine beats, each potentially a
paragraph:

```latex
% Ordinary world: Established field context
Prior work has shown that~\cite{...} \dots

% Catastrophic event: The gap
However, existing approaches fail to account for~\dots

% Decision to act: Proposed method
In this paper, we propose~\dots

% Achieve goal: Summary of contribution
Our contributions are:
\begin{itemize}
  \item \dots
\end{itemize}
```

### 11.3 Discussion

```latex
% AND: Our findings confirm...
Our results demonstrate that~\dots

% BUT: Unexpected limitation / contrast with prior work
Surprisingly, we observed that~\dots, which contrasts with~\cite{...}

% THEREFORE: Implication
This suggests that~\dots, opening new directions for~\dots
```

### 11.4 Dobzhansky Anchor in LaTeX Titles

A strong Dobzhansky anchor can inspire the paper title:

```latex
\title{Nothing in [Domain] Makes Sense Except in the Light of [Concept]}
% or more naturally:
\title{[Concept] for [Domain]: A [Method] Approach}
```

### 11.5 Avoiding ABT in Equations

Never force narrative structure into mathematical expressions. Equations
should be presented factually with clear notation. The narrative (ABT)
belongs in the surrounding prose that *motivates* and *interprets* the
equation, not in the equation itself.
