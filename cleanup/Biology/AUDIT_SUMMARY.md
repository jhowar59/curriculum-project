# Biology Curriculum Audit — Cross-Chapter Summary

**Date:** 2026-06-11
**Standards:** ND 2019 Science Content Standards (HS Life Science)
**Scope:** Chapters 1–8, 10, 11 (each has its own `REPORT_CARD.md`). **Chapter 9 (biotechnology) was intentionally skipped** — a late-year pacing choice to reach evolution; it maps to **zero high-school LS standards** (biotech language in ND 2019 appears only at the middle-school level, MS-LS4-5), so nothing was lost by skipping it.

This summary rolls up the standards coverage, the recurring patterns, the equipped-but-unused labs, the build items, and the cleanup picture. Per-chapter detail lives in each `REPORT_CARD.md`.

---

## 1. Standards coverage map

The audited chapters cover three of the four HS Life Science strands well — **LS1 (molecules/cells), LS3 (heredity), LS4 (evolution)**. The **LS2 (ecology/ecosystems)** strand is almost entirely absent from these chapters (see the gap note below).

| PE | Covered in | Notes |
|----|-----------|-------|
| HS-LS1-1 (DNA→protein structure/function) | **Ch8** (core), Ch1 | Ch8 is the spine; 8.1 history-of-science is a strong CER hook |
| HS-LS1-2 (multicellular systems/organization) | **Ch3** | onion-cell + cell-model labs (equipped) |
| HS-LS1-3 (homeostasis/feedback) | Ch1, Ch2, **Ch3** | foundational across early chapters |
| HS-LS1-4 (mitosis & differentiation) | **Ch5** | mitosis lab missing but equipped |
| HS-LS1-5 (photosynthesis) | Ch2, **Ch4** | Ch4 = energy heart of the course |
| HS-LS1-6 (carbon-based macromolecules) | **Ch2** | macromolecule food-testing lab equipped |
| HS-LS1-7 (cellular respiration) | **Ch4** | lab gap, best-equipped chapter |
| HS-LS2-1 (carrying capacity/population math) | Ch1 (light touch only) | **ecology — see gap note** |
| HS-LS2-3 (aerobic/anaerobic energy & matter) | **Ch4** | touched via respiration |
| HS-LS3-1 (DNA/chromosomes → traits) | **Ch6, Ch7, Ch8** | well covered |
| HS-LS3-2 (variation: mutation + sexual reprod.) | Ch6, Ch7, Ch10, **Ch11** | mutation source taught in **11.1** (see correction note) |
| HS-LS3-3 (statistics/probability of traits) | **Ch6, Ch7** | Ch6 trait survey is a built HS-LS3-3 investigation |
| HS-LS4-1 (multiple lines of evidence) | **Ch10** | strongest single-PE coverage in the set |
| HS-LS4-2 (four factors of natural selection) | **Ch10, Ch11** | complete across the two chapters |
| HS-LS4-3 (mathematical models / Hardy-Weinberg) | Ch10 (none), **Ch11** | **the one real remaining gap — equation shown, never used** |
| HS-LS4-4 (natural selection → adaptation) | **Ch10** | qualitative |
| HS-LS4-5 (speciation/extinction) | **Ch11** | richly covered; the 11.5 writing task is the best CER in the audit |
| HS-LS4-6 (design solution for biodiversity) | Ch11 (named only) | **ecology — see gap note** |

**Coverage gap — the LS2 ecology strand (confirmed a Biology responsibility).** Checking the course badges in the original ND 2019 PDF (pp. 180–187) settled this: **all eight HS-LS2 standards carry the Biology badge** — so ecology *is* part of the Biology course, not just Environmental Science. Six (LS2-1, 2, 4, 6, 7, 8) are **shared** Biology + Environmental Science; **two (LS2-3 and LS2-5) are Biology-only.** Status in the audited chapters:
- **HS-LS2-3** (aerobic/anaerobic cycling) — **covered** in Ch4 (cellular energy). ✓
- **HS-LS2-1, 2, 4, 5, 6, 7, 8** and **HS-LS4-6** — **not covered** in the audited Ch1–11 arc. Notably **LS2-5** (photosynthesis/respiration in the global carbon cycle) is **Biology-only**, so Environmental Science can't be its home; and the shared standards still apply to every Biology student, whether or not they take the (non-required) Env Sci course.

**This is a genuine Biology coverage gap — with one likely-benign explanation.** The audited chapters (Ch1–8, 10, 11) are the molecules→cells→genetics→evolution arc; in a typical HMH sequence ecology lives in *later* chapters. So either (a) ecology chapters exist beyond Ch11 that weren't in this cleanup folder and simply weren't audited, or (b) the course doesn't reach ecology (consistent with the end-of-year pacing squeeze that also dropped Ch9). **Action: confirm where the ecology unit lives and whether it's taught.** If it exists, point the audit at it; if it's not being reached, LS2 (especially the Biology-only LS2-5) is the real standards gap for the course, not HS-LS4-3.

**One genuine within-scope standards gap remains: HS-LS4-3 math.** Hardy-Weinberg (`p² + 2pq + q² = 1`) is shown on slide 11.4-5 but never *used* — no calculation, no problem set, no IWS 11.4. The standard says "**use** mathematical models." A single HW practice problem closes it (see build items).

---

## 2. Recurring patterns across chapters

1. **CFUs are recall-by-default.** Almost every Check-For-Understanding worksheet is definitional ("What is X?"), a direct artifact of LLM-generate-from-notes producing Q&A by default (see the `cfu-digital-workflow` framing). The systematic fix is the same everywhere: **add one `[short-answer]` application/CER item on top of the recall** — costs nothing on paper; in Forms it's the one item that won't auto-grade. The exceptions prove the rule: **Ch6** (Punnett problems, trait survey) and **Ch11** (the 11.5 speciation writing assignment) already carry real reasoning — and the 11.5 task is the **model** the rest should imitate.

2. **Labs are often absent despite a well-equipped room.** The single highest-value, lowest-cost theme of the whole audit: several chapters teach on slides what the room is already stocked to do hands-on. The equipped-but-unused labs are listed in §3.

3. **Heavy version/edition clutter — but nothing byte-identical.** Every chapter carries working-copy sprawl: "bona fide" decks, `(1)` download-collision copies, `Copy of …` files, Holt-edition vs. HMH-edition parallels, doc-format deck mirrors, and per-section breakouts of canonical decks. **Across all chapters, no two working files were byte-identical** (all distinct md5s), so under the project rule ("exact duplicates only") **nothing was auto-removed** — every near-dup is flagged for the teacher's manual pruning. Heaviest in **Ch10** (Holt parallels, 10.2 in three copies, CFU 10.4 in three forms).

4. **The digital workflow is visible throughout.** AI-generated MCQ tests (Ch5, Ch6, Ch8 — one was an unnamed "Untitled document"), AI readings, export-slimmed decks (Ch8), and AI lesson plans (Ch11 speciation) recur. These are QuestionWell/Brisk outputs; the recall-only CFU pattern traces to the same source.

5. **Exclusions were consistent.** Publisher test banks (`hssb*`), Kahoot/Quizizz `.xlsx` reviews, ExamView PDFs, `.tst` tests, Holt publisher tests, and AI enrichment readings were listed but not audited, per scope.

---

## 3. Equipped-but-unused labs (the highest-value wins)

Every one of these is **already resourced in the room** (INVENTORY.md section in parens) — they need planning time, not purchasing:

- **Ch2 — Macromolecule food-testing** (Biuret + iodine; lipase enzyme lab): reagents in stock (§5). *Verify Benedict's reagent for reducing sugars (§5/§14).*
- **Ch3 — Diffusion-Osmosis**: Carolina Diffusion-Osmosis BioKit (§7) on hand; onion-cell + cell-model labs already built and equipped.
- **Ch4 — Photosynthesis/respiration** (the lab gap in the best-equipped chapter): Carolina Plant Pigments & Photosynthesis kit and related gear (§7).
- **Ch5 — Mitosis**: onion-root-tip microscopy or a pipe-cleaner modeling activity; microscopes + prepared slides (§1), craft consumables (§11).
- **Ch6 — Human-trait survey**: already built (HS-LS3-3) — needs only the interpretation/CER step added.
- **Ch7 — ABO/codominance**: Innovating Science "Forensic Chemistry of Blood Types" kit (§7).
- **Ch8 — DNA structure/replication modeling**: Carolina DNA Necklace Kit + Molecular Model Kit (§7).
- **Ch10 — Comparative anatomy** (homologous structures): Carolina Comparative Skeletal Anatomy Kit (§7) + skeleton/specimens (§8); a bird-beak natural-selection simulation (§11) for 10.3.

---

## 4. Build items (things to create)

Tracked in the `curriculum-build-items` memory; consolidated here:

- **HS-LS4-3 Hardy-Weinberg practice problem (Ch11.4)** — *the one item that closes a real within-scope standards gap.* Given q², compute q, p, and genotype frequencies; compare predicted vs. observed.
- **Ch8 §8.5 (Translation) slide deck** — teacher-flagged; decks stop at transcription, translation carried only by IWS 8.5 + the test. (Optionally a CFU 8.5.)
- **Ch10 §10.3 mutation insert** — *drafted & committed* (`10.3 Mutation Insert (DRAFT).md`): 2 slides + `CFU 10.3 - C`. **Reframed as an enhancement, not a gap-fix** (see correction note) — mutation is taught in 11.1; the insert just pulls it forward to where 10.3 first needs it. Keep on pedagogical grounds; convert slides/CFU to binaries when convenient.
- **Per-chapter CER bolt-ons** — one `[short-answer]` per recall-only section. Highest-value singles: Ch8 8.1 history-of-science argument; Ch10 HS-LS4-1 evidence synthesis; Ch6 trait-survey interpretation; Ch7 pedigree analysis.

---

## 5. Correction logged during the audit

While auditing Ch11 I corrected an earlier overstatement: I had told you (when weighing the Ch9 skip) that mutation as the source of variation was taught **nowhere**. **Ch11.1 teaches it directly** ("Genetic variations come from two main sources: Mutation … Recombination …"), so HS-LS4-2's mutation factor and HS-LS3-2's mutation prong **are** met — they just land in Ch11, after natural selection is introduced in Ch10. The mutation gap was real as a *sequencing* observation, not as an unmet standard. The Ch10 insert remains useful for that sequencing reason.

---

## 6. Bottom line

For the strands these chapters cover (LS1 cells/molecules, LS3 heredity, LS4 evolution), **content coverage is solid to strong** — evolution (Ch10–11) and heredity (Ch6) are the highlights. The course's consistent weaknesses are **pedagogical, not content**: recall-only formative assessment and under-used lab equipment, both cheap to fix and both with a working in-house model (Ch11's writing task; Ch6's built investigation). Within the chapters audited, the only **standards** gap is **HS-LS4-3's unpracticed Hardy-Weinberg math**. The bigger question is **ecology (LS2)**: the ND course badges confirm it *is* a Biology responsibility (all eight LS2 PEs carry the Biology badge; two are Biology-only), and it's absent from the audited cells→genetics→evolution arc — so the priority is to find out whether an ecology unit exists beyond Ch11 and whether the course actually reaches it.
