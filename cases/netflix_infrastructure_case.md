# Case: Netflix AI Infrastructure Scaling

## Source
Rogers, *The Digital Transformation Roadmap*, Chapter 3
Publicly available Netflix technology and business reporting, 2007 to 2016

## Purpose
Use this case to apply the AI infrastructure prerequisite framework. Every AI deployment in your client industry has a Netflix sequencing equivalent. Find it.

---

## The core argument

Netflix had the recommendation algorithm in 2008. It waited until 2013 to deploy it at scale. The five-year gap was not hesitation. It was discipline. The discipline to build infrastructure before deploying AI is what made the 80 percent figure possible.

---

## Timeline

| Year | What happened | Strategic logic |
|---|---|---|
| 2007 | Launches streaming from on-premise servers. Every subscriber sees the same homepage. Zero personalisation. | Streaming works at small scale without infrastructure investment. The constraint is not visible yet. |
| 2008 | Begins AWS migration. Internal decision: do not build the recommendation engine until the data infrastructure migration is complete. | The infrastructure-first commitment is made explicitly. The algorithm exists. The data is not ready. |
| 2010 to 2012 | Four years of data cleaning, labelling, and pipeline building. The recommendation algorithm is not deployed during this period. | The discipline is exercised under commercial pressure to launch. Competitors are gaining subscribers. Netflix holds the line. |
| 2012 | AWS migration complete. Data infrastructure production-ready. First time Netflix has clean, structured, real-time viewing data at scale. | The foundation is complete. Layer 1 is in place. |
| 2013 | Recommendation engine deploys to the full subscriber base. Performance at scale matches performance in testing. | Deployment works because the data was ready. The five-year infrastructure investment prevented the gap between test performance and live performance. |
| 2016 | Recommendation engine drives 80 percent of all content watched. Saves an estimated $1 billion annually through reduced subscriber churn. | The ROI on infrastructure investment is realised exactly as modelled. |

---

## The numbers

| Metric | Value |
|---|---|
| Years of infrastructure before AI deployment | 4 |
| Content driven by AI recommendation | 80 percent |
| Annual churn value saved by recommendation engine | $1 billion (estimated) |
| Annual AWS and data infrastructure cost | $1 billion |

The infrastructure is not a cost centre. It is the revenue protection mechanism.

---

## What the case teaches

### Infrastructure determines the ceiling on AI performance

A recommendation algorithm trained on undocumented, inconsistent data does not produce an 80 percent engagement rate. It produces unreliable recommendations that users learn to distrust. Netflix built the data infrastructure first because without it, the model could not function at the level required to deliver the ROI.

### The discipline to wait is a strategic decision

Netflix had commercial pressure to deploy the recommendation engine earlier. Subscribers were churning to competitors. The decision to wait until the infrastructure was ready was a strategic choice, not a technical limitation. Most organisations make the opposite choice and pay for it in failed pilots.

### The AI strategy followed the data strategy

Netflix did not decide to build a recommendation engine and then build the data infrastructure to support it. The sequence was the reverse. The data infrastructure was built first. The AI capability was deployed when the infrastructure was ready to support it at scale.

---

## Discussion questions

1. What is the equivalent of Netflix's viewing data for your client? What high-frequency, structured, proprietary transactional data does your client generate that a new entrant cannot replicate in year one?

2. What infrastructure prerequisite must be in place before your most important H2 AI initiative can deploy at scale? Is that prerequisite in your roadmap, and is it in H1?

3. Netflix invested in infrastructure for four years before seeing the ROI. How would you structure the board-level business case for an infrastructure investment with no direct revenue impact for 12 to 24 months? What is the cost of not building it?
