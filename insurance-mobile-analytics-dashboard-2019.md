---
title: "Mobile App Analytics Dashboard — Insurance Services Conglomerate"
year: 2019
domain: Insurance / Financial Services
duration: ~3 months (2019)
primary_role: Senior Information Architect
secondary_roles:
  - Data Analyst
  - Research Ops
methods:
  - Stakeholder interviews
  - Report inventory and analysis
  - App store review analysis
  - Prioritization workshop
  - Dashboard information architecture
impact: Gave product managers direct self-service access to app metrics, eliminating an analytics bottleneck that previously took months per request
---

# Insurance Conglomerate — Designing a Mobile Analytics Dashboard From First Principles

One of Brazil's largest insurance conglomerates had a data bottleneck: all product analytics requests went through a central team of five people, creating delays of months for a simple data query. As the mobile app design team leader, I ran a three-phase research and design process — stakeholder interviews, prioritization workshop, and dashboard architecture — that gave product managers direct, self-service access to the metrics they needed.

| | |
|---|---|
| **9 insurance product lines** covered in the dashboard | **5 metric categories** defined through research |
| **82.4%** of app store complaints concentrated in recurring topics | Analytics team of **~5 people** serving the entire company |
| **3 phases**: research → workshop → architecture | Dashboard scoped entirely through team-validated requirements |

---

## 1. Context

A large insurance conglomerate operated a mobile app covering nine product lines: Auto, Life, Health, Dental, Residential, Pension, Card, Capitalization, and a consolidated group view. Product managers across the mobile team made decisions with limited data visibility — any analytics request had to be routed through a central analytics team of approximately five people, and fulfillment could take months.

As the mobile app design team leader, I identified both the problem and the opportunity. The data existed; the access and structure didn't. A self-service dashboard would eliminate the bottleneck — but only if the metrics it contained were the right ones, defined by the people who needed to use it.

---

## 2. My Role

**Primary: Senior Information Architect**
I led the end-to-end process from research through architecture and handoff — designing the dashboard structure, not just researching the requirements. My role combined research leadership with information architecture and design direction.

**Secondary roles:**
- **Data Analyst**: Analyzed App Store and Google Play reviews to identify recurring product complaint clusters; quantified that 82.4% of complaints concentrated in recurring topics, directly shaping the Content and Platform metric categories.
- **Research Ops**: Facilitated the online prioritization workshop with the product and design team; structured the metric inventory and voting process that produced the final specification.

---

## 3. Method

**Phase 1 — Stakeholder research**
Inventoried every recurring report that product managers already received — understanding what data existed, in what format, and at what frequency. Conducted individual interviews with each manager to map what decisions they were making and what information they were missing. This produced two aligned outputs: an inventory of available data and a map of unmet needs.

Also conducted a review analysis of App Store and Google Play feedback to identify the most recurring product complaints — both to validate that known issues were reflected in the data model, and to inform metric selection.

**Phase 2 — Prioritization workshop**
Facilitated an online workshop with the product and design team. Working from the full inventory of potential metrics, the team voted on and ranked what they most needed to do their jobs. This session transformed a long list of possibilities into a structured, agreed-upon specification with explicit rationale for each metric included.

**Phase 3 — Architecture and design**
Translated the workshop output into a dashboard architecture across 5 metric categories, including filter logic. Briefed a UI designer on the architecture, who produced the prototype through multiple review rounds with the team. Final specification delivered to the analytics team for production build in Google Data Studio.

---

## 4. Analysis and Insights

**Finding 1 — Product managers were making decisions without the data that would most affect them.**
The bottleneck wasn't only logistical — it had created a culture of working around analytics rather than with it. Managers had developed proxies and workarounds for information they should have had directly. The interviews revealed gaps nobody had formally articulated before.

**Finding 2 — App store reviews were a concentrated signal.**
**82.4% of app store complaints** concentrated in a small set of recurring topics. This meant review analysis was not "read every review" but rather "identify the recurring clusters" — and those clusters directly shaped which Content and Platform metrics were prioritized in the dashboard.

**Finding 3 — The right metrics varied significantly by product line.**
Nine insurance product lines behave differently: Auto claims drive different usage patterns than Dental benefits or Pension management. The filter logic — by time period and by product line — was as important as the metrics themselves. Without per-product-line filtering, aggregate data would have obscured the signals most useful to any individual manager.

**Finding 4 — The workshop prevented building a dashboard nobody would use.**
Prior to the workshop, there were more than enough potential metrics to build a dashboard that satisfied nobody — too much data, poorly prioritized. The voting process forced the team to make explicit choices about what mattered most, which produced both a better specification and collective ownership of the output.

---

## 5. Deliverables and Outcomes

**Dashboard architecture across 5 metric categories:**
- **Application**: App Store and Play Store ratings, downloads, ranking evolution
- **Demographics**: Gender, age, and city distribution of active users
- **Usage**: Active users, sessions, session duration, screen depth
- **Platforms**: Device types, OS versions, app version adoption rates
- **Content**: Most accessed screens, service availability and failure rates

**Filter logic:** By time period and by each of the 9 insurance product lines (plus consolidated group view).

**Embedded chart reference:** A Google Data Studio chart-type reference was included in the architecture spec to guide implementation decisions for each metric type, reducing ambiguity in the handoff to the analytics team.

**Outcome:** Product managers gained direct, self-service access to the app metrics they needed to make decisions, eliminating the months-long wait for analytics request fulfillment. The metric scope was validated by the team before any implementation work began.

*Note: I left the company in January 2020 before the production dashboard was completed. Long-term adoption outcomes are unavailable. The methodology — research-led metric definition, team workshop for prioritization, and architecture handoff — is the transferable value.*

---

## 6. Recommendations and Next Steps

Top recommendations delivered through the process:

1. **Dashboard-first thinking for product decisions** — the bottleneck was structural; once resolved, the team could move from reactive to data-driven decision-making
2. **Per-product-line filtering as a first-class feature** — aggregate app data hides product-line-specific signals; granularity at the product line level was the primary utility
3. **App store review monitoring as an ongoing input** — the 82.4% concentration finding meant review analysis was tractable and repeatable, not just a one-time activity

Follow-up research that would have been valuable:
- Post-launch adoption study: which metrics did managers actually use most frequently, vs. which were selected in the workshop but rarely accessed?
- Qualitative check-in at 3 months: were the product decisions the dashboard was meant to inform being made more effectively?

---

## 7. Reflection

**What worked:** The three-phase structure was the right sequence. Stakeholder interviews before the workshop ensured the voting process was grounded in actual unmet needs rather than hypothetical desiderata. The workshop itself was efficient because participants arrived knowing what problems they were trying to solve.

The app store review analysis as a Phase 1 input was a useful complementary signal. It added user perspective (what customers complained about) to the stakeholder perspective (what managers needed to track), and the 82.4% concentration finding validated that the pain points were specific enough to be addressable.

**Challenges:** The analytics team who would build the dashboard were engaged late in the process — after the architecture was defined rather than as collaborators in it. Some implementation decisions (chart types, data pipeline constraints) would have been better if the analytics team had been at the table during the workshop rather than receiving a finished spec.

**What I'd do differently:** Involve the analytics team from Phase 2 onward. Their constraints on data availability and Google Data Studio capabilities would have shaped the workshop output in practical ways — reducing the gap between "what product managers want" and "what is feasible to build and maintain." Producing a spec that needs significant revision during implementation is a handoff failure, even if the research is solid.
