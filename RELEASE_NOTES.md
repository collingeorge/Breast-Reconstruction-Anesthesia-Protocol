# 2026.10-rc2 - educational review candidate

> **Educational work by a pre-medical student — not medical advice.** Not a clinical protocol, prescription, or patient handout, and not for patient care. See [DISCLAIMER](DISCLAIMER.md).

Revised 27 October 2026 after the rc1 PRs were merged.

This pass corrects newly identified source and software defects and deliberately narrows unsupported clinical/methodological content. Earlier versions remain recoverable in Git history. See PUBLICATION_REVIEW.md for the precise scope and limitations, PROVENANCE.md for author statements, and RELEASE_MANIFEST.json for current-file hashes.

The candidate is not a clinical protocol, validated controller, systematic/scoping review certification, or legal opinion. No repository visibility change is included.

## Applied example set — 28 October 2026
Added 7 topic-specific male/female case pairs, a local copy of the shared anesthesia-options set, two levels of source mapping and an explicit verification standard. The profiles are entirely synthetic; the source checks are scoped and do not certify clinical validity. Existing clinical/manuscript text and PDF exports are preserved.


## 29 October 2026 — Portfolio presentation and reading path

Added a concise reader’s guide, explicit AI-assistance/authorship scope and review-status notes. Linked the portfolio home and corrected navigation wording. This presentation pass preserves substantive manuscripts, casebooks, code and existing exports. Repository visibility is unchanged.

## November 2026 — accuracy and governance review

*Dated 5 November 2026. Author: Collin B. George, pre-medical student. AI-assisted editing is disclosed in [AUTHORSHIP_AND_REVIEW.md](AUTHORSHIP_AND_REVIEW.md).*

### What changed

1. **The educational dosing reference was restored.** The rc2 discussion stubs were replaced with operational content from a citation-audited v2.0 draft (kept locally, not previously published). The live filenames were kept so external links keep working:
   - v2.0 `06_References_and_Evidence.md` → `06_References_Evidence_Breast_Augmentation.md`, titled "References & Evidence".
   - v2.0 `07_OR_Readiness_Checklist.md` → `OR_Checklist_Pre-Induction.md`.
   - v2.0's `docs/index.html` was not restored.
   - Every live-only file was kept (cases, shared guide, audits, manifests, governance files).
2. **[DOSING_SOURCES.md](DOSING_SOURCES.md) was added**, with entries S1–S39.
   - Every numeric dose, rate, maximum, interval, conversion factor, threshold or timing in the restored documents carries an inline tag linking to an entry.
   - Each entry gives the full citation or FDA label, the exact values it supports, and how it was verified.
   - Only these source types are accepted: guidelines and consensus statements, FDA labels, and score-validation papers.
3. **rc2 corrections that are stricter than v2.0 were preserved:**
   - IV lidocaine is never combined with blocks or infiltration (Foo 2021). v2.0 had allowed it "if the attending elects", or as an alternative to infiltration with a shared budget.
   - POFA is framed as showing important adverse outcomes.
   - There is no first/second/third-line order and no "preferred / fallback / lowest PONV / superior analgesia" language. v2.0's "Preferred" and "Fallback" labels, its "Bottom line: start with Protocol 1" statement, its "best for" columns, and the comparison table's "choose / avoid" summary were removed or reframed as considerations.
   - No numeric respiratory triggers before seeking help.
   - No fixed home instructions.
4. **Citation currency:**
   - The fifth PONV consensus (Gan 2025, doi:10.1213/ANE.0000000000007816) was added. Its PMID is unverified: PMID 41237407, cited by the sibling review repository, could not be confirmed in this session.
   - The fourth consensus (Gan 2020) is kept and labeled historical, because its dose table is the one that could be checked.
   - The ASRA antithrombotic guideline is now Kopp 2025 (fifth edition).
   - The 2026 ASA local/regional analgesia guideline (Joshi, *Anesthesiology* 2026;144:19-43, PMID 41363869) was added.
   - Also added: the ASRA/AAPM/ASA ketamine consensus (Schwenk 2018), the CDC 2022 opioid guideline, the STOP-Bang papers (Chung 2008, 2016), Aldrete 1995, and the ASA basic monitoring standard (amended 2025).

### Dose values changed to match the source (v2.0 → now)

**Anesthetic agents and reversal**
- Propofol induction 1.5–2 mg/kg → about 2–2.5 mg/kg (<55 y) / 1–1.5 mg/kg (elderly, debilitated, ASA III–IV). Diprivan label, S16.
- Propofol maintenance 75–150 mcg/kg/min → 100–200 / 50–100 mcg/kg/min. S16.
- Rocuronium 0.6–1 mg/kg → 0.6 mg/kg, and RSI 0.6–1.2 mg/kg. S17.
- Neostigmine 0.03–0.05 mg/kg (max 5 mg) → 0.03–0.07 mg/kg, max 0.07 mg/kg or 5 mg, whichever is less. S12.
- Sugammadex "TOF 2–4 → 2 mg/kg; TOF 0–1 → 4 mg/kg" → label wording: 2 mg/kg at T2 reappearance; 4 mg/kg at 1–2 post-tetanic counts. S11.
- Phenylephrine 50–100 mcg → 40–100 mcg bolus, with the label's repeat-bolus and infusion limits. S28.
- Glycopyrrolate for bradycardia 0.2–0.4 mg → 0.1 mg, repeated every 2–3 min. S13.
- IV lidocaine "max 100 mg" cap → consensus limits: ≤1.5 mg/kg IBW, ≤1.5 mg/kg/h, ≤120 mg/h, ≤24 h, not under 40 kg. S1.

**Adjuncts**
- Dexmedetomidine: v2.0's 0.2–0.5 mcg/kg/h falls within the label range and was kept. The label's loading dose, procedural maintenance range (0.2–1 mcg/kg/h), >65 y reduction and hepatic reduction were added, and the use was marked off-label. S14.
- Ketamine fixed 10–20 mg microboluses → expressed as the consensus limit, bolus ≤0.35 mg/kg (infusion up to about 1 mg/kg/h). v2.0's 0.2–0.3 mg/kg and 0.1–0.2 mg/kg/h fall within it. S15.

**Opioids and naloxone**
- Hydromorphone PACU rescue "0.2–0.4 mg q15–20 min / 0.4–0.8 mg (tolerant) / q20–30 min (elderly, OSA)" → label 0.2–1 mg IV slowly, every 2–3 h. Lower start (0.2 mg) in elderly or debilitated patients; ¼–½ dose in hepatic or renal impairment; PACU titration interval per institutional protocol. S19.
- Fentanyl induction phenotype table (0.5–2 mcg/kg by group) → label statements: individualize; low-dose general-anesthesia tier 2 mcg/kg; reduce in elderly and debilitated patients. S18.
- Naloxone 0.04–0.08 mg every 2–3 min → label 0.1–0.2 mg every 2–3 min, with repeat doses possible at 1–2 h intervals. S22.

**Non-opioid analgesics**
- Ketorolac "15 mg IV q6h" → label tiers. <65 y: 30 mg every 6 h, max 120 mg/day. ≥65 y, renal impairment or <50 kg: 15 mg every 6 h, max 60 mg/day. ≤5 days. S23.
- Ibuprofen 600 mg q6h / 400–600 mg q6h → 400 mg every 4–6 h. S26.
- Celecoxib premedication 200–400 mg → label acute-pain regimen, 400 mg then 200 mg if needed on day 1. S25.

**Antiemetics and PONV**
- Promethazine 6.25–12.5 mg → 6.25 mg. S7.
- Scopolamine patch "continue ×72 h" → removed 24 h after surgery, per label. S30.
- Apfel risk ~10/20/40/60/80% → 10/21/39/61/79%. S9.
- PONV rescue gained amisulpride 10 mg (label). Prophylaxis options gained amisulpride 5 mg. S31.

**Antibiotics**
- Cefazolin timing "30–60 min before incision" → "within 60 min". S6.
- Vancomycin redosing "q12h" → not applicable. S6.

**Scores**
- Aldrete oxygen item "SpO₂ >90% with O₂ = 1" → "needs O₂ to maintain SpO₂ >90%". The circulation middle band is stated as ±20–49 mmHg. S34.

### Values deleted (no acceptable, verifiable source)

**Local anesthetics and blocks (Protocol 1, Protocol 2)**
- PECS I/II and serratus per-plane volumes.
- "Typical" bilateral volumes.
- Infiltration example volumes and concentrations.
- mg/kg ceilings (about 3 mg/kg ropivacaine; 2–2.5 mg/kg bupivacaine). The U.S. labels give absolute doses instead (S4, S5).
- Minimum-weight column.
- "Aspirate every 3–5 mL".
- Perineural dexamethasone 2–4 mg.
- Epinephrine 1:400,000.
- Ultrasound frequency and needle size.
- Block-assessment timing and dermatomes.

**Premedication and adjuncts**
- Gabapentin 100–300 mg and "300 mg maximum" (perioperative use is off-label; no acceptable dose source).
- Midazolam elderly "≤0.5–1 mg".
- Elderly-specific dexmedetomidine and ketamine numbers. Replaced by label reductions.
- "Stop dexmedetomidine 10–15 min before end".
- "Stop ketamine 5–10 min before end".

**Intraoperative targets and airway**
- Preoxygenation duration and EtO₂ target.
- BIS ranges.
- MAC fractions; sevoflurane and desflurane percentages.
- Ventilation targets: tidal volume, PEEP, respiratory rate, EtCO₂, FiO₂, SpO₂.
- MAP, HR and temperature targets.
- Fluid rate, "<1500 mL", "LR 500–1000 mL".
- HR triggers for bradycardia treatment.
- ETT sizes and cuff pressure.
- Extubation thresholds (RR, SpO₂, BIS 70–80, 5-s head lift).
- RASS cut-offs.
- Succinylcholine 1–1.5 mg/kg (label not verified this session).

**Opioid technique and PACU monitoring (Protocol 3)**
- Fentanyl infusion 0.5–1 mcg/kg/h and 1–1.5 mcg/kg/h (tolerant).
- Fentanyl 25–50 / 50–100 mcg increments; "typical total 100–200 mcg".
- "Stop fentanyl 20–30 min before end".
- "Hydromorphone ≥20–30 min before extubation"; "provides 3–4 h".
- "Hydromorphone 0.8–1.2 mg total".
- Fixed PACU vital-sign, SpO₂ and RASS intervals and durations.
- Exposure triggers (">150/200 mcg fentanyl equivalent").
- Capnography alarm values; RR/SpO₂/RASS severity tables for naloxone.
- Naloxone 0.04 mg/mL dilution instruction, infusion 0.04–0.08 mg/h, "usually 0.4 mg total", half-life figure, "4–6 h minimum" monitoring.
- Respiratory-depression incidence "1–5%".
- Monitored-bed numeric triggers.
- OSA discharge minute rules, AHI and exposure thresholds.
- "Reduce 33–50%" and "reduce all agents 25–33%".
- Chronic-opioid ">50 MME/day" threshold.

**PONV**
- Metoclopramide 10 mg (dose not confirmed in the cited consensus this session).
- Ondansetron infusion 1 mg/h.
- Propofol 10–20 mg rescue.
- Repeat dexamethasone 4 mg.
- Home ondansetron #10–15.

**Opioid conversion and home prescribing**
- IV equianalgesic table: hydromorphone 1.5 mg IV ≈ fentanyl 100 mcg ≈ morphine 10 mg IV, with its worked IV example. Only the CDC oral MME factors are given (S21).
- Oxycodone prescription quantities (#5–20) and durations (3–5 days; taper 1–3 days).
- "ER 40 mg + IR 10 mg #20" example.
- Expected home pain-score course.

**Antibiotics and irrigation**
- Vancomycin "max 2 g".
- Triple-antibiotic irrigation recipe (cefazolin 1 g + gentamicin 80 mg + bacitracin 50,000 U per 500 mL). Its sources are primary studies, and bacitracin injection was withdrawn (S38).
- Pulse lavage "≥3 L".

**Surgical workflow (04)**
- All clock times (T-60 … T+100 min) and "typical OR time 90–130 min".
- Upright angle 45–80°.
- Arm abduction "<90°" (replaced by "avoid hyperabduction").
- Suture sizes.

**PACU, discharge and home (05, 02, 04)**
- O₂ 2–4 L/min and SpO₂ ≥94%.
- Vitals q15 min.
- Pain ≤4/10 targets.
- "Stable vitals ×1–2 h".
- Drain emptying every 8–12 h; removal "<30 mL/24 h ×2 days".
- Lifting 5–10 lb; activity week bands.
- Showering 48 h; Steri-Strips 7–14 days.
- Alcohol 48–72 h; driving 24 h.
- Fever >101°F; drain output >100 mL/shift.
- Follow-up schedule.
- Counseling-script recovery timings and "2–4 injections".

**OR checklist**
- E-cylinder "≥1800–2200 psi".
- Push-dose epinephrine 10 mcg/mL.

**Quality metrics**
- QI trigger percentages (>30%, >15%, >5%).

### Other content changes
- v2.0's ranking and "superior / lowest" language was removed (see item 3 above).
- The counseling script's "Nausea risk: Lowest / Low / Higher" and "Best for" columns were replaced with a neutral trade-offs column.
- A "values deliberately not given" section was added to DOSING_SOURCES.md.
- The author line was standardized to "Collin B. George, pre-medical student". v2.0's "B.A.S." was removed.

### Review findings applied (reviewer A, November 2026)
- **#3** — `APPLIED_CASES.md` registry: guideline N now attributed to Thilen SR et al., with volume and pages; B given 2026;144:19-43. The same correction was made in `EXAMPLE_SOURCE_AUDIT.json`.
- **#7** — BR-06's awareness point now cites T (Nimmo 2019 TIVA/pEEG) instead of N (in the Markdown and the JSON case map).
- **#8** — Duplicate DOI links removed from the `APPLIED_CASES.md` registry. Markdown links stripped from JSON `title` strings.
- **#9** — Circular "See ANESTHESIA_OPTIONS_AND_CASES.md" `checked` fields replaced with a check statement that cross-references `SHARED_SOURCE_AUDIT.json`.
- **#10, #11** — The boilerplate three-source "Sources and limits" blocks and the fragile POFA PDF link were removed with the replaced modules. Module-specific tags and DOI links are used instead.
- **#12** — A retained-filename note was added to 06.
- **#13** — The README disclaimer blockquote now sits directly under the H1.
- **Not applied** (outside scope or done elsewhere):
  - #1 (capnography wording) was already fixed in the shared guide.
  - #2, #4, #5 and #6 concern `ANESTHESIA_OPTIONS_AND_CASES.md` and `SHARED_SOURCE_AUDIT.json`, which were left unchanged as instructed.
  - #14 is informational.

### Verification limits
- DailyMed, Drugs@FDA, PubMed and doi.org could not be opened from the build environment. Labels and identifiers were checked through web-search records of FDA-hosted label PDFs, manufacturer pages, label mirrors and indexing services. Each DOSING_SOURCES entry states what was confirmed.
- **Unverified identifiers:**
  - the fifth PONV consensus PMID;
  - the CDC 2022 PMID;
  - the Bratzler and Chung DOIs;
  - the ASRA 2020 checklist DOI (recorded from the repository's audit, not re-resolved).
- **Partly verified content:**
  - The CDC MME factor values were taken from the guideline's table as read by the author; the search record did not display them.
  - The promethazine and scopolamine consensus details came from secondary summaries.
  - The ASRA LAST checklist dosing panel was confirmed only in secondary reproductions.

### Folded in: v2.0 review notes and changelog (November 2026, previously unpublished)

**v2.0 summary judgment.** v1.0 had a sound structure. Its safety framing was careful in many places: LAST, opioid stacking, the naloxone protocol and delirium mitigation. Three problems would have undermined it with any physician reader:
1. **Citation integrity.** 14 of 24 references matched no published article, and 9 more had the wrong year, journal, title or edition.
2. **Outcome figures with no source.** Examples: "PONV 3–8% vs 15–25%", "respiratory events <2% vs 5–10%" and "PACU 60–90 vs 120–180 min". These ran opposite to the best RCT on dexmedetomidine-based OFA (POFA 2021).
3. **Arithmetic and consistency errors:**
   - local-anesthetic volumes exceeding mg/kg ceilings in small patients;
   - IV lidocaine stacked on bilateral blocks;
   - lipid emulsion marked "not needed" for pathways using infiltration;
   - single-agent PONV prophylaxis at Apfel 2;
   - an incorrect oxycodone conversion (15 → 20 mg PO per 10 mg IV morphine);
   - a per-liter triple-antibiotic recipe that should have been per 500 mL.

**v2.0 changes.**
- **Citations.** 14 unmatched entries were removed and 9 corrected. Verified sources were added: POFA, Foo 2021, Verret 2020, Kharasch 2020, Grape 2020, Hussain 2019, Thilen 2023, Neal 2018/2021, Kopp 2025, Bratzler 2013, Jewell 2021, the FDA 2020 bacitracin withdrawal, and the FDA 2020/2021 implant labeling. "Strong (A)" labels were replaced with author-judged certainty levels.
- **Clinical safety corrections:**
  - a calculate-ceiling-first instruction for local anesthetic;
  - IV lidocaine omitted with blocks and infiltration;
  - lipid emulsion available in all pathways;
  - two-agent PONV prophylaxis at Apfel 1–2;
  - PACU PONV rescue from a different drug class;
  - neostigmine limited to minimal-depth block, with quantitative TOFR ≥0.9;
  - removal of sedative escalation in Protocol 2;
  - chronic opioid use routed to block + multimodal care with the baseline continued;
  - MOUD continued, with indicated opioids not withheld;
  - lymphedema-side BP cuff and IV guidance;
  - separate cefazolin and vancomycin timing;
  - gabapentinoids removed from routine premedication;
  - anticoagulation recast as relative and block-depth-dependent per ASRA.
- **Analytic integrity.**
  - All unsourced numeric outcome benchmarks were removed.
  - The pathway hierarchy was reframed around block evidence and opioid stewardship.
  - Promotional language was removed from the counseling script, and implant-specific risks (BIA-ALCL) and block risks were added.
  - "Validated, Clinically Accurate" was removed from the OR checklist.
- **Hygiene.** Broken README links fixed. Scope unified as post-mastectomy implant revision, not cosmetic augmentation.

**Open items carried forward from v2.0 (still open):**
- [ ] Fill remaining PMIDs and DOIs from PubMed when it is reachable.
- [ ] Review PROSPECT 2026 for oncological breast surgery (Desai et al., *Anaesthesia*, doi:10.1111/anae.70313) and reconcile it with the three approaches, especially gabapentinoids and block choice.
- [ ] Read the full fifth PONV consensus dose table and update S7/S8.
- [ ] Re-check each label entry directly on DailyMed or Drugs@FDA.
- [ ] Capsulectomy and drain criteria remain expert-opinion level.
- [ ] An anesthesiologist's review would strengthen the portfolio. Do not describe the work as "attending-reviewed" unless that review actually happens.
