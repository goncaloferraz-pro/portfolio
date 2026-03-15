---
title: "UX Leadership on a Global Cochlear Implant Community Platform"
year: 2026
domain: Hearing Health / Social Platform
duration: Ongoing (March–May 2026 initial engagement)
primary_role: Senior UX Lead
secondary_roles:
  - UX Designer
  - UX Researcher
  - Information Architect
methods:
  - RBAC audit (code extraction + UX translation)
  - Connections page redesign
  - User task mapping by role
  - HTML prototype delivery
  - UX backlog prioritization from user feedback
  - Triangulation research design
impact: "RBAC-to-UX translation delivered for 7 user roles; connections page redesigned with role-aware 3-carousel architecture; 28-item UX backlog produced; user task map for all 5 business roles; interactive HTML prototype delivered for client presentation"
---

# Cochlear Implant Community Platform — UX Leadership Across 7 User Roles

A global cochlear implant community platform connecting recipients, peer mentors, and clinicians across 45 countries had soft-launched but was struggling with bugs, unclear role permissions, and a connections experience that didn't match how users actually navigated the platform. The UX leadership role was handed off between consultants at the start of the engagement. This case documents the first phase: taking over UX leadership, auditing role-based access control (RBAC) from the codebase, designing the connections page, and delivering structured documentation for a major client review — all in the first three weeks.

*(Engagement ongoing as of March 2026.)*

---

## Stats

| Metric | Value |
|---|---|
| Countries on platform | 45 |
| User profiles (roles) | 7 (Candidate, Recipient, Caregiver, Peer Mentor, Professional Mentor, Area Manager, Super Admin) |
| UX backlog items produced (Nov 2025) | 28 |
| Connection tasks analyzed (RBAC cross-analysis) | 19 |
| Role-permission domains documented | 7 (Connections, Groups, Posts, Comments, Chat, Profile, Administration) |
| RBAC anomalies flagged for team review | 8 |

---

## 1. Context

The platform is a closed social network for cochlear implant recipients and their communities — a rare, niche audience where users include pre-implant candidates seeking peer information, post-implant recipients, caregivers, peer mentors, clinical professionals, regional coordinators, and administrators. The product is present in 45 countries; the manufacturer operates in 140.

The platform soft-launched on International Cochlear Implant Day (February 25, 2026). Within days, the German-speaking team refused to promote it until critical bugs were resolved. The US team was engaging with local users. Other regions were waiting.

**The structural challenge:** A 7-profile platform with complex role-based access logic, built by a development team using a Laravel backend and Nuxt frontend. The permission logic lived in the code — there was no documented UX-facing reference for which roles could do what, on which pages, under which conditions. This created a gap between what the platform was supposed to do (as designed) and what it actually allowed (as implemented).

**Three simultaneous tracks at handoff:**
1. Operational — bug triaging, weekly deliverables, critical task backlog
2. Strategic — platform strategy, Phase 2 feature roadmap, stakeholder alignment
3. Innsbruck preparation — connections page redesign and role documentation delivered within 2 weeks for a client presentation in Austria

---

## 2. My Role (analyzed from project log)

**Primary: Senior UX Lead**
Took over UX leadership from the previous lead; balanced operational bug triaging with strategic feature design and structured client deliverables across three parallel tracks simultaneously.

**Secondary roles:**
- **UX Designer**: Designed the connections page redesign — 3-carousel architecture (My Mentors / My Connections / Recommended), role-aware visibility per carousel, search mode that collapses carousels into a flat list, onboarding overlay, profile modal, and request inbox. Delivered as an interactive HTML prototype.
- **Information Architect**: Translated the RBAC codebase extraction into a UX-readable plain-language permissions document (7 sections, 5 business roles, 8 anomalies), a user tasks map for all roles, and a design cross-analysis for the connections page.
- **UX Researcher**: Extracted and structured the 28-item UX backlog from raw user feedback; contributed to triangulation research design (4-segment persona framework, 36-item survey blueprint for future execution).

---

## 3. Method

**RBAC code extraction — coordinated approach.**
Rather than documenting permissions from memory or user stories (which were aspirational and pre-implementation), I defined a structured extraction spec for the developer team. The spec requested three deliverables: a roles file, a permissions file, and a permissions matrix — both for the backend (Laravel) and frontend (Nuxt). The developer extracted these from the actual codebase. The result: a trustworthy ground-truth permissions model, not a design fiction.

**RBAC-to-UX translation.**
The code-level permission keys were translated into a plain-language document organized by platform section (not by code module). Each section lists which roles can perform which actions, making it reviewable by non-technical stakeholders. Eight anomalies were flagged — cases where the implemented behavior differed from the expected product spec or created confusing user experiences.

**Connections page redesign — evidence-driven.**
Six MED-EL-provided mockups were analyzed as a task analysis input, not as a design spec. I produced a written task list from the mockups, identified gaps (e.g., no mechanism for accept/decline/cancel on connection requests — connection management was outbound-only), and synthesized these with the RBAC cross-analysis before designing the prototype.

**Designer handoff structure.**
The prototype was accompanied by a written design brief, Figma Make prompts (two states: default 3-carousel and search-active flat-list), and a handoff ZIP containing all reference materials — so the visual designer could work independently without repeated clarification cycles.

**UX backlog production (Nov 2025 — prior engagement).**
The 28-item backlog was produced from raw user feedback provided by the platform operations team. Items were tagged by profile (which role is affected), severity (Critical → Lower), and bug type (Functional / UX Defect). The backlog was structured for direct use in a sprint planning tool.

---

## 4. Analysis and Insights

**Insight 1 — The platform had never documented what each role could actually do.**
The aspirational roles and journeys spec from November 2025 (pre-implementation) was being used as the reference document. It was not authoritative — the codebase had evolved. The gap between the written spec and the actual implementation was the root cause of multiple "bug" reports that were in fact undocumented design decisions.

**Insight 2 — The connections page had no connection lifecycle.**
The mockups designed by the platform team showed an outbound connection model: users could send requests, but there was no UI for receiving, accepting, declining, or cancelling requests. This created a one-sided experience — the person receiving a request had no visible mechanism to manage it. This gap was identified through task analysis of the mockups before any design work began.

**Insight 3 — Role labels in the UI did not match user mental models.**
The platform used the technical role name "MED-EL User" in the UI, where users expected "Recipient." Similarly, role badges created confusion about who a "Member" was relative to a "Recipient" or "Caregiver." Relabeling was one of the 28 backlog items and also one of the 8 RBAC anomalies.

**Insight 4 — The Global Group had been implemented incorrectly.**
The Global Group was intended for users in countries without a regional Area Manager (e.g., Uganda). The implementation had incorrectly migrated existing members into the Global Group, and the auto-join logic was not per-group or per-role as specified. The group's 404 error behavior also created a question visibility UX problem that had been open since launch.

**Insight 5 — Candidate experience was effectively a dead end.**
Candidates (pre-implant users) had the most restricted access profile: they could register and send questions to groups. But there was no clear path from "received an answer" to "joining the community as a full member." The onboarding journey for Candidates had no post-answer CTA.

**Insight 6 — Notification volume was creating disengagement.**
One of the critical backlog items documented user complaints about notification overload. The platform had no notification grouping, no mark-all-read, and no badge cap. For Mentors — who receive questions from multiple Candidates — this was creating email and in-app noise that worked against engagement.

---

## 5. Deliverables and Outcomes

**Deliverables produced (March 2026 — first 3 weeks):**
- `rbac-permissions-by-section.md` / `.html` — Plain-language RBAC document for client review; 7 sections, 5 business roles, 8 anomalies flagged
- `user-tasks-by-role.html` — Interactive role-by-task matrix; color-coded by role, checkboxes with persistence, open items table
- `connections-redesign-prototype.html` — Interactive HTML prototype; 3-carousel architecture; role switcher (4 roles); RBAC-aware carousel visibility; search → flat-list mode; profile modal; request inbox; onboarding overlay
- `connections-rbac-cross-analysis.md` / `.html` — Full task-to-RBAC cross-analysis; 5 UX recommendations (UX-R1–R5); 5 additional suggestions; 9 open questions; 23-item change summary
- `design-description.md` + `figma-make-prompt.md` — Designer handoff materials for Figma implementation
- `connections-redesign-for-figma.zip` — Complete handoff package
- `ux-suggestions.md` — Platform-wide improvements outside individual-page scope (notification grouping, role badge relabeling, FAQ visibility for Candidates)
- `index.html` — Branded deliverables index page (Cloudflare Pages entry point)

**Deliverables produced (Nov 2025 — prior engagement):**
- `backlog-from-user-feedback-hearpeers.md` / `.csv` — 28-item prioritized UX backlog

**Outcomes:**
- RBAC document provided the development and client teams with the first accurate, plain-language reference for platform permissions — replacing an aspirational spec that did not match the implemented system.
- The connections page prototype was the primary deliverable for the client presentation in Austria. It demonstrated role-aware UX design and gave the client team a concrete reference for the Figma implementation.
- Eight RBAC anomalies flagged — pending client decision on resolution approach.

*Longer-term outcomes not yet measurable — engagement ongoing.*

---

## 6. Recommendations and Next Steps

1. **Resolve the Global Group implementation before expanding to new regions** — the incorrect user migration and auto-join logic will compound as the platform grows.
2. **Implement connection lifecycle UI** — accept/decline/cancel for inbound requests; connection status badges on cards; this is a foundational gap in the current connections model.
3. **Relabel role names in the UI** — "MED-EL User" → "Recipient"; "Member" → clarified. Role labels in the UI should match what users call themselves, not what the codebase calls them.
4. **Build the Candidate exit ramp** — a post-answer CTA from "question answered" to "join as Recipient" is missing; without it, the pre-implant user segment has no onboarding path to full community membership.
5. **Triangulation research** — the 36-item survey blueprint and 4-segment persona framework are ready; executing this research would give the platform its first quantitative understanding of how each role uses (and doesn't use) the platform.

---

## 7. Reflection

**What worked well:**
- Coordinating the RBAC extraction through the developer team, rather than attempting to infer permissions from the UI, produced authoritative findings. The code is the source of truth; designing from it eliminated a category of ambiguity.
- Structuring the connections redesign as task analysis first (what tasks must each role complete?) before UI design (what components serve those tasks?) resulted in a design that surfaces the connection request inbox — a feature that the original mockups had not included.
- Delivering HTML prototypes with role-switching capability gave the client team an interactive reference that could be reviewed by non-designers without Figma access.

**Challenges and constraints:**
- Taking over a live engagement mid-stream meant inheriting in-progress decisions, technical debt, and team relationships without a structured handoff. The aspirational spec vs. implemented reality gap was the first thing that needed resolution — before any design work could be trusted.
- The operational track (bugs, weekly meetings) ran in parallel with the strategic and deliverable tracks. Triaging which bug reports were actual bugs vs. undocumented behavior required RBAC knowledge that didn't exist in document form — which is why producing the RBAC reference was the first priority.
- The 9-day deadline for Innsbruck deliverables created compression on a task (connections page redesign) that ideally would have had user testing before delivery.

**What I'd do differently:**
- Request a structured handoff from the outgoing UX lead before taking over. The absence of a documented state-of-the-design at handoff cost time that could have been spent on design rather than archaeology.
- Propose a Candidate onboarding research study at the start of the engagement — this is the highest-risk user journey and the one with the least evidence base.

<!-- TODO: create assets/hearing-health-community-platform-ux-2026-03/ and add relevant visuals -->
