# Activity: Responsible AI and Governance Workshop
Saturday 30 May 2026
Block 1: 10:40 to 12:10
Delivery: Google Meet (online)

## Purpose

Apply responsible AI principles and EU AI Act risk classification directly to your
client's AI use cases. Produce a governance plan that meets the final exam standard.
This activity feeds directly into the governance section of the final report.

## Output

Updated `governance_plan_v2.md` pushed to your team GitHub repo before lunch.

## What the final exam requires

The governance plan is assessed under two of the four final exam criteria:

- Quality and feasibility of transformation roadmap (30%): governance must appear
  as a named workstream in the roadmap with a timeline, owner function, and budget.
- Strategic insight and analytical rigor (30%): governance decisions must be
  connected to specific AI use cases with explicit reasoning, not generic principles.

A governance plan that lists principles without connecting them to specific use cases
does not meet the standard. A governance plan without a named oversight body,
a stated review cadence, and a human override protocol per high-risk use case
loses points on both criteria.

---

## Part 1: EU AI Act Risk Classification (10 minutes)

Work individually. Then align as a team.

### Task

Take the AI use cases from your AI Opportunity Map. Classify each one using the
EU AI Act risk tiers below. Write the tier next to each use case.

### EU AI Act risk tiers

| Tier | Definition | Examples relevant to your industries |
|---|---|---|
| Unacceptable risk | Prohibited. Cannot be deployed. | Social scoring systems, real-time biometric surveillance in public spaces |
| High risk | Permitted but heavily regulated. Requires conformity assessment, human oversight, transparency to affected individuals, and logging. | Credit scoring (retail banking), automated hiring decisions, biometric categorisation |
| Limited risk | Permitted with transparency obligations. Must inform users they are interacting with AI. | Chatbots, AI-generated content, recommendation engines |
| Minimal risk | Permitted with no specific obligations beyond general law. | Spam filters, AI-powered logistics routing optimisation, inventory forecasting |

### Team A: Retail Banking Georgia
Consider: credit decisioning models, fraud detection, customer onboarding automation,
personalised product recommendation, call centre AI.

### Team B: Retail Pharmacy Georgia
Consider: product recommendation engine, influencer matching algorithm, social media
content generation, demand forecasting, customer loyalty personalisation.

### Team C: Logistics and Last-Mile Delivery Georgia
Consider: route optimisation, delivery time prediction, dynamic pricing, driver
performance scoring, automated dispatch.

### Classification table (complete for your team)

| AI use case | EU AI Act tier | Reason for classification | Georgian law obligation |
|---|---|---|---|
| | | | |
| | | | |
| | | | |
| | | | |
| | | | |

### Georgian data protection law note

The Law of Georgia on Personal Data Protection applies to any automated processing
of personal data. For high-risk use cases involving individual decisions (credit,
hiring, medical), the data subject has the right to human review of the automated
decision. This is not optional. It must appear in the governance plan.

---

## Part 2: Governance Framework Design (15 minutes)

Work as a team. Use the template in `templates/governance_plan_template.md`.

### Task

Design the governance structure your client needs before deploying AI at scale.

### Step 1: Name the oversight body

Give it a specific name relevant to your client. Not "AI Committee." Something
a board would recognise as a real institutional structure.

Examples:
- Retail Banking: AI Credit Risk Review Board
- Retail Pharmacy: Digital Ethics and Platform Integrity Committee
- Logistics: Algorithmic Operations Governance Panel

Define its membership. Which functions must be represented? Minimum requirements:
- A named executive sponsor (C-suite level)
- A risk or compliance function representative
- A technology or data function representative
- A business function representative from the primary AI use case domain

Define its decision rights. What decisions require this body's approval before
proceeding? At minimum:
- Deployment of any high-risk AI use case
- Changes to model thresholds that affect individual outcomes
- Response to a model failure or adverse outcome

Define its review cadence. How often does it meet? Minimum: quarterly for routine
review. Within 48 hours for any adverse outcome or regulatory enquiry.

### Step 2: Human override protocol for your two highest-risk use cases

For each of your two highest-risk AI use cases, write the override protocol.

The protocol must specify:
- The threshold that triggers human review (not "complex cases" — a specific condition)
- Who holds override authority (a role, not a person's name)
- How the override is documented and audited
- The maximum time allowed for human review before a default decision is applied

Example for a credit decisioning model:
- Trigger: model confidence score below 0.72, or loan application above GEL 50,000,
  or applicant flags a data error in their profile
- Override authority: Senior Credit Analyst (minimum Grade 3)
- Documentation: override logged in the credit management system with a written
  rationale within 24 hours
- Maximum review time: 5 business days; default is referral to a human underwriter

### Step 3: Connect governance to the roadmap

Every governance initiative must appear in the 18-month roadmap. Check that your
roadmap includes:
- Data governance framework: months 1 to 3 (prerequisite for any AI deployment)
- Oversight body established: months 2 to 4
- Human override protocols documented and tested: before any high-risk AI use case
  goes live
- First quarterly governance review: month 6

If any of these are missing from your roadmap, add them now.

---

## Part 3: Report-Out (10 minutes)

Each team has 90 seconds. Unmute and speak directly. No slides.

State:
1. The EU AI Act tier of your highest-risk AI use case and the reason for that classification.
2. The name of your oversight body and which executive function sponsors it.
3. The specific trigger threshold for your highest-risk human override protocol.

Instructor identifies the most common gap across all three teams and addresses it
before lunch.

---

## Quality checklist

Before pushing `governance_plan_v2.md` to GitHub, confirm:

- [ ] Every AI use case from the roadmap is classified by EU AI Act tier.
- [ ] The oversight body has a specific name, defined membership, stated decision rights, and a review cadence.
- [ ] Human override protocol exists for every high-risk use case with a specific trigger threshold, a named role for override authority, a documentation requirement, and a maximum review time.
- [ ] Georgian data protection law obligations are referenced for use cases involving individual automated decisions.
- [ ] Governance initiatives appear in the 18-month roadmap in months 1 to 6, before any AI deployment initiative.
- [ ] Change management appears as a separate workstream with a budget estimate at 20 to 30 percent of total transformation cost.

## Submission

Push `governance_plan_v2.md` to your team GitHub repo before 13:00.
