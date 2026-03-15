```yaml
title: "E-Commerce Store Setup Usability Testing — Web Hosting Platform"
year: 2022
domain: Web Hosting / SaaS
duration: 2 weeks (July 2022)
primary_role: Senior UX Researcher
secondary_roles:
  - Research Ops
methods:
  - Unmoderated remote usability testing
  - Prototype evaluation
  - Severity rating
  - Iterative testing (two-round)
impact: 7 prototype issues resolved before development began; 100% task completion validated on revised flow
```

# Web Hosting Platform — Testing an E-Commerce Onboarding Flow Before It Went Live

An enterprise web services platform was launching a new e-commerce package. Before release, I ran a **two-round iterative usability study** to test whether new customers could set up an online store without guidance — and to fix what was blocking them before any development began.

| | |
|---|---|
| **2 rounds** of unmoderated testing with prototype iteration between | **4 core tasks** covering the full store setup flow |
| **100%** task completion rate in Round 2 | **Average completion time: 3 minutes** |
| Publish button identified as primary friction point | **7 prototype issues** resolved before development began |

---

## 1. Context

An enterprise web services platform was adding an e-commerce hosting package to its product lineup. New customers who purchased the package would need to set up an online store — entering their store address, configuring payment methods, adding products, and publishing — without guided support.

The platform's existing onboarding flows served a range of user types, but this was the first e-commerce–specific flow. The stakes: if customers couldn't complete setup without help, it would mean support load, frustration, and early churn from a brand new product line. The team needed to know whether the flow worked before engineering built it.

---

## 2. My Role

**Primary: Senior UX Researcher**
I planned and ran the full two-round study, synthesized findings from pilot sessions, worked with the design team to prioritize and implement fixes, and validated the revised prototype in Round 2.

**Secondary roles:**
- **Research Ops**: Developed the test plan and task scenarios, conducted severity ratings for all documented issues, and structured the Round 2 criteria to distinguish validation from re-discovery.

---

## 3. Method

**Study design:** Two-round iterative unmoderated remote usability study using Figma prototypes. Test scenario: participants were told they had just purchased an e-commerce hosting package and needed to set up a new online store.

**4 core task scenarios:**
1. Enter store address
2. Choose how to receive payments from customers
3. Add a new product to the store
4. Make the store public and open for business

**Round 1 (pilot) — 5 participants**
Senior managers, directors, and business owners in the US and Canada, aged 35–65+, household income $100K–$150K+. This profile matched the platform's target e-commerce customer segment. After analyzing session recordings, all issues were documented, severity-rated, and prioritized with the design team.

**7 prototype adjustments before Round 2:**
Viewport scaling, shipping info consistency, scroll position on the Tax Info page, site status flow behavior, and contextual content framing on plan pages.

**Round 2 (validation) — full unmoderated study**
Goal: confirm that the highest-priority issues were resolved and surface any new issues introduced by the fixes.

---

## 4. Analysis and Insights

**Finding 1 — All participants completed all tasks; the flow structure was sound.**
100% task completion and a 3-minute average completion time confirmed that the underlying sequence was logical, well-paced, and easy to navigate once core friction was removed. The problems were specific and fixable — not structural.

**Finding 2 — The Publish button was the primary friction point.**
Participants struggled to locate the button at the final step — the moment of making the store live. The issue was compounded by a missing website preview: participants expected to see what their store looked like before making it public. The flow offered no preview. Both problems pointed to the same underlying gap: users needed clearer signaling and more confidence at the moment of commitment.

**Finding 3 — Progress-tracking checkmarks were consistently and unpromptedly praised.**
Multiple participants volunteered positive comments about the visual confirmation of completed steps. The checkmark pattern reduced uncertainty about where they were in the process and what remained — an unprompted observation that validated the design pattern and identified it as a feature worth preserving.

**Finding 4 — Users wanted a clear distinction between required and optional steps.**
Participants wanted the system to differentiate "things you have to do to launch" from "things you might want to do later." The checklist model didn't yet make this distinction. This wasn't a blocking issue for task completion, but it surfaced as a future enhancement to reduce cognitive load during the critical setup phase.

---

## 5. Deliverables and Outcomes

- Round 1 findings report with 7 documented prototype issues, severity ratings, and fix recommendations
- Round 2 validation report confirming resolution of priority issues
- Test plan and task scenarios (reusable for future flows on the same platform)

**Prototype changes confirmed before development:**
1. Publish button: increased visibility and repositioned to the primary action area
2. Pre-publish preview: added store preview step before the Publish action
3. Viewport scaling: fixed across all devices in the prototype
4. Shipping info: consistent labeling across all references in the flow
5. Tax Info page: scroll position reset on entry
6. Site status flow: corrected to reflect accurate post-publication states
7. Plan pages: improved contextual framing for the specific e-commerce context

**Impact:** Preventing 7 critical issues from reaching production reduced the risk of post-launch support burden and stakeholder rework. Development began on a validated flow.

---

## 6. Recommendations and Next Steps

Top findings delivered:

1. **Publish button must be in the primary CTA position** with explicit "go live" language — at the moment of commitment, visual hierarchy and label must eliminate ambiguity
2. **Add a pre-publish preview step** — users will not confidently go live without seeing their store first
3. **Introduce required/optional task distinction** in the onboarding checklist — reduces anxiety about what happens if you skip something
4. **Preserve the progress-tracking checkmark pattern** — it was the most positively noted design element in both rounds; any changes to it should be treated with caution

Follow-up research recommended:
- Post-launch behavioral analysis of time-to-publish and step abandonment rates to validate whether Round 2 findings hold under real-traffic conditions
- Qualitative follow-up at 30 days post-setup to assess whether customers who completed setup felt confident managing their store independently

---

## 7. Reflection

**What worked:** The two-round iterative structure was the right approach for this type of study. Round 1 as a pilot (smaller, faster, diagnostic) and Round 2 as validation is more efficient than running a single large-scale study — it allows the prototype to be the thing being tested, not the participants' time. The 7 fixes between rounds meant Round 2 was genuinely testing a better product, not just generating more findings about the same problems.

The severity rating process was valuable for the team. Not all issues are equally urgent, and having a framework to distinguish "must fix before launch" from "should fix in the next sprint" made the handoff to the design team faster.

**Challenges:** Unmoderated testing captures behavior well but misses the reasoning. The Publish button issue was clear in recordings (participants hesitated, moved the cursor across the screen, looked at other elements), but understanding *why* participants expected a preview required inference from observation rather than direct explanation. A moderated session for at least the first round would have produced richer insight into the mental model driving the preview expectation.

**What I'd do differently:** Include at least one moderated session in Round 1, even if the majority of sessions are unmoderated. The volume advantage of unmoderated testing is significant, but for the critical steps in a flow (especially the final commitment step), hearing participants explain their expectations in real time produces different and more actionable insight than watching their cursor movements alone.
