# Supplementary Data: CPST Assessment Framework for African Minor Language Preservation

[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.xxxxxxx-blue.svg)](https://doi.org/10.5281/zenodo.xxxxxxx)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Excel](https://img.shields.io/badge/Excel-.xlsx-brightgreen.svg)]()

This repository contains the supplementary data file for the research paper:

> **A Cyber-Physical-Social-Thinking (CPST) Framework for African Minor Language Preservation and Revitalization in the AGI Era**  
> *Scientific African* (submitted)  
> Authors: Jifar Wakuma Ayana et al.

---

## About This Dataset

This Excel workbook provides the structured assessment data underlying the CPST framework evaluation in the paper. It contains detailed ratings, sub-criteria scores, and cross-dataset language coverage data used to diagnose the state of African minor language preservation across five case-study countries.

---

## CPST Framework

**CPST (Cyber-Physical-Social-Thinking)** — four-dimensional framework originally proposed by Ning and Liu (2015) for socio-technical systems analysis, applied here to African minor language preservation.

| Dimension | Coverage | Key Question |
|-----------|----------|--------------|
| **Cyber** | Digital resources: corpora, models, benchmarks, speech data, APIs | Functional NLP tools availability |
| **Physical** | Offline deployment, radio, textbooks, signage, writing systems | Physical presence in community |
| **Social** | Institutions, policies, networks, capacity building, data sovereignty | Institutional support |
| **Thinking** | Cognition, identity, trust, participatory design, epistemic justice | Speaker perception and trust |

---

## DLVS Mapping

**Digital Language Vitality Scale (DLVS)** (Kornai 2013; DLDP 2018) mapped to CPST:

| DLVS Dimension | CPST Dimension | Typical African Score |
|----------------|----------------|----------------------|
| Capacity | Cyber | 2–3 (Minimal/Limited) |
| Presence | Physical | 2–3 (None/Minimal) |
| Performance | Social | 3–4 (Minimal/Medium) |
| Prestige | Thinking | 2–4 (Varies widely) |

---

## File Overview

| File | Description |
|------|-------------|
| `CPST_Assessment_Supplementary.xlsx` | Primary dataset — 10 sheets |
| `README.md` | Documentation file |

---

## Workbook Structure

### 1. Cover
Landing page with key metrics, sheet index, and rating legend.

### 2. Country CPST Ratings
CPST dimension ratings for Ghana, Nigeria, Ethiopia, South Africa, and Kenya, including categorical and composite scores.

### 3–6. Sub-criteria Sheets (Cyber / Physical / Social / Thinking)
Six diagnostic sub-criteria per dimension across five countries (24 total indicators).

Example — Cyber:
| Sub-criterion | Ghana | Nigeria | Ethiopia | South Africa | Kenya |
|--------------|-------|---------|----------|--------------|-------|
| Digital corpora | Moderate | Strong | Moderate | Strong | Moderate |
| Language models | Moderate | Strong | Moderate | Strong | Weak |
| Benchmarks | Weak | Moderate | Moderate | Strong | Weak |

### 7. DLVS Mapping
Mapping between DLVS and CPST with example scores for selected African languages.

Swahili shows highest average score (4.25). Ghomala shows lowest (1.25).

### 8. Language Coverage
Cross-dataset presence of 16 African languages across AfriSenti, MasakhaNER, AfroLM, and NLLB-200.

Only Hausa, Yoruba, Igbo, and Swahili appear in all datasets.

### 9. Rating Protocol
Assessment methodology including rating categories, scoring procedure, and validation steps.

### 10. Sources
19 datasets and references used in the assessment, including dataset type and URLs.

---

## Rating Legend

| Rating | Color | Numeric | Meaning |
|--------|-------|---------|---------|
| Strong | Green | 5 | Well-developed |
| Moderate | Amber | 4 | Partially developed |
| Mixed | Purple | 3.5 | Uneven |
| Emerging | Blue | 3 | Early-stage |
| Weak | Red | 2 | Minimal |
| Not Addressed | Gray | 1 | No evidence |

---

## Key Metrics

| Metric | Value |
|--------|-------|
| Countries assessed | 5 |
| CPST dimensions | 4 |
| Sub-criteria per dimension | 6 |
| Languages | 37 |
| Datasets | 4 |
| Rating categories | 6 |

---

## Key Findings

1. No country is balanced across CPST dimensions.
2. Cyber-only development is insufficient.
3. Government partnerships improve scalability.
4. Linguistic pride influences outcomes.
5. Digital resources are highly concentrated.

---

## Citation

To be provided.

---

## License

Creative Commons Attribution 4.0 International License (CC BY 4.0).

---


---

## Acknowledgments

Masakhane, GhanaNLP, NKENNE, NITDA, Addis Ababa University, and African NLP contributors.
