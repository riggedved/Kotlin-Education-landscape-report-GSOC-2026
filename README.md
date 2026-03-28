# Kotlin Education Landscape Report
### Google Summer of Code 2026 - Kotlin Foundation

This repository contains my preliminary research for the **Kotlin in Education Landscape Report** - a project under the Kotlin Foundation that aims to create the first structured, data-driven overview of where and how Kotlin is taught worldwide.

---

## About the Project

Kotlin is growing rapidly in educational institutions globally, but no comprehensive, up-to-date picture of its presence in formal and informal education currently exists. This project fills that gap by:

- Mapping institutions, courses, and platforms that teach Kotlin worldwide
- Identifying geographic trends, curriculum gaps, and adoption barriers
- Producing clean, reusable datasets for internal and public use
- Delivering a public-facing **Kotlin in Education** report with strategic recommendations for the Kotlin Foundation

**Project size:** Medium (175 hours)
**Organization:** Kotlin Foundation

---

## Repository Structure

```
kotlin-education-landscape/
│
├── README.md
│
|
├── data/
│   └── kotlin_education_sample_dataset.xlsx      ← Preliminary sample dataset (4 sheets)
│
└── research/
    └── sources.md                                ← All sources used in research and dataset
```

---

## Sample Dataset — What's Inside

As part of my proposal, I have already begun preliminary data collection. The sample dataset contains four sheets:

| Sheet | Rows | Description |
|---|---|---|
| **institutions** | 20 | Universities and bootcamps known to teach Kotlin, across 6 regions |
| **courses** | 20 | Verified online courses from Coursera, Udemy, JetBrains Academy, edX, and more |
| **educators** | 15 | Illustrative survey-style data based on commonly reported educator experiences |
| **trends_over_time** | 21 | Year-by-year Kotlin education growth data (2017–2025), sourced from JetBrains surveys |

Every row is tagged with a **confidence level** — Verified, Inferred, or Self-reported — and a source reference. See [`research/sources.md`](research/sources.md) for full source documentation.

> **Note:** The Educators sheet contains illustrative data modelled on real community discussions, not live survey responses. Primary data collection from real educators will begin in Week 1 of the GSoC project.

---

## Research Design (Summary)

I'm using a **mixed-methods approach** combining:

- **Quantitative data** — counts, distributions, platform metrics, year-on-year trends
- **Qualitative data** — educator surveys, interviews, community discussions

**Three core research questions:**
1. Where is Kotlin taught? — institutions, geographies, platforms
2. How is Kotlin taught? — curriculum depth, tools, course levels
3. Where are the gaps? — underserved regions, missing topics, adoption barriers


