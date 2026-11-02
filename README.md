# Hi, I'm Derren 👋

**Data science, AI, and product engineering — mostly at the point where a model has to become something a person can actually use.**

B.Sc. Data Science & Analytics, National University of Singapore (2026) · Singapore

---

Most of my work ends up in front of someone who has to make a decision with it: a family wondering
whether to seek a cognitive assessment, a researcher running a time-trade-off interview, a teacher
running a classroom session, a programme manager who needs the numbers by Monday morning.

That shapes what I build. I'd rather ship something that says what it *can't* do than something that
only looks clever in a demo — so the parts I'm proudest of tend to be the least photogenic ones: the
held-out month, the baseline I had to beat, the label I refused to impute.

---

## Some things I've built

**[ViralIQ](https://github.com/darderrdur17/ViralIQ)** · `Python` `FastAPI` `DuckDB` `CatBoost`

Top-1% view prediction for TikTok, from pre-publication metadata only — training on engagement and
then predicting engagement isn't a prediction. Beats random by **2.18×** on a month it never saw, and
nulls the 34.72% of labels whose stats predate publication rather than guessing at them.

**[ApexIQ](https://apexiq-theta.vercel.app)** · `Python` `FastAPI` `scikit-learn` `ECharts`

F1 telemetry analytics and race forecasting, built so a prediction can never be mistaken for a
measurement. Every forecast runs from a fixed information cutoff and is reported against a baseline
the model sometimes loses to — where the numbers are weak, the interface says so.

**[TennisIQ](https://tennisiq-self.vercel.app)** · `Python` `FastAPI` `React`

ATP and WTA match forecasting, modelled as two separate problems rather than one. 118,210 matches
with strict temporal cutoffs; gradient-boosted trees hold **64.7%** on seasons they never saw — 14.7
points over a coin flip.

**[360 Cogni](https://360cogni.com)** · `React 19` `React Native` `Supabase`

A cognitive health platform for families acting on early signs of dementia — screening, brain
training, and caregiver tools in one place. I helped take it from problem definition to a live MVP,
which mostly meant deciding what *not* to build first.

**[Creativity is…](https://github.com/darderrdur17/creative-puzzle-studio)** · `React 18` `Supabase Realtime`

A classroom puzzle game about the four stages of the creative process. Students place stage keys and
match quotes; the teacher runs the room from a live dashboard. Each student's own answer to *"where
do you get your best ideas?"* gets dealt onto the board — which is the part they remember.

**[EQ-5D-5L TTO Research Tool](https://github.com/darderrdur17/EQ-5D-5L-TTO)** · `React` `PostgreSQL` `Supabase`

A research tool for health-economics time-trade-off studies: real-time utility calculation,
pseudonymised participant data, and accessible design throughout. It gets used in live interviews,
so accessibility was a requirement rather than a nice-to-have.

**[DDOG Earnings Tracker](https://github.com/darderrdur17/ddog-earnings-tracker)** · `Python` `scikit-learn`

A pre-earnings nowcast for Datadog built entirely from public data — npm downloads, SEC XBRL,
Wikimedia pageviews. Benchmarked against a dumb persistence baseline, and reported straight when
persistence won.

<sub>Also around: a Go/Kafka social pipeline ([Pulse](https://github.com/darderrdur17/pulse)), a bilingual university site prototype ([UNR](https://github.com/darderrdur17/unr-website)), an ASEAN competition judging portal ([AIRA](https://github.com/darderrdur17/aira-youth-judging-portal)), five years of S&P 500 sector work, and a Leaflet nightlife map ([Bassline](https://github.com/darderrdur17/nightlife-navigator-main)).</sub>

---

## What I'm working on

- **Leakage-controlled ML** — how much of an outcome is genuinely knowable *before* it happens, and what an honest accuracy number looks like when you find out it isn't much
- **Shipping small things end to end** — a classroom puzzle game, an ASEAN judging portal, a bilingual university site
- **Open to full-time** data / software engineering roles in Singapore

---

## Tools I reach for

TypeScript and React by default, Python when there's data to argue with. Postgres or Supabase for
most things, FastAPI or Node behind it, Vercel or Docker in front.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB&style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white&style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat-square)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white&style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat-square)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white&style=flat-square)

---

## Say hello

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/derren-winata/)
[![Portfolio](https://img.shields.io/badge/Portfolio-derren--winata--portfolio-000000?logo=vercel&logoColor=white&style=flat-square)](https://derren-winata-portfolio.vercel.app)
[![Email](https://img.shields.io/badge/Email-wderren17@gmail.com-EA4335?logo=gmail&logoColor=white&style=flat-square)](mailto:wderren17@gmail.com)

Always happy to talk about data pipelines, evaluation methodology, or why the demo is never the hard
part. If you're hiring in Singapore, my inbox is open.
