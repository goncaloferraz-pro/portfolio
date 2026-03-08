# Digital Ecosystem Unification — State Bar Association

**Domain:** Legal / Professional Association
**Type:** Enterprise IA & UX Strategy
**Year:** 2025
**Role:** Senior UX Researcher & Information Architect

---

| | |
|---|---|
| **70+** subdomains audited | **7** isolated auth systems eliminated |
| **43** critical tasks mapped | **12** heuristic violations documented |
| **6.2/10** baseline usability score | **3** access layers designed |
| **50+** regional offices standardized | **40%** projected support cost reduction |

---

A state bar association serving **50,000+ legal professionals** operated a fragmented network of portals, each with its own login, navigation logic, and visual language. Attorneys managing routine professional obligations — renewing licenses, tracking continuing education, accessing benefits — were forced to context-switch across disconnected systems daily. The organization wanted a unified platform. The problem was they didn't know what that should actually mean.

## What I did

I led a triangulated research engagement combining systems audit, qualitative interviews, and stakeholder prioritization workshops.

The **systems audit** mapped all 70+ digital properties, documenting a service inventory of **43 critical tasks** and running a formal heuristic evaluation against Nielsen's 10 principles. The result: **12 critical violations**, an overall usability score of **6.2/10**, and navigation structured entirely around the organization's internal departments — not around what attorneys needed to accomplish.

**Qualitative interviews** surfaced three distinct attorney archetypes with fundamentally incompatible needs: corporate practitioners who needed deep integration with external tools; general practice attorneys who used the portal sporadically and couldn't find anything; and court-appointed attorneys with high portal dependency, working primarily on mobile, who needed proactive notifications rather than a portal they had to remember to check.

**Stakeholder workshops** used weighted scoring to classify all 43 services by business impact and usage frequency, producing the definitive service hierarchy and MVP roadmap. This step was critical — without it, every department believed their services were the priority.

![Service classification workshop — Venn diagram mapping services by audience (members-only, public, shared) with weighted prioritization grid](assets/legal-portal-ecosystem-workshop-board.png)

## What we found

The core problem wasn't fragmentation of systems. It was fragmentation of purpose. The homepage tried to serve everyone simultaneously: institutional news mixed with critical attorney tools, public transparency mixed with members-only services. No user group could efficiently complete their primary tasks.

The deeper insight: attorneys don't want to "visit the bar association website" — they want to resolve specific problems. The existing structure was organized around *who owns the service*, not *what the user is trying to do*.

![Three-layer architecture — public portal, transitional users, and attorney workspace](assets/legal-portal-ecosystem-architecture.jpg)

## What I designed

A **three-layer architecture** based on hypersegmentation — distinct environments for fundamentally different use cases, eliminating the conditional logic that made a single interface unworkable:

- **Layer 1 — Public Portal:** Institutional content, attorney directory, transparency. Open access, SEO-optimized, no login required.
- **Layer 2 — Transitional Users:** Bar exam candidates and non-practicing members. Self-service onboarding flows to reduce inbound support volume.
- **Layer 3 — Attorney Workspace:** The paradigm shift. Upon login, attorneys see a task-oriented dashboard integrating continuing education, benefits, pension, financial management, and electronic filing — all from one place, one login, one search bar. Navigation restructured from department-centric (*Treasurer's Office*) to task-centric (*My Finances*).

![Attorney workspace information architecture — full service map for Layer 3](assets/legal-portal-ecosystem-attorney-ia.jpg)

The same architecture produced a **standardized template** for the association's **50+ regional offices**, which had been operating completely independent websites with no consistency.

## What changed

The research reframed the project from a redesign into an organizational change argument. The three-layer structure reduced system complexity by eliminating the need for progressive disclosure across a single interface — counterintuitively, more environments meant simpler experiences. SSO consolidation projected to eliminate **7 separate login systems**. Self-service improvements projected to reduce Level 1 support inquiries by **40%**. Standard administrative tasks running at **10–20 days** completion time were re-architected to **48 hours**.
