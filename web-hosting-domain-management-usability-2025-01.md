---
title: "Domain Management Usability Study — Enterprise Web Hosting Platform"
year: 2025
domain: Web Hosting / Enterprise SaaS
duration: 2 weeks (January 2025)
primary_role: Senior UX Researcher
secondary_roles:
  - Research Ops
methods:
  - Moderated remote usability testing
  - Think-aloud protocol
  - Iterative two-round testing
  - Video highlight reel
impact: 7 critical usability issues caught and resolved before development; all 5 priority design changes implemented pre-sprint
---

# Enterprise Web Hosting — Catching Domain Flow Failures Before They Reached Production

An enterprise web hosting platform was redesigning its domain management experience — the flows users follow to purchase a domain or connect one they already own. I planned and led a **two-round moderated remote usability study** that caught **7 critical issues** before a single line of production code was written, and validated their fixes before the development sprint began.

| | |
|---|---|
| **15 participants** across 2 rounds (8 + 7) | **7 critical usability issues** identified in Round 1 |
| **5 task scenarios** covering the full domain management journey | All **5 priority design changes** implemented before development |
| Core step-by-step workflow **validated as intuitive** | Video highlight reel produced for stakeholder presentations |

---

## 1. Context

An enterprise web hosting platform was rebuilding its domain management flows — the paths users take to purchase a new domain or connect one they already own from a third-party registrar. Domain management is a primary acquisition and retention driver for the platform: the ability to purchase and configure domains drives new customer sign-ups, and ongoing domain management is one of the most frequent reasons customers log in.

Confusing terminology or hidden entry points translate directly into abandonment, failed purchases, and support tickets. The team was working from Figma prototypes and needed to know whether the flows worked before handing them to engineering.

---

## 2. My Role

**Primary: Senior UX Researcher**
I developed the test plan, designed the 5 task scenarios, conducted all moderated sessions across both rounds, synthesized findings, and delivered prioritized design recommendations between rounds.

**Secondary roles:**
- **Research Ops**: Produced a condensed video highlight reel of key pain points for stakeholder presentations, allowing product and engineering leadership to see failures rather than only read about them.

---

## 3. Method

**Study design:** Two-round moderated remote usability study using Figma prototypes, conducted through a remote testing platform. Think-aloud protocol to capture mental models alongside task performance.

**5 task scenarios covering the full domain management journey:**
1. Discovering the entry point for domain management
2. Purchasing a new domain
3. Connecting a domain already owned at another registrar
4. Handling an edge case in the connection flow
5. Confirming the action was completed successfully

**Round 1 — 8 participants**
Domain purchasers and website owners with varied technical backgrounds. Goal: identify critical issues in the current prototype.

After Round 1: synthesized findings, delivered prioritized design recommendations to the product team, waited for prototype revisions.

**Round 2 — 7 fresh participants**
Same profile as Round 1. Goal: validate that Round 1 fixes held and surface any issues introduced by the revisions.

**Highlight reel:** Produced a condensed video of key observed pain points for stakeholder presentations.

---

## 4. Analysis and Insights

**Finding 1 — "Connect" and "purchase" were perceived as opposite actions by most participants.**
Users attempting to buy a domain consistently failed to recognize the entry point because the interface used the word "connect" — which they associated with linking a domain they already owned, not with a purchase flow. This terminology mismatch was the most pervasive issue and persisted through multiple scenarios.

**Finding 2 — The "I own this domain" button was styled to look like an error.**
Positioned far from the domain name it related to and styled in red (triggering a warning perception), the button was missed entirely by two participants and caused three to hesitate before clicking. The visual design communicated "danger" at a moment requiring confident action.

**Finding 3 — Confirmation language was ambiguous regardless of what the user had done.**
The system confirmed "domain added" whether a domain had been purchased or connected. Participants in both scenarios saw the same message — eliminating the feedback that would have told them whether the correct action had been taken.

**Finding 4 — The step-by-step flow structure was consistently praised.**
Once users found the correct entry point, every participant found the progression clean, uncluttered, and easy to complete. The issue was not the flow itself — it was finding the way in. This was a significant positive finding: the core product work was sound, and the problems were addressable without redesigning the flow.

**Finding 5 — Round 2 confirmed the entry point terminology had not been fully resolved.**
Despite iterations between rounds, participants continued navigating through quick links, website buttons, and left-hand navigation searching for "purchase" or "buy" language. The language fix had been applied in some places but not consistently — which was itself a finding about where in the interface the language mattered most.

---

## 5. Deliverables and Outcomes

- Round 1 findings report with 7 critical issues, observed behaviors, and prioritized design recommendations
- Round 2 validation report confirming fixes and residual issues
- Video highlight reel of key pain points for stakeholder presentations

**5 priority design changes implemented before development:**
1. "Purchase" and "buy" language added prominently throughout all entry points
2. "I own this domain" button visually redesigned and repositioned adjacent to the domain name it relates to
3. Next Steps section moved above the fold on all viewport sizes
4. Confirmation messages updated to distinguish "purchased" from "connected" explicitly
5. Pricing transparency improved — total costs surfaced earlier in the purchase flow

**Impact:** Preventing 7 critical issues from reaching production reduced post-launch support risk and rework. The two-round approach confirmed which fixes held (the button redesign, the confirmation language) and revealed which required further iteration (consistent entry-point language across all surfaces).

---

## 6. Recommendations and Next Steps

Top recommendations delivered:

1. **Establish a single, consistent label for domain purchase across all entry points** — "connect" can only mean "link an existing domain"; "buy" or "purchase" must appear wherever a new domain can be obtained
2. **Redesign warning-colored elements at action points** — red styling signals errors or danger; action buttons should not inherit this treatment
3. **Differentiate confirmation language by action type** — "domain purchased" and "domain connected" are different states requiring different messages
4. **Surface pricing earlier in the purchase flow** — users want to know the cost before they commit to a path, not at the final step
5. **Audit the full domain management surface for language consistency** — the terminology gaps found in testing were not isolated to one screen; a systematic language audit across all domain-related flows would prevent recurrence

Follow-up research recommended:
- Post-launch behavioral analysis: drop-off rates at the entry point and at the confirmation step, to validate whether the fixes hold under real traffic
- Return visit study: do users who completed setup return to manage their domains confidently, or do they still require support?

---

## 7. Reflection

**What worked:** The two-round structure was essential for this type of study. Round 1 identified the critical structural issues (terminology, button design, confirmation language); Round 2 validated that the fixes for some issues held while surfacing the more nuanced inconsistency in entry-point language across the full interface. Without Round 2, the team would have shipped a partially fixed product under the impression it was fully resolved.

The video highlight reel was a highly effective stakeholder communication tool. The "I own this domain" button hesitation, recorded across three separate participants with visible cursor movements and audible uncertainty, was more convincing to engineering and product leadership than any written finding.

**Challenges:** The prototype scope for both rounds covered the primary flows but not all edge cases in the connection flow. Several participants expressed uncertainty about what would happen if they entered a domain they didn't own — a scenario the prototype didn't handle. This left an untested risk for the launch.

**What I'd do differently:** Map all error and edge-case states before testing and confirm with the design team which should be prototyped. The primary happy-path flows were well covered; error handling (domain unavailable, connection failed, third-party authentication required) deserved at least one scenario in Round 2. Edge cases in domain management are common — users frequently make typos, test ownership of domains they're considering buying, or encounter authentication failures — and they represent a significant support driver.
