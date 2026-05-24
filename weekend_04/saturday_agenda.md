# Saturday Agenda
Saturday 30 May 2026
10:00 to 17:00
Delivery: Google Meet (online)

## Technical requirements
Join from a quiet location with a stable internet connection. Camera on for the
full session. Have your presentation deck open and ready to share before 10:00.
Test screen sharing before the session starts. If you have a connection problem,
message the group WhatsApp channel immediately and reconnect as fast as possible.

If a presenter drops during the coaching session, the next team member takes over
from the last slide shown. Wait 90 seconds for reconnection before continuing.

## Purpose
Teaching day and final coaching session. Two blocks of syllabus content in the
morning and early afternoon. Structured presentation coaching in the mid-afternoon.
Hard submission check and sprint close at the end of the day.

## Schedule at a glance

| Time | Block | Method | Key output |
|---|---|---|---|
| 10:00 to 10:30 | Sprint review and day framing | Sprint review, team report-out | Gaps identified, coaching priorities set |
| 10:30 to 10:40 | Break | | |
| 10:40 to 12:10 | Block 1: Responsible AI and governance | Lecture, case discussion, activity | Governance plan updated |
| 12:10 to 13:00 | Lunch | | |
| 13:00 to 14:00 | Block 2: Future of work and course synthesis | Lecture, scenario discussion | Personal synthesis notes |
| 14:00 to 14:10 | Break | | |
| 14:10 to 16:20 | Block 3: Final presentation coaching | Team presentations with structured feedback | Deck refined, three improvements identified per team |
| 16:20 to 16:30 | Break | | |
| 16:30 to 17:00 | Submission check and close | Submission check, exit ticket | All Saturday deliverables confirmed in repo |

---

## 10:00 to 10:30 — Sprint Review and Day Framing

### Purpose
Create accountability for the one-week final sprint. Surface the three changes each
team made to their final presentation since Weekend 3. Identify the one remaining
risk per team before coaching begins.

### Format
Each team has two minutes. No slides. Three questions only. Teams unmute and
speak directly. No chat responses for this section — verbal only.
1. What are the three most significant changes you made to your final presentation this week?
2. What is the one structural weakness you still have going into Sunday?
3. Is your deck submitted to GitHub?

### Instructor action
Note each team's stated weakness. These become the coaching priorities for Block 3.
Any team that has not submitted their deck to GitHub by 10:00 must do so before
lunch. There are no exceptions. Submission is confirmed by the instructor checking
the repo live during the break.

---

## 10:40 to 12:10 — Block 1: Responsible AI and Governance

### Syllabus coverage
Week 13: Responsible AI principles, EU AI Act, regulatory landscape.

### Learning objectives
By the end of this block, students will be able to:
- name the four core responsible AI principles and explain how each applies to a specific AI use case in their client context,
- identify which risk tier their client's AI use cases fall into under the EU AI Act,
- design a governance framework with a named oversight body, review cadence, and human override protocol,
- connect the governance plan to the roadmap as a prerequisite for AI deployment.

### Block structure

**10:40 to 11:10 — Responsible AI principles and EU AI Act**

Four principles: bias and fairness, transparency and explainability, accountability,
and privacy. Each principle applied to a Georgian industry context.

EU AI Act risk tiers: unacceptable risk, high risk, limited risk, minimal risk.
Practical classification exercise: where do retail banking credit models, pharmacy
recommendation engines, and logistics routing algorithms sit?

Georgian data protection law: Law of Georgia on Personal Data Protection. Key
obligations for automated decision-making that affect individuals.

**11:10 to 11:50 — Governance framework design activity**

Teams work on their governance plan using the template in `templates/governance_plan_template.md`.

Activity structure (40 minutes):
- Part 1 (10 min): Classify each AI use case from your roadmap by EU AI Act risk tier.
- Part 2 (15 min): Design the oversight body. Name it. Define its membership (which functions must be represented), its decision rights, and its review cadence.
- Part 3 (15 min): Write the human override protocol for your two highest-risk AI use cases. State the threshold that triggers human review and who holds override authority.

Quality standard: a governance plan without a named oversight body, a stated review cadence, and a human override protocol per high-risk use case does not meet the final exam standard.

**11:50 to 12:10 — Report-out and instructor synthesis**

Each team states in 90 seconds:
- which EU AI Act tier their highest-risk use case falls into,
- who sits on their oversight body,
- what the human override threshold is for that use case.

Instructor identifies the most common gap across all three teams and addresses it
before lunch.

### Saturday submission from this block
Updated `governance_plan_v2.md` pushed to team GitHub repo before lunch.

---

## 13:00 to 14:00 — Block 2: Future of Work and Course Synthesis

### Syllabus coverage
Week 14: Future of work, human-AI collaboration models, workforce transformation,
personal leadership in the digital era.
Week 15: Course synthesis and key takeaways.

### Learning objectives
By the end of this block, students will be able to:
- describe three human-AI collaboration models and identify which applies to their client's workforce,
- articulate the change management implications of AI deployment for their client's workforce,
- synthesise the key strategic insight from the full course arc in one sentence per major framework.

### Block structure

**13:00 to 13:30 — Human-AI collaboration models and workforce transformation**

Three models: AI as tool (human decides, AI informs), AI as colleague (shared
decision-making with defined handoff thresholds), AI as manager (AI decides within
defined parameters, human audits).

Which model applies at each horizon of the Three Horizons portfolio? H1 pilots
typically start at AI as tool. H2 platform plays move toward AI as colleague. H3
business model transformations may require AI as manager in specific domains.

Workforce implications: which roles change, which roles disappear, which new roles
emerge. Change management as the largest underestimated cost in transformation.

**13:30 to 13:50 — Scenario planning: Digital Transformation 2030**

What does the competitive landscape in each team's industry look like in 2030 if
AI deployment accelerates at current rates? One-sentence answer per team. This is
not a research exercise. It is a synthesis of everything learned across the semester.

**13:50 to 14:00 — Course synthesis**

Five framework-level takeaways from the full course arc. Students write one sentence
per framework summarising the most important strategic insight. These sentences become
the analytical backbone of the final presentation's executive summary.

---

## 14:10 to 16:20 — Block 3: Final Presentation Coaching

### Purpose
Each team presents their executive summary and strategic options section only.
Instructor and peers give structured feedback using the 40-point rubric criteria.
Teams use any remaining time to make targeted improvements before Sunday.

### Format
Three teams. Approximately 40 minutes per team including feedback. Each team
shares their screen to present. Peer teams have cameras on and are muted during
the presentation. Q&A is structured turn-taking: instructor calls on peer teams
by name. Open mic is not used.

**Per team (40 minutes):**
- Team shares screen and presents executive summary and strategic options: 10 minutes
- Instructor feedback using the four final exam criteria: 10 minutes
- Peer team challenge via structured turn-taking (one number challenge, one structural distinction challenge): 10 minutes
- Team records three specific improvements to make before Sunday: 10 minutes

### Coaching focus areas (based on consistent gaps from Weekend 3 midterms)
- Executive summary must state three conclusions, not describe the presentation structure
- Strategic options must be structurally distinct: different value proposition, different revenue model, different capability requirement
- ROI sensitivity table must show the worst credible downside, not just the base case
- Roadmap must show data governance in months 1 to 6 before any AI deployment initiative
- Change management must appear as a named workstream with a budget estimate and owner function
- Governance plan must be a section of the final report, not a bullet in the risk register

### Output
Each team leaves Block 3 with three specific written improvements assigned to named
owners, to be completed before Sunday 10:00.

---

## 16:30 to 17:00 — Submission Check and Close

### Submission check
Every item below must be confirmed in the team GitHub repo before students leave.

| Deliverable | Deadline | Status |
|---|---|---|
| Final presentation deck (complete) | Saturday 17:00 | |
| Governance plan v2 | Saturday 17:00 | |
| Comprehensive report (near-complete draft) | Saturday 17:00 | |
| Roadmap final version | Saturday 17:00 | |
| Three improvements from coaching session (written) | Saturday 17:00 | |

### Exit ticket (individual, 2 minutes)
1. The three specific improvements I am making to my team's presentation tonight.
2. My personal role in Sunday's presentation and the section I own.
3. One thing I would do differently in the sprint if I had the week again.

---

## Readings for this weekend
- McKinsey Global Institute reports on AI (2024 to 2026)
- Rogers — The Digital Transformation Roadmap (Chapters 7 to 9)
- Course readings review and synthesis
