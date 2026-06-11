# REPORT_CARD — Chapter 7: Extending Mendelian Genetics

**Audit date:** 2026-06-11
**Standards:** ND 2019 Science Content Standards
**Scope:** Canonical slide deck + per-section breakouts, the doc-format note parallels, IWS PDFs, and the CFU worksheets — this folder has **no publisher banks, Kahoot, ExamView/.tst tests, or labs** to exclude
**Lab/activity column** cross-references the room's [INVENTORY.md](../../../INVENTORY.md) (§ = inventory section) to flag where a hands-on component exists or could plug in, and whether the equipment is on hand.
**A CER bolt-on and a CFU revision are the same artifact** — the question content — not a separate worksheet. CFUs are delivered in **two modes, chosen day to day**: handed out as the **paper worksheets** seen here, or **LLM-generated from the notes into a Google Form** (Forms/Classroom). The **[auto-grade]** / **[short-answer]** tags below matter **only in Forms mode**: [auto-grade] = recall item Forms scores automatically, [short-answer] = open CER/explanation item Forms can't grade. On paper every item is hand-graded anyway, so adding the CER item costs nothing extra. Going digital, the pattern is mostly [auto-grade] recall **+ one [short-answer] CER item**; on paper, just add that CER item.

Chapter 7 extends Mendel into the complications: chromosomes & phenotype, including sex-linkage and X-inactivation (7.1); complex inheritance — incomplete dominance, codominance/ABO blood types, multiple alleles, polygenic traits, epistasis, and environment × genotype (7.2); gene linkage and mapping via Morgan's fruit flies (7.3); and studying human genetics through pedigrees and karyotypes (7.4). It sits squarely on **HS-LS3-1** (how chromosomes/genes encode the instructions for traits — here the *non-simple* cases) with **HS-LS3-3** reasoning hooks in the pedigree analysis (7.4) and linkage-map distances (7.3), and a **HS-LS3-2** thread (multiple alleles + polygenic traits as sources of variation, 7.2).

---

| File | Type | PE touched | Dimension coverage | Recommended move | Flag | Lab/activity (equipment on hand) |
|------|------|------------|-------------------|-----------------|------|----------------------------------|
| Chapter 7 Notes - all.pptx | Slides (24 slides, all 4 sections — the canonical full-chapter deck, Apr 2025) | 7.1 → **HS-LS3-1** (autosomal vs. sex-linked genes, X-inactivation, autosomal disorders); 7.2 → **HS-LS3-1 / HS-LS3-2** (incomplete dominance, codominance/ABO, multiple alleles, polygenic, epistasis, environment × genotype); 7.3 → **HS-LS3** (linkage, recombination, linkage maps); 7.4 → **HS-LS3-1 / HS-LS3-3** (pedigrees, sex-linked disorders, karyotypes). CC: Cause & Effect, Patterns, Structure & Function | content only throughout | Content source for the chapter's bolt-ons: the **7.4 pedigree-analysis** item (read a pedigree → name the inheritance pattern → justify) and the **7.2 codominance/ABO** application (both **[short-answer]** / problem-based) | Canonical deck. Per-section breakouts and two doc-format parallels are working copies — see Cleanup flags | Anchors the blood-type codominance lab (see note) and a paper pedigree-analysis activity |
| Chapter 7.1 / 7.1–7.2 / 7.2 / 7.3 / 7.4 Notes.pptx (per-section breakouts) | Slides (daily-use decks split from the canonical: 7.1 = 6 sl, 7.1–7.2 = 12 sl, 7.2 = 6 sl, 7.3 = 5 sl, 7.4 = 7 sl) | one section each, same PE map as the canonical row | content only | leave be — daily teaching units; keep in sync with the canonical deck | Working breakouts; the `7.1 - 7.2` combined deck overlaps the standalone 7.1 and 7.2 decks — version clutter, see Cleanup flags | 7.2 is the natural home for the blood-type lab |
| Chapter 7 Notes - all.docx / Chapter 7 - Notes.docx | Doc-format note parallels (text-only versions of the deck, ~93 paras each) | mirror the deck section-by-section | content only | leave be (or fold into the deck-cleanup pass) — same doc-parallel pattern seen in Ch5/Ch6 | **Near-duplicates of each other** (distinct md5s, ~93 vs ~95 paras); keep one | None — reading/notes text |
| IWS 7.1.pdf — *Chromosomes and Phenotype* | IWS (publisher source, HMH) | **HS-LS3-1** — autosomal genes, sex-linked genes, carriers, X-inactivation | content; Instant Replay / Big Picture add light reasoning | leave be | Publisher source material (HMH); converted through a free PDF tool — carries watermark text noise. *(Renamed from `IWS 7.1b.pdf` — the `b` was a misnomer; this is the 7.1 reading.)* | None — publisher reading |
| IWS 7.2.pdf — *Complex Patterns of Inheritance* | IWS (publisher source, HMH; reading + teacher answers, 4 pp) | **HS-LS3-1 / HS-LS3-2** — incomplete dominance vs. codominance, multiple alleles, polygenic traits | content; Instant Replay contrasts the inheritance modes (genuine reasoning) | leave be — the cleanest reading in the chapter | Publisher source material (HMH) | Reading; substrate for the blood-type lab |
| IWS 7.3.pdf — *Gene Linkage and Mapping* | IWS (publisher source, HMH) | **HS-LS3** — linked genes, crossing-over frequency, linkage-map distance | content; the map-distance reasoning is quantitative | leave be | Publisher source material (HMH) | Reading; substrate for a linkage-map calculation task |
| Biology CFU 7.1.docx | CFU | **HS-LS3-1** — sex-linked genes, carrier, autosomes, X-inactivation, dominant-disorder frequency | content only (recall) | CFU revision — Q4/Q5 already probe X-inactivation and disorder frequency; one edit from a **[short-answer]** "why are males more often affected by sex-linked disorders?" | None | None — formative check |
| Biology CFU 7.2.docx | CFU | **HS-LS3-1 / HS-LS3-2** — epistasis, polygenic trait, incomplete dominance, codominance, environment × phenotype | definition-focused by design (see note) | CFU revision — this is the section with the richest reasoning content (ABO codominance); add a **[short-answer]** ABO/blood-type cross or an incomplete-dominance prediction *on top of* the definitions | The "don't give an example" instruction is **deliberate**: it targets students who answer "what is X?" with only an example instead of a definition — a persistent habit for some. It forces the definition; it is not a recall-vs-reasoning choice | None built-in; the blood-type lab is the natural companion |
| Biology CFU 7.3.docx | CFU | **HS-LS3** — linkage maps, Morgan, cause of linked traits, map distance, linked genes | content only (recall) | CFU revision — Q4 (farther apart → more likely to ___) is one step from a **[short-answer]** linkage-map *calculation* (estimate distance from recombination %) | None | None — formative check |
| Biology CFU 7.4.docx | CFU | **HS-LS3-1 / HS-LS3-3** — human inheritance patterns, carriers, pedigree, karyotype, chromosome changes | content only (recall) | **Best CFU-revision target in the chapter** — Q3 ("what is a pedigree?") should become a **[short-answer]** *read-this-pedigree* task: determine the inheritance pattern and justify from the chart. That single edit turns the recall item into HS-LS3-1/3 analysis | None | None built-in; a pedigree worksheet is the missing activity (paper, no equipment) |

---

**Chapter verdict:** Content coverage is complete across the four sections and the material is genuinely reasoning-friendly (codominance, pedigrees, linkage maps all invite analysis), but the chapter is **the thinnest on materials so far**: four recall CFUs, the decks, and three publisher readings — **no application worksheets, no lab, and no assessment instrument in the folder at all**. Where Chapter 6 already had a built data activity, Chapter 7 has the *opportunities* fully unbuilt. The good news is that closing the gaps needs little: two of the hooks are paper-only, and the third lab is already on the shelf.

**Findings worth acting on:**

1. **The ABO/codominance lab is equipped — and it's the chapter's standout hands-on hook.** 7.2 teaches codominance through ABO blood types on slides only, but the **Innovating Science "Forensic Chemistry of Blood Types" kit (§7)** is on hand. Simulated blood typing turns codominance from a definition into an investigation, and it pairs naturally with an ABO Punnett-cross problem (which blood-type offspring are possible from given parents?). This is the highest-value addition in the chapter.

2. **Pedigree analysis is the missing worksheet — pure reasoning, zero equipment.** 7.4 introduces pedigrees and karyotypes, but the only check is CFU 7.4's "what is a pedigree?" There is **no pedigree-reading worksheet**. Adding one (trace a trait through a family tree → determine dominant/recessive and autosomal/sex-linked → justify with the evidence) is a clean HS-LS3-1/HS-LS3-3 task on paper, and it's the most natural **[short-answer]** CER in the chapter.

3. **The CFUs are recall — but that's the right floor here, not a defect.** All four CFUs check definitions, and CFU 7.2's "don't give an example" instruction is a *deliberate* correction: some students, asked "what is X?", answer with only an example and never state the definition, so the prompt forces the definition out. That's sound. The point isn't to replace the recall — it's to **add** one application item per section on top of it (an ABO cross, an incomplete-dominance prediction, a linkage-map distance), exactly the two-mode "[auto-grade] recall + one [short-answer]" pattern. The reasoning content is all in the notes already.

4. **No assessment artifact in the folder.** Unlike the other chapters, Chapter 7 has no test, quiz, or Kahoot present — the recall CFUs are the only checks. If the digital-workflow MCQ test exists for this chapter, it lives elsewhere; if not, this is the chapter to generate one (auto-grade recall **+ one [short-answer]** = the pedigree item from finding #2).

5. **Linkage maps (7.3) are an easy quantitative win.** Estimating map distance from recombination frequency is a short numeracy task that fits HS-LS3 and gives 7.3 an application item beyond the recall CFU.

---

## Cleanup flags

**Version / format clutter:**
- **Two doc-format note parallels** — `Chapter 7 Notes - all.docx` and `Chapter 7 - Notes.docx` — are near-duplicate text versions of the deck (distinct md5s). Keep one; same doc-parallel pattern flagged in Ch5/Ch6.
- **Per-section breakouts overlap the combined deck:** the standalone `Chapter 7.1 Notes.pptx` and `Chapter 7.2 Notes.pptx` are both also contained in `Chapter 7.1 - 7.2 Notes.pptx`. Working day-splits, not byte copies — keep whichever you teach from.

**Resolved this pass:**
- **`IWS 7.1b.pdf` → renamed `IWS 7.1.pdf`** — the `b` was a misnomer; it is the 7.1 reading.
- **`IWS 7.2 - Zae.pdf` deleted** — a watermarked student/working copy of `IWS 7.2.pdf`; removed at the teacher's direction.

**Coverage notes:**
- **No IWS for 7.4** (human genetics / pedigrees) — the deck is the sole source for that section; reinforces the pedigree-worksheet recommendation (finding #2).
- **`IWS 7.1.pdf`** carries free-PDF-converter watermark text ("...hange Vi...") embedded in the extract; the reading itself is intact.

*No exact-duplicate working files found among the remaining files (the doc parallels carry distinct md5s); nothing qualifies for automatic removal under the "exact duplicates only" rule.*
