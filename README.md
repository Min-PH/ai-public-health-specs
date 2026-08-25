# AI in Public Health — Specs & Implementations

*A single-source repository for offline implementations and specifications.*

For conceptual background, essays, and textbook integration, visit **[ai-public-health.com](https://ai-public-health.com)**.

Items below are tagged by how settled they are: `v1.0+` matches the published textbook, `v0.x` is an active preprint or blueprint being tested, `v0.0.x` is an experimental draft.

---

## Chapter index

### Chapter 1 — Introduction
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_1)
*No specs yet.*

### Chapter 2 — AI Components
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_2)
*No specs yet.*

### Chapter 3 — Design Models for AI in Public Health
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_3)
*No specs yet.*

### Chapter 4 — Evaluation Models for AI in Public Health
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_4)

**ICV-4-1 concept map** `v0.x` — spec in [`/ch04-evaluation-models/icv-4-1`](./ch04-evaluation-models/icv-4-1) · [Live map →](https://min-ph.github.io/ICV-4-1/)

### Chapter 5 — Data Issues for AI
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_5)
*No specs yet.*

### Chapter 6 — Public Health Domain Data for AI
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_6)
*No specs yet.*

### Chapter 7 — AI Applications for Public Health Systemic Factors
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_7)

**EquiRisk** `v0.x` — spec & schema in [`/ch07-systemic-factors/equirisk`](./ch07-systemic-factors/equirisk) · full implementation → [EquiRisk-FoodDeserts repo](https://github.com/Min-PH/EquiRisk-FoodDeserts) · [SSRN preprint →](https://doi.org/10.2139/ssrn.6150926)

### Chapter 8 — AI Applications for Public Health Personal Responsibilities
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_8)

**PAPO** `v0.x` — spec in [`/ch08-personal-responsibilities/papo`](./ch08-personal-responsibilities/papo) · full implementation → [PAPO-Heatwave-AI repo](https://github.com/Min-PH/PAPO-Heatwave-AI) · [SSRN preprint →](https://doi.org/10.2139/ssrn.6198260)

**PMCO-AI** `v0.x` — spec in [`/ch08-personal-responsibilities/pmco-ai`](./ch08-personal-responsibilities/pmco-ai) · [SSRN preprint →](https://dx.doi.org/10.2139/ssrn.7128200)

### Chapter 9 — From Acceptance to Thinking Partner
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_9)
*No specs yet.*

### Chapter 10 — AI and Workforce for Public Health
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_10)
*No specs yet.*

### Chapter 11 — Challenges and Opportunities in the Future
[Textbook chapter →](https://doi.org/10.1007/978-3-032-15872-7_11)
*No specs yet.*

### Pending chapter assignment

**C-E-A Framework** `v0.x` — spec in [`/pending/cea-framework`](./pending/cea-framework) · [SSRN preprint →](https://dx.doi.org/10.2139/ssrn.7208279)


---

## Repository structure

```
ai-public-health-specs/
├── README.md
├── ch01-introduction/
├── ch02-ai-components/
├── ch03-design-models/
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
├── pending/
│   └── cea-framework/
│       └── spec.md
└── shared/
    ├── schemas/        # data-preparation schemas that span chapters (e.g. CMDDS)
    └── fine-tuning/     # local model fine-tuning scripts (e.g. Llama 3.1)
```

Each chapter folder holds that chapter's specs, schemas, and blueprints directly. Where a framework also has a full runnable simulation, that code stays in its own dedicated repo (linked above) — this repo is the specification layer, not a monorepo of every implementation.

`shared/` is for technical resources that don't belong to one chapter — data schemas or fine-tuning scripts used across multiple frameworks.

## Related resources

- Conceptual essays, chapter directory, and author background → [ai-public-health.com](https://ai-public-health.com)
- [EquiRisk-FoodDeserts](https://github.com/Min-PH/EquiRisk-FoodDeserts) — full implementation, Ch. 7
- [PAPO-Heatwave-AI](https://github.com/Min-PH/PAPO-Heatwave-AI) — full implementation, Ch. 8
- [ICV-4-1](https://github.com/Min-PH/ICV-4-1) — concept map source, Ch. 4
