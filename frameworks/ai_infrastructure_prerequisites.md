# Framework: AI Infrastructure Prerequisites

## Source
Rogers, *The Digital Transformation Roadmap*, Chapters 1 to 9

## Core argument

Most AI strategies fail at infrastructure, not at ambition. The error is deploying AI before the data and infrastructure foundation is ready. Infrastructure must sequence before strategy, not after it.

---

## The wrong sequence (what most organisations do)

1. Board approves an ambitious AI vision with a launch date.
2. Technology team deploys a pilot using whatever data is available.
3. Pilot works on clean test data in a controlled environment.
4. Deployment fails on messy live production data at scale.
5. Project is declared a success in the press release.
6. Quietly abandoned 18 months later. Post-mortem: data was not ready, governance did not exist, staff were not trained.

---

## The three infrastructure layers

Each layer must be in place before the one above it can function reliably at production scale.

### Layer 1: Data (the foundation)

Contents: clean labelled data for the specific AI use case, data lake or mesh architecture with real-time pipelines, governance framework covering ownership, access, consent, and audit trail.

Why it comes first: a model trained on unclean, undocumented data will fail in production even if it performs on test data. Most organisations underestimate both the time required and the cost to get this layer production-ready.

### Layer 2: Model and compute

Contents: foundation model selection or training, MLOps pipeline for versioning and retraining, cloud or on-premise compute, model registry for audit and rollback.

Dependency: cannot exist without Layer 1. Garbage in, garbage out at scale.

### Layer 3: Application and integration

Contents: API integration with core systems, user interface for frontline staff, monitoring dashboard, feedback loops that send production data back for model retraining.

Dependency: cannot exist without Layer 2. A beautiful AI interface connected to an unreliable model produces unreliable outcomes at scale.

---

## The four data strategy prerequisites

These must be completed in sequence. The order is not arbitrary.

### Prerequisite 1: Data inventory and ownership
- Map every data asset.
- Assign a named owner.
- Document quality level, recency, and access restrictions.
- Timeline: 3 to 6 months for a mid-size enterprise.
- Consequence if skipped: when the model fails, no one knows which dataset caused it. Regulatory audit is impossible.

### Prerequisite 2: Data quality remediation
- Clean and label data for the specific AI use case.
- Historical data is typically 70 percent usable without remediation. AI training requires 95 percent or more.
- Timeline: 6 to 12 months depending on data volume and legacy system complexity.
- Consequence if skipped: the pilot succeeds on curated test data and fails on live data. Full implementation cost paid, zero value realised.

### Prerequisite 3: Architecture modernisation
- Migrate from siloed legacy systems to a data lake or mesh architecture with clean APIs.
- Core banking and healthcare record systems are the hardest and longest to migrate.
- Timeline: 12 to 24 months for core system migration.
- Consequence if skipped: AI integration requires clean APIs. Legacy systems without APIs cannot feed real-time models.

### Prerequisite 4: Governance framework
- Define who can query which data, under what conditions, with what audit trail.
- Required before any customer-facing AI in regulated industries.
- Timeline: 3 to 6 months for policy; ongoing enforcement for the life of the AI system.
- Consequence if skipped: regulatory exposure. GDPR and Georgian data protection law require auditability of automated decisions.

---

## The Netflix case (Rogers Chapter 3)

Netflix had the recommendation algorithm in 2008. It waited five years to deploy it at scale because the data was not ready.

Timeline:
- 2007: launches streaming. All content from on-premise servers. Zero personalisation.
- 2008: begins migrating to AWS. Internal commitment: no AI recommendation engine until data infrastructure migration is complete.
- 2010 to 2012: four years of data cleaning, labelling, and pipeline building. No recommendation engine launched.
- 2012: AWS cloud migration complete. Data infrastructure production-ready.
- 2013: recommendation engine deploys to the full subscriber base.
- 2016: recommendation engine drives 80 percent of content watched. Saves an estimated $1 billion annually through reduced churn.

The lesson: Netflix had the technology and still waited five years. The discipline to invest in infrastructure before deploying AI is what made the 80 percent figure possible.

---

## Calibration for your roadmap

If your roadmap shows AI deployment in month 6 but Prerequisite 2 (data quality remediation) takes 12 months, the financial model is wrong.

Build the prerequisite timeline first. Then place the AI deployment initiatives after the prerequisites are complete. The roadmap sequence is evidence of your understanding of infrastructure logic.

---

## Application to Weekend 3

In your data strategy section:
- Sequence all four prerequisites explicitly.
- State the estimated timeline for each prerequisite in your client's context.
- Name the specific data quality issue that would prevent your Deploy Now use cases from scaling.
- Connect data governance (Prerequisite 4) to a named H1 roadmap initiative before any AI deployment.
