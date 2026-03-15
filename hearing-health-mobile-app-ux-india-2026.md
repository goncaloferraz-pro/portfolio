```yaml
title: "Scoping a Dual-Product UX Engagement After Vendor Failure"
year: 2026
domain: Hearing Health / Mobile App / Healthcare Professional Platform
duration: Discovery and scoping phase (March 2026; UX/UI design phase ongoing)
primary_role: Senior UX Lead
secondary_roles:
  - Business Analyst
  - Research Ops
methods:
  - Legacy artifact evaluation (PRD, wireframes, vendor videos)
  - Briefing meeting synthesis
  - Dual-product UX scoping
  - Effort estimation
  - GitHub project structure definition
  - Authentication cost research
impact: "131-hour UX estimate across two products; 44 GitHub issues created from estimate; legacy PRD critically evaluated and selectively adopted; OTP authentication cost research redirected toward WhatsApp Auth; dual-product UX scope defined in 48 hours"
```

# Hearing Health Professional Community App (India) — Restarting a Failed Vendor Engagement

A global medical electronics manufacturer needed a closed mobile community platform for hearing health professionals in India — ENT surgeons, audiologists, and related specialists. A previous vendor had been contracted for over a year and delivered nothing functional. The project was restarted from scratch with a new team, a 3-week design timeline, and a hard deadline tied to a national medical conference. This case documents the discovery and scoping phase: evaluating legacy artifacts critically, defining the UX scope for two simultaneous products, and establishing the project infrastructure — all within 48 hours of the first briefing.

*(Engagement ongoing as of March 2026. UX/UI design phase begins March 16.)*

---

## 1. Context

**The product:** A closed, invite-only community platform for medical professionals in the hearing domain operating in India. Organized around "Circles" — closed groups led by senior Key Opinion Leaders (KOLs). Designed to educate doctors about cochlear implant referral timing and foster professional knowledge sharing.

**Two simultaneous products in scope:**
1. **Mobile App (iOS + Android):** A social/professional feed app. Circle Leaders (senior ENT surgeons) create and moderate content; Circle Members (residents, audiologists) consume and react. Invite-only. OTP login. No password.
2. **Admin Panel (Web Desktop):** Internal management platform for the manufacturer's team — user management, content, roles, notifications, analytics.

**The business context:** Indian cochlear implant clinics often have institutional rivalries. This is why the product was designed as a closed "circles" model — no cross-circle interaction in v1. The app is exclusive to professionals; patients have a separate product.

**The deadline:** A functional MVP was required by end of May 2026 for testing ahead of a national audiology conference in September 2026. The conference in Agra, India was the public launch target. This was a hard deadline — the conference had already been selected.

**Why the vendor failed:** The previous Indian vendor worked for over a year and delivered nothing functional. Their legacy artifacts (PRD, wireframes, videos of partially built app) were handed over as the only starting point for the new engagement.

**Strategic importance:** The project was the manufacturer's first direct collaboration with a Brazilian technology team — strategically significant for establishing the agency's international credibility.

---

## 2. My Role (analyzed from project log)

**Primary: Senior UX Lead**
Scoped a dual-product UX engagement from scratch after vendor failure; defined information architecture deliverables, flows, and testing plan under a 3-week design constraint; led legacy artifact evaluation and restructured the project for a new team.

**Secondary roles:**
- **Business Analyst**: Translated the vendor PRD, briefing notes, client emails, and KOL keynote into a structured UX requirements and effort estimate; identified which legacy decisions were valid and which should be discarded.
- **Research Ops**: Defined a 44-issue GitHub project structure from the UX estimate; scoped the usability testing plan (6 mobile sessions + 3 admin sessions); organized issues with 8 labels for cross-team tracking.

---

## 3. Method

**Legacy artifact evaluation — critical, not deferential.**
The starting point was not a blank brief but a failed engagement: an 18-month vendor PRD, four wireframe screenshots, three screen-recording videos (Circle Lead flow, Circle Member flow, Admin Panel), and a KOL onboarding keynote from a previous conference. These were evaluated critically — extracting what was architecturally sound, identifying what reflected poor design, and flagging what was simply unimplemented.

**Briefing meeting synthesis.**
Two meetings on the same day: a morning session with the manufacturer's India team and European stakeholders, and an afternoon internal alignment session with the delivery team. Notes from both were structured into a single source of truth — distinguishing what the client had decided vs. what was still open, and what scope had been confirmed vs. what was aspirational.

**Effort estimation as UX scoping tool.**
The first deliverable was a UX effort estimate — not as a billing document but as a scope definition exercise. Identifying every user flow, IA deliverable, writing task, audit task, and testing plan in quantifiable hours made explicit what would and would not be designed in 3 weeks. The estimate (131h total: 79h mobile, 52h admin) became the project's UX scope document.

**Authentication cost research.**
The original PRD specified SMS OTP for login. Research into the Indian telecom market revealed that SMS OTP is 18–50× more expensive per unit than WhatsApp Auth (₹0.15–0.40 vs. ₹0.11–0.12). For a platform targeting medical professionals in India — where WhatsApp is ubiquitous across professional networks — WhatsApp Auth was identified as the better default.

**GitHub project structure.**
44 issues were created from the UX effort estimate and organized into a GitHub Project. Eight labels were defined: mobile-app, admin-panel, analysis, information-architecture, user-flows, ux-writing, usability-testing, handoff. This gave the delivery team a trackable UX backlog from day one.

---

## 4. Analysis and Insights

**Insight 1 — The circles model is a UX response to real-world political dynamics.**
The decision to isolate circles from each other (no cross-circle interaction in v1) is not a technical constraint — it is a deliberate social architecture decision. Clinics in India have institutional rivalries. If doctors from competing institutions could see each other's activity, trust would break down before it formed. The closed circle model makes the politics invisible and safe by design. Every UX decision about what to show, to whom, in which context, flows from this constraint.

**Insight 2 — The previous vendor built for the PRD, not for the user.**
Reviewing the vendor's screen recordings revealed a technically correct but behaviorally misaligned product. Flows were implemented as specified, but the sign-up form asked medical professionals for 12+ fields before they could enter the app. The logic was defensible from a data-collection standpoint; the experience was not defensible from an adoption standpoint. KOLs — senior ENT surgeons with high status and low time — would simply not complete it.

**Insight 3 — "Surgeon who referred me" is a better membership identifier than ID number.**
The original PRD used a membership ID field to assign new members to circles. A KOL-referral model is more natural: a Circle Member knows who their KOL is (the surgeon who trained them or referred them), not what their membership ID number is. This change was identified in the briefing and logged as a UX decision before design began.

**Insight 4 — Post-moderation is more appropriate than pre-moderation for KOL-led groups.**
Pre-moderation (admin reviews content before it appears) reduces trust in KOL authorship — it implies the KOL's content is being filtered. Post-moderation (content appears immediately; admin can remove retroactively) is more appropriate for a community structured around senior professional authority. This was a product decision made in the briefing and recorded as a UX rationale.

**Insight 5 — The admin panel is a different UX problem from the mobile app.**
The briefing treated both as one project. The UX effort estimate separated them explicitly: 79h mobile, 52h admin. The mobile app is a consumer-grade professional experience requiring smooth, trust-building flows for high-status users. The admin panel is an internal operational tool for the manufacturer's local team — requiring efficiency, oversight, and error prevention. Designing both under the same UX logic would have produced a misaligned product for at least one of them.

---

## 5. Deliverables and Outcomes

**Deliverables produced (March 5–7, 2026):**
- `ux-effort-estimate-en.md` / `ux-effort-estimate-pt.md` — Dual-language UX effort estimate (English for client, Portuguese for internal team); itemized by flow, task type, and product; 131h total
- 44 GitHub Issues — Created from the UX estimate and organized in the GitHub Project with 8 labels for cross-team tracking
- `auth-cost-sms-vs-email.md` — Authentication cost research; SMS vs. WhatsApp Auth cost comparison for India; recommendation to use WhatsApp Auth as default

**Outcomes:**
- UX scope defined and agreed within 48 hours of the first briefing.
- Legacy PRD analyzed and selectively adopted — saving the team from building on a flawed foundation without discarding all prior work.
- WhatsApp Auth recommendation flagged before development architecture was set — avoiding a higher-cost authentication infrastructure.
- Project infrastructure (GitHub Issues, labels, Project) established for cross-team UX tracking before design began.

*Design deliverables (flows, IA, Figma wireframes, usability test plan) pending — engagement ongoing.*

---

## 6. Recommendations and Next Steps

1. **Prototype the KOL onboarding flow before any Circle Member flow** — KOL adoption is the network's dependency. If Circle Leaders don't use the app, Circle Members have no content. The KOL experience must be simple, high-status, and resistant to abandonment.
2. **Test the "surgeon who referred me" field in the registration flow** — this is a UX hypothesis; it needs validation with a small group of Indian medical professionals before the full build.
3. **Confirm App Store / Play Store medical content policy before design is finalized** — health content in professional-facing apps is subject to review flags. Clarify what content classification the app falls under before investing in content design.
4. **Establish the "Air Manager" role scope before v1 design is finalized** — an intermediate role between Circle Leader and Super Admin was proposed in the briefing. If it is in v1 scope, the IA changes significantly. If deferred, the decision should be documented.
5. **User access for usability testing** — the 6-session mobile usability test plan requires access to Indian medical professionals. Confirm with the manufacturer's India team whether real KOLs and residents can participate in testing before the MVP deadline.

---

## 7. Reflection

**What worked well:**
- Treating the effort estimate as the scope definition document — not as a billing tool — made the 3-week design constraint explicit and negotiable before work began. Every item out of scope was a conscious decision, not a gap.
- Critical evaluation of the legacy vendor artifacts prevented the team from treating a failed product as a reliable reference. The vendor PRD was useful as a catalog of features; it was not useful as a design guide.
- Separating mobile and admin panel in the estimate forced clarity about what each product was for — before both were handed to the same team as if they were interchangeable.

**Challenges and constraints:**
- The previous vendor's failure created a political environment where both the client and the new team had to manage trust carefully. The legacy artifacts were useful for understanding scope, but they also carried the shadow of a failed engagement — which required conscious effort to prevent anchoring.
- No Indian medical professional users were available for research at the scoping stage. The UX decisions about KOL experience (invite model, "surgeon who referred me" field, OTP simplicity) are informed by the briefing and by general knowledge of professional app design — not by user research. This is a known risk that the usability testing plan was designed to address.
- The 3-week design timeline for a dual-product with 7 user flows per product is aggressive. The effort estimate made this visible; whether the timeline adjusts is a client decision.

**What I'd do differently:**
- Propose a 2-day immersive research session with 3–4 Indian ENT surgeons before the design phase begins — even remote interviews would validate the most critical UX hypotheses (KOL onboarding, content formats, engagement patterns) before they are built into Figma flows.

<!-- TODO: create assets/hearing-health-mobile-app-ux-india-2026/ and add relevant visuals -->
