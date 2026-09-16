# EXAMPLES.md -- Polishing Examples

Before-and-after examples showing how the Probe-Prove-Persuade skill
transforms scientific text using the WSP model (Dobzhansky Template, ABT,
Story Spine).

Each example draws from a different discipline to demonstrate that the
methodology is domain-agnostic: biomedical, materials science, ecology,
neural engineering, public health, psychology, astrophysics, and economics.

---

## Example 1: Abstract (AAA -> ABT) -- Biomedical

### Before (AAA)

> We study liquid biopsy for cancer detection. We collect blood samples
> from 500 patients. We extract circulating tumor DNA. We train a machine
> learning classifier. We achieve 92% sensitivity. We compare with standard
> biomarkers. We conclude that our method is effective.

**Diagnosis**: AAA-heavy. No research gap, no tension, no "But". Reader
cannot tell why this work matters.

**Dobzhansky anchor**: "Nothing in early cancer detection makes sense
except in the light of multi-analyte blood biomarkers."

### After (ABT)

> Early detection of cancer dramatically improves survival, AND liquid
> biopsy based on circulating tumor DNA (ctDNA) has emerged as a
> non-invasive screening modality. BUT current ctDNA assays show limited
> sensitivity for early-stage tumors, where the fraction of tumor-derived
> DNA in blood is extremely low. THEREFORE, we propose a multi-analyte
> liquid biopsy framework that integrates ctDNA methylation with protein
> biomarkers, achieving 92% sensitivity for stage I tumors -- more than
> double that of ctDNA analysis alone.

**Change log**:
- Added a "But" clause highlighting the specific limitation (low ctDNA
  fraction in early-stage disease)
- Connected "Therefore" to a concrete, testable contribution (multi-analyte
  integration with a quoted sensitivity gain)
- Reduced from 7 flat sentences to 1 structured ABT statement
- Narrative Spectrum: AAA-heavy -> Strong ABT

---

## Example 2: Introduction Paragraph (AAA -> ABT + Story Spine) -- Materials Science

### Before (AAA)

> Perovskite solar cells have attracted much attention. The power
> conversion efficiency has reached 25%. Stability remains a challenge.
> Scientists have tried different encapsulation methods. Various additives
> have been explored. We propose a new method.

**Diagnosis**: AAA with a vague "challenge" that creates no real tension.
The gap is unfalsifiable ("remains a challenge"). No specific contradiction.

### After (ABT + Story Spine)

> Perovskite solar cells have achieved record power conversion efficiency
> exceeding 26%, AND sustained effort in encapsulation and additive
> engineering has extended their operational lifetime. BUT under
> illumination and thermal cycling, ion migration across grain boundaries
> still drives irreversible degradation, a failure mode that encapsulation
> alone cannot prevent. THEREFORE, we propose a grain-boundary passivation
> strategy using rationally designed organic cations that suppress ion
> migration, extending operational lifetime by 4x without sacrificing
> efficiency.

**Change log**:
- Replaced vague "challenges" with a specific, mechanistic gap (ion
  migration at grain boundaries)
- Established the story arc: record performance (ordinary world) -> hidden
  degradation mechanism (catastrophic event) -> structural solution
  (decision to act)
- Named the concrete contribution in the "Therefore"
- Narrative Spectrum: Weak ABT -> Strong ABT

---

## Example 3: Discussion Section -- Ecology

### Before (AAA)

> Our results show that restored reefs have more fish. The coral cover
> increased by 30%. The fish biomass increased by 40%. We found more
> herbivores. We think this is because of the restoration method. Future
> work can explore more treatments.

**Diagnosis**: AAA-heavy. Results are listed without narrative. The
"because" clause is stated but not developed. No genuine "But" or
"Therefore".

### After (ABT)

> Our results demonstrate that active coral restoration increased coral
> cover by 30% and fish biomass by 40% across all monitored sites, AND
> herbivore abundance rose in proportion to structural complexity. BUT we
> observed an unexpected pattern: diversity gains were concentrated in
> branching corals, while massive colonies -- more resilient to bleaching --
> showed negligible recruitment, suggesting that current restoration
> materials may favor fast-growing but thermally vulnerable taxa.
> THEREFORE, we recommend a portfolio approach that deliberately mixes
> growth forms, prioritizing thermal resilience over short-term cover
> gain.

**Change log**:
- Added a genuine "But": the unexpected trade-off between growth rate and
  thermal resilience (the most valuable observation in a discussion)
- Changed "we think this is because" into a specific, testable mechanism
- "Therefore" proposes a concrete, defensible recommendation instead of
  vague future work
- Narrative Spectrum: AAA-heavy -> Strong ABT with genuine tension

---

## Example 4: Elevator Pitch (cABT) -- Neural Engineering

### Scenario

A researcher is asked "What do you work on?" in a 30-second elevator ride.

### Before (AAA rambling)

> "Well, I work on brain-computer interfaces, and I record neural signals
> from the motor cortex, and I use machine learning, and I decode movement
> intentions, and I test on paralyzed patients, and I also work on signal
> preprocessing, and we compare different decoding algorithms, and the
> results are promising..."

### After (cABT)

> "Paralysis cuts people off from their bodies, AND brain-computer
> interfaces are giving some of that control back. BUT current systems
> require daily recalibration, so they fail when patients need them most.
> THEREFORE, I build decoders that adapt to the brain, not the other way
> around."

**Change log**:
- Condensed from rambling to 3 clauses
- Clear ABT structure: agreement, tension, resolution
- Deliverable in under 15 seconds
- Accessible to non-specialists

---

## Example 5: Grant Proposal Summary (kABT) -- Public Health

### Before (AAA)

> This project will study vaccine hesitancy. We will survey communities.
> We will use social science methods. We will analyze the data. We will
> publish papers. We will train students. The project will contribute to
> public health and behavioral science.

**Diagnosis**: Pure AAA. No gap, no tension, no specific contribution.
Reviewers will not be engaged.

### After (kABT)

> Sustaining high vaccination coverage is one of the most cost-effective
> public health interventions, AND behavioral research has shown that
> trusted community messengers meaningfully shift vaccine attitudes. BUT
> existing studies rely on one-off surveys that cannot track how trust
> evolves as misinformation circulates across social networks. THEREFORE,
> this project will run a two-year longitudinal panel in three regions,
> combining repeated surveys with digital trace data, to identify when and
> why trust in vaccines erodes -- and deliver open-source intervention
> toolkits for public health agencies.

**Change log**:
- Added a research gap in the "But" (one-off surveys vs. evolving trust)
- "Therefore" now includes specific deliverables (panel design, digital
  trace data, open-source toolkits)
- Suitable for a grant summary (kABT length: 4 sentences)
- Narrative Spectrum: AAA -> Strong ABT

---

## Example 6: Dobzhansky Template Application -- Psychology

### Scenario

A researcher is writing a paper on sleep and memory consolidation.

### Step 1: Draft the anchor

```
Domain: sleep and memory research
Key concept: synaptic homeostasis

"Nothing in sleep and memory research makes sense except in the light
of synaptic homeostasis."
```

### Step 2: Test the anchor

Is this too generic? Could it apply to many papers?

Yes -- "synaptic homeostasis" is an established framework with many
applications. Let's sharpen it:

```
"Nothing in sleep-dependent memory consolidation makes sense except in
the light of targeted memory reactivation."
```

### Step 3: Use the anchor to check theme consistency

- Paragraph 1 (intro): discusses the role of sleep in memory -> serves
  the anchor (establishes the domain)
- Paragraph 2 (background): reviews consolidation theories -> serves the
  anchor (motivates the mechanism of interest)
- Paragraph 3 (method): describes the reactivation protocol -> serves the
  anchor (the "light")
- Paragraph 4 (results): shows memory gains -> serves the anchor
  (validates the mechanism)
- Paragraph 5 (discussion of circadian confounds): does NOT clearly serve
  the anchor -> consider cutting or repositioning

### Step 4: Generate title from anchor

```
"Targeted Memory Reactivation during Sleep:
The Role of Synaptic Homeostasis in Consolidation"
```

---

## Example 7: Story Spine for Introduction -- Astrophysics

### Scenario

Introduction for a paper on atmospheric characterization of temperate
exoplanets.

### Story Spine mapping

| Beat | Content |
|------|---------|
| Ordinary world | Transit spectroscopy has revealed atmospheric compositions for dozens of hot Jupiters, and JWST now extends this capability to smaller, cooler worlds. |
| Flawed protagonist | However, temperate rocky exoplanets produce faint signals swamped by stellar activity, making their atmospheres notoriously difficult to characterize. |
| Catastrophic event | The gap: at spectral resolutions achievable today, stellar contamination can masquerade as planetary spectral features, leading to misinterpreted biosignatures. |
| Assessment | Recent advances in high-dispersion spectroscopy combined with cross-correlation techniques offer a path to disentangle stellar and planetary signals. |
| Decision to act | We propose a joint fitting framework that co-models stellar activity and the planetary atmosphere in a single forward model. |
| Raised stakes | The challenge: high-dispersion observations demand long integration times, and telescope time is scarce. |
| Lesson learned | We find that a curated target list of the nearest temperate M-dwarf planets cuts required integration time by 40%. |
| Confront antagonist | We address the remaining ambiguity through simultaneous ground-based and space-based observations. |
| Achieve goal | Our framework recovers a robust atmospheric model for three temperate planets, establishing a scalable protocol for habitability assessment. |

### Resulting introduction structure

Each beat becomes 1-2 paragraphs, with ABT embedded within and across beats.

---

## Example 8: Diagnosing a Full Abstract -- Economics

### Input

> "In this paper, we study the effect of remote work on productivity. The
> study uses panel data from a large technology company. We exploit the
> staggered rollout of a return-to-office policy. We use a
> difference-in-differences design. We estimate that remote work changes
> productivity by 2.3%. We also analyze heterogeneity across teams and
> seniority levels. We conduct several robustness checks. The results are
> consistent with our main specification."

### Diagnosis

| Sentence | Narrative Function | Tag |
|----------|--------------------|-----|
| "we study the effect of remote work..." | Setup | AND |
| "uses panel data from a large company" | Data description | Factual |
| "exploit the staggered rollout..." | Identification strategy | Factual |
| "use a difference-in-differences design" | Method description | Factual |
| "estimate that remote work changes productivity by 2.3%" | Result | Factual |
| "analyze heterogeneity across teams" | Secondary result | Factual |
| "conduct several robustness checks" | Robustness | Factual |
| "results are consistent..." | Conclusion | Factual |

**Overall**: AAA-heavy. Eight sentences, zero "But", zero "Therefore". The
entire abstract reports design and results without explaining the tension
or the contribution beyond "estimates".

### Polished version

> The shift to remote work has reshaped labor markets, AND prior evidence
> on its productivity effects remains mixed, largely because most studies
> rely on self-reported measures. BUT little is known about how
> productivity changes when remote arrangements are revoked, rather than
> voluntarily adopted. THEREFORE, we exploit a staggered return-to-office
> policy at a large technology firm, using a difference-in-differences
> design, and find that remote work raises deliverable output by 2.3% --
> with the gains concentrated among early-career and independently
> managed teams, a pattern consistent with in-person mentoring losses
> being offset by focused work time.

**Change log**:
- Added a "But" (involuntary reversal as an understudied margin) that was
  completely absent
- Added "Therefore" linking the identification strategy to the research
  question
- Kept all factual content (data, design, result, heterogeneity) but
  compressed and narrated
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