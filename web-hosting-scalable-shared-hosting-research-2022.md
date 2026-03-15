```yaml
title: "Scalable Shared Hosting UX Research — Web Services Platform"
year: 2022
domain: Web Hosting / SaaS
duration: ~5 weeks (late August–late September 2022)
primary_role: Senior UX Researcher
secondary_roles:
  - Product Strategist
methods:
  - Prior research synthesis
  - Customer interviews
  - Mockup evaluation
  - Prototype usability testing
  - Screener survey
impact: Provided validated product-market fit evidence and failure-mode analysis for a new hosting tier targeting high-value churning customers
```

# Web Hosting Platform — Why High-Traffic Customers Left for Competitors at 5–10× the Price

An enterprise web services platform was losing high-traffic small and medium business customers at a critical growth inflection point. When these customers outgrew shared hosting, the upgrade path pushed them to VPS plans — which many found too complex and too expensive. Rather than upgrading, they migrated to competitors at **5–10× the monthly price**. I led a four-phase mixed-methods study to understand whether a more capable shared hosting tier could retain them — and what the current experience was doing wrong at the moment they most needed clarity.

| | |
|---|---|
| **251** screener respondents qualifying the research sample | **86** participants (34%) accepted research invitations |
| **100% SMB** target segment — 70% non-web professionals | Customers leaving for competitors at **5–10×** the monthly price |
| Usability issues documented at **3 levels**: Interaction, Journey, Relationship | **4 research phases** from prior synthesis to prototype testing |

---

## 1. Context

An enterprise web hosting platform's shared hosting tier served SMB customers well at entry level — but hit a ceiling. When sites grew and performance degraded due to high traffic, the platform's only upgrade path was VPS or dedicated plans. Both were significantly more expensive and more technically complex than the customers who needed them were equipped to manage.

The pattern the team observed: high-traffic customers were migrating to competitors who offered plans at 5–10× the monthly price, choosing the pain and cost of migration over the complexity of upgrading within the platform. This was a retention failure at exactly the moment when customers should be most committed — when their sites were succeeding.

The question: could a new tier between shared and VPS retain these customers? And first: what exactly was failing when customers hit the performance wall?

---

## 2. My Role

**Primary: Senior UX Researcher**
I led all four phases of the study — from synthesizing prior research through prototype testing — and produced structured, actionable recommendations organized by impact and implementation effort.

**Secondary roles:**
- **Product Strategist**: Identified that the core retention problem was an upgrade path architecture failure, not primarily a price or feature problem — reframing the product direction from "build a better VPS" to "remove the upgrade cliff entirely."

---

## 3. Method

**Phase 1 — Prior Research Synthesis**
Analyzed existing customer research across the platform's hosting tiers: prior surveys and lean interviews from the preceding two years. Established what was already known about shared, VPS, and dedicated hosting customers before designing new research. Identified persistent patterns: customers in shared hosting primarily wanted more websites, more traffic handling, and more storage. Key cancellation reason for VPS: lack of guidance and the product not meeting needs.

**Phase 2 — Customer Interviews**
Recruited and interviewed SMB customers who had needed to upgrade from shared hosting. Three focus areas: Were their needs being met? What difficulties were they experiencing? Would they have preferred a more powerful shared hosting option over full VPS?

**Phase 3 — Mockup Evaluation**
Evaluated mockups of a proposed in-product alert and resolution flow for clarity and tone. Core scenario: a customer receives an alert that their site is experiencing performance issues due to high traffic and needs to understand what's happening and decide what to do next.

**Phase 4 — Prototype Testing**
Tested the refined prototype with a screened sample. **251 screener respondents**, **86 participants (34%)** accepted invitations. Sample: **100% SMB**, **70% non-web professionals** — customers managing their own sites without technical support staff. The most realistic possible test of the upgrade flow clarity.

---

## 4. Analysis and Insights

**Finding 1 — Alerting customers about a performance problem — without a self-service resolution path — accelerated churn.**
Customers who received a performance alert immediately began researching alternative hosting providers. The alert communicated "your site has a problem" but not "here's how to fix it yourself." Without a clear, accessible resolution path, the alert became a prompt to leave rather than a reason to upgrade.

**Finding 2 — The alert email's CTA was too passive.**
Participants expected a more direct, action-oriented label. The call-to-action was framed in a way that didn't communicate urgency or a clear next step. This was an interaction-level finding, but its impact was relationship-level: customers who saw a vague CTA at a high-stress moment lost confidence in the platform.

**Finding 3 — Upgrade plans weren't available to purchase at the moment customers were most motivated.**
When customers wanted to act on a resolution, the relevant plans were shown as "coming soon" rather than available for immediate purchase. This was confirmed to frustrate customers further — a "coming soon" state at a moment of motivated intent broke the conversion.

**Finding 4 — The knowledge base was too generic to help at the moment of a specific problem.**
Customers were directed to a general help landing page when they needed a purpose-built troubleshooting page for the specific CPU-consuming issue. "General resources" and "I'm in a crisis right now" are incompatible mental modes.

**Finding 5 — Resolution options needed to be ordered from lowest cost to highest cost.**
Customers wanted to see no-cost resolution options (self-service, contacting support) *before* being offered a paid upgrade. Presenting upgrade options first made the platform feel exploitative rather than helpful.

**Finding 6 — Customers couldn't identify which component was causing the performance issue.**
Without knowing which website, plugin, or component was responsible, customers couldn't act without contacting support. This removed self-service as a viable path and increased support load unnecessarily.

---

## 5. Deliverables and Outcomes

- Full four-phase research report with findings at interaction, journey, and relationship levels
- Prioritized recommendations organized by impact and implementation effort
- Prior research synthesis establishing baseline knowledge across hosting tiers
- Mockup and prototype evaluation with specific issue documentation

**Key product directions delivered:**
- Present no-cost resolution options (self-service, support contact) *before* upgrade offers in the alert flow
- Identify and surface the specific CPU-consuming component in the alert — customers need to know *what* is causing the issue, not just that a problem exists
- Keep upgrade plans unavailable rather than "coming soon" — showing an inaccessible upgrade further frustrated motivated customers
- Create a purpose-built troubleshooting page for performance incidents instead of pointing to a general knowledge base
- Rewrite the alert email CTA with direct, action-oriented language

**Strategic finding for the product roadmap:** The study provided validated evidence that a higher-performance shared tier, positioned correctly (no complex management required, self-service resolution, immediate availability), could address the retention problem without forcing customers into VPS complexity they didn't want or need.

---

## 6. Recommendations and Next Steps

Top recommendations delivered (ordered by impact):

1. **Fix the resolution path first** — an alert without resolution accelerates churn; the path from alert to fix must be self-contained
2. **Surface the root cause in the alert** — "your site is using too much CPU" needs to say which component is responsible
3. **Reorder the CTA hierarchy** — no-cost options (self-service fix, contact support) before paid upgrade options
4. **Replace "coming soon" with nothing** — an unavailable plan shown at a moment of intent is worse than no plan at all
5. **Build a performance-specific troubleshooting resource** — generic KB is not help during a crisis

Follow-up research recommended:
- Test the revised alert flow with the same SMB, non-technical-professional profile to validate whether the reordered CTA changes resolution behavior
- Validate the "no-cost first" ordering specifically with customers who have expressed intent to leave

---

## 7. Reflection

**What worked:** The four-phase structure was the right architecture for this question. Phase 1 (prior synthesis) prevented re-discovering what was already known and focused new research on genuine gaps. Phase 3 (mockup evaluation) allowed early tone and clarity testing before investing in full prototyping. The progression was efficient.

The framing of usability issues at three levels — interaction, journey, and relationship — was a useful organizing structure for the product team. Interaction-level issues (bad CTA copy) and relationship-level issues (alerting without helping) require different owners and different timelines. Separating them prevented the common failure of treating a relationship-level trust problem as a copywriting fix.

**Challenges:** The screener recruited SMB customers who had already upgraded — which introduced recency bias in their evaluation of the alert flow. Customers who had already lived through the upgrade experience were evaluating a hypothetical version of their past, not a current stressor. Recruiting customers *currently* experiencing performance issues would have been more ecologically valid but harder to source.

**What I'd do differently:** Include a behavioral analytics component alongside the interviews to identify what support tickets and page paths preceded churn. Qualitative research established the experiential failure modes well, but quantitative data on churn timing relative to performance alerts would have strengthened the business case for the new tier.
