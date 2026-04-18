# Research Paper Plan
## AI-Guided CRISPR-Cas9 with Radiation-Enhanced Homology-Directed Repair for Direct β-Globin Gene Correction in β-Thalassemia: A Conceptual Framework

---

## THE MERGED CONCEPT: WHY THIS IS STRONGER THAN EITHER IDEA ALONE

**Idea A (Casgevy/BCL11A approach):** CRISPR disrupts BCL11A enhancer → fetal hemoglobin reactivates → compensates for broken HBB. FDA-approved in 2023. Proven, powerful — but it is a *workaround*, not a cure. It does not fix the broken HBB gene.

**Idea B (AI + Radiation + CRISPR):** Use AI to design the guide RNA, use controlled low-dose radiation to prime the cell's own DNA repair machinery, use CRISPR to directly correct the HBB mutation via homology-directed repair (HDR).

**The merge:** Neither idea alone is complete. Together they form a two-layer argument:

- **Layer 1 (established baseline):** Casgevy proves that CRISPR can cure thalassemia — but through compensation. This is cited as proof of concept and as the current gold standard.
- **Layer 2 (the new contribution):** The next frontier is *direct* HBB correction, which requires HDR. HDR in hematopoietic stem cells (HSCs) is frustratingly inefficient (~1–8% in published studies). This paper proposes that controlled low-dose ionizing radiation — by activating ATM/ATR-mediated DNA damage response and pre-loading the RAD51/BRCA2 homologous recombination machinery — can increase HDR rates at Cas9 cut sites. AI selects the optimal guide RNA per patient mutation and models repair pathway choice, making the entire system precision-guided.

**Result:** A conceptual framework for a smarter, more efficient gene correction strategy that builds on established science, identifies a real gap, proposes a mechanistically grounded solution, and is honest about what remains to be tested.

---

## FULL PAPER TITLE

**AI-Guided CRISPR-Cas9 with Radiation-Enhanced Homology-Directed Repair for Direct β-Globin Gene Correction in β-Thalassemia: A Conceptual Framework**

**Short title:** Radiation-Primed Precision Gene Editing for β-Thalassemia

---

## SECTION-BY-SECTION PLAN

---

### ABSTRACT (write last, ~250 words)

**What to include:**
- Background sentence: β-thalassemia burden, HBB mutation, inadequacy of current CRISPR approach (compensatory, not corrective)
- Gap: HDR efficiency in HSCs is too low for clinical-grade direct correction
- Proposed solution: AI-guided gRNA selection + controlled low-dose radiation to prime ATM/ATR-HR pathway + CRISPR-Cas9 HDR
- Hypothesis statement (one sentence)
- Expected outcomes (brief)
- Significance for high-burden populations (Bangladesh context)

**APA note:** No citations in abstract.

---

### SECTION 1: INTRODUCTION (~600 words)

**Goal:** Establish the problem, identify the gap, state the objective.

**Paragraph 1 — The Disease**
Write: β-thalassemia is one of the most common monogenic disorders globally, caused by mutations in *HBB* on chromosome 11p15.5, resulting in deficient β-globin synthesis and transfusion-dependent anemia. Bangladesh carries a carrier rate of approximately 7%, placing it among the highest-burden nations worldwide.

**Cite:**
- Taher et al. (2021) — *Nature Reviews Disease Primers* — for global epidemiology and pathophysiology
- APA in-text: (Taher et al., 2021)

**Paragraph 2 — Current CRISPR Therapy: Proven but Incomplete**
Write: The 2023 FDA approval of exagamglogene autotemcel (Casgevy) established CRISPR gene therapy as a clinical reality for β-thalassemia. However, Casgevy does not correct the causative HBB mutation — it disrupts the BCL11A erythroid enhancer, reactivating fetal hemoglobin as a compensatory mechanism.

**Cite:**
- Frangoul et al. (2021) — *NEJM* — CLIMB trial results
- Zeng et al. (2020) — *Nature Medicine* — base editing of BCL11A enhancer in HSCs
- APA in-text: (Frangoul et al., 2021; Zeng et al., 2020)

**Paragraph 3 — The Gap: HDR Efficiency**
Write: Direct correction of the HBB mutation requires homology-directed repair (HDR), but HDR efficiency in human HSCs remains a critical bottleneck. Published studies report HDR rates of 1–8% under standard conditions, insufficient for clinical translation without cell selection protocols that compromise stem cell fitness.

**Cite:**
- Dever et al. (2016) — *Nature* — CRISPR/Cas9 HDR in HSCs, seminal paper
- Antony et al. (2018) — *Molecular and Cellular Pediatrics* — HBB correction with ssODN, ~8% HDR
- DeWitt et al. (2016) — *Science Translational Medicine* — selection-free HSC editing
- APA in-text: (Antony et al., 2018; Dever et al., 2016; DeWitt et al., 2016)

**Paragraph 4 — The Proposed Framework**
Write: This paper proposes an integrated conceptual framework combining three components: (1) artificial intelligence for patient-specific guide RNA optimization and off-target risk prediction; (2) low-dose ionizing radiation to activate ATM/ATR-mediated DNA damage response and pre-prime homologous recombination machinery; and (3) CRISPR-Cas9 with an HDR repair template for direct HBB mutation correction.

**Paragraph 5 — Objective Statement**
Write: The objective of this study is to propose, justify, and evaluate a conceptual framework in which controlled radiobiological priming enhances HDR-mediated CRISPR correction of HBB mutations in human HSCs, guided by AI-optimized editing parameters.

---

### SECTION 2: BACKGROUND (~900 words, 4 subsections)

#### 2.1 β-Thalassemia: Molecular Pathophysiology

**What to read and extract:**
- Read: Taher et al. (2021) — *Nat Rev Dis Primers* — full review of HBB mutations, ineffective erythropoiesis, iron overload, treatment
- Read: Butt et al. (2025) — *Molecular Therapy* — review of gene editing strategies for HBB, bench-to-bedside overview
- Extract: The >300 pathogenic HBB variants, classification (β⁰ vs β⁺), NHEJ vs HDR repair outcomes at the HBB locus, why direct correction is preferred over BCL11A workaround

**Write:** Cover HBB gene structure, types of mutations, downstream pathophysiology (α-chain imbalance → RBC destruction → anemia → iron overload → organ failure), and the case for curative vs compensatory therapy.

**Key APA citations:**
- (Butt et al., 2025)
- (Taher et al., 2021)

#### 2.2 CRISPR-Cas9 and the HDR Bottleneck in HSCs

**What to read and extract:**
- Read: Dever et al. (2016) — *Nature* — first demonstration of CRISPR HDR at HBB in HSCs; enrichment to >90% but only in edited fraction
- Read: Xie et al. (2014) — *Genome Research* — CRISPR + piggyBac in β-thal iPSCs; shows footprint-free correction is feasible
- Read: Yang et al. (2024) — *Frontiers in Cell and Developmental Biology* — universal HBB correction method using rAAV6 + HDR in HSCs, with engraftment data
- Read: Antony et al. (2018) — *Mol Cell Pediatr* — comparison of CRISPR vs TALENs vs ZFNs for HBB; CRISPR indel rate 87% in HSCs but HDR only ~8%
- Read: Wattanapanitch (2021) — *Methods in Mol Biology* — HDR efficiency in HbE/β-thal iPSCs only 3% with plasmid-based approach
- Read: Saboor et al. (2026) — *Hemoglobin* — bibliometric analysis of CRISPR thalassemia research trends

**Key finding to highlight:** The consistent finding across papers is that NHEJ dominates in HSCs — indel rates 60–90% but HDR rates 1–8%. This is because HSCs are predominantly quiescent (G0/G1), and HDR is restricted to S/G2 phases when a sister chromatid template is available. This is the mechanistic root of the problem.

**Write:** Explain CRISPR-Cas9 mechanism, the two competing repair pathways (NHEJ vs HDR), why HSCs favor NHEJ, and why this creates an efficiency ceiling for direct HBB correction.

**Key APA citations:**
- (Antony et al., 2018; Dever et al., 2016; Wattanapanitch, 2021; Xie et al., 2014; Yang et al., 2024)

#### 2.3 Next-Generation Editing: Prime Editing and Base Editing

**What to read and extract:**
- Read: Everette et al. (2023) — *Nature Biomedical Engineering* — ex vivo prime editing of HSCs for sickle cell disease; 15–41% correction at HBB, engraftment maintained
- Read: Zeng et al. (2020) — *Nature Medicine* — base editing of BCL11A enhancer in HSCs; clean edits, no indels
- Read: Butt et al. (2025) — same review — compare base editing, prime editing, and HDR approaches for HBB correction

**Key insight to extract:** Prime editing does not require DSBs and shows higher efficiency than traditional HDR (15–41% vs 1–8%). However, prime editing has its own efficiency constraints at specific loci and mutation types. Not all HBB mutations are efficiently correctable by prime editing (pegRNA design limits). Traditional HDR with Cas9 remains the most flexible direct correction approach but needs efficiency improvement.

**Write:** Contrast prime editing (no DSB needed, low indels, limited efficiency ceiling of ~40%) with traditional HDR (flexible for any mutation, but 1–8% efficiency in HSCs). Establish that for broadly applicable HBB correction, improving HDR efficiency is still necessary.

**Key APA citations:**
- (Everette et al., 2023; Zeng et al., 2020)

#### 2.4 AI in CRISPR Guide RNA Design

**What to read and extract:**
- Read: Chuai et al. (2018) — *Genome Biology* — DeepCRISPR; deep learning unifies on-target and off-target prediction; key: data-driven sequence and epigenetic feature extraction
- Read: Zhang et al. (2023) — *Briefings in Bioinformatics* — benchmarking 10 deep learning methods for sgRNA; key finding: large datasets perform well, small datasets are the challenge; most methods fail on imbalanced off-target datasets
- Read: Wessels et al. (2023) — *Nature Biotechnology* — TIGER model for Cas13d; ~200,000 guide RNAs tested; convolutional neural network for on-target and off-target prediction; position- and context-dependent mismatch effects
- Read: Marquart et al. (2024) — *Nature Methods* — deep learning for TnpBmax editing efficiency; TEEP model achieves r>0.8 predictive accuracy; 75.3% editing efficiency in murine liver

**Key insight to extract:** AI models can predict sgRNA activity, off-target risk, and editing efficiency from sequence context. The most powerful models (DeepCRISPR, TIGER, TEEP) use convolutional or transformer architectures trained on >10,000 guide-target pairs. These are applicable to HBB-targeting guides with proper training data. No published model has been specifically trained on HBB-targeting guides in HSCs — this is a gap the paper can identify.

**Write:** Explain how ML models work for guide design, what features they use (sequence, secondary structure, epigenetics, PAM context), current performance benchmarks, and the specific application to HBB targeting in HSCs.

**Key APA citations:**
- (Chuai et al., 2018; Marquart et al., 2024; Wessels et al., 2023; Zhang et al., 2023)

---

### SECTION 3: THE RADIATION-HDR CONNECTION (~700 words)

**This is the most novel and mechanistically critical section. Get this right.**

#### 3.1 Ionizing Radiation and the DNA Damage Response

**What to read and extract:**
- Read: Santivasi & Xia (2014) — *Antioxidants & Redox Signaling* — comprehensive review of ionizing radiation-induced DSBs, DDR signaling cascades (ATM/ATR/DNA-PKcs), cell cycle checkpoint activation, and repair pathway choice (HR vs NHEJ)
- Key extract: IR-induced DSBs activate ATM kinase → phosphorylates H2AX (γH2AX foci), CHK2, p53 → cell cycle arrest and recruitment of repair factors. NHEJ repairs DSBs rapidly throughout cell cycle; HDR operates specifically in S/G2 and requires end resection mediated by CtIP and the MRN complex.
- Read: Groelly et al. (2023) — *Nature Reviews Cancer* — targeting DDR pathways in cancer; covers BRCA1/2 roles, ATM signaling, synthetic lethality; critical for understanding the HR machinery at the molecular level
- Read: Roy et al. (2012) — *Nature Reviews Cancer* — BRCA1 and BRCA2 roles in HR; BRCA2 loads RAD51 filaments onto ssDNA; BRCA1 promotes end resection — the two rate-limiting steps of HDR
- Read: Zhou et al. (2024) — *Drug Resistance Updates* — ATM-Syk-CtIP pathway; shows ATM activates CtIP phosphorylation at Thr-847 to promote resection and HDR; important mechanistic detail

**Key argument to build:** Low-dose radiation → ATM activation → CtIP/BRCA1-mediated resection → RAD51/BRCA2 loading → HR-favorable chromatin state. If a Cas9 DSB is introduced *after* this state is established, the cellular environment is biased toward using the HDR template rather than NHEJ for repair.

**Write:** Explain ATM/ATR signaling in response to radiation-induced DSBs, the molecular steps of HR initiation (resection → RPA → RAD51 filament), and why a pre-activated HR state could increase HDR efficiency at a Cas9 cut site.

**Key APA citations:**
- (Groelly et al., 2023; Roy et al., 2012; Santivasi & Xia, 2014; Zhou et al., 2024)

#### 3.2 Rationale for Low-Dose Radiation as a Priming Agent

**What to write (based on known biology + the papers above):**
The key conceptual distinction: radiation is NOT being proposed as a therapeutic — it is proposed as a *biological conditioning agent* applied to HSCs ex vivo before CRISPR editing. This parallels the use of busulfan conditioning before HSC transplantation, but at a fraction of the dose and for a different mechanistic purpose.

**Specific arguments:**
1. HDR is cell-cycle restricted: HSCs are mostly quiescent (G0). Any strategy that transiently shifts cells into S/G2 or activates the S/G2-associated repair machinery creates an HDR-permissive window.
2. Low-dose radiation (sub-lethal, <0.5 Gy range) can activate ATM without causing catastrophic genome damage. The NET effect in a short ex vivo window needs experimental validation — this is the hypothesis.
3. The timing is critical: radiation → wait ~2–4 hours for HR machinery priming → deliver Cas9 RNP + HDR template → edit during the HDR-permissive window.
4. Risk: radiation dose must be precisely calibrated. Too low: no effect. Too high: genomic instability, apoptosis. This is the primary experimental question.

**Write:** Present this as a conceptual bridge, explicitly acknowledge the unproven nature, and frame it as a testable hypothesis.

**Key APA citations:**
- (Groelly et al., 2023; Roy et al., 2012; Santivasi & Xia, 2014)

---

### SECTION 4: HYPOTHESIS (~200 words)

**The formal hypothesis (write this exactly):**

*"We hypothesize that controlled ex vivo exposure of human hematopoietic stem and progenitor cells to ultra-low-dose ionizing radiation (0.1–0.5 Gy) will transiently activate ATM-mediated DNA damage response signaling, increasing RAD51 foci formation and homology-directed repair activity at Cas9-induced double-strand breaks in the HBB locus. Combined with AI-optimized guide RNA selection, this integrated approach will achieve significantly higher rates of precise HBB mutation correction compared to standard CRISPR-Cas9 HDR protocols, without compromising HSPC viability, self-renewal capacity, or genomic stability."*

**Null hypothesis:**
*"Low-dose ionizing radiation pre-treatment does not significantly alter the HDR/NHEJ ratio at Cas9-induced DSBs in human HSPCs under ex vivo conditions."*

**Why this is testable:** Measurable endpoints — HDR/NHEJ ratio by next-generation sequencing, RAD51 foci quantification by immunofluorescence, γH2AX kinetics by flow cytometry, HSPC viability by colony-forming assays, engraftment by xenograft (NSG mice).

---

### SECTION 5: PROPOSED METHODOLOGY (~800 words)

**This section exists as a CONCEPTUAL DESIGN — not an executed experiment.**

#### Step 1: Cell Model Selection
- Primary: Patient-derived HSPCs (CD34+) from β-thalassemia donors with characterized HBB mutations
- Secondary model: K562 erythroleukemia cell line (for initial dose optimization experiments)
- Controls: Unirradiated HSPC + Cas9 (standard CRISPR); irradiated HSPC without Cas9 (radiation-only); non-edited HSPC (negative)

#### Step 2: Radiation Dose Optimization Protocol
- Expose K562 cells and HSPCs to doses: 0.1, 0.25, 0.5, 1.0, 2.0 Gy gamma radiation (Cs-137 or X-ray source)
- At each dose: measure ATM phosphorylation (pATM Ser1981), γH2AX foci, RAD51 foci, and cell viability (Annexin V) at 0.5h, 1h, 2h, 4h, 8h post-irradiation
- Select the dose-time combination that maximizes RAD51 foci (HDR activation proxy) while maintaining >80% cell viability
- This establishes the "priming window" — the time period of maximum HR activation before cells repair IR-induced damage

#### Step 3: AI-Guided gRNA Design
- Input: Patient-specific HBB mutation sequence (genotyped by Sanger sequencing)
- Tool: DeepCRISPR (Chuai et al., 2018) or CRISPOR/CHOPCHOP for candidate gRNA generation; secondary filtering by TIGER (Wessels et al., 2023) for on-target efficacy scoring
- Output: Top 3 ranked gRNAs per patient mutation, ranked by: (a) predicted on-target cleavage efficiency, (b) off-target profile (genome-wide GUIDE-seq or computational prediction), (c) proximity to mutation site for HDR
- HDR template design: 200-bp single-stranded oligonucleotide donor (ssODN) or rAAV6 vector carrying corrective sequence with homology arms flanking the Cas9 cut site

#### Step 4: Integrated Editing Protocol
1. Mobilize and collect CD34+ HSPCs from patient via plerixafor-based apheresis
2. Culture cells briefly (48h) to allow proliferation entry (increases S/G2 fraction)
3. Apply optimized radiation dose (from Step 2)
4. Wait for priming window (e.g., 2h post-radiation)
5. Deliver Cas9 RNP + ssODN or rAAV6 donor by electroporation
6. Rest cells for 48–72h, then proceed to analysis or transplantation preparation

#### Step 5: Outcome Assessment
- **Primary outcome:** HDR rate at HBB locus (amplicon deep sequencing: Illumina MiSeq, >10,000x coverage)
- **Secondary outcomes:**
  - NHEJ/indel rate at on-target site
  - Off-target editing at AI-predicted risk sites (GUIDE-seq)
  - RAD51 foci by immunofluorescence
  - HSPC colony-forming capacity (CFU-C assay)
  - β-globin expression in erythroid progeny (RT-qPCR, HPLC)
  - Engraftment in NSG mice (16-week xenograft)

#### Comparison Groups (the key table for the paper)

| Condition | Expected HDR Rate | Rationale |
|---|---|---|
| Standard CRISPR (no radiation, no AI) | 1–8% | Literature baseline |
| AI-optimized gRNA only | 5–15% (estimated) | Better targeting = better efficiency |
| Radiation pre-treatment only | Unknown (hypothesis: 10–20%) | DDR priming hypothesis |
| AI + Radiation (proposed model) | Hypothesis: 20–40% | Synergistic enhancement |
| Prime editing (comparator) | 15–41% | Everette et al. (2023) |

---

### SECTION 6: EXPECTED OUTCOMES AND SIGNIFICANCE (~400 words)

**Write:**
If the hypothesis holds, AI-guided radiation-primed CRISPR-Cas9 HDR would:
- Achieve clinically significant HBB correction rates (>20%) in patient HSCs without viral integration
- Reduce dependence on cell selection post-editing, preserving stem cell fitness
- Enable a mutation-specific precision approach applicable to all HBB variants (unlike BCL11A editing, which works regardless of mutation)
- Provide a framework applicable to other monogenic diseases where HDR efficiency is rate-limiting

**Significance for Bangladesh and South Asia:**
Direct HBB correction, if achievable at sufficient efficiency, offers a true biological cure rather than a compensatory workaround — and with autologous cells, eliminates the need for matched donors that most South Asian patients cannot find (Dever et al., 2016).

---

### SECTION 7: LIMITATIONS (~300 words)

**Be brutally honest. Judges and reviewers respect honesty more than false confidence.**

1. **The radiation-HDR hypothesis is unproven.** No published study demonstrates that low-dose IR pre-treatment increases Cas9-mediated HDR in human HSPCs. This paper is a conceptual proposal requiring experimental validation.

2. **Cell-cycle challenge.** HSCs are predominantly quiescent. Brief culture and radiation may not be sufficient to shift a meaningful fraction into S/G2. G2/M synchronization agents (e.g., nocodazole) may be necessary and carry their own risks.

3. **Radiation-induced genomic instability.** Even sub-lethal radiation doses induce DSBs throughout the genome. In HSCs that will reconstitute a patient's entire hematopoietic system for decades, any radiation-induced mutation has the potential for clonal expansion. This requires rigorous whole-genome sequencing in engrafted animals.

4. **AI model generalizability.** Existing deep learning models (DeepCRISPR, TIGER) were trained on data from non-HSC cell lines. Their predictions may not accurately reflect guide RNA efficiency and off-target rates in primary HSCs with a different chromatin landscape.

5. **Radiation dose calibration.** The therapeutic window between "HDR priming" and "genomic damage" is unknown and likely narrow. Precise dosimetry and standardized ex vivo irradiation protocols would require specialized radiobiology infrastructure not available in most gene therapy labs.

**Cite:** (Antony et al., 2018; Santivasi & Xia, 2014; Zhang et al., 2023) for corresponding limitation context.

---

### SECTION 8: FUTURE DIRECTIONS (~300 words)

1. **In vitro validation:** Test the radiation-priming protocol in K562 → then CD34+ HSPCs → measure HDR rates by deep sequencing
2. **Mechanistic validation:** Quantify RAD51, BRCA2, γH2AX, 53BP1 foci at multiple time points to confirm DDR priming state corresponds to increased HDR
3. **Cell-cycle integration:** Combine radiation priming with transient cell cycle manipulation (CDK1 inhibitor or hydroxyurea) to maximize S/G2 fraction
4. **AI model re-training:** Collect >1,000 guide RNA efficiency measurements specifically at the HBB locus in primary HSPCs; retrain DeepCRISPR or a transformer-based model on this data
5. **Expansion to other hemoglobinopathies:** Sickle cell disease (same locus, different mutation — same framework applies)
6. **In vivo radiation delivery:** If ex vivo results are positive, explore targeted nanoparticle-based radiomimetic agents (e.g., PARP inhibitors, ATM activators) to avoid actual radiation entirely while mimicking the DDR priming effect — this would be the eventual clinical path

---

### SECTION 9: CONCLUSION (~200 words)

**Write:**
β-thalassemia is curable. Casgevy has proven that CRISPR can do it. But the compensatory strategy has a ceiling — it does not restore normal hemoglobin biology. The next frontier is direct HBB correction, and the primary obstacle is HDR efficiency in quiescent HSCs.

This paper proposes that controlled radiobiological priming of the ATM/ATR-HR pathway, guided by AI-optimized CRISPR design, represents a scientifically grounded strategy to close this efficiency gap. If validated, it would convert a frustratingly marginal process (~8% HDR) into a clinically translatable one. The biological principles are sound. The mechanistic connections are established in the literature. The hypothesis is specific and testable. What remains is the experiment.

For Bangladesh and the 14,000 children born annually with thalassemia major in South Asia, the implications are not abstract. Every percentage point of improvement in HDR efficiency is a step toward a cure that is genuinely curative, not compensatory.

---

## REFERENCE LIST (APA 7th Edition)

*Note: All papers marked [PubMed verified] were retrieved from PubMed and DOIs confirmed. Papers marked [training knowledge] are widely cited landmark papers whose DOIs are well-established but were not directly retrieved in this search session.*

---

Antony, J. S., Latifi, N., Haque, A. K. M. A., Lamsfus-Calle, A., Daniel-Moreno, A., Graeter, S., Baskaran, P., Weinmann, P., Mezger, M., Handgretinger, R., & Kormann, M. S. D. (2018). Gene correction of HBB mutations in CD34+ hematopoietic stem cells using Cas9 mRNA and ssODN donors. *Molecular and Cellular Pediatrics*, *5*(1), 9. https://doi.org/10.1186/s40348-018-0086-1 [PubMed verified]

Anzalone, A. V., Randolph, P. B., Davis, J. R., Sousa, A. A., Koblan, L. W., Levy, J. M., Chen, P. J., Wilson, C., Newby, G. A., Raguram, A., & Liu, D. R. (2019). Search-and-replace genome editing without double-strand breaks or donor DNA. *Nature*, *576*(7785), 149–157. https://doi.org/10.1038/s41586-019-1711-4 [training knowledge — Nature landmark]

Butt, H., Sathish, S., London, E., Lee Johnson, T., Essawi, K., Leonard, A., Tisdale, J. F., & Demirci, S. (2025). Genome editing strategies for targeted correction of β-globin mutation in sickle cell disease: From bench to bedside. *Molecular Therapy*, *33*(5), 2154–2171. https://doi.org/10.1016/j.ymthe.2025.03.047 [PubMed verified]

Chuai, G., Ma, H., Yan, J., Chen, M., Hong, N., Xue, D., Zhou, C., Zhu, C., Chen, K., Duan, B., Gu, F., Qu, S., Huang, D., Wei, J., & Liu, Q. (2018). DeepCRISPR: Optimized CRISPR guide RNA design by deep learning. *Genome Biology*, *19*(1), 80. https://doi.org/10.1186/s13059-018-1459-4 [PubMed verified]

Dever, D. P., Bak, R. O., Reinisch, A., Camarena, J., Washington, G., Nicolas, C. E., Pavel-Dinu, M., Saxena, N., Wilkens, A. B., Mantri, S., Uchida, N., Hendel, A., Narla, A., Majeti, R., Weinberg, K. I., & Porteus, M. H. (2016). CRISPR/Cas9 β-globin gene targeting in human haematopoietic stem cells. *Nature*, *539*(7629), 384–389. https://doi.org/10.1038/nature20134 [PubMed verified]

DeWitt, M. A., Magis, W., Bray, N. L., Wang, T., Berman, J. R., Urbinati, F., Heo, S. J., Mitros, T., Muñoz, D. P., Boffelli, D., Kohn, D. B., Walters, M. C., Carroll, D., Martin, D. I. K., & Corn, J. E. (2016). Selection-free genome editing of the sickle mutation in human adult hematopoietic stem/progenitor cells. *Science Translational Medicine*, *8*(360), 360ra134. https://doi.org/10.1126/scitranslmed.aaf9336 [PubMed verified]

Everette, K. A., Newby, G. A., Levine, R. M., Mayberry, K., Jang, Y., Mayuranathan, T., Nimmagadda, N., Dempsey, E., Li, Y., Bhoopalan, S. V., Liu, X., Davis, J. R., Nelson, A. T., Chen, P. J., Sousa, A. A., Cheng, Y., Tisdale, J. F., Weiss, M. J., Yen, J. S., & Liu, D. R. (2023). Ex vivo prime editing of patient haematopoietic stem cells rescues sickle-cell disease phenotypes after engraftment in mice. *Nature Biomedical Engineering*, *7*(5), 616–628. https://doi.org/10.1038/s41551-023-01026-0 [PubMed verified]

Frangoul, H., Altshuler, D., Cappellini, M. D., Chen, Y. S., Domm, J., Eustace, B. K., Foell, J., de la Fuente, J., Grupp, S., Handgretinger, R., Ho, T. W., Kattamis, A., Kernytsky, A., Lekstrom-Himes, J., Li, A. M., Locatelli, F., Mapara, M. Y., de Montalembert, M., Rondelli, D., … Corbacioglu, S. (2021). CRISPR-Cas9 gene editing for sickle cell disease and β-thalassemia. *New England Journal of Medicine*, *384*(3), 252–260. https://doi.org/10.1056/NEJMoa2031054 [training knowledge — NEJM landmark]

Groelly, F. J., Fawkes, M., Dagg, R. A., Blackford, A. N., & Tarsounas, M. (2023). Targeting DNA damage response pathways in cancer. *Nature Reviews Cancer*, *23*(2), 78–94. https://doi.org/10.1038/s41568-022-00535-5 [PubMed verified]

Jinek, M., Chylinski, K., Fonfara, I., Hauer, M., Doudna, J. A., & Charpentier, E. (2012). A programmable dual-RNA-guided DNA endonuclease in adaptive bacterial immunity. *Science*, *337*(6096), 816–821. https://doi.org/10.1126/science.1225829 [training knowledge — foundational CRISPR paper]

Komor, A. C., Kim, Y. B., Packer, M. S., Zuris, J. A., & Liu, D. R. (2016). Programmable editing of a target base in genomic DNA without double-stranded DNA cleavage. *Nature*, *533*(7603), 420–424. https://doi.org/10.1038/nature17946 [training knowledge — base editing]

Marquart, K. F., Mathis, N., Mollaysa, A., Müller, S., Kissling, L., Rothgangl, T., Schmidheini, L., Kulcsár, P. I., Allam, A., Kaufmann, M. M., Matsushita, M., Haenggi, T., Cathomen, T., Kopf, M., Krauthammer, M., & Schwank, G. (2024). Effective genome editing with an enhanced ISDra2 TnpB system and deep learning-predicted ωRNAs. *Nature Methods*, *21*(11), 2084–2093. https://doi.org/10.1038/s41592-024-02418-z [PubMed verified]

Roy, R., Chun, J., & Powell, S. N. (2012). BRCA1 and BRCA2: Different roles in a common pathway of genome protection. *Nature Reviews Cancer*, *12*(1), 68–78. https://doi.org/10.1038/nrc3181 [PubMed verified]

Saboor, M., Jasem Alblooshi, M., Adel Alkaabi, A., Ramazan Soozaei, F., & Hamad Alketbi, M. (2026). CRISPR in thalassemia: Global research trend analysis. *Hemoglobin*, *50*(2), 141–155. https://doi.org/10.1080/03630269.2026.2634815 [PubMed verified]

Sankaran, V. G., & Orkin, S. H. (2013). The switch from fetal to adult hemoglobin. *Cold Spring Harbor Perspectives in Medicine*, *3*(1), a011643. https://doi.org/10.1101/cshperspect.a011643 [training knowledge — HbF switch review]

Santivasi, W. L., & Xia, F. (2014). Ionizing radiation-induced DNA damage, response, and repair. *Antioxidants & Redox Signaling*, *21*(2), 251–259. https://doi.org/10.1089/ars.2013.5668 [PubMed verified]

Taher, A. T., Musallam, K. M., & Cappellini, M. D. (2021). β-thalassaemias. *New England Journal of Medicine*, *384*(8), 727–743. https://doi.org/10.1056/NEJMra2024028 [training knowledge — NEJM review]

Wattanapanitch, M. (2021). Correction of hemoglobin E/beta-thalassemia patient-derived iPSCs using CRISPR/Cas9. In M. Wattanapanitch (Ed.), *Methods in molecular biology* (Vol. 2211, pp. 193–211). Humana Press. https://doi.org/10.1007/978-1-0716-0943-9_14 [PubMed verified]

Wessels, H. H., Stirn, A., Méndez-Mancilla, A., Kim, E. J., Hart, S. K., Knowles, D. A., & Sanjana, N. E. (2023). Prediction of on-target and off-target activity of CRISPR-Cas13d guide RNAs using deep learning. *Nature Biotechnology*, *42*(4), 628–637. https://doi.org/10.1038/s41587-023-01830-8 [PubMed verified]

Xie, F., Ye, L., Chang, J. C., Beyer, A. I., Wang, J., Muench, M. O., & Kan, Y. W. (2014). Seamless gene correction of β-thalassemia mutations in patient-specific iPSCs using CRISPR/Cas9 and piggyBac. *Genome Research*, *24*(9), 1526–1533. https://doi.org/10.1101/gr.173427.114 [PubMed verified]

Yang, Y., He, L., Xie, Y., Zhu, L., Wu, J., Fan, Y., Yang, Y., & Sun, X. (2024). Correction of various β-thalassemia mutations in human hematopoietic stem cells. *Frontiers in Cell and Developmental Biology*, *11*, 1276890. https://doi.org/10.3389/fcell.2023.1276890 [PubMed verified]

Zeng, J., Wu, Y., Ren, C., Bonanno, J., Shen, A. H., Shea, D., Gehrke, J. M., Clement, K., Luk, K., Yao, Q., Kim, R., Wolfe, S. A., Manis, J. P., Pinello, L., Joung, J. K., & Bauer, D. E. (2020). Therapeutic base editing of human hematopoietic stem cells. *Nature Medicine*, *26*(4), 535–541. https://doi.org/10.1038/s41591-020-0790-y [PubMed verified]

Zhang, G., Luo, Y., Dai, X., & Dai, Z. (2023). Benchmarking deep learning methods for predicting CRISPR/Cas9 sgRNA on- and off-target activities. *Briefings in Bioinformatics*, *24*(6). https://doi.org/10.1093/bib/bbad333 [PubMed verified]

Zhou, Q., Tu, X., Hou, X., Yu, J., Zhao, F., Huang, J., Kloeber, J., Olson, A., Gao, M., Luo, K., Zhu, S., Wu, Z., Zhang, Y., Sun, C., Zeng, X., Schoolmeester, K. J., Weroha, J. S., Hu, X., Jiang, Y., Wang, L., Mutter, R. W., & Lou, Z. (2024). Syk-dependent homologous recombination activation promotes cancer resistance to DNA targeted therapy. *Drug Resistance Updates*, *74*, 101085. https://doi.org/10.1016/j.drup.2024.101085 [PubMed verified]

---

## WRITING SEQUENCE (do this in order)

1. **Read all papers** — Start with Santivasi & Xia (2014) for radiation biology, Dever et al. (2016) for the HDR baseline, Chuai et al. (2018) for AI foundation
2. **Write Section 2.3 first** — The HDR bottleneck. This is the core problem. Once you can articulate why HDR fails in HSCs, the rest flows.
3. **Write Section 3** — The radiation-HDR connection. This is your novel contribution. Be precise, be mechanistic, be honest about what is proven vs hypothesized.
4. **Write Section 4** — The hypothesis. One paragraph. One testable claim. Do not dilute it.
5. **Write Section 5** — Methodology. Tables and numbered steps. Clear. Specific.
6. **Write Sections 1 and 2** — Introduction and background. These reference everything you wrote in 2–5.
7. **Write Section 6, 7, 8** — Outcomes, limitations, future directions.
8. **Write Section 9** — Conclusion.
9. **Write Abstract** — Last. Compress everything into 250 words.
10. **Format references** — APA 7th, alphabetical, DOIs as hyperlinks.

---

## APA 7TH IN-TEXT CITATION QUICK REFERENCE

| Situation | Format |
|---|---|
| 1 author | (Santivasi, 2014) |
| 2 authors | (Roy & Powell, 2012) |
| 3+ authors | (Dever et al., 2016) |
| Multiple citations in one bracket | (Antony et al., 2018; Dever et al., 2016; DeWitt et al., 2016) — alphabetical |
| Author mentioned in sentence | Dever et al. (2016) demonstrated that… |
| Direct quote | (Chuai et al., 2018, p. 3) |
| Secondary source | As cited in Butt et al. (2025) — avoid where possible |

---

*Plan prepared based on articles retrieved from PubMed. All PubMed-verified references include confirmed DOIs. [training knowledge] references are landmark papers with established DOIs from published record.*
