---
title: "Discovery Briefing for a B2B Internet Banking Redesign"
year: 2026
domain: Financial Services / B2B Fintech
duration: February 2026 (discovery phase only)
primary_role: UX Consultant / Business Analyst
secondary_roles:
  - UX Designer (conceptual prototype scoping)
methods:
  - Discovery briefing (stakeholder meeting)
  - Business context analysis
  - Competitive landscape identification
  - UX scope definition
  - Conceptual prototype scoping
impact: "UX scope defined for conceptual prototype; personas scoped (Operator + Decision-Maker); 3 core flows identified; competitor set established; prototype to be presented to CEO"
---

# B2B Internet Banking — Discovery Briefing and UX Scope Definition

A digital financial institution offering corporate banking services to medium-sized businesses recognized that its internet banking platform had been built with a technology-first logic — functional, but low on usability. The engagement began with a discovery briefing to understand the product vision, user context, and competitive landscape, then defined the UX scope for a conceptual high-fidelity prototype to be presented to the company's CEO. This case documents the discovery phase only — the prototype was out of scope for this engagement.

---

## 1. Context

**The product:** A B2B digital banking platform primarily offering current accounts (conta de movimentação) for medium-sized businesses — their primary banking product for daily financial operations: deposits, payments, boleto management, PIX/TED transfers, and account statement management.

**The business problem:** The platform was developed with a technology focus. It worked — but users (finance department staff at medium-sized businesses) found it unintuitive and slow for routine tasks. This generated unnecessary support volume and reduced client retention confidence. The CEO framing: "We have a great opportunity to create an experience that builds client trust."

**The brief:** Create a conceptual high-fidelity prototype of the post-login internet banking experience for desktop, with a responsive design approach. The prototype would be presented directly to the company's CEO to unlock the full redesign project.

**Key constraint:** The prototype must convey four qualities — trust, security, efficiency, and agility — as a single experience. "The digital corporate wallet: simple, objective, and structured for your financial operations."

**Strategic context:** The company has 6 business units (banking, credit, collections/PIX/boleto, platform services, and two planned units — including an investment BU planned for 2028–2029). The prototype scope was intentionally narrow: the core banking experience only (account statement, boleto management, PIX/TED transfers).

---

## 2. My Role (analyzed from project log)

**Primary: UX Consultant / Business Analyst**
Participated in the discovery briefing; translated the B2B fintech product vision and business context into UX scope and design priorities for a conceptual prototype.

**Secondary roles:**
- **UX Designer (conceptual prototype scoping)**: Identified the three flows that must be designed (account statement/dashboard, boleto management, PIX/TED transfers) and the conceptual differentiator — a unified one-page/dashboard view as the "star" of the prototype.

---

## 3. Method

**Discovery briefing — structured stakeholder meeting.**
A 37-minute structured briefing with the product owner of the financial institution, facilitated by the agency team. The briefing covered: the primary business problem, success KPIs, ecosystem and brand identity, user personas, competitive landscape, UI references and what to avoid, and the conceptual prototype scope.

**Business context mapping.**
The briefing revealed a 6-BU product ecosystem. Understanding the broader context (even features out of scope for the prototype) informed the design constraints — specifically, that the prototype must feel like a focused, sober product, not a "super app." The product owner explicitly referenced a competitor whose approach of aggregating many services created confusion and should be avoided.

**Persona scoping — two users, one prototype.**
The briefing identified two personas: the Operator (finance department staff who spend hours in the platform daily — running transfers, emitting boletos, checking statements) and the Decision-Maker (the company's CEO, who would evaluate the prototype). The prototype must work as an experience for the Operator *and* as a demonstration for the CEO.

**Competitive landscape — 5 competitors identified.**
Five direct competitors named: QI Tech, BMP, CDC, Grafeno, Celcoin. Positive reference: the Account section of a specific retail bank (praised for objectivity and simplicity, not adopted as full reference). Negative reference: the super-app model (too many products in one interface, becoming confusing). Design direction: sober, professional, no marketing banners, no feature sprawl.

**UX scope definition — 3 core flows.**
The prototype scope was defined around three flows:
1. **Account Statement** — consolidated balance, recent transactions, receivables from issued boletos
2. **Boleto Management** — issue and track boleto payments; receivables overview
3. **PIX/TED Transfers** — primary payment flows; simplified and efficient

The differentiating element: a one-page dashboard where the user has an immediate, complete view of their financial position on login — balance, recent movements, provisionamento de cobranças (upcoming receivables). "Clarity and efficiency of this dashboard is the star."

---

## 4. Analysis and Insights

**Insight 1 — The target user is a finance professional, not a consumer banking customer.**
The Operator spends hours in the platform daily — routine tasks are the core use case, not emergency transactions. The UX imperative is efficiency and scannability for known workflows, not discovery or onboarding. This is a professional tool, not a consumer app. Every visual design decision (no marketing banners, no promotional cards, no feature discovery carousels) follows from this.

**Insight 2 — The CEO is both the Decision-Maker persona and the presentation audience.**
The prototype serves two purposes simultaneously: it must function as a believable experience for the Operator, and it must impress a decision-maker who is "conservative and visionary." The visual language must be sober and professional — not technically revolutionary, not casually modern (the product owner explicitly rejected both the purple-bright consumer-bank aesthetic and the super-app complexity model).

**Insight 3 — "One page" is the differentiator, not a feature.**
The product owner described the key differentiator not as a specific functionality but as the experience of a unified, clear view of the financial position on first load. This is an IA and visual hierarchy problem, not a feature problem. The dashboard must answer "what is my financial state right now?" in a single visual scan.

**Insight 4 — The escrow account is out of scope but must not create confusion.**
The platform has two current account types: the standard conta de movimentação and an escrow account for contractual transactions. The prototype focuses on the standard account. The escrow account's existence must not create navigation confusion — users should not wonder which account they are viewing.

---

## 5. Deliverables and Outcomes

**Deliverables produced (discovery phase):**
- Structured briefing notes and action items
- UX scope definition: 3 core flows, dashboard-first architecture, 2-persona model
- Competitor set established: QI Tech, BMP, CDC, Grafeno, Celcoin

**Next steps (confirmed in briefing):**
- Competitor UX analysis (QI Tech, BMP, Grafeno)
- Existing platform analysis (identify friction points in current account, boleto, and transfer flows)
- Conceptual prototype development (desktop, responsive approach, focused on dashboard + 3 flows)

*Prototype development was a separate engagement — not documented here.*

---

## 6. Recommendations and Next Steps

1. **Dashboard as single-screen financial position** — on login, the user should see: current balance, recent 5–7 transactions, upcoming receivables from open boletos, and access to the three core flows. No banners. No secondary content. No cross-sell.
2. **Boleto management as a financial calendar** — issued boletos with their due dates, status (paid, pending, overdue), and total projected receivables. This is the information the finance professional needs to manage cash flow — not just a boleto issuance tool.
3. **PIX/TED flow — speed as the metric** — a PIX transfer should be completable in 3 taps or fewer from the dashboard. Every additional step in a routine transfer is a support call waiting to happen.
4. **Audit trail in the transaction history** — every transfer, boleto, and payment should show timestamp, channel (PIX/TED/boleto), and recipient. Finance professionals are accountable for every transaction; the statement is their audit trail.

---

## 7. Reflection

**What worked well:**
- The structured briefing format (covering business problem, personas, competitive landscape, and scope) in a single 37-minute session produced a clear design brief without requiring multiple follow-up meetings. The product owner had thought through the constraints carefully and could articulate the "what to avoid" as clearly as the "what to build."
- Identifying the dashboard-as-differentiator insight in the briefing, not as a design recommendation after the fact. The product owner described it — "when you enter, you must have a clear and immediate vision of your financial position" — and the UX role was to name it as the core design problem.

**Challenges and constraints:**
- This is a discovery-phase case only. The prototype development and CEO presentation are not documented here.
- The briefing-only scope means the UX analysis rests on the product owner's characterization of user needs — not on direct research with finance department staff. The Operator persona is inferred from the briefing, not from user interviews.

**What I'd do differently:**
- Propose a 2-day shadow study with finance department staff at 2–3 existing clients before finalizing the prototype. Watching someone use the current platform for 30 minutes would surface friction points that the product owner's mental model of "usability problems" cannot fully capture.

<!-- TODO: create assets/financial-internet-banking-discovery-2026/ and add relevant visuals -->
