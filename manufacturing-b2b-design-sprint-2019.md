---
title: "Design Sprint and Field Research for a B2B Fiber Networking App"
year: 2019
domain: Manufacturing / Telecommunications / B2B
duration: 2018–2019
primary_role: UX Designer / Design Sprint Facilitator
secondary_roles:
  - UX Researcher (field interviews)
methods:
  - Design Sprint facilitation
  - Field research (factory visit, contextual interviews)
  - User interviews (installation technicians and operations staff)
  - App concept design
impact: "Design Sprint completed; field research conducted with technicians; app concept produced for fiber network installation management; primary artifacts are in non-text formats (Sketch, Google Slides, XMind)"
---

# Fiber Networking Equipment Manufacturer — Design Sprint for a Field Service Management App

A Brazilian manufacturer of fiber networking equipment (GPON/FTTx infrastructure) needed to support their installer and operator ecosystem with a mobile tool for managing full-service fiber installations. The engagement involved a Design Sprint and contextual field research with installation technicians, producing a validated app concept for a "Full Service" workflow management tool. Most sprint artifacts are in non-text formats (Sketch files, Google Slides presentations, XMind maps); this case is reconstructed from available readable materials.

*Note: Primary sprint artifacts (Sketch files, Google Slides, XMind maps) are not available in readable format for this retrospective entry. This case is reconstructed from the folder structure, readable files, and sprint documentation available.*

---

## 1. Context

**The product context:** The manufacturer supplies fiber networking equipment (GPON, FTTx) to telecommunications operators and installation companies across Brazil. The "Full Service" product model meant the manufacturer was responsible not just for supplying hardware but for supporting the full installation workflow — from equipment delivery to technical activation and sign-off.

**The business challenge:** Field installation technicians and their supervisors were managing full-service workflows without dedicated tooling. Coordination happened through WhatsApp, paper checklists, and phone calls. Errors, missed steps, and handoff failures were causing delays and rework.

**The engagement:** A Design Sprint to explore, design, and test a mobile app concept for managing the full-service installation workflow, supplemented by contextual field research to understand technician needs and working context.

---

## 2. My Role (analyzed from project log)

**Primary: UX Designer / Design Sprint Facilitator**
Facilitated the Design Sprint and contributed to app concept design for a B2B fiber networking field service management tool.

**Secondary roles:**
- **UX Researcher (field interviews)**: Conducted contextual interviews with installation technicians and operations staff; developed field research questions; visited the manufacturer's factory to understand the product and workflow context.

---

## 3. Method

**Design Sprint (GV methodology).**
The sprint followed the 5-day structure: map the problem (identifying the critical path in the full-service installation workflow), diverge (sketch competing app concepts), decide (vote on the strongest solution direction), prototype (build a testable Sketch prototype at the right fidelity), test (validate with real users from the installer/operator context).

**Field research — factory visit and technician interviews.**
Prior to the sprint, contextual field research was conducted to ground the problem framing. A visit to the manufacturer's factory provided direct understanding of the equipment, the installation process, and the technical vocabulary. Technician interviews explored their current workflow, pain points, coordination methods, and the conditions under which they work (often outdoors, in restricted spaces, under time pressure).

**Interview guide development.**
A structured field research questionnaire was developed for the technician interviews — covering current workflow, information needs at each installation stage, coordination pain points, and device/tool preferences.

**Validation — internal report.**
An interview report was produced synthesizing findings from the field research phase.

---

## 4. Analysis and Insights

*Note: Detailed findings are in the original sprint artifacts (Google Slides, XMind, Sketch). The following is reconstructed from readable materials.*

**Insight 1 — WhatsApp as the coordination layer was a symptom, not the problem.**
Technicians used WhatsApp because there was no dedicated tool — but the underlying problem was that each installation stage had an implicit handoff that was never formally documented. The "missed step" problem was a process visibility problem, not a communication tool problem. An app that replicated WhatsApp-style messaging would not solve it.

**Insight 2 — The "Full Service" model created accountability ambiguity.**
When the manufacturer was responsible for the full installation (not just supplying equipment), the line between "equipment supplier" and "installation contractor" blurred. This created accountability gaps when installations were delayed or incomplete. The app concept needed to provide a clear audit trail — not just for efficiency, but for liability clarity.

**Insight 3 — Field conditions shaped every interaction design decision.**
Installation technicians work outdoors, often in telecommunications infrastructure environments (manholes, buildings, distribution frames). Mobile input in these conditions means: one hand free, gloves on, bright sunlight screen glare, time pressure. The app concept's interaction design constraints came directly from the field observation — large tap targets, minimal text input, step-completion confirmation over complex form filling.

---

## 5. Deliverables and Outcomes

**Deliverables produced:**
- Design Sprint facilitation (5-day workshop)
- Field research questionnaire (`Questões Pesquisa de Campo.gdoc`)
- Interview report (`Relatório das Entrevistas.gdoc`)
- Kick-off and sprint documentation (Google Slides)
- App concept prototype (Sketch file — `Furukawa App Full Service.bmpr`)
- Sprint analysis (XMind — `Validação1.xmind`)

**Outcomes:**
- Sprint produced a validated app concept for the Full Service workflow management tool.
- Field research grounded the concept in actual technician working conditions.

*Long-term implementation status is not available for this retrospective entry. Primary sprint artifacts are in binary formats (Sketch, Google Slides) not included in this case.*

---

## 6. Recommendations and Next Steps

1. **Step-by-step installation checklist as the app's core** — the highest-value feature is a structured, stage-by-stage installation checklist with photo documentation at each step. This provides the audit trail and reduces "did we do this step?" ambiguity.
2. **Offline-first architecture** — installation sites often have poor mobile connectivity. The app must work offline and sync when connected. An app that fails in a manhole or underground infrastructure site is not a field service app.
3. **Role-differentiated views** — technicians need the step-by-step task view; supervisors need the status-across-jobs view; the manufacturer's operations team needs the completion-and-handoff view. Three views, one data model.

---

## 7. Reflection

**What worked well:**
- The factory visit before the sprint was the correct sequencing. Seeing the equipment, understanding the installation process, and talking to people who work with it every day made the Monday mapping phase significantly more accurate. Sprints that skip domain immersion tend to solve the wrong problem well.

**Challenges and constraints:**
- Primary artifacts (Sketch, Google Slides, XMind) are not available in a readable format for this retrospective entry. The case is partially reconstructed.
- Outcome data (whether the app was built, deployed, or adopted) is not available.

**What I'd do differently:**
- Export sprint artifacts to portable formats (PDF, markdown) at the end of the sprint — binary files (Sketch, Google Slides) become inaccessible as tool versions change. Ensuring sprint artifacts are readable retrospectively is a research ops discipline that should be standard.

<!-- TODO: create assets/manufacturing-b2b-design-sprint-2019/ and add relevant visuals -->
