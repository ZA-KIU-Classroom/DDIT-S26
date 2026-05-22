# Framework: Operating Model Transformation

## Source
Westerman, Bonnet, and McAfee, *Leading Digital*, Chapters 3 to 5

## Core definition

The operating model is how an organisation creates value day to day: its processes, structures, technology use, and performance metrics. Digital transformation is not primarily a technology change. It is an operating model change. Technology is an input. The operating model is the mechanism.

---

## Traditional vs AI-first operating model

| Dimension | Traditional | AI-first |
|---|---|---|
| Processes | Documented workflows executed by specialised humans | Algorithmic decision loops; humans handle exceptions and judgment |
| Structure | Functional hierarchy; decisions escalate upward | Product and platform teams; decisions pushed to the algorithm boundary |
| Technology | Systems of record that support humans | AI systems that create value directly; humans govern thresholds |
| Metrics | Efficiency and output quality | Prediction accuracy, data freshness, learning velocity |
| Innovation | Dedicated R&D separate from operations | Continuous through A/B testing and algorithmic optimisation |

---

## Three transformation levers

Every transformation must address all three levers. Skipping one produces the implementation gap.

### Lever 1: Process redesign

Redesign workflows from first principles for AI augmentation. Do not automate a broken process.

The automation trap: most organisations map their existing process and ask where AI can fit in. This produces a 10 to 15 percent efficiency gain on a workflow designed for humans. The ceiling is reached immediately.

First principles redesign: start from the outcome. What decision needs to be made, with what information, in what time frame? Design the workflow backwards from that outcome. AI handles routine decisions. Humans handle exceptions and judgment calls.

TBC Bank example: before deploying AI credit scoring, TBC redesigned the credit decision workflow from a sequential human review process to an algorithmic first-pass with human escalation for edge cases only. Decision time: 4 days to 4 minutes.

Key test: is the AI handoff threshold specific? "Complex cases" is not a threshold. "Loan applications above GEL 50,000 or with missing income documentation" is a threshold.

### Lever 2: Structure and talent

Reorganise teams around products and data flows, not functions. Hire AI-literate managers at every layer.

The structural failure pattern: organisations create a "Digital Transformation Team" inside the existing structure. The new team reports to the same management, uses the same budget process, and is evaluated on the same metrics. Nothing changes.

Cross-functional squads: each squad owns a domain end to end: the data, the model, the application, and the business outcome. No handoffs between data science, engineering, and product.

ING Bank example: moved to agile squads of 9 people. Developers, data scientists, and product managers in one team. Time from idea to production: 18 months to 3 weeks. The structural change preceded the speed improvement.

Agile at scale levels:
1. Team agile: one squad, one product, two-week sprints.
2. Tribe agile: 10 to 15 squads by domain with shared data contracts.
3. Enterprise agile: capital allocation follows learning quarterly, not annual plans.
4. AI-native agile: models are products; retraining cycles replace feature release cycles.

### Lever 3: Governance and data

Establish data ownership, quality standards, and AI output governance before scaling.

The liability risk: one bad algorithmic decision at scale becomes a regulatory event. Governance must precede deployment.

Required governance elements:
- Named data owner for every dataset.
- Quality thresholds before AI training.
- Model review board for high-stakes AI decisions.
- Human override protocol per use case.
- Audit trail for every AI decision.

Ant Financial example: deployed AI to 500 million credit customers only after establishing a three-tier model review process, real-time anomaly detection, and human override protocols. Governance first, scale second.

---

## The human tax

Technology is the smallest cost in a transformation. Change management is the most consistently underfunded.

Typical transformation budget breakdown:
- Technology platform and licensing: 15 to 25 percent
- Implementation and integration: 25 to 35 percent
- People and change management: 20 to 30 percent
- Governance and contingency: 15 to 20 percent

The adoption gap: a model that runs but is not used by staff delivers full implementation cost with zero realised value. This is invisible on the P&L until the business case review.

Why AI change is harder than other change:
- AI changes how decisions are made, not just how work is done.
- Employees resist because AI adoption threatens their judgment as a source of professional value.
- The change is continuous, not one-time. Models are retrained. Thresholds shift. Roles evolve after go-live.

---

## Application to Weekend 3

In your operating model section:
- Show both current state and target state for the primary process. Do not show only the target.
- Name a specific AI handoff threshold, not a category.
- Connect every operating model change to a named H1 or H2 roadmap initiative.
- Include change management as a line item in the budget, not a row in the risk register.
