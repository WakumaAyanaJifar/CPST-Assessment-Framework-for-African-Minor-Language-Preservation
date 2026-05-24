# Supplementary Data: CPST Assessment Framework for African Minor Language Preservation

[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.xxxxxxx-blue.svg)](https://doi.org/10.5281/zenodo.xxxxxxx)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Excel](https://img.shields.io/badge/Excel-.xlsx-brightgreen.svg)]()

This repository contains the supplementary data file for the research paper:

> **A Cyber-Physical-Social-Thinking (CPST) Framework for African Minor Language Preservation and Revitalization in the AGI Era**  
> *Scientific African* (submitted)  
> Authors: Jifar Wakuma Ayana.et al

---

## About This Dataset

This Excel workbook provides the structured assessment data underlying the CPST framework evaluation in the paper. It contains detailed ratings, sub-criteria scores, and cross-dataset language coverage data used to diagnose the state of African minor language preservation across five case-study countries.

### What is CPST?

**CPST** stands for **Cyber-Physical-Social-Thinking** — a four-dimensional framework originally proposed by Ning and Liu (2015) for analyzing complex socio-technical systems. In this paper, it is applied to African minor language preservation:

| Dimension | What it covers | Key question |
|-----------|---------------|-------------|
| **Cyber** | Digital resources: corpora, models, benchmarks, speech data, APIs | Are functional NLP tools available for this language? |
| **Physical** | Tangible anchors: offline deployment, radio, textbooks, signage, writing systems | Is the language physically present in the community? |
| **Social** | Institutions and communities: policies, networks, capacity building, data sovereignty | Are institutions supporting this language's digital future? |
| **Thinking** | Cognition and identity: participatory design, pride, trust, epistemic justice | Do speakers value and trust technology in their language? |

### What is DLVS?

The **Digital Language Vitality Scale (DLVS)** is an established framework (Kornai 2013; DLDP 2018) that maps to CPST as follows:

| DLVS Dimension | CPST Dimension | Typical African Score |
|----------------|----------------|----------------------|
| Capacity | Cyber | 2-3 (Minimal/Limited) |
| Presence | Physical | 2-3 (None/Minimal) |
| Performance | Social | 3-4 (Minimal/Medium) |
| Prestige | Thinking | 2-4 (Varies widely) |

---

## File Overview

| File | Description |
|------|-------------|
| `CPST_Assessment_Supplementary.xlsx` | Primary dataset — 10 sheets with full assessment data |
| `README.md` | This documentation file |

---

## Workbook Structure

### 1. Cover
**What it is:** Landing page with key metrics, sheet index, and rating legend.  
**Use for:** Quick orientation before exploring the data.

### 2. Country CPST Ratings
**What it is:** Overall CPST dimension ratings for five case-study countries (Ghana, Nigeria, Ethiopia, South Africa, Kenya).  
**Contains:**
- Categorical ratings (Strong / Moderate / Mixed / Emerging / Weak / Not Addressed) with color coding
- Numeric composite scores (1-5 scale) for quantitative comparison
- A bar chart showing CPST composite scores by country

**How to read it:** Nigeria scores highest (4.00) due to strong government partnerships (NITDA/NKENNE). Ghana and Kenya score lowest due to underdeveloped Physical and Thinking dimensions.

### 3-6. Sub-criteria Sheets (Cyber / Physical / Social / Thinking)
**What they are:** Detailed breakdowns of each CPST dimension into 6 diagnostic sub-criteria per country.  
**Contains:**
- 24 sub-criteria total (6 per dimension)
- Individual ratings with evidence sources
- Color-coded cells matching the rating legend

**Example — Cyber Sub-criteria:**
| Sub-criterion | Ghana | Nigeria | Ethiopia | South Africa | Kenya |
|--------------|-------|---------|----------|--------------|-------|
| Digital corpora | Moderate | Strong | Moderate | Strong | Moderate |
| Language models | Moderate | Strong | Moderate | Strong | Weak |
| Benchmarks | Weak | Moderate | Moderate | Strong | Weak |

### 7. DLVS Mapping
**What it is:** Maps the Digital Language Vitality Scale to CPST dimensions with example scores for 10 African languages.  
**Contains:**
- DLVS dimension definitions and 6-point scale
- Example vitality scores for Swahili, Amharic, Hausa, Yoruba, Zulu, Oromo, Wolof, Tigrinya, Xitsonga, and Ghomala
- Data bars for visual score comparison

**Key insight:** Swahili scores highest (4.25 average) due to strong corpora and institutional support. Ghomala scores lowest (1.25) with minimal digital presence across all dimensions.

### 8. Language Coverage
**What it is:** Cross-dataset presence of 37 African languages across 4 major NLP resources.  
**Contains:**
- Presence indicators (Y = present, N = absent) with counts where available
- Coverage depth score C(l) = number of datasets present
- Color-coded presence/absence and data bars for C(l)

**Key finding:** Only 4 languages (Hausa, Yoruba, Igbo, Swahili) appear in all 4 datasets. Most languages appear in 1-2 datasets only.

### 9. Rating Protocol
**What it is:** The complete assessment methodology used to derive all ratings in this workbook.  
**Contains:**
- **6 rating category definitions** with numeric conversions
- **6-step assessment procedure** (evidence collection → dimension mapping → independent rating → consensus → composite scoring → validation)
- **24-item sub-criteria checklist** with evidence requirements for each item

**Use for:** Replicating the assessment, extending to new countries/languages, or validating the methodology.

### 10. Sources
**What it is:** Complete citations for all 19 data sources used in the assessment.  
**Contains:** Dataset/resource name, type, source organization, and direct URL.

---

## Rating Legend

| Rating | Color | Numeric | Meaning |
|--------|-------|---------|---------|
| **Strong** | Green | 5 | Well-developed with multiple functional components |
| **Moderate** | Amber | 4 | Partially developed; functional but limited |
| **Mixed** | Purple | 3.5 | Uneven development across sub-criteria |
| **Emerging** | Blue | 3 | Early-stage; pilots or plans in place |
| **Weak** | Red | 2 | Minimal development; few functional components |
| **Not Addressed** | Gray | 1 | No evidence of intervention |

---

## Key Metrics

| Metric | Value |
|--------|-------|
| Countries assessed | 5 (Ghana, Nigeria, Ethiopia, South Africa, Kenya) |
| CPST dimensions | 4 (Cyber, Physical, Social, Thinking) |
| Sub-criteria per dimension | 6 (24 total) |
| Languages in coverage matrix | 37 |
| Datasets tracked | 4 (AfriSenti, MasakhaNER, AfroLM, NLLB-200) |
| Rating categories | 6 |

---

## How to Use This Dataset

### For Researchers
- **Replicate the assessment:** Follow the 6-step procedure in the Rating Protocol sheet to apply CPST to new countries or languages
- **Compare initiatives:** Use the sub-criteria sheets to benchmark language preservation projects against the 24 diagnostic indicators
- **Quantify gaps:** Use the numeric composite scores to identify which dimensions need investment

### For Policymakers
- **Diagnose national readiness:** Look up your country's row in Country CPST Ratings to identify strengths and gaps
- **Allocate resources:** Use sub-criteria sheets to pinpoint specific areas needing intervention (e.g., offline deployment, capacity building)
- **Track progress:** Re-assess periodically using the same protocol to measure improvement

### For Practitioners
- **Design projects:** Ensure your initiative addresses all 4 CPST dimensions, not just Cyber (technology)
- **Learn from leaders:** Nigeria's Social dimension and Ethiopia's Thinking dimension provide models to emulate
- **Avoid common failures:** Ghana's "Strong Cyber + Weak Physical/Social/Thinking" pattern shows why technology alone is insufficient

### For Students
- **Understand the field:** The DLVS Mapping sheet shows how language vitality is measured
- **Explore the data:** The Language Coverage sheet reveals which African languages have digital resources and which do not

---

## Important Findings from the Data

1. **No country is balanced.** All five case studies show uneven CPST profiles — strong in some dimensions, weak in others.

2. **Cyber alone is insufficient.** Ghana has strong Cyber resources (GhanaNLP corpus) but Weak Physical, Social, and Thinking dimensions — limiting real-world impact.

3. **Government partnership matters.** Nigeria's strong Social rating reflects NITDA government partnership, which enables scaling beyond volunteer efforts.

4. **Linguistic pride is critical.** Ethiopia's strong Thinking dimension (75% youth pride in mother-tongue communication) correlates with better preservation outcomes.

5. **Coverage is highly concentrated.** Only 4 languages (Hausa, Yoruba, Igbo, Swahili) appear in all 4 tracked datasets. Most African languages have minimal or no digital presence.

---

## Citation

We will provide it soon


## License

This dataset is released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made

---

## Contact

For questions, corrections, or suggestions regarding this dataset, please open an issue in this repository or contact the corresponding author.
wakexayanajifar01@gmail.com

---

## Acknowledgments

The authors thank the many African researchers, engineers, and community members whose work inspired this study. Special thanks to the teams at Masakhane, GhanaNLP, NKENNE, NITDA, Addis Ababa University, and all contributors to the African NLP ecosystem.
