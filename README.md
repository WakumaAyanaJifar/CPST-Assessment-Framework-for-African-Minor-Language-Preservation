# Supplementary Data: CPST Assessment Framework for African Minor Language Preservation

[![License](https://img.shields.io/badge/License-CC%20BY%204.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Excel](https://img.shields.io/badge/Excel-.xlsx-brightgreen.svg)]()

This repository contains the supplementary workbook (Supplementary File 2) for the research paper:

> **A Cyber-Physical-Social-Thinking (CPST) Framework for African Minor Language Preservation and Revitalization in the AGI Era**
> *Scientific African* (under review, manuscript SCIAF-D-26-02266)
> Authors: Jifar Wakuma Ayana, Zita Lifelo, Scholas Mbonihankuye, Doreen Sebastian Sarwatt, Huansheng Ning

---

## About This Dataset

The workbook documents the CPST rating rubric, the assessment protocol, and the ratings behind the paper's comparative case studies. It covers five positive cases (Ghana, Nigeria, Ethiopia, South Africa, Kenya) and one negative case (Murle, South Sudan). It also contains a blank template for new assessments, the source identification log, and cross-corpus language coverage data.

The study is a **structured documentary review, not a formal PRISMA systematic review**. The case set is purposively selected.

---

## CPST Framework

**CPST (Cyber-Physical-Social-Thinking)** is a four-dimensional framework originally proposed by Ning and Liu (2015) for socio-technical systems analysis. It is applied here to African minor language preservation.

| Dimension | Coverage | Key Question |
|-----------|----------|--------------|
| **Cyber** | Digital corpora, language models, machine translation, speech technology, benchmarks, APIs | Are functional NLP tools available? |
| **Physical** | Offline deployment, print materials, community radio, writing systems, public signage, archives | Is the language physically present in the community? |
| **Social** | Institutional partnerships, community engagement, capacity building, policy, platforms, sustainability | Is there institutional support? |
| **Thinking** | Linguistic identity, participatory design, technology trust, prestige, epistemic justice, cognitive load | How do speakers perceive and trust the language and its tools? |

Each dimension has six sub-criteria (24 in total).

---

## File Overview

| File | Description |
|------|-------------|
| `CPST_Assessment_Supplementary.xlsx` | Supplementary workbook, 7 sheets (Supplementary File 2 of the paper) |
| `README.md` | This documentation file |

---

## Workbook Structure

| # | Sheet | Contents |
|---|-------|----------|
| 1 | **Cover** | Sheet index, instructions for use, and citation |
| 2 | **CPST Rating Rubric** | 6-level rating scale plus Insufficient Evidence (IE); definitions, evidence requirements and assessment guidance for all 24 sub-criteria |
| 3 | **Assessment Protocol** | Protocol overview, dimension mapping criteria, 7-step data collection protocol, quality assurance measures |
| 4 | **Case Study Results** | Ratings for the six cases with median profiles, key evidence (including the Murle negative case) and diagnostic findings |
| 5 | **Dataset Coverage** | Coverage of 36 African languages across AfriSenti, MasakhaNER 2.0, AfroLM, NLLB-200 and Common Voice v18, with summary statistics |
| 6 | **Assessment Template** | Blank form for new evaluations: sub-criterion ratings (1–6 or IE), sub-criteria medians as a guide, assessor-assigned dimension ratings, profile and sign-off |
| 7 | **Source ID Log (Not PRISMA)** | Records identified from five databases and other sources, screening steps, and the 96 included sources |

---

## Rating Scale

The scale is **ordinal**. Profiles are summarised by the median, the weakest dimension and the range, not by arithmetic means.

| Value | Label | Meaning |
|-------|-------|---------|
| 6 | Strong | Well-developed infrastructure with documented, sustained impact and active community engagement |
| 5 | Moderate | Established infrastructure with some deployment but limited reach or sustainability concerns |
| 4 | Mixed | Uneven development: some sub-dimensions strong, others weak |
| 3 | Emerging | Initial, pilot-stage efforts, not yet operational or scalable |
| 2 | Weak | Minimal, fragmented or ad-hoc efforts |
| 1 | Not addressed | No identifiable initiatives or infrastructure |
| IE | Insufficient Evidence | Cannot be scored for lack of documentation; excluded from medians |

The "Typical Impact" percentages in the rubric indicate relative importance in typical scenarios **for guidance only; they are not applied as weights**. Dimension ratings are holistic expert judgements informed by the six sub-criteria, not mechanical aggregations of them.

---

## Case Study Ratings

| Dimension | Ghana | Nigeria | Ethiopia | South Africa | Kenya | South Sudan (Murle) |
|-----------|:-----:|:-------:|:--------:|:------------:|:-----:|:-------------------:|
| Cyber | 6 | 6 | 4 | 6 | 5 | 2 |
| Physical | 2 | 3 | 5 | 2 | 2 | 2 |
| Social | 2 | 6 | 5 | 5 | 4 | 2 |
| Thinking | 2 | 6 | 4 | 5 | 2 | 2 |
| **Median** | **2.0** | **6.0** | **4.5** | **5.0** | **3.0** | **2.0** |

Each rating required convergent evidence from at least two independent documentary sources. Two authors rated each case independently. Disagreements were resolved by discussion, and a third author adjudicated the one remaining disagreement (Murle, Physical). Inter-rater reliability for the 20 positive-case ratings: Cohen's κ = 0.864, linear-weighted κ = 0.944, Krippendorff's α (ordinal) = 0.965, bootstrap 95% CI [0.650, 1.000].

---

## Key Findings

1. None of the six cases is strong across all four CPST dimensions.
2. Cyber resources alone are insufficient: Ghana pairs a Strong Cyber rating with Weak Physical, Social and Thinking ratings.
3. Government partnership supports scale: Nigeria has the highest median (6.0), with Physical (Emerging) as its weakest dimension.
4. Ethiopia has the most balanced profile (median 4.5, range 1.0).
5. The Murle negative case scores Weak across all dimensions. It shows that the rubric discriminates between well-resourced and severely under-resourced contexts.
6. Digital resources are highly concentrated: only 12 of the 36 sampled languages appear in four or more of the five corpora.

---

## How to Use

1. Read the **CPST Rating Rubric** sheet for the scale and the criteria for each dimension.
2. Follow the **Assessment Protocol** sheet for data collection and rating.
3. Use **Case Study Results** and **Dataset Coverage** for comparison.
4. Use the **Assessment Template** for new evaluations. Record IE rather than forcing a rating when evidence is insufficient.

---

## Citation

Ayana, J.W., Lifelo, Z., Mbonihankuye, S., Sarwatt, D.S., & Ning, H. (2026). A Cyber-Physical-Social-Thinking (CPST) Framework for African Minor Language Preservation and Revitalization in the AGI Era. *Scientific African* (under review).

---

## License

Creative Commons Attribution 4.0 International License (CC BY 4.0).

---

## Acknowledgments

Masakhane, GhanaNLP, NKENNE, NITDA, Addis Ababa University, and African NLP contributors.
