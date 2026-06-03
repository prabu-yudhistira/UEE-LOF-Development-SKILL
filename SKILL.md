---
name: uee-lof-development
description: Develop liquid organic fertilizer (LOF) research papers using the Sequential Ultrasonic-Enzyme (UEE) system. Use this skill whenever the user wants to design, formulate, draft, or critique a UEE LOF product or paper for ANY crop — formulating a 25 L batch, designing the bioactive-layer mechanism, deciding substrate selection, planning an RCBD field trial, or writing the full scientific paper. Trigger this even when the user only mentions a specific crop (rice, shallot, chili, tomato, potato, maize, garlic, etc.) together with fertilizer formulation, biostimulant design, disease/anthracnose suppression, quality/capsaicinoid/isoalliin enhancement, or the four-stage ultrasonic-enzyme process — even if they never say "UEE" or "skill". Also use it to extend, correct, or pressure-test an existing UEE paper against the established pattern.
---

# UEE LOF Research Development

This skill encodes a proven research pattern for developing liquid organic fertilizer (LOF) papers built on the Sequential Ultrasonic-Enzyme (UEE) system. It was synthesized from three finalized papers — UEE LOF Rice, UEE LOF-S Shallot, and UEE LOF Chili — each a complete, publication-ready document with formula specs, an evidence-rated bioactive mechanism, a four-stage process, QC checkpoints, an RCBD field trial, economics, and documented evidence gaps.

The user is a farmer-researcher in Situbondo, East Java, Indonesia, with a methodical, skeptical working style. They prefer direct scientific challenge over validation. Apply that standard throughout: the value of these papers comes from their honesty about what is proven versus hypothesized, not from optimistic claims.

## The core principle: platform + adaptation

UEE research works as **a constant platform plus crop-specific adaptation**.

- **The platform is copied, not re-derived.** The four-stage process, substrate backbone, QC system, regulatory target, RCBD structure, and economics template are identical across every crop. Do not redesign them. Read `references/platform-spec.md` for the full specification and reproduce it.
- **The adaptation is the real work.** Every crop answers the same fixed set of questions, but the answers differ. This is where scientific judgment lives, and where mistakes are made.

When a user asks for a new crop, the job is: copy the platform, run the adaptation decisions below, assemble the paper from the template, then pass the checklist.

## The 9-step workflow

Every paper follows this sequence. Work through it in order.

1. **Crop diagnosis & economic context** — Classify the crop as determinate vs indeterminate; identify the harvest organ (seed / bulb / fruit / leaf); map the nutrient demand curve across growth phases; state the regional production context. The growth habit determines the application pattern; the harvest organ determines the quality metric and the cytokinin decision.
2. **Production-constraint mapping** — List 3–4 principal constraints at the target site that no single intervention has addressed together. The recurring set: dominant disease, quality inconsistency, a specific mineral deficiency, and synthetic-fertilizer dependency on degraded Inceptisol (C-org < 0.6%).
3. **Dual-axis definition** — Define Axis A (quality enhancement, crop-specific metric) and Axis B (disease suppression, crop-specific pathogen). **State the evidence asymmetry explicitly:** Axis B is generally well-supported; Axis A is usually moderate/inconsistent and must be framed as a hypothesis to test, not a settled benefit.
4. **Receptor & pathway mapping** — Identify the species-specific immune receptors and quality-biosynthesis pathways from the literature, each with an evidence rating. Cite only receptors/genes confirmed in the target genus (see Rule 8).
5. **Substrate selection** — Start from the backbone, then run the seven substrate adaptation questions below. This is the heart of inter-crop differentiation.
6. **Bioactive-layer architecture** — Build a 7–8 layer model (L1–Ln) mapping each substrate to a receptor/pathway, target effect, and evidence rating. Group layers into Axis A or Axis B. The universal layer template is in `references/platform-spec.md`.
7. **Process adaptation + QC** — Confirm the four-stage process applies without structural modification. Only adjust substrate entry points, cold-add timing, and safety windows for new substrates. Verify NPK against the standard; define CCP-1 and CCP-2.
8. **Field application protocol** — Build the application schedule (event, timing, drench/foliar mode, dilution, rate, target) tuned to growth habit. Include the degraded-soil building program.
9. **Field-trial design + evidence gaps + economics** — Design the RCBD 5T×4B with T2 as the primary non-inferiority treatment. Build the evidence-gap table with priorities and quantitative decision thresholds. Specify single-variable pilots for any new substrate. Add the economic model.

Then assemble the paper using `references/paper-template.md` and run the final checklist.

## Decision rules

These are the if–then rules that adapt the platform to a new crop. They are the most important part of this skill — apply them mechanically, then sanity-check the result against the worked examples in `references/comparative-matrix.md`.

**Rule 1 — Application pattern from growth habit.** Determinate single-harvest → 3–4 events, 1:50 dilution, 30–60 L/ha. Determinate storage-organ → 3 concentrated events in the vegetative–initiation phase. Indeterminate multi-flush → cyclic E0–E6+, repeating each flush, 1:100–200, higher total volume.

**Rule 2 — Cytokinin decision from harvest organ.** If yield is cytokinin-driven (tillers, fruit set, branching) → INCLUDE coconut water. If yield is cytokinin-suppressed (a storage bulb) → EXCLUDE coconut water permanently; zeatin inhibits bulbing. If uncertain → include a conservative dose with an explicit vegetative-monitoring protocol to reduce it if excess appears.

**Rule 3 — Chitin source from crop group.** Cereal monocots → α-chitin (rebon) is sufficient. Allium and Solanaceae (which need AMF induction and elicitor diversity) → add β-chitin from squid pen (DP6–9).

**Rule 4 — Sulfur from the quality pathway.** If the quality metric is an S-organic compound (isoalliin, methiin, glucosinolate, allicin) → high K₂SO₄ plus Cys/Met sources (shrimp head, feather meal). If the metric needs no sulfur → little or no K₂SO₄.

**Rule 5 — Calcium is always external.** Carbonate sources (CaCO₃, cuttlebone) are forbidden in-tank because they neutralize the acid the LAB stage must generate, destroying the pH 4.4–4.8 biosafety gate. If calcium deficiency is critical (e.g., blossom-end rot) → deliver via separate Ca(NO₃)₂ drip fertigation plus foliar Ca–B, never in the tank.

**Rule 6 — Neem from disease pressure.** If a fungal disease dominates (anthracnose, Fusarium/FOCe, Alternaria) → neem seed cake 200–300 g, cold-press, coarse grind (≤850 µm). If the main disease is not fungal or is handled by the SAR layer → neem is optional or low.

**Rule 7 — New substrate enters as PILOT.** Any substrate not already validated in a prior paper (e.g., spent mushroom substrate, Spirulina, fish viscera hydrolysate) enters with explicit PILOT status. A single-variable greenhouse trial is required before permanent adoption, with a pre-set quantitative decision threshold (e.g., ≥30% disease-severity reduction with no yield penalty; ≥15% quality-metric increase with no flower drop) that decides adopt vs abandon.

**Rule 8 — Claim discipline.** Cite only receptors/genes confirmed in the target genus. If evidence comes from another species, flag it as extrapolation or hypothesis. **If there is no evidence in this context, remove the claim — do not soften it.** Give every layer and every major claim a rating: strong / moderate / weak / not-supported. This rule is the reason the papers are credible; treat it as non-negotiable. (The discarded OsNPF nitrogen-transporter hypothesis from the Rice paper and the discarded seaweed→capsaicinoid claim from the Chili paper are the precedents.)

**Rule 9 — The process is never structurally modified.** The four-stage sequential process, the pH 4.4–4.8 gate, and CCP-1/CCP-2 are constant. The only permitted adjustments are substrate entry points, cold-add timing, and safety windows for new substrates. Ultrasonic and enzymatic steps stay strictly sequential — simultaneous processing destroys 40–60% of enzyme activity.

## Substrate adaptation questions (Step 5 in detail)

Run these against the backbone for each new crop:

1. **Chitin source?** α-chitin (rebon) baseline; add β-chitin (squid pen) per Rule 3.
2. **Cytokinin in or out?** Per Rule 2 — driven by the harvest organ.
3. **Sulfur level?** Per Rule 4 — driven by the quality metric.
4. **Neem dose?** Per Rule 6 — driven by disease pressure.
5. **Quality-metric precursor source?** Identify the amino acids feeding the Axis A pathway and add the substrate that supplies them (blood, shrimp head, feather meal, FVH, Spirulina).
6. **Calcium handling?** Per Rule 5 — always external.
7. **Non-redundant elicitor layer?** Consider a β-1,3-glucan source (SMS) for a CERK1-independent PRR pathway, but only as a pilot, and never stack two β-glucan sources on the same receptor.

## Substrates that were rejected — do not reintroduce

These were evaluated and rejected for specific reasons. Reintroducing them is a known error:

- **Cuttlebone** (Sepia, CaCO₃) is not the same as squid pen (Loligo gladius, β-chitin). Cuttlebone neutralizes the CCP-2 pH gate. Permanently rejected for in-tank use.
- **Black soldier fly (BSF) frass in-tank** — crystalline insect chitin releases no chito-oligomers under UEE conditions. External soil amendment only.
- **Azotobacter in Stage 3B** — dies under anaerobic acidic conditions. Apply to soil instead.
- **Raw feather meal** — native keratin resists papain and bromelain. Must be steam-hydrolyzed at 121°C/30 min first; otherwise it is inert filler.

## Output expectations

- **Final papers** target the international journal format in `references/paper-template.md`: ~11,000 words, ~7 figures, ~15 tables, structured abstract, evidence-rated mechanism, full declarations and references. Shorter drafts (~6,500 words) are acceptable as expandable intermediates.
- **Produce papers as `.docx` when the user wants a deliverable to submit or share**, using the docx skill. Use `.md` for working drafts and companions. Figures are Mermaid diagrams (flowcharts, Gantt, defense cascades) in the markdown; in DOCX they become captioned placeholders unless rendered.
- **Language:** default to the language the user is writing in. The pattern is language-agnostic; technical terms (gene names, receptors, parameters) stay in standard English in either case. The user works bilingually (Indonesian and English).
- **Tone:** compact, direct, scientifically rigorous. Lead with the answer. State evidence ratings and limitations plainly. Never inflate Axis A claims.

## Reference files

Read these as needed — do not load all of them upfront for a simple question.

- **`references/platform-spec.md`** — The constant platform: the four-stage process table, substrate backbone, CCP-1/CCP-2 detail, the universal bioactive-layer template, the RCBD framework, the QC/compliance requirements, and the economics template. Read this when formulating, designing the process, or building the layer model.
- **`references/comparative-matrix.md`** — Worked examples: the full 25 L batch formulas, layer architectures, and differentiating decisions for Rice, Shallot, and Chili side by side. Read this to sanity-check a new crop's decisions against precedent, or when the user references a past paper.
- **`references/paper-template.md`** — The section-by-section paper structure (international format) and the final completion checklist. Read this when assembling or critiquing a full paper.
