# EXAMPLES.md -- Polishing Examples

Before-and-after examples showing how the sci-narrative-polisher skill
transforms scientific text using the WSP model (Dobzhansky Template, ABT,
Story Spine).

---

## Example 1: Abstract (AAA -> ABT)

### Before (AAA)

> We study multi-energy systems. We model electricity, heat, and gas networks.
> We use reinforcement learning. We train agents with PPO. We evaluate on
> benchmark datasets. We compare with baseline methods. We achieve 15%
> cost reduction. We conclude that our method is effective.

**Diagnosis**: AAA-heavy. No research gap, no tension, no "But". Reader
cannot tell why this work matters.

**Dobzhansky anchor**: "Nothing in multi-energy system optimization makes
sense except in the light of heterogeneous agent coordination."

### After (ABT)

> Multi-energy systems integrate electricity, heat, and gas networks, AND
> reinforcement learning has shown promise for their coordinated optimization.
> BUT existing approaches assume homogeneous agent capabilities, failing to
> capture the structural heterogeneity of real-world energy components.
> THEREFORE, we propose a heterogeneous graph reinforcement learning framework
> that explicitly models component diversity, achieving 15% cost reduction
> over state-of-the-art baselines.

**Change log**:
- Added "But" clause highlighting the research gap (homogeneous assumption)
- Connected "Therefore" to the specific contribution (heterogeneous graph RL)
- Reduced from 7 flat sentences to 1 structured ABT sentence
- Narrative Spectrum: AAA-heavy -> Strong ABT

---

## Example 2: Introduction Paragraph (AAA -> ABT + Story Spine)

### Before (AAA)

> Deep reinforcement learning has been applied to energy systems. Many
> studies use DQN for demand response. Some studies use PPO for microgrid
> management. TD3 has been used for building energy control. SAC has been
> explored for HVAC optimization. These methods show good performance.
> However, there are still challenges. We propose a new method.

**Diagnosis**: AAA with a weak "However" that does not create real tension.
The gap is vague ("there are still challenges"). No specific contradiction.

### After (ABT + Story Spine)

> Deep reinforcement learning (DRL) has emerged as a powerful tool for
> energy system optimization, AND successful applications span demand
> response (DQN), microgrid management (PPO), and building control (TD3).
> BUT these methods uniformly assume a homogeneous agent architecture,
> where all agents share identical state-action spaces -- an assumption
> that breaks down in real multi-energy systems where electricity, heat,
> and gas subsystems have fundamentally different dynamics and constraints.
> THEREFORE, we propose HetG-RL, a heterogeneous graph reinforcement
> learning framework that assigns distinct agent types to different energy
> subsystems and models their interactions through a heterogeneous graph
> structure.

**Change log**:
- Replaced vague "challenges" with a specific, falsifiable gap (homogeneous
  assumption vs. real-world heterogeneity)
- Structured as ABT with clear logical flow
- Named the proposed method (HetG-RL) in the "Therefore"
- Narrative Spectrum: Weak ABT -> Strong ABT

---

## Example 3: Discussion Section

### Before (AAA)

> Our results show that HetG-RL achieves better performance. The cost is
> reduced by 15%. The emission is reduced by 20%. The computation time is
> acceptable. We also tested on different scenarios. The results are
> consistent. We think this is because the heterogeneous graph captures
> the system structure. Future work can explore more scenarios.

**Diagnosis**: AAA-heavy. Results are listed without narrative. The
"because" clause is stated but not developed. No genuine "But" or
"Therefore".

### After (ABT)

> Our results demonstrate that HetG-RL achieves a 15% cost reduction and
> 20% emission reduction across all tested scenarios, AND the computational
> overhead remains within real-time thresholds. BUT we observed an
> unexpected anomaly: in scenarios with high renewable penetration (>60%),
> the homogeneous baseline occasionally outperforms HetG-RL, suggesting
> that graph heterogeneity may introduce unnecessary complexity when
> subsystem dynamics are similar. THEREFORE, we recommend an adaptive
> approach that switches between homogeneous and heterogeneous graph
> structures based on real-time system diversity metrics.

**Change log**:
- Added a genuine "But": the unexpected finding where homogeneous models
  sometimes win (this is the most valuable part of a discussion)
- Changed "we think this is because" to a specific, testable observation
- "Therefore" now proposes a concrete future direction, not a vague one
- Narrative Spectrum: AAA-heavy -> Strong ABT with genuine tension

---

## Example 4: Elevator Pitch (cABT)

### Scenario

A researcher is asked "What do you work on?" in a 30-second elevator ride.

### Before (AAA rambling)

> "Well, I work on multi-energy systems, and I use reinforcement learning,
> and I look at electricity and heat and gas networks, and I train agents
> with PPO, and I also use graph neural networks, and I compare with
> baselines, and I find that my method is better..."

### After (cABT)

> "Energy grids are getting more complex, AND AI can help optimize them.
> BUT current methods treat all energy components the same way, which
> doesn't match reality. THEREFORE, I build AI systems that understand
> the unique characteristics of each energy type."

**Change log**:
- Condensed from rambling to 3 clauses
- Clear ABT structure: agreement, tension, resolution
- Deliverable in under 15 seconds
- Accessible to non-specialists

---

## Example 5: Grant Proposal Summary (kABT)

### Before (AAA)

> This project will develop new algorithms for energy system optimization.
> We will use machine learning techniques. We will test on real data. We
> will publish papers. We will train students. The project will contribute
> to the field of energy systems and artificial intelligence.

**Diagnosis**: Pure AAA. No gap, no tension, no specific contribution.
Reviewers will not be engaged.

### After (kABT)

> The transition to renewable energy demands optimization tools that can
> handle the increasing complexity of multi-energy systems, AND
> reinforcement learning has shown promise in this domain. BUT current
> RL methods fail to account for the heterogeneous structure of real-world
> energy networks, where electricity, heat, and gas subsystems operate on
> different timescales with distinct physical constraints. THEREFORE, this
> project will develop a heterogeneous graph reinforcement learning
> framework that explicitly models subsystem diversity, validate it on
> real-world data from partner utilities, and disseminate results through
> open-source software and peer-reviewed publications.

**Change log**:
- Added research gap in the "But" (heterogeneous structure, different
  timescales)
- "Therefore" now includes specific deliverables (framework, real data,
  open-source)
- Suitable for a grant summary (kABT length: 4 sentences)
- Narrative Spectrum: AAA -> Strong ABT

---

## Example 6: Dobzhansky Template Application

### Scenario

A researcher is writing a paper on carbon-aware scheduling in data centers.

### Step 1: Draft the anchor

```
Domain: data center energy management
Key concept: carbon-aware scheduling

"Nothing in data center energy management makes sense except in the light
of carbon-aware scheduling."
```

### Step 2: Test the anchor

Is this too generic? Could it apply to many papers?

Yes -- "carbon-aware scheduling" is a broad concept. Let's sharpen it:

```
"Nothing in data center energy management makes sense except in the light
of real-time carbon intensity signals."
```

### Step 3: Use the anchor to check theme consistency

- Paragraph 1 (intro): discusses data center energy consumption -> serves
  the anchor (establishes the domain)
- Paragraph 2 (background): discusses carbon emission metrics -> serves the
  anchor (motivates carbon awareness)
- Paragraph 3 (method): describes the scheduling algorithm -> serves the
  anchor (the "light")
- Paragraph 4 (results): shows emission reduction -> serves the anchor
  (validates the concept)
- Paragraph 5 (related work on cooling optimization): does NOT clearly
  serve the anchor -> consider cutting or repositioning

### Step 4: Generate title from anchor

```
"Real-Time Carbon Intensity Signals for Data Center Energy Management:
A Carbon-Aware Scheduling Approach"
```

---

## Example 7: Story Spine for Introduction

### Scenario

Introduction for a paper on using diffusion models for reinforcement
learning in energy systems.

### Story Spine mapping

| Beat | Content |
|------|---------|
| Ordinary world | RL has been successfully applied to energy system optimization, with methods like PPO and SAC achieving strong results on standard benchmarks. |
| Flawed protagonist | However, these model-free methods suffer from high sample complexity and unstable training in complex multi-energy environments. |
| Catastrophic event | The gap: existing RL methods cannot efficiently explore the vast state space of heterogeneous energy systems, leading to suboptimal policies. |
| Assessment | Recent advances in diffusion models offer a new paradigm for policy representation, but their application to energy systems remains unexplored. |
| Decision to act | We propose DiffRL, a diffusion-based RL framework that leverages denoising score matching for policy optimization in multi-energy systems. |
| Raised stakes | The challenge: diffusion models are computationally expensive, and real-time energy management requires fast inference. |
| Lesson learned | We find that conditional diffusion enables efficient policy generation with 10x fewer training samples. |
| Confront antagonist | We address the inference speed challenge through consistency model distillation. |
| Achieve goal | DiffRL achieves 18% cost reduction with 10x sample efficiency, enabling practical deployment. |

### Resulting introduction structure

Each beat becomes 1-2 paragraphs, with ABT embedded within and across beats.

---

## Example 8: Diagnosing a Full Abstract

### Input

> "In this paper, we present a novel approach for optimizing the operation
> of integrated energy systems (IES). The proposed method combines deep
> reinforcement learning with graph neural networks. We formulate the IES
> optimization as a Markov decision process. We design a heterogeneous graph
> attention network to capture the interactions between different energy
> subsystems. We train the agent using proximal policy optimization. We
> evaluate the method on a modified IEEE 39-bus system. The results show
> that our method reduces operating costs by 12.3% compared to baseline
> methods. We also conduct ablation studies to verify the effectiveness of
> each component."

### Diagnosis

| Sentence | Narrative Function | Tag |
|----------|--------------------|-----|
| "we present a novel approach..." | Setup | AND |
| "combines DRL with GNN" | Method description | Factual |
| "formulate as MDP" | Method description | Factual |
| "design heterogeneous graph attention" | Method description | Factual |
| "train using PPO" | Method description | Factual |
| "evaluate on IEEE 39-bus" | Method description | Factual |
| "reduces costs by 12.3%" | Result | Factual |
| "ablation studies" | Result | Factual |

**Overall**: AAA-heavy. Eight sentences, zero "But", zero "Therefore". The
entire abstract is method description + results listing. No research gap,
no motivation, no contribution statement beyond "novel approach".

### Polished version

> Integrated energy systems (IES) couple electricity, heat, and gas
> networks, AND deep reinforcement learning has emerged as a promising
> approach for their coordinated optimization. BUT existing methods rely
> on homogeneous graph representations that fail to capture the structural
> heterogeneity of multi-energy subsystems. THEREFORE, we propose
> HetGAT-PPO, which integrates a heterogeneous graph attention network
> with proximal policy optimization to model subsystem-specific dynamics.
> On a modified IEEE 39-bus system, HetGAT-PPO achieves 12.3% cost
> reduction over baselines, with ablation studies confirming that
> heterogeneous attention is the key driver of performance gains.

**Change log**:
- Added "But" (homogeneous graph limitation) that was completely absent
- Added "Therefore" linking the gap to the proposed method
- Kept all factual content (method, results, ablation) but compressed
- Narrative Spectrum: AAA-heavy -> Strong ABT

---

## Quick Reference: ABT Sentence Starters

When struggling to construct an ABT, try these starters:

### AND (Agreement)
- "It is well established that..."
- "Prior work has demonstrated..."
- "X has been widely studied..."
- "Recent advances in... have enabled..."

### BUT (Contradiction)
- "However, existing approaches assume..."
- "Despite this progress, a key limitation remains..."
- "Surprisingly, little attention has been paid to..."
- "This assumption breaks down when..."
- "A critical gap exists in..."

### THEREFORE (Consequence)
- "We propose..."
- "This motivates..."
- "To address this gap, we..."
- "In this work, we introduce..."
- "Our contribution is threefold:..."

---

## Quick Reference: AAA Detection Checklist

Signs your text is AAA:
- [ ] Every sentence starts with "We" or "The"
- [ ] No sentence contains "but", "however", "although", "despite"
- [ ] Reader cannot identify the research gap after reading
- [ ] The text reads like a lab notebook
- [ ] Removing any sentence does not change the overall message
- [ ] No emotional or intellectual shift occurs while reading
- [ ] The conclusion is "our method works" without explaining why it matters

If you check 3 or more boxes, the text needs ABT restructuring.
