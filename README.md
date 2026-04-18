# Rewriting Fate: CRISPR-Cas9 & Beta-Thalassemia
### World DNA Day Poster Competition 2026 · BUSB · BRAC University

**Theme:** Genetic Disorder & Medication  
**Submission deadline:** April 25, 2026  
**Topic:** How CRISPR-Cas9 (Casgevy™) transforms beta-thalassemia from a lifelong burden into a one-time cure — mechanism, Phase 3 trial evidence, and implications for Bangladesh.

---

## Files

| File | Description |
|---|---|
| `poster.html` | **Primary submission.** Full A2 scientific poster — HTML/CSS/SVG with animated DNA helix, BCL11A molecular switch diagram, CRISPR mechanism flow, clinical bar chart, Bangladesh section. Print to PDF via Chrome. |
| `poster.pptx` | Editable PowerPoint version at A2 dimensions (420 × 594 mm). Open in PowerPoint or LibreOffice Impress. |
| `manuscript.md` | Full academic manuscript: Abstract → Introduction → Pathophysiology → BCL11A mechanism → Casgevy manufacturing → CLIMB-Thal-111 trial → Bangladesh → Discussion → Conclusion. 20 references with DOIs. |
| `research_paper_plan.md` | Comprehensive plan for the extended research paper merging Casgevy/BCL11A (established) with novel radiation-primed HDR + AI-guided gRNA design (conceptual). 22 APA 7th references. |
| `build_poster.py` | Python script that generated `poster.pptx` using python-pptx. |

---

## How to Print the Poster (PDF)

1. Open `poster.html` in **Google Chrome**
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Set: **Paper size → A2** · **Margins → None** · **Background graphics → ON**
4. Click **Save as PDF**

> On Windows, if A2 is not listed, add a custom paper size: 420 mm × 594 mm in printer settings.

---

## Science Summary

**Beta-thalassemia** is caused by mutations in the *HBB* gene (chromosome 11p15.5) that eliminate β-globin production. Without functional hemoglobin, red blood cells are destroyed in the bone marrow before reaching circulation. Patients require 2–4 blood transfusions per month, every month, for life — accumulating iron overload that eventually destroys the heart.

**Casgevy (exa-cel)** bypasses the broken *HBB* gene entirely. It uses CRISPR-Cas9 to disrupt the erythroid-specific enhancer of *BCL11A* — the transcriptional repressor that silences fetal hemoglobin (HbF) after birth. With BCL11A silenced in red blood cells, the fetal globin genes *HBG1/HBG2* remain permanently active, flooding the erythroid lineage with functional HbF (α₂γ₂) that compensates fully for absent adult hemoglobin. The edit lives in a self-renewing hematopoietic stem cell — every red blood cell the patient produces for the rest of their life inherits it.

**CLIMB-Thal-111 Phase 3 trial (NEJM, 2024):**  
- n = 52 transfusion-dependent patients  
- 93% (48/52) achieved transfusion independence ≥12 months  
- Median hemoglobin during TI: 13.1 g/dL  
- Zero off-target editing events detected by deep sequencing  
- Approved FDA + EMA + MHRA: December 2023

**Bangladesh relevance:** ~7% carrier rate — 1 in 14 people. ~12 million carriers. Most patients never diagnosed. The immediate action is carrier screening (<$15/test) and prenatal diagnosis. The long-term trajectory is in vivo CRISPR delivery and biosimilar access pathways.

---

## Key References

1. Locatelli F et al. Exagamglogene autotemcel for transfusion-dependent β-thalassemia. *N Engl J Med*. 2024;390:1663–1676.
2. Frangoul H et al. CRISPR-Cas9 gene editing for sickle cell disease and β-thalassemia. *N Engl J Med*. 2021;384:252–260.
3. Sankaran VG et al. Human fetal hemoglobin expression is regulated by BCL11A. *Science*. 2008;322:1839–1842.
4. Uda M et al. BCL11A associated with persistent fetal hemoglobin. *Proc Natl Acad Sci USA*. 2008;105:1620–1625.
5. Jinek M, Doudna JA, Charpentier E et al. A programmable dual-RNA-guided DNA endonuclease. *Science*. 2012;337:816–821.
