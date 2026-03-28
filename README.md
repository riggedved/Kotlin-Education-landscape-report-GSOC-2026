# Kotlin Education Landscape Report
### Google Summer of Code 2026 - Kotlin Foundation

This repository contains my GSoC 2026 proposal and preliminary research for the **Kotlin in Education Landscape Report**, a project under the Kotlin Foundation that aims to create the first structured, data-driven overview of where and how Kotlin is taught worldwide.

---

## About Me

**Ved Saxena** | B.Tech CSE, AKTU, India | [vedsaxena19458@gmail.com](mailto:vedsaxena19458@gmail.com) | [github.com/riggedved](https://github.com/riggedved)

I have been programming in Kotlin for the past year, primarily in Android Development. Java was my first programming language, introduced to me in high school, back then I hadn't even heard of Kotlin. 

I have forever had an urge to be different. Most of my college was doing web development and I knew for a fact I’m not gonna do that. I started exploring and found out not many people are practicing app development here. 
So, I started app development and got introduced to Kotlin and how it's related to Java, a big plus point for me. I, primarily, referred to YouTube channels, such as Philipp Lackner and Cheezy Code, as my University didn't have any particular course for it (making me realise how big of a gap actually exists in the education sector regarding Kotlin).

Since my first year in college, I have been throwing different things at the wall to see which one sticks, and cinematography is something I got really interested in. I started photography and then filming videos itself and I’m really proud to share that by the time someone would be reading this proposal, my first short film would be out.
In this whole process I figured out, writing is amongst the best eigen skills one could learn and I was already writing scripts for my videos, so why not double down on it.
I started working as a content manager at Mathongo and now I’m working as a content writer at Legal4sure, where I independently research technical regulatory topics and publish blogs on them.

All of this just makes me a perfect fit for this project and I want to give in more than my best efforts and also to actually contribute to narrowing the gap between academic teaching and practical application. 


---

## About the Project

Kotlin is growing rapidly in educational institutions globally, but no comprehensive, up-to-date picture of its presence in formal and informal education currently exists. This project fills that gap by:

- Mapping institutions, courses, and platforms that teach Kotlin worldwide
- Identifying geographic trends, curriculum gaps, and adoption barriers
- Producing clean, reusable datasets for internal and public use
- Delivering a public-facing **Kotlin in Education** report with strategic recommendations for the Kotlin Foundation

**Project size:** Medium (175 hours)
**Organization:** Kotlin Foundation / JetBrains

---

## Repository Structure

```
Kotlin-Education-Landscape-Report-GSOC-2026/
│
├── README.md
│
├── proposal/
│   └── gsoc_proposal.pdf            ← Full GSoC proposal document
│
├── data/
│   ├── institutions.csv             ← Universities and bootcamps teaching Kotlin
│   ├── courses.csv                  ← Online platform course listings
│   ├── educators.csv                ← Educator survey-style data
│   └── trends_over_time.csv         ← Year-by-year Kotlin education growth
│
└── research/
    └── sources.md                   ← All sources used in research and dataset
```

---

## Sample Dataset - What's Inside

As part of my proposal, I have already begun preliminary data collection. The sample dataset contains four CSV files:

| File | Rows | Description |
|---|---|---|
| `institutions.csv` | 20 | Universities and bootcamps known to teach Kotlin, across 6 regions |
| `courses.csv` | 20 | Verified online courses from Coursera, Udemy, JetBrains Academy, edX, and more |
| `educators.csv` | 15 | Illustrative survey-style data based on commonly reported educator experiences |
| `trends_over_time.csv` | 21 | Year-by-year Kotlin education growth (2017–2025), sourced from JetBrains surveys |

Every row is tagged with a **confidence level** - Verified, Inferred, or Self reported and a source reference. See [`research/sources.md`](research/sources.md) for full source documentation.

> **Note:** The educators dataset contains illustrative data modelled on real community discussions, not live survey responses. Primary data collection from real educators will begin in Week 1 of the GSoC project.

---
