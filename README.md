# Critical Review of Genetic Research Methods and Their Ethical, Legal and Social Implications

**Genetics Assistant Internship — Week 5** | Rabi Narayan Patra | 30 September 2026

A critical literature review of how modern genetic research is done, what its methods can and cannot deliver, and the ethical, legal and social questions those methods raise — with seven documented case studies and a practical framework for integrating ethics into research workflows.

## The argument

The review's organising claim is that **methodology and ethics are the same question asked in two vocabularies**. A polygenic score that does not travel across ancestries is both a scientific defect and a source of health inequity. The irreversibility of germline editing is both a technical property and the reason it is governed differently from somatic therapy. The price of a gene therapy is an economic fact and the reason a cure can be a partial success.

Three conclusions follow, and they are stated at the outset:

1. **The most serious harms in the field's history came from research that was permitted and governed** — and then used in ways participants had not anticipated. Consent that names the present study but not the possible futures of the data is the recurring mechanism of that failure.
2. **The populations least represented in research are systematically those for whom its results work least well**, which makes diversity a scientific requirement, not only a matter of fairness.
3. **Ethics confined to a paper's final section cannot change anything**, because the consequential decisions are taken earlier. Ethics that lives in the workflow's artefacts — the consent form, the findings policy, the published calibration — is auditable, and therefore real.

## What the review covers

**Methods surveyed and compared** (Section 2, Table 1, Figure 2): Sanger and next-generation sequencing, long-read and single-cell methods, exome sequencing, GWAS, family and linkage studies, biobanks and cohorts, Mendelian randomisation, CRISPR screens, somatic and heritable gene editing, base and prime editing, polygenic scores, machine learning and sequence-based models, liquid biopsy, multi-omics and synthetic biology.

**Critical analysis** (Section 3): effect size and the limits of individual prediction; the ancestry gap and portability of polygenic scores; reproducibility, winner's curse and multiple testing; the distance from association to causation; and the translation gap between a validated finding and a clinical service.

**Ethics, organised in four domains** (Section 4, Figure 3): the individual (privacy and re-identification, consent, incidental findings, the right not to know); the family and community (relational data, duty to warn, community consent and Indigenous data sovereignty, benefit-sharing); society and the state (insurance and employment discrimination, forensic genetic genealogy, commercialisation, equity, national screening programmes); and the human future (heritable genome editing, embryo selection, enhancement, eugenic history).

## Seven documented cases (Section 5, Figure 4)

| Case | Period | The question it raises |
|---|---|---|
| Henrietta Lacks and HeLa | 1951–2023 | Consent as a historical artefact; who benefits from a research resource |
| The Havasupai tribe | 1990–2010 | Community consent; consent to a subject, not to a form |
| Iceland and deCODE | 1998–2003 | Consent by opt-out; the descendant's own privacy interest |
| He Jiankui's gene-edited twins | 2018–2019 | When the prohibited becomes actual; jurisdictional governance gaps |
| Forensic genetic genealogy | 2018– | Acting on people who consented to nothing |
| Sickle cell gene therapy | 2023 | Scientific success and the access question |
| India's sickle cell mission | 2023–2025 | Consent and counselling at population scale |

Plus two hypothetical scenarios — a polygenic score deployed without ancestry-specific calibration, and a de-identified cohort with a re-identification route — chosen because neither requires bad intent, only ordinary inertia.

## Contested questions are presented as contested

The review does not advocate on questions where reasonable people disagree. Heritable genome editing, polygenic embryo screening, the disability-rights critique of prenatal screening, and the true prevalence of genetic discrimination are each presented with the strongest arguments on **both** sides, with a note on what evidence would settle the disagreement. On the disability critique in particular, the review states explicitly that it does not follow from the fact that a screening programme reduces the incidence of a condition that the programme disrespects people who have it — and that the counter-argument about intention versus effect is also serious.

## Repository contents

**Committed here:**

```
├── README.md
├── fact_check_ledger.md      # every quantitative claim, with its source document
└── references.md             # the full bibliography (64 references)
```

**In the v1.0 release bundle:**

```
├── Critical_Review_Genetic_Research_ELSI.docx   # the review (31 pages, ~10,000 words)
├── Critical_Review_Genetic_Research_ELSI.pdf
├── figures/                                     # all seven figures
│   ├── fig1_methods_landscape.png       # the four families of method
│   ├── fig2_method_comparison.png       # advantages and limitations
│   ├── fig3_elsi_domains.png            # the four ethical domains
│   ├── fig4_case_timeline.png           # seven cases, 1951-2025
│   ├── fig5_translation_pipeline.png    # where ethical decisions actually sit
│   ├── fig6_equity_gaps.png             # two equity gaps, with real data
│   └── fig7_ethics_workflow.png         # the nine-step framework
└── scripts/make_figures.py              # regenerates all seven figures
```

## Verification

Every quantitative claim in the review is attributed to a source, and `fact_check_ledger.md` lists each figure against the document it comes from. Where published estimates differ — as they do for the ancestry composition of genomic studies, where different analyses report 78%, 86.3% and 88.45% — the review reports the range rather than selecting the most convenient number, and explains why the estimates differ.

## Author

**Rabi Narayan Patra** — Genetics Assistant Internship (2026). GitHub: [@rabinarayanpatra350-biotech](https://github.com/rabinarayanpatra350-biotech)
