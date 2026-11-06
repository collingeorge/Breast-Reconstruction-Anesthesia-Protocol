# Dosing sources registry

> **Educational work by a pre-medical student — not medical advice.** Not a clinical protocol, prescription, or patient handout, and not for patient care. See [DISCLAIMER](DISCLAIMER.md).

Author: Collin B. George, pre-medical student. Registry compiled November 2026.

## What this file is

Every numeric dose, rate, maximum, interval, conversion factor, threshold or timing in the educational dosing reference (modules 01–05, `03_Anesthesia_Protocols/`, and the pre-induction checklist) carries an inline tag such as [S4](#s4). The tag points to one entry below. Each entry gives the citation, the exact numbers it supports, and how the entry was checked.

The numbers are **illustrative**. They show what the cited source states. They are not orders, they are not validated for implant-revision surgery, and every real dose is individualized by the treating clinician under institutional policy. Several intraoperative uses described in the modules (for example, dexmedetomidine as a general-anesthesia adjunct, IV lidocaine infusion, low-dose ketamine and haloperidol for PONV) are **outside FDA-labeled indications**; for those, the tag points to a consensus statement, not to the label.

**Acceptable source types (and only these):**
- society guidelines, consensus statements and practice advisories;
- FDA-approved prescribing information;
- the original validation papers for scoring tools.

Narrative reviews, single trials, textbooks and websites are not used as dose sources. Where v2.0 of this repository gave a dose that none of these sources supports, the value was changed to the source value or deleted. Every change is listed in [RELEASE_NOTES.md](RELEASE_NOTES.md).

**Verification limits (stated plainly).** For this session, DailyMed (dailymed.nlm.nih.gov), Drugs@FDA (accessdata.fda.gov), PubMed and doi.org could not be opened directly from the build environment. Label content was therefore checked through web-search records of FDA-hosted label PDFs, manufacturer prescribing-information pages and label mirrors (medlibrary.org, drugs.com and similar), and journal identifiers through publisher and indexing records. Each entry says what was confirmed. Where an identifier could not be confirmed it is omitted and marked "(identifier unverified)". Labels are revised often and vary by manufacturer: **check the current label for the specific product before relying on any number.**

## Contents

| Tag | Source | Type |
|---|---|---|
| [S1](#s1) | Foo et al. 2021, IV lidocaine consensus | Consensus statement |
| [S2](#s2) | Neal et al. 2018, ASRA LAST practice advisory | Practice advisory |
| [S3](#s3) | Neal et al. 2021, ASRA LAST checklist (2020 version) | Society checklist |
| [S4](#s4) | Ropivacaine (Naropin) | FDA label |
| [S5](#s5) | Bupivacaine (Marcaine) | FDA label |
| [S6](#s6) | Bratzler et al. 2013, ASHP/IDSA/SIS/SHEA surgical prophylaxis | Guideline |
| [S7](#s7) | Gan et al. 2020, Fourth PONV consensus | Consensus guideline |
| [S8](#s8) | Gan et al. 2025, Fifth PONV consensus (executive summary) | Consensus guideline |
| [S9](#s9) | Apfel et al. 1999, simplified PONV risk score | Score validation |
| [S10](#s10) | Thilen et al. 2023, ASA neuromuscular blockade guideline | Guideline |
| [S11](#s11) | Sugammadex (Bridion) | FDA label |
| [S12](#s12) | Neostigmine (Bloxiverz) | FDA label |
| [S13](#s13) | Glycopyrrolate injection | FDA label |
| [S14](#s14) | Dexmedetomidine (Precedex) | FDA label |
| [S15](#s15) | Schwenk et al. 2018, ASRA/AAPM/ASA ketamine consensus | Consensus guideline |
| [S16](#s16) | Propofol (Diprivan) | FDA label |
| [S17](#s17) | Rocuronium bromide injection | FDA label |
| [S18](#s18) | Fentanyl citrate injection | FDA label |
| [S19](#s19) | Hydromorphone hydrochloride injection | FDA label |
| [S20](#s20) | Oxycodone immediate-release (Roxicodone) | FDA label |
| [S21](#s21) | CDC 2022 opioid prescribing guideline | Guideline |
| [S22](#s22) | Naloxone hydrochloride injection | FDA label |
| [S23](#s23) | Ketorolac tromethamine injection | FDA label |
| [S24](#s24) | Acetaminophen injection (Ofirmev) | FDA label |
| [S25](#s25) | Celecoxib (Celebrex) | FDA label |
| [S26](#s26) | Ibuprofen tablets (prescription) | FDA label |
| [S27](#s27) | Midazolam hydrochloride injection | FDA label |
| [S28](#s28) | Phenylephrine (Biorphen) | FDA label |
| [S29](#s29) | Ephedrine sulfate (Akovaz) | FDA label |
| [S30](#s30) | Scopolamine transdermal (Transderm Scop) | FDA label |
| [S31](#s31) | Amisulpride (Barhemsys) | FDA label |
| [S32](#s32) | Chung et al. 2008, STOP / STOP-Bang questionnaire | Score validation |
| [S33](#s33) | Chung et al. 2016, STOP-Bang risk categories | Score validation |
| [S34](#s34) | Aldrete 1995, post-anesthesia recovery score revisited | Score validation |
| [S35](#s35) | ASA Standards for Basic Anesthetic Monitoring | Society standard |
| [S36](#s36) | Kopp et al. 2025, ASRA antithrombotic guideline (5th ed.) | Guideline |
| [S37](#s37) | Joshi et al. 2026, ASA local/regional analgesia guideline | Guideline |
| [S38](#s38) | FDA 2020, bacitracin for injection withdrawal request | FDA action |
| [S39](#s39) | FDA 2020 breast implant labeling guidance and 2021 labeling approval | FDA guidance/action |

---

## Local anesthetics and LAST

### S1
**Foo I, Macfarlane AJR, Srivastava D, et al.** The use of intravenous lidocaine for postoperative pain and recovery: international consensus statement on efficacy and safety. *Anaesthesia*. 2021;76(2):238-250. doi:10.1111/anae.15270. PMID 33141959.

- **Supports:** loading dose ≤1.5 mg/kg given over about 10 min; infusion ≤1.5 mg/kg/h; duration ≤24 h with review; dosing on **ideal body weight**; an hourly ceiling of 120 mg/h for any patient; not for patients under 40 kg; IV lidocaine **not given concurrently with other local-anesthetic interventions** (nerve blocks, wound infiltration) or while their effect is still active; separation of about 4 h between a nerve block and starting IV lidocaine, and about 4 h after stopping IV lidocaine before a block.
- **Note:** IV lidocaine infusion for analgesia is not an FDA-labeled indication.
- **Verified via:** WebSearch record of the abstract and full-text excerpts (Nottingham and Glasgow repository copies; read.qxmd.com/read/33141959), 2026-11-05.

### S2
**Neal JM, Barrington MJ, Fettiplace MR, et al.** The third American Society of Regional Anesthesia and Pain Medicine practice advisory on local anesthetic systemic toxicity: executive summary 2017. *Reg Anesth Pain Med*. 2018;43(2):113-123. doi:10.1097/AAP.0000000000000720. PMID 29356773.

- **Supports (qualitative only):** prevention by lowest effective dose, incremental injection with aspiration, ultrasound guidance, and immediate availability of lipid emulsion. This repository does **not** cite it for a mg/kg ceiling or for a specific aliquot volume; those could not be confirmed in this session.
- **Verified via:** WebSearch record of rapm.bmj.com/content/43/2/113 and qxmd.com/r/29356773, 2026-11-05.

### S3
**Neal JM, Neal EJ, Weinberg GL.** American Society of Regional Anesthesia and Pain Medicine local anesthetic systemic toxicity checklist: 2020 version. *Reg Anesth Pain Med*. 2021;46(1):81-82. doi:10.1136/rapm-2020-101986 (DOI as recorded in this repository's SHARED_SOURCE_AUDIT.json; not re-resolved in this session).

- **Supports:** 20% lipid emulsion. Patient >70 kg: bolus 100 mL over 2–3 min, then infusion 200–250 mL over 15–20 min. Patient ≤70 kg: bolus 1.5 mL/kg over 2–3 min, then infusion about 0.25 mL/kg/min. If still unstable: repeat the bolus once or twice and/or double the infusion rate. Upper limit about 12 mL/kg. Reduced epinephrine doses (≤1 mcg/kg). Avoid vasopressin, calcium-channel blockers, beta-blockers and further local anesthetic. Benzodiazepines for seizures. Avoid propofol when there are signs of cardiovascular instability.
- **Verified via:** WebSearch record of rapm.bmj.com/content/46/1/81 (publication record), with the dosing panel confirmed only in secondary reproductions of the checklist (APSF, flashcard and treatment-guide copies), 2026-11-05. Readers should use the official checklist from asra.com.

### S4
**Ropivacaine hydrochloride injection (NAROPIN).** Fresenius Kabi USA. FDA-approved prescribing information. DailyMed setid 6a2f1f6d-026f-4f39-aee0-5b75b8eb5c02: https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=6a2f1f6d-026f-4f39-aee0-5b75b8eb5c02 (label revision date not retrieved).

- **Supports:** the label's adult dosage table. Major nerve block, 5 mg/mL (0.5%): 35–50 mL (175–250 mg). Field block (minor nerve block and infiltration): 1–40 mL of 5 mg/mL (5–200 mg); infiltration at 2 mg/mL (0.2%): 2–200 mg. Doses are adult guidelines to be adjusted to the site and the patient's status. The label gives **no mg/kg ceiling**.
- **Verified via:** WebSearch record of the DailyMed listing and the medlibrary.org copy of the dosage table, 2026-11-05. The current label renders the table as an image, so the figures are from the most recent text version found.

### S5
**Bupivacaine hydrochloride injection (MARCAINE).** Hospira, Inc. (Pfizer). FDA-approved prescribing information. https://www.pfizermedical.com/marcaine/dosage-admin (label revision date not retrieved).

- **Supports:** the maximum dosage limit is to be individualized by patient size, physical status and expected absorption; most experience is with single doses up to 175 mg without epinephrine and up to 225 mg with epinephrine 1:200,000; total daily dose not to exceed 400 mg in 24 h. The U.S. label gives **no mg/kg ceiling** (mg/kg figures in circulation come from secondary references, not this label).
- **Verified via:** WebSearch record of pfizermedical.com Marcaine dosage-and-administration page and medlibrary.org label copy, 2026-11-05.

## Antibiotic prophylaxis

### S6
**Bratzler DW, Dellinger EP, Olsen KM, et al.** Clinical practice guidelines for antimicrobial prophylaxis in surgery. *Am J Health Syst Pharm*. 2013;70(3):195-283. PMID 23327981. (Joint ASHP/IDSA/SIS/SHEA guideline; also published in *Surg Infect (Larchmt)*. 2013;14(1):73-156. DOI not re-verified in this session.)

- **Supports:** cefazolin 2 g IV; 3 g if weight ≥120 kg; start within 60 min before incision; redose every 4 h during prolonged surgery. Vancomycin 15 mg/kg IV, started within 120 min before incision; routine redosing not applicable. Clindamycin 900 mg IV; redose every 6 h. Cefazolin is the recommended agent for clean plastic surgery with implants (including breast), with clindamycin or vancomycin as β-lactam-allergy alternatives. Prophylaxis duration under 24 h.
- **Verified via:** WebSearch record of the OU publication list (PMID 23327981) and of institutional summaries of the guideline (UNMC surgical prophylaxis and redosing tables; ASA quality measure using the 4-h cefazolin interval), 2026-11-05. Breast-specific wording was not confirmed against the original table in this session.

## PONV

### S7
**Gan TJ, Belani KG, Bergese S, et al.** Fourth consensus guidelines for the management of postoperative nausea and vomiting. *Anesth Analg*. 2020;131(2):411-448. doi:10.1213/ANE.0000000000004833. PMID 32467512.

- **Supports:** multimodal prophylaxis for adults with 1–2 risk factors (two agents) and with more than 2 risk factors (three to four agents). Dexamethasone 4–8 mg IV at induction. Ondansetron 4 mg IV at end of surgery. Droperidol 0.625 mg IV at end of surgery. Haloperidol 0.5 to <2 mg IV/IM (off-label). Promethazine 6.25 mg. Transdermal scopolamine applied the evening before or 2 h before surgery. Rescue should use a drug class different from the prophylactic agent; repeating a 5-HT3 antagonist within 6 h of the prophylactic dose adds little benefit.
- **Verified via:** WebSearch records of PubMed 32467512 and of the APSF podcast notes and the Meyer TSHP handout summarizing Table 4, 2026-11-05. The promethazine and scopolamine details come from secondary summaries; the original Table 4 was not opened.
- **Status:** the fourth consensus is superseded in part by the fifth [S8](#s8). It is kept because the fifth's full dose table could not be read in this session.

### S8
**Gan TJ, et al.** Fifth consensus guidelines for the management of postoperative nausea and vomiting: executive summary. *Anesth Analg*. Published online November 14, 2025. doi:10.1213/ANE.0000000000007816. PMID: identifier unverified (a sibling repository cites PMID 41237407; this session could not confirm it).

- **Supports:** prophylaxis with **two interventions in adults at risk** of PONV (guideline 3 of the full report); dexamethasone 4–8 mg IV at induction (8 mg may be optimal); ondansetron 4 mg IV (or 16 mg PO) at end of surgery; dexamethasone plus a 5-HT3 antagonist as the best-studied pair. Secondary summaries report three to four agents for adults with ≥3 risk factors; that statement is tagged to [S7](#s7) in this repository.
- **Verified via:** WebSearch records of journals.lww.com (executive summary landing page), the LWW-hosted full report (cdn-links.lww.com/permalink/aa/f/aa_1_1_2025_11_24_cd_1_sdc1.pdf), scholars.duke.edu and a NYSORA summary, 2026-11-05. Full text not opened.

### S9
**Apfel CC, Läärä E, Koivuranta M, Greim CA, Roewer N.** A simplified risk score for predicting postoperative nausea and vomiting: conclusions from cross-validations between two centers. *Anesthesiology*. 1999;91(3):693-700. doi:10.1097/00000542-199909000-00022. PMID 10485781.

- **Supports:** four risk factors (female sex, non-smoking, history of PONV or motion sickness, postoperative opioids), one point each. Estimated PONV incidence for 0, 1, 2, 3 and 4 factors: about 10%, 21%, 39%, 61% and 79%.
- **Verified via:** citation and percentages as audited in v2.0 of this repository against the PubMed record; not re-searched in this session (2026-11-05).

## Neuromuscular blockade and reversal

### S10
**Thilen SR, Weigel WA, Todd MM, et al.** 2023 American Society of Anesthesiologists practice guidelines for monitoring and antagonism of neuromuscular blockade. *Anesthesiology*. 2023;138(1):13-41. doi:10.1097/ALN.0000000000004379. PMID 36520073.

- **Supports:** quantitative monitoring (adductor pollicis preferred) over clinical assessment alone; confirm train-of-four ratio (TOFR) ≥0.9 before extubation; sugammadex over neostigmine for deep, moderate and shallow rocuronium/vecuronium block; neostigmine reasonable at **minimal depth** (TOFR 0.4 to <0.9).
- **Verified via:** WebSearch record of PubMed 36520073 and the APSF summary, 2026-11-05.

### S11
**Sugammadex injection (BRIDION).** Merck Sharp & Dohme LLC. FDA-approved prescribing information, revised 11/2022. https://www.accessdata.fda.gov/drugsatfda_docs/label/2022/022225Orig1s012lbl.pdf

- **Supports:** 2 mg/kg if spontaneous recovery has reached reappearance of the second twitch (T2); 4 mg/kg if recovery has reached 1–2 post-tetanic counts with no twitch response; 16 mg/kg for immediate reversal after rocuronium 1.2 mg/kg. Dosing on actual body weight.
- **Verified via:** WebSearch record of the FDA-hosted 2022 label, the Merck PI (merck.com/product/usa/pi_circulars/b/bridion/bridion_pi.pdf) and the Medsafe datasheet, 2026-11-05.

### S12
**Neostigmine methylsulfate injection (BLOXIVERZ).** Exela Pharma Sciences. FDA-approved prescribing information, 2023 revision. https://www.accessdata.fda.gov/drugsatfda_docs/label/2023/204078Orig1s014lbl.pdf

- **Supports:** 0.03–0.07 mg/kg IV (0.03 mg/kg for agents with shorter half-lives such as rocuronium); maximum total 0.07 mg/kg or 5 mg, whichever is less; give an anticholinergic (glycopyrrolate or atropine) before or with neostigmine.
- **Verified via:** WebSearch record of the FDA-hosted 2023 and 2015 labels and the Amneal PI, 2026-11-05.

### S13
**Glycopyrrolate injection, USP.** Multiple manufacturers (e.g., the label copies indexed at medlibrary.org/lib/rx/meds/glycopyrrolate-54/). FDA-approved prescribing information (revision dates vary by manufacturer).

- **Supports:** with neostigmine reversal, 0.2 mg glycopyrrolate for each 1 mg neostigmine. Intraoperative anticholinergic use: 0.1 mg IV, repeated as needed at 2–3 min intervals.
- **Verified via:** WebSearch record of several glycopyrrolate label copies (medlibrary.org; ndclist.com), 2026-11-05. The 0.1 mg intraoperative wording was confirmed in one manufacturer's label but not tied to its section heading.

## Adjuncts and hypnotics

### S14
**Dexmedetomidine hydrochloride injection (PRECEDEX).** Hospira, Inc. (Pfizer). FDA-approved prescribing information, 2026 revision. https://www.accessdata.fda.gov/drugsatfda_docs/label/2026/021038s061lbl.pdf

- **Supports:** labeled indications are ICU sedation of intubated patients and procedural sedation of non-intubated patients. **Use as an adjunct during general anesthesia is off-label.** Procedural sedation: loading infusion 1 mcg/kg over 10 min (0.5 mcg/kg over 10 min may suit less invasive procedures); maintenance started at 0.6 mcg/kg/h and titrated within 0.2–1 mcg/kg/h. ICU maintenance 0.2–0.7 mcg/kg/h. Patients >65 years: loading 0.5 mcg/kg over 10 min and consider reducing maintenance. Hepatic impairment: consider dose reduction. Bradycardia and hypotension warnings.
- **Verified via:** WebSearch record of the FDA-hosted 2026 and 2013 labels and Pfizer labeling pages, 2026-11-05. The 0.6 and 0.2–1 mcg/kg/h procedural wording was confirmed in the 2013 text; the 2026 procedural section was not opened.

### S15
**Schwenk ES, Viscusi ER, Buvanendran A, et al.** Consensus guidelines on the use of intravenous ketamine infusions for acute pain management from the American Society of Regional Anesthesia and Pain Medicine, the American Academy of Pain Medicine, and the American Society of Anesthesiologists. *Reg Anesth Pain Med*. 2018;43(5):456-466. doi:10.1097/AAP.0000000000000806. PMID 29870457.

- **Supports:** subanesthetic ketamine for acute pain with bolus doses not exceeding 0.35 mg/kg and infusions up to about 1 mg/kg/h; larger doses call for a monitored setting with resuscitation capability. Contraindications for acute pain largely mirror those for chronic pain (see the guideline).
- **Note:** analgesic (subanesthetic) ketamine is outside the anesthetic indications on the FDA label.
- **Verified via:** WebSearch record of PubMed 29870457, PMC6023582 and the ASRA guideline page, 2026-11-05. The 0.35 mg/kg and 1 mg/kg/h figures were confirmed in a secondary summary; the original wording was not opened.

### S16
**Propofol injectable emulsion (DIPRIVAN).** Fresenius Kabi USA. FDA-approved prescribing information, 2022 revision. https://www.accessdata.fda.gov/drugsatfda_docs/Label/2022/019627s069lbl.pdf

- **Supports:** induction in healthy adults <55 years, about 2–2.5 mg/kg (40 mg every 10 s until onset); elderly, debilitated or ASA III–IV, about 1–1.5 mg/kg (20 mg every 10 s). Maintenance infusion: 100–200 mcg/kg/min in healthy adults <55 years; 50–100 mcg/kg/min in elderly, debilitated or ASA III–IV patients. The label's maintenance rates assume co-administered agents (nitrous oxide or opioids); requirements change with adjuncts.
- **Verified via:** WebSearch record of the FDA-hosted 2022 label and the medlibrary.org label copy, 2026-11-05.

### S17
**Rocuronium bromide injection.** Generic manufacturer label (e.g., DailyMed setid a54a79f7-5207-43d8-a139-7d57557caa50: https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=a54a79f7-5207-43d8-a139-7d57557caa50) and Pfizer prescribing information (https://www.pfizermedical.com/rocuronium-bromide-injection/dosage-admin). Revision dates vary.

- **Supports:** recommended initial intubating dose 0.6 mg/kg; rapid sequence intubation 0.6–1.2 mg/kg; maintenance doses guided by response to the prior dose (older labels: 0.1, 0.15 or 0.2 mg/kg at 25% recovery of T1).
- **Verified via:** WebSearch record of the Pfizer dosage page, the DailyMed listing and an FDA-hosted 2026 rocuronium label, 2026-11-05.

### S27
**Midazolam hydrochloride injection, USP.** Multiple manufacturers (e.g., DailyMed setid e22611dd-1830-40af-9139-7cdb07f5a426: https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=e22611dd-1830-40af-9139-7cdb07f5a426). Revision dates vary.

- **Supports:** dosage must be individualized; IV sedation in a healthy adult starts with as little as 1 mg and should not exceed 2.5 mg as the initial dose, titrated slowly; reduce dose in older, debilitated or chronically ill patients and with concomitant opioids or CNS depressants. Boxed warning on respiratory depression and continuous monitoring.
- **Verified via:** WebSearch record of a prescriberpoint.com label copy and the DailyMed listing, 2026-11-05. The age ≥60 figure (1.5 mg) was **not** confirmed and is not used.

## Opioids and opioid reversal

### S18
**Fentanyl citrate injection, USP.** Hospira, Inc. (Pfizer), https://pfizermedicalinformation.com/fentanyl-citrate/dosage-admin; and Fresenius Kabi label copies. Revision dates vary.

- **Supports:** dosing individualized by age, weight, physical status, other drugs, anesthetic type and procedure. Premedication 50–100 mcg IM 30–60 min before surgery. General-anesthesia "low dose" tier: 2 mcg/kg (for minor procedures). Reduce the initial dose in elderly and debilitated patients and guide further increments by the response to the first dose.
- **Verified via:** WebSearch record of the Pfizer dosage page and Fresenius/medlibrary label copies, 2026-11-05. The label's maintenance-increment range was **not** confirmed and is not used.

### S19
**Hydromorphone hydrochloride injection, USP.** Hospira, Inc. (Pfizer), https://labeling.pfizer.com/ShowLabeling.aspx?id=4472; DailyMed setid e034eb96-03e0-46e1-8b92-5e1f94555e7b. Revision dates vary.

- **Supports:** IV starting dose 0.2–1 mg every 2–3 h as needed, given slowly over at least 2–3 min; initial dose reduced in elderly or debilitated patients (may be lowered to 0.2 mg); start hepatic or renal impairment at one-fourth to one-half of the usual starting dose. The high-potency formulation is only for opioid-tolerant patients.
- **Verified via:** WebSearch record of Pfizer labeling pages and the DailyMed listing, 2026-11-05.

### S20
**Oxycodone hydrochloride tablets (ROXICODONE).** DailyMed setid 5a8157d3-ba20-4abf-b0d4-6ad141b31d63: https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=5a8157d3-ba20-4abf-b0d4-6ad141b31d63 (April 2026 revision as indexed).

- **Supports:** as the first opioid analgesic, initiate at 5–15 mg every 4–6 h as needed; titrate to response; use the lowest effective dose for the shortest duration.
- **Verified via:** WebSearch record of the DailyMed listing (section 2.3 heading) and drugs.com dosage reproductions, 2026-11-05. The numeric range was confirmed in label reproductions, not in the DailyMed text itself.

### S21
**Dowell D, Ragan KR, Jones CM, Baldwin GT, Chou R.** CDC Clinical Practice Guideline for Prescribing Opioids for Pain — United States, 2022. *MMWR Recomm Rep*. 2022;71(No. RR-3):1-95. doi:10.15585/mmwr.rr7103a1. https://www.cdc.gov/mmwr/volumes/71/rr/rr7103a1.htm (PMID: identifier unverified).

- **Supports:** for acute pain, prescribe immediate-release opioids at the lowest effective dose, and no more than needed for the expected duration of severe pain. Morphine milligram equivalent (MME) conversion factors for **oral** opioids: morphine 1, oxycodone 1.5, hydromorphone 5. The factors are for estimating total daily exposure. They are **not** for converting a patient from one opioid to another and are not for IV doses or for opioid-use-disorder treatment. Do not abruptly discontinue long-term opioid therapy. Long-term opioid therapy means use on most days for >3 months.
- **Verified via:** WebSearch record of the CDC MMWR page and the CDC Opioid CDS implementation guide (fhir.org/guides/cdc/opioid-cds), 2026-11-05. The individual factor values were not displayed in the search record. They were transcribed from the guideline's MME table during the AI-assisted November 2026 review (see AUTHORSHIP_AND_REVIEW.md) and not re-displayed in the search record; check the CDC table before reuse.

### S22
**Naloxone hydrochloride injection, USP.** Generic manufacturer labels (e.g., copies indexed at medlibrary.org/lib/rx/meds/naloxone-hydrochloride-14/page/3/). Revision dates vary.

- **Supports:** for postoperative opioid depression, inject 0.1–0.2 mg IV at 2–3 min intervals to the desired degree of reversal (adequate ventilation and alertness without significant pain); larger doses can reverse analgesia and raise blood pressure; repeat doses may be needed at 1–2 h intervals, depending on the opioid, because naloxone's duration can be shorter than the opioid's.
- **Verified via:** WebSearch record of multiple naloxone label copies, 2026-11-05.

## Non-opioid analgesics

### S23
**Ketorolac tromethamine injection, USP.** Hospira, Inc. (Pfizer). https://www.pfizermedical.com/ketorolac-inj/dosage-admin (revision date not retrieved).

- **Supports:** multiple-dose IV/IM: patients <65 years, 30 mg every 6 h, maximum 120 mg/day; patients ≥65 years, renally impaired, or <50 kg, 15 mg every 6 h, maximum 60 mg/day. Combined IV/IM and oral use not to exceed 5 days. Boxed warnings: GI bleeding, cardiovascular and renal risk, bleeding risk, contraindicated in advanced renal impairment.
- **Verified via:** WebSearch record of the Pfizer dosage page and medlibrary.org label copies, 2026-11-05.

### S24
**Acetaminophen injection (OFIRMEV).** Mallinckrodt Hospital Products. FDA-approved prescribing information, NDA 022450 (original 2010 label: https://www.accessdata.fda.gov/drugsatfda_docs/label/2010/022450lbl.pdf; later Mallinckrodt label on DailyMed, SPL set ID c5177abd-9465-40d8-861d-3904496d82b7, effective 2021-12-07: https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=c5177abd-9465-40d8-861d-3904496d82b7). Mallinckrodt told FDA in June 2021 that the 1,000 mg/100 mL presentation was being discontinued; FDA determined it was not withdrawn for reasons of safety or effectiveness (Federal Register, January 2023).

- **Supports:** adults and adolescents ≥50 kg: 1000 mg every 6 h or 650 mg every 4 h, maximum single dose 1000 mg, maximum 4000 mg/day; minimum interval 4 h. Adults <50 kg: 15 mg/kg every 6 h or 12.5 mg/kg every 4 h, maximum 75 mg/kg/day. The daily maximum counts **all routes and all acetaminophen-containing products**. Contraindicated in severe hepatic impairment; caution in hepatic impairment, chronic alcohol use, malnutrition or hypovolemia.
- **Verified via:** WebSearch record of the FDA-hosted 2010 label, the Mallinckrodt PI and drugs.com label copy, 2026-11-05. On 2026-11-06 the Mallinckrodt-hosted PDF link was replaced: the DailyMed set ID was confirmed in WebSearch records of the fda.report DailyMed mirror and the Guideline Central label copy (both name set ID c5177abd-9465-40d8-861d-3904496d82b7, OFIRMEV, Mallinckrodt Hospital Products Inc., effective 2021-12-07; Guideline Central shows the ≥50 kg dosing above and the 4000 mg/day maximum). The <50 kg regimen and 4 h minimum interval were re-confirmed in a WebSearch record of the 2010 FDA label. The discontinuation and determination come from a WebSearch record of the January 2023 Federal Register notice. The DailyMed page itself could not be opened from the build machine (network policy).

### S25
**Celecoxib capsules (CELEBREX).** Pfizer (now distributed by Viatris). FDA-approved prescribing information (revision date not retrieved; copies indexed at medlibrary.org/lib/rx/meds/celebrex-18/).

- **Supports:** acute pain in adults: 400 mg initially, then an additional 200 mg if needed on the first day; thereafter 200 mg twice daily as needed. Boxed warnings: cardiovascular thrombotic events (contraindicated for CABG peri-operative pain) and GI bleeding.
- **Verified via:** WebSearch record of label copies (medlibrary.org; ndclist.com), 2026-11-05.

### S26
**Ibuprofen tablets, USP (prescription).** Generic manufacturer labels (e.g., copies indexed at medlibrary.org/lib/rx/meds/ibuprofen-96/page/6/). Revision dates vary.

- **Supports:** mild to moderate pain: 400 mg every 4–6 h as needed; in controlled analgesic trials, doses above 400 mg were no more effective than 400 mg. NSAID boxed warnings (cardiovascular, GI).
- **Verified via:** WebSearch record of label copies, 2026-11-05.

## Vasopressors

### S28
**Phenylephrine hydrochloride injection (BIORPHEN).** FDA-approved prescribing information, 2019. https://www.accessdata.fda.gov/drugsatfda_docs/label/2019/212909s000lbl.pdf

- **Supports:** hypotension during anesthesia: initial IV bolus 40–100 mcg; additional boluses every 1–2 min as needed, not exceeding 200 mcg per bolus; infusion 10–35 mcg/min, not exceeding 200 mcg/min. Concentration-specific dilution instructions.
- **Verified via:** WebSearch record of the FDA-hosted 2019 label and drugs.com label copy, 2026-11-05.

### S29
**Ephedrine sulfate injection (AKOVAZ).** Exela Pharma Sciences. FDA-approved prescribing information (drugs.com copy last updated December 2022: https://www.drugs.com/pro/akovaz.html).

- **Supports:** clinically important hypotension in the setting of anesthesia: IV bolus 5–10 mg as needed, not to exceed 50 mg; tachyphylaxis possible.
- **Verified via:** WebSearch record of drugs.com and medlibrary.org label copies, 2026-11-05.

## Antiemetics (label sources)

### S30
**Scopolamine transdermal system (TRANSDERM SCŌP).** FDA-approved prescribing information (copy at https://drugs.com/pro/transderm-scop.html; revision date not retrieved).

- **Supports:** PONV (non-cesarean surgery): apply one patch behind the ear the evening before surgery and remove it 24 h after surgery; apply at least 4 h before the antiemetic effect is needed. Anticholinergic adverse effects (confusion, visual disturbance), relevant to older patients.
- **Verified via:** WebSearch record of the drugs.com label copy, 2026-11-05.

### S31
**Amisulpride injection (BARHEMSYS).** Acacia Pharma / Eagle Pharmaceuticals. FDA-approved prescribing information (copy at https://www.drugs.com/pro/barhemsys.html; revision date not retrieved).

- **Supports:** prevention of PONV: 5 mg IV over 1–2 min at induction, alone or with an antiemetic of a different class. Treatment of PONV: 10 mg IV over 1–2 min, including after failed prophylaxis with an agent of a different class. QT-prolongation caution.
- **Verified via:** WebSearch record of drugs.com and medlibrary.org label copies, 2026-11-05.

## Scores

### S32
**Chung F, Yegneswaran B, Liao P, et al.** STOP questionnaire: a tool to screen patients for obstructive sleep apnea. *Anesthesiology*. 2008;108(5):812-821. PMID 18431116.

- **Supports:** the STOP items (snoring, tiredness, observed apnea, high blood pressure) and the Bang items added in STOP-Bang (BMI >35 kg/m², age >50 years, neck circumference >40 cm, male sex). Adding the Bang items raised sensitivity for AHI >15 and >30.
- **Verified via:** WebSearch record of PubMed 18431116 and qxmd.com/r/18431116, 2026-11-05. DOI not re-verified.

### S33
**Chung F, Abdullah HR, Liao P.** STOP-Bang questionnaire: a practical approach to screen for obstructive sleep apnea. *Chest*. 2016;149(3):631-638. PMID 26378880.

- **Supports:** STOP-Bang score 0–8. A score of 0–2 is low risk. A score of 3–4 is intermediate risk, needing further criteria. A score of 5–8 is high risk of moderate-to-severe OSA. A cutoff of ≥3 is highly sensitive for moderate-to-severe OSA.
- **Verified via:** WebSearch record of PubMed 26378880 and the UW-hosted STOP-Bang appendix, 2026-11-05. DOI not re-verified.

### S34
**Aldrete JA.** The post-anesthesia recovery score revisited. *J Clin Anesth*. 1995;7(1):89-91. PMID 7772368.

- **Supports:** five items scored 0–2: activity, respiration, circulation (BP within ±20 mmHg of pre-anesthetic level = 2; ±20–49 mmHg = 1; ±50 mmHg or more = 0), consciousness, and O₂ saturation (maintains SpO₂ >92% on room air = 2; needs O₂ to maintain SpO₂ >90% = 1; SpO₂ <90% even with O₂ = 0). A total ≥9 is the usual threshold for PACU discharge.
- **Verified via:** WebSearch record of PubMed 7772368 and reproductions of the 1995 table (SAJAA; Osmosis), 2026-11-05. One secondary reproduction gives the 1-point oxygen item as ">92%". The original letter was not opened.

## Standards, regional anesthesia guidance and FDA actions

### S35
**American Society of Anesthesiologists.** Standards for Basic Anesthetic Monitoring. Committee on Standards and Practice Parameters; original approval October 21, 1986; last amended October 15, 2025. https://www.asahq.org/standards-and-practice-parameters/standards-for-basic-anesthetic-monitoring

- **Supports:** during all anesthetics, arterial blood pressure and heart rate determined and evaluated at least every 5 min; continuous ECG; pulse oximetry; continual end-tidal CO₂ monitoring during general anesthesia, with exhaled-CO₂ monitoring during moderate or deep sedation unless precluded or invalidated by the patient, procedure or equipment; temperature monitoring when clinically significant changes are intended, anticipated or suspected.
- **Verified via:** WebSearch record of the asahq.org standards page (amendment date) and the OpenAnesthesia summary (5-min interval), 2026-11-05.

### S36
**Kopp SL, Vandermeulen E, McBane RD, Perlas A, Leffert L, Horlocker T.** Regional anesthesia in the patient receiving antithrombotic or thrombolytic therapy: American Society of Regional Anesthesia and Pain Medicine evidence-based guidelines (fifth edition). *Reg Anesth Pain Med*. 2025. doi:10.1136/rapm-2024-105766. PMID 39880411.

- **Supports (no numeric value is cited from it in this repository):** agent-, dose- and timing-specific management of antithrombotic drugs around neuraxial and deep blocks; for superficial, compressible blocks, management may be individualized by site compressibility and vascularity. Drug-specific intervals must be read from the guideline itself.
- **Verified via:** PMID 39880411 confirmed by the November 2026 portfolio reviewer (record in the review notes) and DOI as recorded in this repository's audits, 2026-11-05.

### S37
**Joshi GP, et al.** 2026 American Society of Anesthesiologists practice guideline on perioperative pain management using local and regional analgesia for cardiothoracic surgeries, mastectomy, and abdominal surgeries. *Anesthesiology*. 2026;144:19-43. doi:10.1097/ALN.0000000000005790. PMID 41363869.

- **Supports (no numeric dose is cited from it):** procedure-specific use of fascial plane blocks to reduce pain and opioid use in the first 24 h after surgery. Secondary summaries report a recommendation for fascial plane or paravertebral blocks in adult mastectomy. The guideline does not address implant revision specifically, and the Task Force notes low methodologic quality of much of the evidence.
- **Verified via:** WebSearch record of PubMed 41363869, the Mayo Clinic research record and the ASA guideline page, 2026-11-05.

### S38
**U.S. Food and Drug Administration.** FDA requests withdrawal of bacitracin for injection from market. January 31, 2020 (the original fda.gov announcement page is no longer available). Current FDA record: Determination That Bacitracin for Injection, 10,000 Units/Vial and 50,000 Units/Vial, Was Withdrawn From Sale for Reasons of Safety or Effectiveness. *Federal Register*, September 15, 2022 (FR Doc. 2022-19995; Docket FDA-2020-N-2143). https://www.federalregister.gov/documents/2022/09/15/2022-19995/determination-that-bacitracin-for-injection-10000-unitsvial-and-50000-unitsvial-was-withdrawn-from

- **Supports:** the January 31, 2020 request that all application holders voluntarily withdraw bacitracin for injection, and the reasons (serious risks including nephrotoxicity and anaphylactic reactions; other effective FDA-approved treatments are available). FDA has since withdrawn approval of all bacitracin-for-injection applications (last ANDA effective July 11, 2022) and determined the product was withdrawn for reasons of safety or effectiveness. Topical and ophthalmic bacitracin are not affected.
- **Verified via:** citation as audited in v2.0 of this repository, 2026-11-05. On 2026-11-06 the original fda.gov URL was reported as 404 and replaced; the Federal Register determination (title, date, docket, January 31, 2020 request, nephrotoxicity and anaphylactic reactions, withdrawal of all ANDAs) was confirmed in WebSearch records of federalregister.gov and its regulations.gov copy (FDA-2020-N-2143-0010). The Federal Register page itself could not be opened from the build machine (network policy).

### S39
**U.S. Food and Drug Administration.** Breast Implants – Certain Labeling Recommendations to Improve Patient Communication: Guidance for Industry and FDA Staff. September 2020 (Docket FDA-2019-D-4467). https://www.fda.gov/regulatory-information/search-fda-guidance-documents/breast-implants-certain-labeling-recommendations-improve-patient-communication — and FDA's October 27, 2021 approval of updated implant labeling (boxed warning, Patient Decision Checklist) with sales restriction.

- **Supports:** the 2020 guidance date and the 2021 Patient Decision Checklist requirement referenced in modules 01 and 02.
- **Verified via:** citation as audited in v2.0 of this repository, 2026-11-05 (fda.gov page not re-opened in this session).

---

## Values deliberately not given

The following v2.0 numbers had no acceptable, verifiable source and were removed rather than tagged. Details are in [RELEASE_NOTES.md](RELEASE_NOTES.md).

- Block volumes per plane.
- mg/kg local-anesthetic ceilings.
- Fixed fentanyl infusion rates and increments.
- PACU opioid-titration intervals shorter than the label's.
- Respiratory-rate or SpO₂ triggers for naloxone.
- Naloxone 0.04 mg increments and infusion rates.
- Ventilator, hemodynamic and temperature targets.
- Gabapentin doses.
- The triple-antibiotic irrigation recipe.
- Discharge prescription quantities.
- Drain-removal, activity, wound-care and follow-up timings.
- IV opioid equianalgesic ratios.
- Extubation timing rules.
