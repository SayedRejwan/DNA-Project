# Rewriting Fate: CRISPR-Cas9-Mediated Reactivation of Fetal Hemoglobin as a Curative Strategy for Beta-Thalassemia — Mechanism, Clinical Evidence, and Implications for High-Burden Populations

*World DNA Day Poster Competition 2026 · Extended Scientific Documentation*
*BRAC University Society for Biotechnology (BUSB) · Theme: Genetic Disorder & Medication*

---

## Abstract

Beta-thalassemia is a monogenic hemoglobin disorder arising from over 300 documented pathogenic variants in the *HBB* gene (chromosome 11p15.5), resulting in deficient or absent beta-globin chain synthesis and severe transfusion-dependent anemia. Conventional management — lifelong blood transfusions, iron chelation, and the rare option of allogeneic hematopoietic stem cell transplantation (HSCT) — addresses symptoms without correcting the underlying genetic defect, and remains practically inaccessible to the majority of patients in low- and middle-income countries. In December 2023, the United States Food and Drug Administration (FDA), the European Medicines Agency (EMA), and the UK Medicines and Healthcare products Regulatory Agency (MHRA) concurrently approved exagamglogene autotemcel (exa-cel; Casgevy™) — the world's first CRISPR-Cas9-based gene therapy for any disease. Rather than repairing the defective *HBB* gene, the therapy exploits a deeply conserved biological mechanism: by precisely disrupting the erythroid-specific enhancer of *BCL11A* — a transcriptional repressor that silences fetal hemoglobin (HbF) production after birth — CRISPR-edited autologous hematopoietic stem cells permanently reactivate the fetal hemoglobin pathway in all descendent red blood cells. In the pivotal Phase 3 CLIMB-Thal-111 trial (NCT03655678; *N Engl J Med*, 2024), 93% of treated patients (48/52) achieved transfusion independence for ≥12 consecutive months, with a median total hemoglobin of 13.1 g/dL and effects durable at the longest follow-up of 48 months. No off-target editing events were detected by deep sequencing. This paper examines the molecular pathophysiology of beta-thalassemia, the mechanistic elegance of the BCL11A-targeting CRISPR approach, the manufacturing and clinical execution of exa-cel, the trial evidence supporting regulatory approval, and the imperative — both preventive and therapeutic — for high-burden populations, with particular focus on Bangladesh, where approximately 7% of the population carries a pathogenic *HBB* allele.

**Keywords:** beta-thalassemia, CRISPR-Cas9, fetal hemoglobin, BCL11A erythroid enhancer, gene therapy, exagamglogene autotemcel, Casgevy, hemoglobinopathy, hematopoietic stem cells, Bangladesh

---

## 1. Introduction

Hemoglobin disorders are the most prevalent class of monogenic disease worldwide, affecting an estimated 7% of the global population as carriers and imposing catastrophic clinical burdens on those born with severe homozygous or compound heterozygous forms. Beta-thalassemia, arising from over 300 documented pathogenic variants in the *HBB* gene on chromosome 11p15.5, disrupts the synthesis of the β-globin subunit of adult hemoglobin (HbA, α₂β₂). The resultant imbalance between alpha- and beta-globin chains drives precipitation of excess α-chains within developing erythroid cells, generating reactive oxygen species that trigger apoptosis of red cell precursors before they complete maturation — a process termed ineffective erythropoiesis [1,2]. In its most severe form — thalassemia major, or Cooley's anemia — patients require packed red blood cell transfusions every two to four weeks from infancy to sustain life, while each transfused unit deposits approximately 200–250 mg of iron that the body cannot excrete, inevitably producing iron overload cardiomyopathy, hepatic cirrhosis, and endocrine failure [3].

The global burden is concentrated where it is least resourced. Approximately 1.5% of the world population carries a pathogenic *HBB* allele, with the highest frequencies in the Mediterranean basin, the Middle East, the Indian subcontinent, and Southeast Asia — geographic regions where the heterozygous carrier state historically conferred partial resistance to *Plasmodium falciparum* malaria, enriching the frequency of thalassemia alleles through natural selection [4]. In Bangladesh, carrier frequency reaches approximately 7%, placing it among the highest-burden nations globally [5]. An estimated 14,000 or more thalassemia major births occur annually across South Asia, the majority in settings where sustained transfusion programs, iron chelation drugs, and specialist haematological care are absent or intermittent — meaning that many children who could be kept alive with adequate treatment simply die without it [6].

Prior to 2023, the only genuinely curative intervention was allogeneic haematopoietic stem cell transplantation (HSCT). Though effective when performed with a matched sibling donor in young patients before organ damage accumulates, HSCT is constrained by three barriers that collectively exclude the vast majority of patients: donor availability (fewer than 30% of patients find an HLA-compatible sibling), transplant-related morbidity including graft-versus-host disease (GvHD), and cost that renders the procedure categorically inaccessible in low- and middle-income country settings [7]. Lentiviral gene therapy approaches — most notably betibeglogene spartacus (beti-cel; Zynteglo™), approved conditionally in 2022 — introduce a functional *HBB* transgene via semi-random genomic integration, raising theoretical insertional mutagenesis concerns that do not apply to precision genome editing strategies [8].

Against this landscape, CRISPR-Cas9 genome editing offered a therapeutically and intellectually distinct approach: rather than inserting a corrective transgene or attempting to repair the mutated *HBB* gene directly, it exploits a developmental biological truth — that the human genome already encodes a functional oxygen-carrying hemoglobin, HbF, which is simply suppressed postnatally by a transcriptional regulatory switch. Disabling that switch permanently, in the patient's own hematopoietic stem cells, would re-engage a compensatory mechanism that nature itself demonstrated is sufficient to sustain healthy life. The December 2023 FDA, EMA, and MHRA approval of exagamglogene autotemcel (exa-cel; Casgevy™), developed jointly by Vertex Pharmaceuticals and CRISPR Therapeutics, represents the regulatory validation of this logic — the first CRISPR-based medicine approved anywhere in history, and a genuine paradigm shift in the therapeutic approach to monogenic disease [9].

This paper synthesizes the molecular pathophysiology of beta-thalassemia, the mechanistic rationale for targeting BCL11A's erythroid enhancer, the manufacturing and clinical execution of exa-cel, the Phase 3 trial evidence underlying regulatory approval, and the implications — immediate and prospective — for high-burden populations, with particular attention to Bangladesh where the epidemiological burden demands urgent policy action even as the curative technology now exists.

---

## 2. Molecular Pathophysiology of Beta-Thalassemia

### 2.1 The HBB Gene and Globin Chain Biology

Adult hemoglobin (HbA) is a tetramer composed of two alpha-globin chains (encoded by *HBA1* and *HBA2* on chromosome 16) and two beta-globin chains (encoded by *HBB* on chromosome 11). The beta-globin locus control region (LCR), located 5' to the gene cluster on chromosome 11, orchestrates the developmental switch from embryonic (ε) to fetal (γ, encoded by *HBG1/HBG2*) to adult (β and δ) globin expression through long-range chromatin interactions [10].

More than 300 pathogenic variants in *HBB* cause beta-thalassemia, classified by their molecular mechanism and clinical severity. The most common include:

- **Beta⁰ mutations** (e.g., codon 39 C→T, IVS-I-1 G→T): complete absence of beta-globin synthesis; homozygosity causes thalassemia major requiring transfusion from the first year of life.
- **Beta⁺ mutations** (e.g., IVS-I-110 G→A): severely reduced but not absent beta-globin synthesis; compound heterozygosity with beta⁰ alleles typically causes transfusion-dependent disease.

### 2.2 Pathophysiology: From Gene Mutation to Organ Damage

In thalassemia major, the profound reduction in beta-globin production leaves excess free alpha-globin chains without binding partners. Unpaired alpha-chains are chemically reactive; they precipitate within developing red blood cells, generating reactive oxygen species (ROS), oxidizing membrane proteins, and causing cellular damage that triggers apoptosis of erythroid precursors within the bone marrow — a process termed ineffective erythropoiesis [11].

The consequences cascade:

1. **Anemia and tissue hypoxia:** Destruction of erythroid precursors before maturation reduces the circulating red cell mass. The resulting anemia is severe (hemoglobin often <7 g/dL without transfusion), causing systemic oxygen deficit.

2. **Erythroid expansion and skeletal deformity:** Compensatory bone marrow hyperplasia occupies medullary and extramedullary spaces, expanding the cortical bone (producing the characteristic "chipmunk" craniofacial appearance and "hair-on-end" skull radiograph) and forming erythropoietic masses in the liver, spleen, and paraspinal tissues.

3. **Splenomegaly:** Extramedullary hematopoiesis in the spleen, combined with sequestration and destruction of damaged red cells, produces progressive splenomegaly. Hypersplenism compounds anemia and increases transfusion requirements.

4. **Iron overload:** Each unit of packed red blood cells introduces approximately 200–250 mg of iron. The human body has no regulated mechanism for iron excretion. Iron accumulates in the myocardium (causing arrhythmias and dilated cardiomyopathy, the leading cause of death), liver (causing fibrosis and cirrhosis), endocrine glands (causing hypogonadism, diabetes mellitus, hypothyroidism, and hypoparathyroidism), and skin (producing bronze discoloration) [3].

5. **Death:** Without treatment, thalassemia major is uniformly fatal in childhood from cardiac failure or infection. With optimal transfusion and chelation, life expectancy extends to the fourth or fifth decade, though with significant morbidity burden.

### 2.3 Fetal Hemoglobin: A Natural Compensatory Mechanism

Fetal hemoglobin (HbF) is a developmentally regulated hemoglobin tetramer consisting of two alpha-globin chains and two gamma-globin chains (α₂γ₂). *HBG1* and *HBG2* — the genes encoding gamma-globin — are members of the beta-globin gene cluster on chromosome 11 and are highly expressed throughout fetal development, producing HbF that constitutes more than 90% of total hemoglobin at birth [12].

Critically, HbF can carry oxygen with comparable efficiency to HbA. Patients with hereditary persistence of fetal hemoglobin (HPFH) — genetic variants that prevent the developmental silencing of *HBG* genes — who also carry beta-thalassemia mutations are clinically asymptomatic or only mildly anemic, because HbF compensates entirely for the absent or deficient HbA [13]. This natural experiment has been recognized since the 1980s as proof-of-concept that re-engaging fetal hemoglobin production could cure thalassemia. The therapeutic challenge was: how to permanently re-engage it.

---

## 3. The BCL11A Switch: Molecular Logic of the CRISPR Approach

### 3.1 Discovery of BCL11A as the Fetal-to-Adult Hemoglobin Switch

The molecular identity of the switch governing HbF silencing remained elusive until 2008, when genome-wide association studies (GWAS) identified single-nucleotide polymorphisms (SNPs) in an intergenic region on chromosome 2p16 as the strongest predictor of naturally high HbF levels in adults [14]. The gene at this locus, *BCL11A* (B-cell lymphoma/leukemia 11A), had been characterized as a transcription factor involved in B-lymphocyte development — its role in erythroid biology was entirely unexpected.

Subsequent mechanistic work established that BCL11A is a sequence-specific transcriptional repressor that directly binds to the promoters of *HBG1* and *HBG2*, silencing fetal hemoglobin production in adult erythroid cells [15]. The SNPs associated with high HbF disrupt a binding motif for GATA1 and TAL1 within an erythroid-specific transcriptional enhancer at the +58 kb region of *BCL11A*. Without this enhancer activity, BCL11A is not expressed in erythroid cells — and without BCL11A repression, the fetal globin genes remain active.

The therapeutic target was thus defined: destroy the erythroid-specific BCL11A enhancer → prevent BCL11A expression in red blood cells → fetal hemoglobin remains permanently ON → HbF compensates for deficient HbA.

The elegance of this approach is that it exploits a lineage-specific regulatory element. BCL11A expression in non-erythroid tissues — including B lymphocytes, where it performs essential developmental functions — is driven by separate enhancers and remains unaffected. The edit is erythroid-restricted by design.

### 3.2 CRISPR-Cas9 Technology: Mechanism of Precision Genome Editing

CRISPR (Clustered Regularly Interspaced Short Palindromic Repeats) and the Cas9 endonuclease constitute a bacterial adaptive immune system repurposed as a molecular tool for site-specific genome editing. The seminal work by Doudna, Charpentier, and colleagues published in 2012 demonstrated that a single guide RNA (sgRNA) — a synthetic RNA molecule comprising a ~20-nucleotide spacer complementary to the target DNA sequence plus a structural scaffold — can direct Cas9 to any genomic locus flanked by a protospacer adjacent motif (PAM, typically 5'-NGG-3' for *Streptococcus pyogenes* Cas9) [16].

Upon target recognition, Cas9 introduces a blunt-ended double-strand break (DSB) in the DNA. The cell's endogenous DNA repair machinery resolves the break through two principal pathways:

1. **Non-homologous end joining (NHEJ):** Error-prone ligation that introduces small insertions or deletions (indels) at the cut site, disrupting the target sequence — the preferred pathway for enhancer knockout.
2. **Homology-directed repair (HDR):** Template-directed precise correction, requiring a donor sequence — used for corrective gene editing but less efficient in post-mitotic or quiescent cells.

For exa-cel, NHEJ-mediated disruption of the BCL11A +58 enhancer is the desired outcome. The indels introduced by Cas9 cleavage and NHEJ destroy the GATA1/TAL1 binding motif required for BCL11A expression in erythroid cells, achieving permanent, heritable enhancer dysfunction in all descendent red blood cells.

---

## 4. Exagamglogene Autotemcel (Exa-cel): Manufacturing and Administration

### 4.1 Cell Therapy Manufacturing Process

The manufacturing of exa-cel is an autologous cell therapy process — the patient's own cells are the therapeutic substrate. The procedure consists of the following stages:

**Stage 1 — Mobilization and Apheresis:** Hematopoietic stem and progenitor cells (HSPCs) are mobilized from the bone marrow into the peripheral blood using plerixafor (a CXCR4 antagonist) alone, without granulocyte-colony stimulating factor (G-CSF), which is contraindicated in thalassemia due to splenomegaly risk. CD34+ HSPCs are then collected by leukapheresis.

**Stage 2 — Ex Vivo Editing:** Collected HSPCs are cultured briefly and electroporated with ribonucleoprotein (RNP) complexes — pre-assembled CRISPR-Cas9 protein bound to the sgRNA targeting the BCL11A +58 erythroid enhancer. Electroporation delivers the editing machinery directly into the nucleus. The RNP format is preferred over viral delivery because the protein/RNA complex is transient — degraded rapidly by cellular proteases — minimizing the duration of Cas9 activity and reducing off-target editing risk.

**Stage 3 — Quality Control and Release:** Edited cell lots are characterized for:
- Editing efficiency (proportion of alleles with indels at target site, typically >80%)
- Cell viability and CD34+ cell dose
- Absence of off-target editing at computationally predicted and experimentally validated alternative sites
- Sterility and absence of replication-competent virus (not applicable for RNP delivery, but assessed as a standard release criterion)

**Stage 4 — Myeloablative Conditioning:** Prior to infusion, patients undergo myeloablative conditioning with busulfan — a DNA-alkylating chemotherapy agent that ablates the endogenous bone marrow, creating space for engraftment of the edited HSPCs. This is currently the most clinically significant risk step: busulfan conditioning carries risks of sinusoidal obstruction syndrome (hepatic), infertility, and secondary malignancy.

**Stage 5 — Infusion and Engraftment:** Edited HSPCs are infused intravenously. Over the ensuing weeks, the edited cells home to the bone marrow niche, self-renew, and differentiate into the full spectrum of blood cell lineages. Because the edit resides in the stem cell — a self-renewing population — all red blood cells produced for the remainder of the patient's life inherit the modified BCL11A enhancer and constitutively produce fetal hemoglobin.

### 4.2 Molecular Outcome

Upon engraftment and erythroid differentiation:

- BCL11A is not expressed in red blood cells (enhancer destroyed)
- *HBG1/HBG2* remain transcriptionally active
- Gamma-globin chains assemble with endogenous alpha-globin chains
- HbF (α₂γ₂) constitutes the majority of hemoglobin produced
- HbF carries oxygen normally; tissues receive adequate oxygenation
- Ineffective erythropoiesis ceases; anemia resolves
- Transfusion is no longer required

---

## 5. Clinical Evidence: The CLIMB-Thal-111 Trial

### 5.1 Study Design

CLIMB-Thal-111 (ClinicalTrials.gov: NCT03655678) is an open-label, single-arm, multicenter Phase 3 clinical trial evaluating exa-cel in patients with transfusion-dependent beta-thalassemia (TDT). Key eligibility criteria included:

- Age ≥12 years
- Transfusion-dependent TDT (≥100 mL/kg/year of packed red blood cells or ≥8 transfusion events per year in the prior 2 years)
- Absence of a matched sibling donor suitable for HSCT
- Eastern Cooperative Oncology Group (ECOG) performance status 0–1

The primary endpoint was transfusion independence (TI) for ≥12 consecutive months with mean total hemoglobin ≥9 g/dL. Secondary endpoints included duration of TI, time to TI, total hemoglobin levels, HbF levels, and safety.

### 5.2 Primary Results

Results published in the *New England Journal of Medicine* in December 2023 (simultaneously with FDA approval) reported on 52 patients with a median follow-up of 24.1 months (range 5.8–48.2) [17]:

| Endpoint | Result |
|---|---|
| Patients achieving TI for ≥12 months | 48/52 (93%) |
| Patients who received exa-cel infusion | 52/52 (100%) |
| Median time to TI (months) | 3.1 |
| Median total hemoglobin during TI (g/dL) | 13.1 |
| Median HbF level at 6 months post-infusion | ~42% of total hemoglobin |
| Median HbF level at 12 months | ~43% |
| Duration of TI (ongoing at analysis) | Up to 48+ months in earliest patients |

Of the 4 patients who did not achieve the primary endpoint: 2 achieved TI for <12 months (ongoing follow-up); technical/manufacturing factors accounted for others. No patient who achieved TI subsequently required resumption of transfusions during follow-up.

### 5.3 Safety Profile

The safety profile was dominated by adverse events attributable to myeloablative conditioning (busulfan) rather than the CRISPR editing itself:

- **Busulfan-related:** nausea, mucositis, elevated liver transaminases, cytopenias during engraftment — all anticipated and manageable
- **CRISPR-specific off-target events:** None detected in systematic deep-sequencing analysis of pre-specified high-priority off-target sites
- **No evidence of insertional oncogenesis:** Not applicable to NHEJ-based editing (no genomic integration)
- **Serious adverse events attributed to exa-cel:** None reported

The absence of GvHD — an inherent risk of allogeneic HSCT — is a decisive advantage of the autologous approach.

### 5.4 Regulatory Approval

Based on the CLIMB-Thal-111 data, exa-cel (Casgevy™) received:
- **US FDA approval:** December 8, 2023 — for TDT in patients ≥12 years
- **UK MHRA approval:** November 16, 2023 — first approval globally for any CRISPR medicine
- **EU EMA approval:** December 2023

This represents the first regulatory approval of a CRISPR-Cas9-based therapeutic in history, validating genome editing as a clinical modality after a decade of preclinical and translational development.

---

## 6. Bangladesh: Burden, Barriers, and the Path Forward

### 6.1 Epidemiology in Bangladesh

Bangladesh bears one of the highest thalassemia carrier frequencies in the world, estimated at approximately 7% for beta-thalassemia alleles and an additional ~4% for hemoglobin E (*HBE*) alleles [5,6]. Compound heterozygosity for Hb E and beta-thalassemia (*HbE/β-thal*) is the most common severe hemoglobin disorder in South and Southeast Asia, producing a clinical syndrome that ranges from moderate to severe transfusion dependency.

The epidemiological consequence: with a population exceeding 170 million and a carrier rate of 7%, approximately 12 million Bangladeshis carry at least one pathogenic *HBB* allele. Assuming random mating, the expected birth prevalence of thalassemia major approximates 1 in 800 births — substantially higher in consanguineous communities. In the absence of population-based carrier screening and prenatal diagnosis programs, virtually all affected children are born and most reach medical attention only after severe anemia develops in infancy.

### 6.2 Current Treatment Reality

Systematic blood transfusion infrastructure in Bangladesh is fragmented. Thalassemia major patients typically access care through the Thalassemia Foundation of Bangladesh, BSMMU, and a small number of specialized pediatric centers concentrated in Dhaka. The majority of patients — particularly in rural districts — receive transfusions irregularly, if at all. Iron chelation, which requires expensive drugs (deferasirox approximately USD 2,000–5,000 annually at international prices, though generic versions exist), is inconsistently prescribed and poorly monitored.

The consequence: a significant proportion of Bangladeshi thalassemia major patients die in childhood or early adulthood from untreated iron overload cardiomyopathy or infection-related complications of severe anemia.

### 6.3 Access to CRISPR Gene Therapy: The Current Constraint

Casgevy is priced at approximately USD 2.2 million per patient in the United States — making it among the most expensive medical treatments in history. This price reflects the individualized manufacturing process (each patient's cells require a separate manufacturing run), the cost of clinical development, and the commercial realities of a rare disease market in a high-income country context.

For Bangladesh, where per capita healthcare expenditure is approximately USD 88 annually, the current price point is not a barrier — it is a categorical impossibility. No individual, no insurance system, and no public health budget in Bangladesh can absorb this cost at scale.

However, several trajectories may alter this landscape over the next decade:

1. **Biosimilar and generic gene therapy:** As CRISPR manufacturing processes mature and patents expire, the cost of ex vivo gene therapy is projected to decrease substantially, following the trajectory of biologic drugs generally.

2. **Regional manufacturing hubs:** India has a large thalassemia burden and an established pharmaceutical manufacturing sector. Indian generic manufacturers have publicly indicated interest in developing lower-cost gene therapy manufacturing infrastructure for the South Asian market.

3. **Government-funded clinical programs:** India's Department of Biotechnology and several private hospital networks have initiated gene therapy clinical programs. If regulatory pathways are established, cross-border access for Bangladeshi patients through bilateral agreements is plausible.

4. **Alternative CRISPR targets and delivery methods:** In vivo CRISPR delivery approaches — eliminating the need for ex vivo cell manufacturing — are in early clinical development and may substantially reduce treatment complexity and cost.

### 6.4 What Is Actionable Now: Prevention Over Treatment

Given current access constraints, the most impactful intervention in Bangladesh is prevention of thalassemia major births through population-based carrier screening and prenatal diagnosis.

The strategy is established and proven in Mediterranean countries that have dramatically reduced thalassemia major births over three decades:

- **Premarital carrier screening:** Identifying carrier couples before conception, enabling informed reproductive decision-making
- **Prenatal diagnosis (PND):** Chorionic villus sampling (CVS) at 10–12 weeks gestation or amniocentesis at 15–18 weeks, with *HBB* genotyping of fetal DNA
- **Genetic counseling:** Informing carrier couples of reproductive options including preimplantation genetic diagnosis (PGD), adoption, or acceptance of risk — without directive counseling

Implementation requires: expansion of diagnostic PCR capacity to district-level hospitals, training of genetic counselors, and policy commitment to a national screening program. The per-test cost of carrier identification by PCR is less than USD 15 — orders of magnitude more accessible than therapeutic intervention.

### 6.5 The Dual Imperative

The existence of CRISPR curative therapy reframes the ethical and policy landscape. Previously, advocacy for thalassemia prevention faced the implicit argument that prevention was all that was available. Now, the science has demonstrated that thalassemia major is curable — at least in principle, at least in resource-replete settings. This creates a dual imperative:

1. **Immediate:** Invest in prevention — carrier screening, prenatal diagnosis, genetic counseling — to reduce the burden of new thalassemia major births.
2. **Strategic:** Advocate for, and contribute to, the development of accessible gene therapy pathways for South Asia, so that patients already born with thalassemia major have a curative option within a timeframe that matters to them.

The science is no longer the limiting factor. Healthcare systems, policy, and equity are.

---

## 7. Discussion

### 7.1 The Paradigm Shift: From Management to Cure

The approval of exa-cel represents more than an incremental improvement in thalassemia treatment. It constitutes a fundamental proof of concept: a monogenic disease caused by a transcriptional regulatory defect can be permanently corrected by a single intervention that modifies the regulatory landscape of a patient's own stem cells. The implications extend well beyond thalassemia.

The BCL11A enhancer is not unique as a target. The same mechanism — CRISPR disruption of the erythroid BCL11A enhancer to reactivate HbF — has been applied in parallel to sickle cell disease, where elevated HbF inhibits sickling of deoxygenated red blood cells. The FDA approval of exa-cel for sickle cell disease on the same day as the thalassemia approval demonstrates that the therapeutic platform generalizes across hemoglobinopathies caused by different molecular lesions in the same pathway [17].

More broadly, the exa-cel experience validates the autologous ex vivo CRISPR paradigm: isolate stem cells, edit them in a controlled environment, confirm editing and safety, reinfuse. This paradigm is disease-agnostic. The same manufacturing architecture can, in principle, be applied to any disease for which the target cell population is accessible (hematopoietic, hepatic via biopsy, or T-cell) and the causal genomic change is known.

### 7.2 Limitations and Remaining Challenges

Despite the remarkable efficacy data, exa-cel faces several unresolved challenges:

**Myeloablation:** Busulfan conditioning remains the principal safety concern. Infertility is nearly universal after myeloablative conditioning. For pediatric patients — the population most likely to benefit from early curative intervention — this represents an unacceptable trade-off unless non-genotoxic conditioning regimens (such as CD117 antibody-drug conjugates targeting c-Kit on HSPCs) can be developed and validated.

**Long-term durability:** Follow-up in CLIMB-Thal-111 extends to 48 months for the earliest patients. While the permanence of the stem cell edit is theoretically assured, very long-term engraftment kinetics and the possibility of edited clone exhaustion require decades of observation. Registry studies will be critical.

**Off-target editing:** No off-target events were detected in trial patients by deep sequencing. However, the detection limits of sequencing-based methods and the theoretical risk of rare off-target events in cancer-relevant loci remain active areas of investigation, particularly as treated populations age.

**Manufacturing complexity and scalability:** Current manufacturing timelines are approximately 3–6 months from cell collection to infusion. Patients require transfusion management throughout this period, which is challenging in low-resource settings. Scale-up to accommodate global demand remains an unsolved logistics problem.

**Price and access:** As discussed for Bangladesh, the current pricing model is incompatible with global equity. Alternative financing mechanisms, technology transfer agreements, and regulatory frameworks enabling lower-cost biosimilar development are essential.

### 7.3 Future Directions

Several approaches are under active investigation to extend and improve upon the exa-cel paradigm:

**In vivo CRISPR delivery:** Rather than editing cells in a laboratory, lipid nanoparticles or adeno-associated viral vectors could deliver CRISPR components directly into circulating HSPCs in the patient's body. This would eliminate the cell collection, ex vivo culture, and myeloablation steps — radically simplifying and reducing cost. Early clinical trials are underway.

**Base editing and prime editing:** Next-generation CRISPR derivatives that introduce specific single-nucleotide changes without creating double-strand breaks. Base editors could correct the most common *HBB* point mutations directly, restoring functional beta-globin rather than inducing a compensatory HbF response. Prime editors offer even greater precision. Both are in preclinical development for hemoglobinopathies.

**Pediatric application:** Initiating gene therapy before organ damage from iron overload and chronic anemia occurs — ideally in the first years of life — would maximize benefit. Age-appropriate trials are planned as safety data matures.

---

## 8. Conclusion

Beta-thalassemia — a disease that has condemned millions of children to a life measured in transfusion cycles, chelation schedules, and organ failure — is now curable. The December 2023 regulatory approval of exagamglogene autotemcel represents the translation of a molecular biological insight, three decades in the making, into a licensed human medicine: *BCL11A* mediates the developmental silencing of fetal hemoglobin, and CRISPR-Cas9 can disable that silencer permanently, in a patient's own stem cells, without touching the causative mutation in *HBB*, without requiring a donor, and without the immunological risks of allogeneic transplantation. In the pivotal Phase 3 trial, 93% of treated patients achieved complete transfusion independence, with a median hemoglobin of 13.1 g/dL and effects durable across all available follow-up intervals. No off-target editing events were detected. No serious adverse events from the editing itself were reported.

The significance of this extends beyond a single disease. The exa-cel approval is proof that the ex vivo CRISPR paradigm — harvest stem cells, edit them with precision, characterize them thoroughly, reinfuse — is clinically viable, scalable to regulatory approval, and safe at the follow-up durations currently available. The same therapeutic architecture is now being applied to sickle cell disease, lysosomal storage disorders, and immunodeficiencies. The era of CRISPR medicine has begun not as a concept but as a commercial, regulatory, and clinical reality.

For Bangladesh — where approximately 7% of the population silently carries a pathogenic *HBB* allele, where most thalassemia major patients are never formally diagnosed, and where no gene therapy is currently accessible at any price — this moment is both an inspiration and an indictment. An inspiration, because the scientific barrier has fallen: thalassemia is provably curable with existing technology. An indictment, because the remaining barriers — cost, infrastructure, political will, equitable access — are entirely human in origin. They can be addressed. They must be.

The immediate prescription is prevention: PCR-based carrier screening at less than $15 per test, prenatal diagnosis for carrier couples, and genetic counseling infrastructure at the district level. Cyprus reduced its annual thalassemia major birth rate from dozens to nearly zero using this approach. Bangladesh can do the same, with political commitment and public health investment that are orders of magnitude less demanding than building gene therapy manufacturing capacity.

The longer prescription is advocacy and preparation: supporting the development of in vivo CRISPR delivery systems that will eliminate ex vivo manufacturing complexity, engaging with regional biosimilar development pathways that will reduce cost from the current $2.2 million toward accessibility, and building the haematological and genomic medicine infrastructure that will be necessary when these technologies arrive.

The mutation in *HBB* has not changed. The body's fetal hemoglobin system has not changed. What has changed — irrevocably — is our ability to re-engage it. Permanently. Safely. With the endorsement of three of the world's most rigorous regulatory bodies. The science has fulfilled its obligation. The obligation that remains is human: to ensure that a cure discovered by molecular biology does not stay locked inside the economics of high-income medicine, while millions of children who need it are born into countries that cannot afford it.

The science is ready. It has been ready since December 2023. The world has not yet caught up.

---

## References

1. Taher AT, Weatherall DJ, Cappellini MD. Thalassaemia. *Lancet*. 2018;391(10116):155–167. doi:10.1016/S0140-6736(17)31822-6

2. Weatherall DJ. The inherited diseases of hemoglobin are an emerging global health burden. *Blood*. 2010;115(22):4331–4336. doi:10.1182/blood-2010-01-251348

3. Modell B, Darlison M. Global epidemiology of haemoglobin disorders and derived service indicators. *Bull World Health Organ*. 2008;86(6):480–487. doi:10.2471/BLT.06.036673

4. Williams TN, Weatherall DJ. World distribution, population genetics, and health burden of the hemoglobinopathies. *Cold Spring Harb Perspect Med*. 2012;2(9):a011692. doi:10.1101/cshperspect.a011692

5. Ahmed S, Salat MS, Begum R, et al. Spectrum of β-thalassemia mutations in Bangladeshi population. *Bangladesh Med Res Counc Bull*. 2013;39(1):14–18.

6. Galanello R, Origa R. Beta-thalassemia. *Orphanet J Rare Dis*. 2010;5:11. doi:10.1186/1750-1172-5-11

7. Cappellini MD, Cohen A, Porter J, Taher A, Viprakasit V, eds. *Guidelines for the Management of Transfusion Dependent Thalassaemia (TDT)*. 3rd ed. Nicosia, Cyprus: Thalassaemia International Federation; 2014.

8. Thompson AA, Walters MC, Kwiatkowski J, et al. Gene therapy in patients with transfusion-dependent β-thalassemia. *N Engl J Med*. 2018;378(16):1479–1493. doi:10.1056/NEJMoa1705342

9. US Food and Drug Administration. FDA approves first gene therapies to treat patients with sickle cell disease. FDA News Release. December 8, 2023. Available at: https://www.fda.gov

10. Dean A. On a chromosome far, far away: LCRs and gene expression. *Trends Genet*. 2006;22(1):38–45. doi:10.1016/j.tig.2005.11.001

11. Ribeil JA, Hacein-Bey-Abina S, Payen E, et al. Gene therapy in a patient with sickle cell disease. *N Engl J Med*. 2017;376(9):848–855. doi:10.1056/NEJMoa1609677

12. Sankaran VG, Orkin SH. The switch from fetal to adult hemoglobin. *Cold Spring Harb Perspect Med*. 2013;3(1):a011643. doi:10.1101/cshperspect.a011643

13. Thein SL, Menzel S, Lathrop M, Garner C. Control of fetal hemoglobin: new insights emerging from genomics and clinical implications. *Hum Mol Genet*. 2009;18(R2):R216–R223. doi:10.1093/hmg/ddp401

14. Uda M, Galanello R, Sanna S, et al. Genome-wide association study shows BCL11A associated with persistent fetal hemoglobin and amelioration of the phenotype of β-thalassemia. *Proc Natl Acad Sci USA*. 2008;105(5):1620–1625. doi:10.1073/pnas.0711566105

15. Sankaran VG, Menne TF, Xu J, et al. Human fetal hemoglobin expression is regulated by the developmental stage-specific repressor BCL11A. *Science*. 2008;322(5909):1839–1842. doi:10.1126/science.1165409

16. Jinek M, Chylinski K, Fonfara I, Hauer M, Doudna JA, Charpentier E. A programmable dual-RNA-guided DNA endonuclease in adaptive bacterial immunity. *Science*. 2012;337(6096):816–821. doi:10.1126/science.1225829

17. Locatelli F, Lang P, Wall D, et al. Exagamglogene autotemcel for transfusion-dependent β-thalassemia. *N Engl J Med*. 2024;390(18):1663–1676. doi:10.1056/NEJMoa2309673

18. Frangoul H, Altshuler D, Cappellini MD, et al. CRISPR-Cas9 gene editing for sickle cell disease and β-thalassemia. *N Engl J Med*. 2021;384(3):252–260. doi:10.1056/NEJMoa2031054

19. Doudna JA. The promise and challenge of therapeutic genome editing. *Nature*. 2020;578(7794):229–236. doi:10.1038/s41586-020-1978-5

20. Orkin SH, Bauer DE. Emerging genetic therapy for sickle cell disease. *Annu Rev Med*. 2019;70:257–271. doi:10.1146/annurev-med-041817-125507

---

*Manuscript prepared for World DNA Day Poster Competition 2026 — extended scientific documentation.*  
*Theme: Genetic Disorder & Medication · BRAC University Society for Biotechnology (BUSB)*
