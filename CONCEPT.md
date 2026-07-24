# CONCEPT — ERR (EIC Pathfinder 2026)

**Version:** 1.0

**Grant:** EIC Pathfinder Open 2026
**Deadline:** 28 October 2026
**Total: ~€3,200,000 / 36 months
**TRL:** 1 → 3

---

## Concept

MCARA (Multi-Counter Architecture of Replicative Aging) — the hypothesis that stem cell aging is governed not by one but by multiple independent molecular counters. The key counter is the centriole.

**CEDAR (Centriolar Entropy-Driven Aging Registry):** the centriole accumulates irreversible damage — polyglutamylation (polyE, entropy marker) and remodels its signaling surface (CAMC — Centrosome-Associated Memory Complex), actively maintaining the differentiated state. During division, centrioles are inherited asymmetrically: old mother → stem cell, new daughter → differentiating cell.

**Central experiment — never conducted:** eliminate centrioles from somatic fibroblasts (p53-KO BJ + SB203580) prior to OSKM reprogramming and measure efficiency as % TRA-1-60+ colonies. If efficiency increases — the centriole is indeed a gatekeeper of cell state. If it drops — CEDAR is falsified in its current form.

---

## Three Work Packages

### WP1 — CEDAR: Theory and Design
- Centriolar Entropy-Driven Aging Registry — mathematical model
- 12-group design: elimination (centrinone, laser, CRISPR, GT335) × control (p53-/-, p38i, OSKM-only, vehicle)
- ≥1×10⁵ cells per group, ≥3 biological replicates
- Primary endpoint: % TRA-1-60+ colonies
- Statistics: FDR (Benjamini-Hochberg)
- WP1 budget: ~€600K

### WP2 — ARGUS-LP: Platform
- Open-source autonomous 24/7 fluorescence microscope (upright)
- 60×/1.2 Water Immersion, sCMOS, lasers 405/488/561 nm
- Hailo-8L AI acceleration, CellPose + spotiflow
- Marker: mEos3.2-CEP135
- Platform cost: €8,170 (v6)
- Licenses: GPLv3 / CC-BY-SA
- Engineering partner: Alex + TBD EU

### WP3 — MCARA Integration
- Integrated multi-component aging model (centrioles + mitochondria + epigenetics + tubulin code)
- Predictive model: which counters limit under which conditions
- Preclinical validation plan
- Go/no-go threshold: asymmetry > 10%

---

## Why EIC Pathfinder

**High risk:** centrioles may prove NECESSARY for reprogramming (falsification of CEDAR). Technical difficulty: laser ablation of single centrioles without cell damage.

**High reward:** if the hypothesis is correct — a new level of reprogramming control (organelle-level) opens up, with consequences for regenerative medicine, aging, and cancer.

**Readiness:** 15 rounds of concept review (9–10 Jul 2026), 60+ verified PMIDs, complete experimental design.

---

## GLA Laboratory — Abastumani

Non-residential space 50–60 m² (of 96 m² total) in the Abastumani research centre under construction.
Leased by GLA from a private owner at market rate. Eligible cost.
Market value: ~$21,600 (36 months) — eligible cost contribution to GLA budget.

Purpose:
- Wet-lab: cell culture (fibroblasts, iPSC), microscopy, sample preparation
- Dry-lab: simulation server (ISE pillar), data analysis
- Reagent and sample storage (−80°C, −20°C, +4°C)

---

## Consortium (target)

| Partner | Country | Role | Total: ~€3,200,000 (+ $21,600 eligible cost) | ✅ |
| Hartmut Geiger (Ulm) | 🇩🇪 Germany | HSC, in vivo validation | ~€400K | ✅ |
| Aleksandra Trifunovic (Cologne) | 🇩🇪 Germany | Mitochondrial counter | ~€300K | ✅ |
| Wolfgang Wagner (RWTH) | 🇩🇪 Germany | Epigenetic counter | ~€350K | 🟡 |
| Maria Magiera (Curie) | 🇫🇷 France | U-ExM / tubulin code | ~€350K | 🟡 |
| TBD (Open Hardware) | 🇪🇺 EU | WP2 engineering | ~€300K | 🔴 |

---

## Key References

- Tkemaladze 2023, PMID: 36583780 — CEDAR hypothesis
- Renzova et al. 2018, PMID: 30197118 — PLK4 inhibition → loss of pluripotency
- Kalbfuss & Gönczy 2023, PMID: 37256957 — 88% C. elegans eliminate centrioles
- Robichaud et al. 2024, PMID: 39266565 — Centrosome → senescence via MT arrays
- 60+ additional PMIDs — see `references/Centriole_Elimination_iPSC_Reprogramming_EN.md`

**GitHub:** https://github.com/Georgia-Longevity-Alliance/ERR

## Consumables (annual)

| **C. elegans maintenance** (NGM agar, OP50/NA22 bacteria, cholesterol, Petri dishes) | **$3,500** |
| **RNAi/strain maintenance** (clones, IPTG, antibiotics, feeding plates) | **$2,000** |
| **Cell culture** (DMEM/RPMI, FBS, pen/strep, trypsin, plastics) | **$8,000** |
| **CO₂ gas + incubator supplies** (cylinders, rental, HEPA filters) | **$3,000** |
| **Transfection reagents** (Lipofectamine, siRNA oligos) | **$3,000** |
| **Sequencing consumables** (library prep, flow cells) | **$12,000** |
| **Microscopy** (immersion oil, coverslips, lens cleaning) | **$2,000** |
| **Glove-box/Enclosure** (HEPA H13 filters, UV-C lamps, gloves, seals, N₂ gas) | **$8,000** |
| **Office consumables** (printing, stationery) | **$500** |


## Hypothesis

*To be specified — see CONCEPT.md §1 for project rationale.*


## References

| # | Reference | PMID |
|---|-----------|------|
| 1 | See parent project | — |
