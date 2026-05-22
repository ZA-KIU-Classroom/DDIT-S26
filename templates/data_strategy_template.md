# Data Strategy Template

## Purpose

Document your client's data strategy. This template produces Section 6 of the final project report. Use the Rogers four-prerequisite framework as the structure.

## Instructions

Complete all four prerequisites in sequence. The order is not arbitrary. Architecture cannot be designed before inventory and quality are assessed. Governance cannot be enforced before the architecture exists.

---

## Part 1. Data asset inventory

Map the five most important data assets the client currently holds.

| Asset name | What it contains | Owner (function) | Current quality level | Update frequency | AI use case it enables |
|---|---|---|---|---|---|
| 1 | | | High / Medium / Low | | |
| 2 | | | High / Medium / Low | | |
| 3 | | | High / Medium / Low | | |
| 4 | | | High / Medium / Low | | |
| 5 | | | High / Medium / Low | | |

Quality level definitions:
- High: structured, labelled, consistent, complete, and accessible via API.
- Medium: mostly structured but with gaps, inconsistencies, or access restrictions.
- Low: unstructured, incomplete, siloed in legacy systems, or missing ownership.

---

## Part 2. Data quality gaps for Deploy Now use cases

For each Deploy Now AI use case from your AI Opportunity Map, name the specific data quality issue that would prevent deployment.

| Deploy Now use case | Data asset required | Current quality issue | Remediation required | Estimated timeline |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |

Do not write "poor data quality" as the issue. Write the specific problem: "Credit application records from 2018 to 2021 lack income verification fields because the system upgrade in 2022 added a mandatory field not previously collected."

---

## Part 3. Architecture requirement

State whether your recommended strategic option requires a data lake, a real-time data pipeline, or both.

| Architecture component | Required? | Estimated timeline | Current state | Gap to close |
|---|---|---|---|---|
| Data lake or mesh | Yes / No | | | |
| Real-time pipeline | Yes / No | | | |
| MLOps infrastructure | Yes / No | | | |
| API layer for legacy integration | Yes / No | | | |

Architecture rationale:
Why does your recommended option require this architecture? What AI use case becomes possible only after this architecture is in place?

---

## Part 4. Governance framework

Name two governance decisions the client must make before any customer-facing AI goes live.

Decision 1:
- What must be decided:
- Who decides:
- Regulatory requirement it addresses:
- What happens if it is not made before AI deployment:

Decision 2:
- What must be decided:
- Who decides:
- Regulatory requirement it addresses:
- What happens if it is not made before AI deployment:

---

## Prerequisite sequencing

State the order in which the four prerequisites must be completed and the reason each must precede the next.

| Step | Prerequisite | Timeline | Why it must precede the next |
|---|---|---|---|
| 1 | Data inventory and ownership | | |
| 2 | Data quality remediation | | |
| 3 | Architecture modernisation | | |
| 4 | Governance framework | | |

---

## Quality check

Before finalising:
- Every data asset has a named owner function.
- Every quality gap is specific enough to assign a remediation task and an owner.
- The architecture requirement is connected to a named AI use case.
- Both governance decisions name a specific regulatory requirement.
- The prerequisite sequence is logical and the reason each step precedes the next is stated.

## Deliverable
Save as: `data_strategy_v1.md` in your team folder.
