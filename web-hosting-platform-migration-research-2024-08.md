---
title: "Platform Migration Customer Feedback Analysis — Enterprise Web Hosting"
year: 2024
domain: Web Hosting / Enterprise SaaS
duration: 4 weeks (August–September 2024)
primary_role: Senior UX Researcher
secondary_roles:
  - Research Ops
methods:
  - Survey analysis (Voice of Customer, in-product feedback)
  - Qualitative interviews
  - Thematic coding
  - Sentiment analysis
  - Cross-platform comparative analysis
  - Issue frequency and severity mapping
impact: Findings directly influenced Q4 2024 and Q1 2025 product roadmap across 4 cross-functional teams
---

# Enterprise Web Hosting — Turning 999 Migration Complaints Into an Action Plan

When an enterprise web hosting company migrated thousands of customers from two acquired platforms to its unified system, initial signals pointed to significant dissatisfaction — but the scope and root causes were unknown. I turned **999 unstructured customer responses** into a clear, prioritized action plan across product, engineering, support, and leadership in four weeks.

| | |
|---|---|
| **999** customer responses analyzed across 3 data streams | **~90,000** emails lost in a single migration incident |
| **8** live conversations with migrated customers | **79** customers who explicitly named their legacy platform |
| **8** prioritized improvement areas with specific actions | **4** cross-functional teams briefed |

---

## 1. Context

An enterprise web hosting company had acquired two competitor platforms and migrated thousands of customers to its unified system. Initial feedback signals pointed to widespread dissatisfaction, but the scope, root causes, and distinctions between the two migrated cohorts were unknown.

The two legacy platforms served fundamentally different customer profiles. Platform A was a domain-focused registrar with a high proportion of long-tenured resellers and power users — many with 10+ years on the platform. Platform B was a website and email-focused service serving small business owners with varied technical skill levels. Both had been migrated to the same unified system, but their experiences of that migration were expected to differ significantly.

The business risk: customer churn at scale from two newly acquired cohorts simultaneously, with no clear picture of what was driving it or where to focus recovery efforts.

---

## 2. My Role

**Primary: Senior UX Researcher**
I designed the cross-platform comparative analysis framework, led all 8 live customer interviews, and synthesized 999 responses across three data streams into a single prioritized report.

**Secondary roles:**
- **Research Ops**: Defined the cohort segmentation strategy (450 Platform A / 549 Platform B), created the tagging framework for open-ended response coding, and structured the 8-priority-area output format for cross-functional briefing.

---

## 3. Method

**Three data streams, analyzed in parallel:**

1. **Voice of Customer surveys** (May–July 2024): large-scale survey responses from recently migrated customers
2. **In-product feedback survey** (July 2024): shorter feedback capture from within the unified platform
3. **Qualitative interviews** (July–August 2024): 8 live conversations with migrated customers, plus written feedback from **79 respondents** who explicitly named their legacy platform (55% Platform A / 45% Platform B in written feedback; 25% / 75% split in live interviews)

**Analysis methods:**
- Thematic coding of open-ended responses across all three streams
- Sentiment analysis by feedback category
- Issue frequency and severity mapping
- Cross-platform comparative analysis to distinguish shared pain points from platform-specific failures

The two cohorts were analyzed separately and then compared: **450 responses** from Platform A, **549 responses** from Platform B.

A secondary analysis of the unified platform's website builder used satisfaction score distribution to quantify polarization.

---

## 4. Analysis and Insights

**Finding 1 — Both cohorts shared the same top three pain points despite coming from fundamentally different products.**
Service quality degradation, feature parity gaps, and communication failures throughout the migration appeared as the top three themes for both Platform A and Platform B customers — suggesting these were structural migration failures, not legacy-platform-specific issues.

**Finding 2 — The most critical incident for Platform A customers was a data integrity failure.**
A single migration event caused the loss of **~90,000 emails** for affected accounts, with no recovery path or compensation communicated. Long-tenured customers — many 10+ years on Platform A — reported active intent to transfer their domains to competitors. The platform had silently removed features they relied on, with no equivalent alternatives provided.

**Finding 3 — Platform B customers hit a wall of missing functionality.**
Web forwarding, email alias management, and nameserver editing had all been deactivated on the unified platform. SSL certificate reliability was broken. Customers received no advance notice of the merger and no documentation explaining what had changed or why.

**Finding 4 — Customers felt blindsided universally.**
No migration guidance, no system-difference documentation, no proactive outreach. This was the most consistent theme across all 999 responses: customers were discovering changes after the fact, on their own, without context.

**Finding 5 — The website builder showed deeply polarized satisfaction (20% very satisfied vs. 45% dissatisfied).**
The gap was driven primarily by technical failures and inaccessible support — not by the product itself. Customers who could access working features were generally satisfied; those who encountered broken features had no path to resolution.

**Finding 6 — Live conversations revealed severe retention risk with compelling specificity.**
One long-tenured domain customer calculated a **72% price increase** on domain renewals ($21.99 → $37.99) and described starting a new customer relationship with an immediate price increase as "absolutely horrendous." A power user managing 20+ domains for family members and non-profits spent approximately **10 hours** attempting to transfer a single locked domain. A third customer transferred all his domains to a competitor the moment email forwarding was announced as discontinued — and completed the transfer before the decision was reversed, making him a lost customer despite the feature rollback.

**Finding 7 — Feature discoverability was a distinct problem from feature availability.**
One customer with a positive post-migration experience noted "once they find the feature, everything goes well" — confirming that even for unaffected users, finding features was the primary obstacle.

---

## 5. Deliverables and Outcomes

- Full research report with 8 prioritized improvement areas, each with specific actionable recommendations
- Cross-platform comparative analysis distinguishing shared failures from cohort-specific issues
- Stakeholder presentations across 4 cross-functional teams:
  - **Product**: feature parity roadmap priorities
  - **Engineering**: critical bug prioritization (SSL, email forwarding, nameserver editing)
  - **Customer Success**: support strategy and staff training recommendations
  - **Executive leadership**: business impact and retention risk assessment

The research directly influenced the **Q4 2024 and Q1 2025 product roadmap** and established the foundation for an ongoing migration quality monitoring program.

---

## 6. Recommendations and Next Steps

Top 8 improvement areas delivered:

1. **Service quality restoration** — prioritize SSL, email forwarding, and nameserver editing; these are table-stakes features for both cohorts
2. **Feature parity recovery** — publish a public roadmap of Platform A and Platform B features and their unified platform equivalents or alternatives
3. **Communication and change management** — establish a migration communication protocol: advance notice, documented changes, proactive outreach before go-live
4. **Data integrity protocols** — conduct a full audit of the email loss incident; create a recovery and compensation framework; prevent recurrence through pre-migration validation
5. **Usability improvements** — address feature discoverability for both cohorts; "the feature works, they just can't find it" is a solvable problem
6. **Legacy service commitments** — establish a formal sunset process for features with active users before deactivation; the email forwarding reversal was too late
7. **Customer retention programs** — prioritize long-tenured high-value accounts (10+ years, multi-domain managers) for proactive outreach and retention offers
8. **Migration quality monitoring** — implement systematic feedback capture at each future migration milestone, not only after customers have churned

Follow-up research recommended:
- Longitudinal tracking of the 79 customers who named their legacy platform to measure retention rate at 6 and 12 months post-migration

---

## 7. Reflection

**What worked:** The cross-platform comparative framework was the right structural decision. Analyzing Platform A and Platform B separately before comparing them revealed that the top three pain points were shared — which shifted the framing from "which platform had a worse migration?" to "what did the migration process do to both cohorts simultaneously?" That reframing was more actionable for the product team.

The live interviews were disproportionately valuable relative to their sample size (8). The three detailed stories — the domain pricing calculator, the 10-hour domain transfer, the lost customer despite a rollback — made the retention risk concrete for executive stakeholders in a way that frequency tables couldn't.

**Challenges:** Four weeks was tight for 999 responses across three data streams. The volume required systematic coding rather than immersive reading, which created a risk of missing nuanced signals in the tail of open-ended responses.

**What I'd do differently:** Establish a real-time feedback mechanism before migration begins — not just a post-migration survey. The 90,000 email incident and the email forwarding deactivation both caused churn before anyone on the product team knew they were happening. A pre-migration feature inventory, cross-referenced with active usage data, would have flagged both as high-risk before go-live.
