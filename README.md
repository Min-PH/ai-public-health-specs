# AI in Public Health — Specs & Implementations

*A single-source repository for offline implementations and specifications.*

The living companion repository to *Artificial Intelligence in Public Health* (Springer Nature, 2026) by Min Wu. For conceptual background, essays, and textbook integration, visit **[ai-public-health.com](https://ai-public-health.com/?ref=github-readme)**.

---

## Chapter index

Each chapter links to the published theory in the textbook, plus whatever is currently active — specs, concept maps, preprints, and teaching artifacts. Chapters without active entries are open ground. *New* marks work not yet included in the published chapter.

### Chapter 1 — Introduction
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_1)
*No specs yet.*

**Teaching artifacts** — [AI definitions study card (PDF)](https://ai-public-health.com/content/files/2026/08/AI-Definitions-Wallet-size-study-card-1.pdf) · [Interview exercise: spot the red flag (PDF)](https://ai-public-health.com/content/files/2026/09/Interview-exercise-spot-the-red-flag2.pdf)

### Chapter 2 — AI Components
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_2)
*No specs yet.*

**Teaching artifact** — [Neural network recipe and calculator handout (PDF)](https://ai-public-health.com/content/files/2026/09/Neural-Network-Recipe-and-Calculator-handout-1.pdf)

### Chapter 3 — Design Models for AI in Public Health
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_3)

**Encoding Justice** (design principle for educating public health AI designers) `v0.x` — [SSRN preprint →](https://doi.org/10.2139/ssrn.7452818)

**C-E-A Framework** (Compliance, Efficacy, Autonomy) `v0.x` · *New* — spec in [`/ch03-design-models/cea-framework`](./ch03-design-models/cea-framework) · [SSRN preprint →](https://dx.doi.org/10.2139/ssrn.7208279)

### Chapter 4 — Evaluation Models for AI in Public Health
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_4)

**ICV-4-1 concept map** `v0.x` — spec in [`/ch04-evaluation-models/icv-4-1`](./ch04-evaluation-models/icv-4-1) · [Live map →](https://min-ph.github.io/ICV-4-1/)

**TFEF** (Temporal Fit Evaluation Framework) `v0.x` · *New* — [SSRN preprint →](https://dx.doi.org/10.2139/ssrn.7359644)

### Chapter 5 — Data Issues for AI
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_5)

**C-E-A applied to data issues** (regrouping Chapter 5's data issue concepts) `v0.x` · *New* — [Zenodo →](https://doi.org/10.5281/zenodo.22726862)

**ICV-5-1 concept map** `v0.x` — [Live map →](https://min-ph.github.io/ICV-5-1/index.html)

### Chapter 6 — Public Health Domain Data for AI
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_6)

**ICV-6-3 concept map** (personal health data concepts) `v0.x` — [Live map →](https://min-ph.github.io/ICV-6-3/)

**ICV-6-4 concept map** (metadata for AI-powered personal health records) `v0.x` — [Live map →](https://min-ph.github.io/ICV-6-4/)

### Chapter 7 — AI Applications for Public Health Systemic Factors
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_7)

**EquiRisk** (Equity-Aware Risk Stratification) `v0.x` — spec & schema in [`/ch07-systemic-factors/equirisk`](./ch07-systemic-factors/equirisk) · full implementation → [EquiRisk-FoodDeserts repo](https://github.com/Min-PH/EquiRisk-FoodDeserts) · [SSRN preprint →](https://doi.org/10.2139/ssrn.6150926)

### Chapter 8 — AI Applications for Public Health Personal Responsibilities
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_8)

**PAPO** (Policy-Aware Personalized Opportunity) `v0.x` — spec in [`/ch08-personal-responsibilities/papo`](./ch08-personal-responsibilities/papo) · full implementation → [PAPO-Heatwave-AI repo](https://github.com/Min-PH/PAPO-Heatwave-AI) · [SSRN preprint →](https://doi.org/10.2139/ssrn.6198260)

**Knowledge Engineering for PAPO** (companion ontology and flowchart, with heatwave response as a worked example) `v0.x` — [SSRN preprint →](https://dx.doi.org/10.2139/ssrn.7315020)

**PMCO-AI** (Personalized Motivation, Capability, and Opportunity, empowered by AI) `v0.x` — spec in [`/ch08-personal-responsibilities/pmco-ai`](./ch08-personal-responsibilities/pmco-ai) · [SSRN preprint →](https://dx.doi.org/10.2139/ssrn.7128200)

### Chapter 9 — From Acceptance to Thinking Partner
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_9)

**ATPM** (AI Thinking Partner Model) `v0.x` — [SSRN preprint →](https://dx.doi.org/10.2139/ssrn.7351618)

### Chapter 10 — AI and Workforce for Public Health
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_10)
*No specs yet.*

**Teaching artifact** — [Meta-AI homework: grading the thinking (PDF)](https://ai-public-health.com/content/files/2026/09/Meta-AI_Homework-1.pdf)

### Chapter 11 — Challenges and Opportunities in the Future
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_11)

**ICV-11-2 concept map** (long-term challenges) `v0.x` — [Live map →](https://min-ph.github.io/ICV-11-2/)

### Shared frameworks

**Middle-range theory** (bridging grand theory and AI practice, demonstrated in PAPO, EquiRisk, and PMCO-AI) `v0.x` — [SSRN preprint →](https://dx.doi.org/10.2139/ssrn.7262480)

---

## Repository structure

```
ai-public-health-specs/
├── README.md
├── ch01-introduction/
├── ch02-ai-components/
├── ch03-design-models/
│   └── cea-framework/
│       └── spec.md
├── ch04-evaluation-models/
│   └── icv-4-1/
├── ch05-data-issues/
├── ch06-domain-data/
├── ch07-systemic-factors/
│   └── equirisk/
│       ├── spec.md
│       └── schema/
├── ch08-personal-responsibilities/
│   ├── papo/
│   │   ├── spec.md
│   │   └── schema/
│   └── pmco-ai/
│       └── spec.md
├── ch09-thinking-partner/
├── ch10-workforce/
├── ch11-future-challenges/
└── shared/
    ├── schemas/        # data-preparation schemas that span chapters (e.g. CMDDS)
    └── fine-tuning/     # local model fine-tuning scripts (e.g. Llama 3.1)
```

Each chapter folder holds that chapter's specs, schemas, and blueprints directly. Where a framework also has a full runnable simulation, that code stays in its own dedicated repo (linked above) — this repo is the specification layer, not a monorepo of every implementation.

`shared/` is for technical resources that don't belong to one chapter — data schemas or fine-tuning scripts used across multiple frameworks.

## Related resources

- Content map, conceptual essays, and author background → [ai-public-health.com/about](https://ai-public-health.com/about/?ref=github-readme)
- [EquiRisk-FoodDeserts](https://github.com/Min-PH/EquiRisk-FoodDeserts) — full implementation, Ch. 7
- [PAPO-Heatwave-AI](https://github.com/Min-PH/PAPO-Heatwave-AI) — full implementation, Ch. 8
- Concept map sources — [ICV-4-1](https://github.com/Min-PH/ICV-4-1) (Ch. 4) · [ICV-5-1](https://github.com/Min-PH/ICV-5-1) (Ch. 5) · [ICV-6-3](https://github.com/Min-PH/ICV-6-3) and [ICV-6-4](https://github.com/Min-PH/ICV-6-4) (Ch. 6) · [ICV-11-2](https://github.com/Min-PH/ICV-11-2) (Ch. 11)
