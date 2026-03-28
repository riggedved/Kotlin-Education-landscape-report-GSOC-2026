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

