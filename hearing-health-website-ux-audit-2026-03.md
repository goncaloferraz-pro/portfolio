```yaml
title: "Six UX Findings That Turned a Brochure Website Into a Journey"
year: 2026
domain: Hearing Health / Consumer Website
duration: 5 days (engagement ongoing as of March 2026)
primary_role: Senior UX Auditor / Consultant
secondary_roles:
  - UX Researcher
  - Content Designer / UX Writer
methods:
  - Analytics review (ATP, bounce rate, exit rate per page)
  - UX heuristic evaluation (screenshot-based)
  - User flow analysis
  - Authentication cascade mapping
  - Slide deck specification
  - Meeting script writing
impact: "6 UX findings documented; authentication cascade across 3 domains mapped; 10-slide presentation deck produced; meeting script written for 25-minute client session; all findings hypothesis-framed for Austrian audience"
```

# Cochlear Implant Recipient Website — Six UX Findings That Revealed a Brochure Pretending to Be a Journey

A global medical device manufacturer's consumer website for cochlear implant recipients and candidates had a consistent problem across every page: users engaged with the content but left without a next step. Analytics showed high active time on page but equally high exit rates. The site acted as a brochure — informing users, but not guiding them. This engagement produced a structured 6-finding audit and a client-ready 10-slide presentation deck for a major stakeholder visit, delivered in 5 days.

*(Engagement ongoing as of March 2026.)*

---

## 1. Context

The website is the public-facing content and marketing platform for a cochlear implant manufacturer's recipient community program. It sits alongside a separate, gated social platform — but the public website and the community platform operate as disconnected products, with no designed path from one to the other.

**Key pages in scope:** Homepage, Hearing Stories editorial section, Connect with a Mentor page, and Hearing Journey section.

**Analytics data provided:** Average time on page, bounce rate, and exit rate per page, from the client's GDPR-compliant analytics platform.

**The brief from the client:** Analyze the four pages and propose UX improvements. Deliverable: a meeting presentation for the client stakeholders during a visit to Austria.

**Constraint:** No access to the live website — all review conducted from screenshots provided by the client team. Deliverable due in 5 days.

**Strategic context:** The website is one channel in a multi-product communication strategy — alongside the community platform, a professional content newsletter, and other tools. Its role is awareness and conversion into the community. The audit was framed around whether the website was successfully serving that role.

---

## 2. My Role (analyzed from project log)

**Primary: Senior UX Auditor / Consultant**
Conducted an analytics-driven UX audit from screenshots; identified a cross-platform authentication cascade that was invisible in any individual analytics report; structured findings as testable hypotheses rather than prescriptions, calibrated for an Austrian/German/Brazilian stakeholder audience.

**Secondary roles:**
- **UX Researcher**: Interpreted per-page behavioral patterns from analytics data; identified the relationship between engagement metrics and the absence of post-engagement guidance.
- **Content Designer / UX Writer**: Wrote the meeting script (hypothesis-framing, data walkthrough, slide transition cues, 3 strategic questions) and slide specifications for the presenter to deliver in Austria.

---

## 3. Method

**Analytics review — per-page behavioral pattern analysis.**
Analytics data provided for 4 pages: average time on page, bounce rate, exit rate. The pattern across all pages was consistent: users stayed and engaged (above-average ATP on Hearing Stories), then exited. High exit rate did not correlate with low engagement — it correlated with the absence of a guided next step.

**Screenshot-based heuristic evaluation.**
12 screenshots reviewed: 4 full-page views, 4 navigation menu states, and 4 flow diagrams (auth cascade, button behavior). Evaluation focused on journey continuity, friction points, navigation clarity, and cross-platform handoffs.

**User flow reconstruction.**
The "Join the Community" button in the navigation was analyzed from multiple screenshots. The button triggered a dropdown menu (not a direct link) — revealing three paths: a dead link, a community login page on a subdomain, and a marketing landing page. Each path led to a different domain. The community login then triggered authentication on a third domain (the manufacturer's global auth system). Mapping this revealed a 3-domain authentication cascade invisible from any single-page analytics view.

**Meeting script and presentation spec.**
A ~25-minute meeting script was written for the presenter — not a slide outline, but a presenter guide with hypothesis framing, data walkthrough narration, slide transition cues, and speaker notes. The tone was calibrated: light but direct, suitable for an Austrian/German/Brazilian stakeholder mix. The 11-slide deck was specified frame by frame (layout type, headline, body copy, screenshot reference, Figma implementation notes, speaker notes).

**Iteration:** The completed deck was reviewed twice — v1 flagged two missing screenshots (Mentor page and Join button annotation); v2 resolved both. Deck approved before submission.

---

## 4. Analysis and Insights

**Finding 01 — Homepage routes users away from content, not into it.**
Analytics: low ATP, high exit. The homepage functions as a routing layer — it points users toward other pages — but does not itself demonstrate the value of the content. Users who land on the homepage leave without a compelling reason to explore. The page does not surface any of the editorial content that performs well deeper in the site.

**Finding 02 — Hearing Stories ends in a dead end.**
Analytics: highest ATP in the dataset. Users spend significant time reading stories — the content is effective. But there is no post-read guidance: no suggested next story, no CTA to connect with the author, no path to the community platform. The highest-engagement page has no exit strategy beyond leaving the site. *Recommendation: Stories as a community funnel — after reading a story, offer "Connect with [author] on the community" or "Join the group this story came from."*

**Finding 03 — Mentor page creates decision paralysis at the commitment point.**
The "Connect with a Mentor" page lists mentors in a grid — often dozens of options — without filters or guidance on how to choose. Users who want peer support face a decision architecture that asks them to make a commitment (selecting a person to contact) before they have enough information to make that decision. The CTA and form complexity compound the friction.

**Finding 04 — Hearing Journey's load time is its only UX problem.**
Analytics: above-average bounce on first visit. The content itself tests well when users reach it. The load time is the measurable friction point — not the information architecture or content structure. This is a technical finding, not a UX redesign opportunity.

**Finding 05 — The "Join the Community" button is secretly a menu.**
The primary navigation CTA — labeled "Join The Community" and styled as a button — triggers a dropdown with three items rather than navigating directly. This violates basic navigation conventions: buttons navigate; menus reveal options. Users who click expecting to join encounter a choice they did not expect. One of the three dropdown items was a dead link at the time of audit.

**Finding 06 — Three-domain authentication cascade breaks community conversion.**
Mapping the full join-community flow revealed: website (domain A) → community platform subdomain (domain B, login page) → manufacturer global authentication system (domain C, opens new browser window or tab). Three domains, two redirects, one new window — before a user can register. This is not a friction point in the traditional sense; it is a structural break in the journey that would not appear in any single-page analytics report.

**Cross-page pattern:**
> Every page shows the same signature: users arrive and engage, but leave without a guided next step. The website acts as a brochure, not a journey.

---

## 5. Deliverables and Outcomes

**Deliverables produced:**
- `website-audit.md` — 6-finding written audit; hypothesis-framed, direct tone
- `meeting-script.md` — ~25-minute presenter guide for Austria stakeholder meeting; includes slide transition cues, hypothesis framing, data walkthrough narration, speaker notes for three strategic questions
- `slide-deck-spec.md` — 11-slide deck specification; layout type, headline, body copy, screenshot reference, Figma implementation notes, and speaker notes per slide
- `HearPeers_Website_A_UX_Perspective.pptx` / `.pdf` — Completed 10-slide presentation deck; sent to presenter for Austria review

**Outcomes:**
- Deck approved and used in the Austria client presentation.
- Authentication cascade (Finding 06) was a previously undocumented user experience failure — mapping it across three domains provided the client team with a structural problem that single-page analytics could not surface.
- Hearing Stories funnel recommendation (Finding 02) identified the site's highest-performing page as an unconverted conversion opportunity.

*Longer-term product changes not yet confirmed — engagement ongoing.*

---

## 6. Recommendations and Next Steps

1. **Hearing Stories → community funnel**: After each story, offer a direct path to connect with the author on the community platform, or join the most relevant community group. The story section is the site's highest-engagement asset — it should convert.
2. **Reduce authentication cascade to one domain**: The 3-domain join flow is the single biggest structural barrier to community growth. Simplifying or eliminating cross-domain redirects would remove the join friction that no engagement optimization can fix.
3. **Replace the "Join" dropdown with a direct link**: A navigation button labeled "Join" should navigate. If multiple paths are genuinely needed, make them visible — not hidden in a dropdown that violates the affordance.
4. **Add Mentor page filters and progressive commitment**: Allow users to filter mentors by language, experience type, and geography before showing a contact form. The commitment ask should come after enough information to make the choice, not before.
5. **Homepage as content preview**: Surface 2–3 recent Hearing Stories on the homepage. If the content is the value proposition, let users encounter it immediately — don't route them away to find it.

**Next steps:**
- Matomo analytics access to confirm behavioral hypotheses with session data and funnel tracking
- User interviews with recipients and candidates to validate the "dead end" experience at Hearing Stories
- Technical investigation of the authentication cascade — whether a single-sign-on or domain consolidation is feasible

---

## 7. Reflection

**What worked well:**
- Framing findings as hypotheses rather than prescriptions. The meeting script was written as "here is what the data shows; here is what we think it means; here are three questions that would confirm or challenge it." This is a more honest and more productive framing for a stakeholder meeting than "here are our recommendations."
- Finding 06 (authentication cascade) required mapping the full user journey across screenshots — it was not visible in any single analytics metric and would not have surfaced in a page-by-page review. The finding emerged from asking "what happens if I actually try to join?" rather than "what does the analytics show?"

**Challenges and constraints:**
- No live website access — all review conducted from screenshots. This limits the audit's ability to discover interaction-state failures (e.g., hover states, form validation, mobile behavior) that screenshots cannot capture.
- 5-day delivery window for audit, script, deck spec, and deck review. The prioritization was correct (find the most important structural issues, not catalog everything), but some findings may have been missed under time pressure.

**What I'd do differently:**
- Request live website access even for a screenshot-first audit. Screenshots miss dynamic states, responsive behavior, and real authentication flows. The 3-domain cascade was identifiable from screenshots, but it could have been mapped more precisely with live access.
- Add a fourth strategic question: "What does success look like for the community conversion rate — and is this website currently set up to be measured against that goal?"

<!-- TODO: create assets/hearing-health-website-ux-audit-2026-03/ and add relevant visuals -->
