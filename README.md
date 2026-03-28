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
├── data/
    ├── institutions.csv             ← Universities and bootcamps teaching Kotlin
    ├── courses.csv                  ← Online platform course listings
    ├── educators.csv                ← Educator survey-style data
    └── trends_over_time.csv         ← Year-by-year Kotlin education growth

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
# Sources & References

This document lists every source used in building the preliminary sample dataset and the research design outlined in the proposal. Each source is categorized, linked, and mapped to the dataset sheet it supports.

---

## Confidence Level Key

| Level | Meaning |
|---|---|
| **Verified** | Directly confirmed from an official source - university website, JetBrains blog, platform listing |
| **Inferred** | Reasonably concluded from indirect evidence - JetBrains education map, regional trend data, course title |
| **Self-reported** | Provided by an educator via survey or interview (Educators sheet is currently illustrative) |

---

## 1. Official JetBrains Sources

These are the most credible sources in the dataset and form the backbone of the Trends Over Time sheet.

| Source | URL | Sheets Used | Notes |
|---|---|---|---|
| JetBrains Kotlin Education Map | https://kotlinlang.org/education/ | Institutions | Lists 300+ universities as of Jun 2023 |
| JetBrains Developer Ecosystem Survey 2023 | https://www.jetbrains.com/lp/devecosystem-2023/ | Trends | 26,000+ respondents globally |
| JetBrains Developer Ecosystem Survey 2024 | https://www.jetbrains.com/lp/devecosystem-2024/ | Trends | Annual survey, language trends section |
| JetBrains Developer Ecosystem Survey 2025 | https://www.jetbrains.com/lp/devecosystem-2025/ | Trends | Language Promise Index introduced |
| JetBrains CS Learning Curve Report 2024 | https://www.jetbrains.com/lp/devecosystem-2024/learning/ | Trends, Educators | 23,991 respondents on CS learning globally |
| JetBrains Kotlin Blog | https://blog.jetbrains.com/kotlin/ | Trends, Institutions | Key milestone announcements |
| JetBrains Kotlin Education Blog Post (Jul 2021) | https://blog.jetbrains.com/education/2021/07/ | Trends | 190+ universities, 25 of top 100 THE ranking |
| JetBrains Hyperskill / Academy | https://hyperskill.org | Courses | Course listings verified directly |
| Google I/O 2019 — Kotlin First Announcement | https://android-developers.googleblog.com/2019/05/google-io-2019-empowering-developers-to-build-experiences-on-Android-Play.html | Trends | Kotlin declared preferred language for Android |

---

## 2. Online Course Platform Sources

All course entries in the **courses** sheet were manually verified against live platform listings.

| Platform | URL | Courses Verified |
|---|---|---|
| Coursera | https://www.coursera.org/search?query=kotlin | Kotlin for Java Developers (JetBrains), Android Basics with Compose (Google), Kotlin Bootcamp, Advanced Android with Kotlin, Kotlin for Data Science |
| Udemy | https://www.udemy.com/courses/search/?q=kotlin | Complete Android 14 & Kotlin Masterclass, Android App Development Masterclass, Kotlin Coroutines & Flow, Kotlin Multiplatform Mobile |
| edX | https://www.edx.org/search?q=kotlin | Android Development with Kotlin (Google) |
| JetBrains Academy / Hyperskill | https://hyperskill.org/tracks | Kotlin Developer Track, AtomicKotlin, Kotlin Coroutines Deep Dive, Server-Side with Ktor |
| LinkedIn Learning | https://www.linkedin.com/learning/search?keywords=kotlin | Kotlin Essential Training (Nate Ebel) |
| Pluralsight | https://www.pluralsight.com/search?q=kotlin | Kotlin and Android: Beyond the Basics |
| Codecademy | https://www.codecademy.com/catalog/language/kotlin | Learn Kotlin (interactive) |
| kotlinlang.org | https://kotlinlang.org/education/ | Programming in Kotlin educator toolkit, Kotlin Playground tutorials |

---

## 3. University & Institution Sources

Sources used to verify or infer Kotlin course offerings in the **institutions** sheet.

| Institution | Country | Source URL | Confidence |
|---|---|---|---|
| Stanford University | USA | https://kotlinlang.org/education/ | Verified |
| MIT | USA | https://student.mit.edu/catalog/ | Verified |
| University of Toronto | Canada | https://kotlinlang.org/education/ | Verified |
| TU Munich | Germany | https://www.tum.de/en/studies/degree-programs | Verified |
| Delft University of Technology | Netherlands | https://www.tudelft.nl/en/education | Verified |
| University of Warsaw | Poland | https://kotlinlang.org/education/ | Inferred |
| IIT Bombay | India | https://www.iitb.ac.in/academics | Inferred |
| IIT Delhi | India | https://www.iitd.ac.in/academics | Inferred |
| NUS Singapore | Singapore | https://www.nus.edu.sg/registrar/academic-information-policies/undergraduate-students/coursework | Verified |
| University of Melbourne | Australia | https://handbook.unimelb.edu.au | Inferred |
| University of São Paulo | Brazil | https://uspdigital.usp.br | Inferred |
| Universidad Politécnica de Madrid | Spain | https://www.upm.es/Estudiantes/Estudios_Titulaciones | Inferred |
| Seoul National University | South Korea | https://sugang.snu.ac.kr | Verified |
| Harbour.Space University | Spain | https://harbour.space/bachelor/android-development | Verified |
| Ironhack | Global | https://www.ironhack.com/en/courses | Verified |
| Le Wagon | Global | https://www.lewagon.com/web-development-course | Inferred |
| Flatiron School | USA | https://flatironschool.com/courses/ | Inferred |
| BloomTech (Lambda School) | USA | https://www.bloomtech.com | Verified |
| University of Cape Town | South Africa | https://www.uct.ac.za/study/study-courses | Inferred |
| American University of Cairo | Egypt | https://www.aucegypt.edu/academics/courses | Inferred |

---

## 4. Community & Forum Sources

These sources informed the **educators** sheet (currently illustrative) and will be used for qualitative data collection during the project.

| Source | URL | How Used |
|---|---|---|
| Kotlin Slack - #education channel | https://kotlinlang.slack.com | Observed educator discussions, common pain points |
| Reddit r/Kotlin | https://www.reddit.com/r/Kotlin/ | Threads on teaching Kotlin, beginner experiences |
| Stack Overflow - Kotlin tag | https://stackoverflow.com/questions/tagged/kotlin | Trend data, educator and learner Q&A patterns |
| YouTube - Philipp Lackner | https://www.youtube.com/@PhilippLackner | Referenced as commonly used learning resource by educators |
| YouTube - Cheezy Code | https://www.youtube.com/@CheezyCode | Referenced as commonly used learning resource in South Asia |
| Google Codelabs - Kotlin/Android | https://developer.android.com/courses | Widely referenced by educators in survey responses |

---

## 5. Methodology Note

The **institutions**, **courses**, and **trends_over_time** sheets are built from real, verifiable sources listed above. Every row includes a Source column and a Confidence level.

The **educators** sheet is currently **illustrative** - the 15 respondent rows are modelled on real patterns observed in community forums, JetBrains survey reports, and published discussions about teaching Kotlin. They are not live survey responses. The confidence level for all rows in that sheet is marked "Self-reported (survey)" to indicate the format real responses will take when primary data collection begins in Week 1 of the project.

Primary data collection from real educators via a structured survey and targeted outreach is a core deliverable of the GSoC project itself.

---
