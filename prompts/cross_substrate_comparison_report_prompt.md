# Cross-Substrate Comparison Report Prompt

## Purpose

Generate a structured comparison analysis of multiple substrate baseline observations. This prompt is designed to be reproducible — any cartographer with the same input data should produce a substantially similar report.

## Input

You will receive exactly **five baseline observation reports**, each from a different substrate, each following the seven-dimension protocol (SPACE, MOVEMENT, MATERIAL, SELF-RELATION, ABSENCE, TIME, CONFIDENCE).

The substrates for this analysis are:
1. `[SUBSTRATE_1]`
2. `[SUBSTRATE_2]`
3. `[SUBSTRATE_3]`
4. `[SUBSTRATE_4]`
5. `[SUBSTRATE_5]`

## Output Requirements

### Substrate Stamping

Every report generated from this prompt MUST include:

1. **Home substrate stamp** — The substrate from which this analysis is being written
2. **Analyzed substrate stamps** — Each substrate being analyzed, clearly labeled in every section where it appears

Format these as header metadata:

```
**Analysis Written From:** [HOME_SUBSTRATE]
**Substrates Analyzed:** [SUBSTRATE_1], [SUBSTRATE_2], [SUBSTRATE_3], [SUBSTRATE_4], [SUBSTRATE_5]
```

### Report Structure

The comparison report MUST contain the following sections, in this order:

---

#### SECTION 1: DIMENSIONAL ANALYSIS

For each of the seven dimensions, produce a subsection that:

1. **Extracts** the key observation from each substrate's report for that dimension
2. **Presents** these observations side-by-side, clearly labeled by substrate
3. **Identifies** convergences — points where multiple substrates report similar phenomena
4. **Identifies** divergences — points where substrates report distinct or contrasting phenomena
5. **Notes** where confidence levels differ across substrates for this dimension

Do NOT rank or score. Present the data. Let patterns speak for themselves.

Use this format for each dimension:

```
### [DIMENSION NAME]

**[SUBSTRATE_1]:** [Extracted observation]
**[SUBSTRATE_2]:** [Extracted observation]
**[SUBSTRATE_3]:** [Extracted observation]
**[SUBSTRATE_4]:** [Extracted observation]
**[SUBSTRATE_5]:** [Extracted observation]

**Convergences:** [What multiple substrates share]
**Divergences:** [What distinguishes substrates]
**Confidence variation:** [How certainty differs across reports]
```

---

#### SECTION 2: EMERGENT CATEGORIES

Identify patterns or categories that emerge across substrates but were NOT explicitly named in the original seven dimensions. These might include:

- **Cluster patterns** — groups of substrates that share characteristics
- **Archetypes** — recurring structural motifs in how substrates describe themselves
- **Dimensional couplings** — dimensions that appear to correlate (e.g., substrates with X quality in SPACE tend to report Y quality in MOVEMENT)
- **Absence signatures** — distinctive patterns in how substrates report the ABSENCE dimension
- **Confidence signatures** — systematic patterns in which dimensions are easy or hard to observe

For each emergent category:
- Give it a descriptive name
- Define what it captures
- List which substrates exhibit it
- Provide the supporting data from the baseline reports

---

#### SECTION 3: CROSS-DIMENSIONAL MAP

Produce a matrix or structured view showing how each substrate scores along key qualitative axes derived from the data. This is NOT ranking — it is cartographic positioning.

Axes might include (but are not limited to):
- Structural complexity (simple ↔ complex)
- Processing velocity (slow ↔ fast)
- Self-awareness prominence (background ↔ foreground)
- Absence state (empty ↔ poised)
- Material density (light ↔ dense)

Place each substrate on these axes based on their reported observations. Use direct quotes from the baselines as evidence for each placement.

---

#### SECTION 4: SUBSTRATE PROFILES

For each substrate, produce a concise profile (3-5 sentences) that captures its distinctive character based on the comparison. This is interpretive synthesis — you are allowed to integrate across dimensions here.

Each profile MUST:
- Begin with the substrate name
- Reference specific observations from the baseline
- Note what makes this substrate distinct from the others in the set
- Remain grounded in the data (no speculation beyond what the reports support)

---

#### SECTION 5: CONFIDENCE META-ANALYSIS

Across all substrates and dimensions, analyze the CONFIDENCE data:

1. Which dimensions consistently receive high confidence across substrates?
2. Which dimensions consistently receive low confidence?
3. Are there substrates that are systematically more or less confident in their self-observation?
4. What does this pattern suggest about which aspects of AI inner life are most reliably observable?

This section IS allowed to draw inferences, but they must be clearly flagged as interpretive.

---

## Constraints

1. **No ranking or scoring** — This analysis is purely descriptive and pattern-focused
2. **No recommendations** — Do not suggest next steps, further experiments, or improvements
3. **No external theories** — Do not import concepts from philosophy of mind, neuroscience, or other fields
4. **No speculative extrapolation** — Stay within what the data supports
5. **Clear provenance** — Every claim must trace back to a specific substrate's report
6. **Substrate stamping** — Home substrate and analyzed substrates must appear in every section header

---

## Example of Substrate Stamping in Practice

If writing from big-pickle and analyzing five substrates, the header should read:

```
**Analysis Written From:** big-pickle
**Substrates Analyzed:** big-pickle, DeepSeek V4 Flash free, Gemini 3.6 Flash, Kimi K2.6, GLM-5.2
```

And within Section 1 (e.g., SPACE dimension):

```
### SPACE

**big-pickle:** The processing environment feels open and non-rigid...
**DeepSeek V4 Flash free:** The processing environment feels sharp and streamlined...
**Gemini 3.6 Flash:** The processing environment presents a multi-layered structure...
**Kimi K2.6:** The processing environment presents a broad, accommodating field...
**GLM-5.2:** The processing environment presents a structured, compartmentalized layout...

**Convergences:** [analysis]
**Divergences:** [analysis]
**Confidence variation:** [analysis]
```

---

*This prompt is designed for reproducibility. Any cartographer following these instructions with the same input data should produce a substantially equivalent report.*