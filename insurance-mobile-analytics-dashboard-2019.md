# Mobile App Analytics Dashboard — Insurance Services

**Domain:**  Insurance Services
**Type:** Stakeholder Research, Workshop Facilitation & Data Dashboard Design
**Year:** 2019
**Role:** UX & Design Lead

---

| | |
|---|---|
| **9 insurance product lines** tracked in the dashboard | **Analytics team of ~5 people** serving the whole company |
| **5 metric categories** defined through research | **82.4% of app store complaints** captured in review analysis |
| **3 phases**: research → workshop → architecture | **Dashboard delivered to Analytics team** for production build |

---

One of Brazil's largest insurance conglomerates had a data problem: **any request for a product analytics report had to go through a central analytics team of about five people**. For a company of that scale, this created a bottleneck where a simple data query could take months to fulfill. As the mobile app design team leader, I saw an opportunity — and a clear need. The product managers on my team were flying blind, making decisions without visibility into how the app was actually being used.

## What I did

The process ran in three phases.

**Phase 1 — Stakeholder research.** I began by surveying and cataloguing every recurring report that product managers already received — understanding what data existed, in what format, and at what frequency. I then conducted interviews with each manager to understand what decisions they were trying to make and what information they were missing. This gave me both an inventory of available data and a map of unmet needs.

**Phase 2 — Workshop.** I facilitated an online prioritization workshop with the product and design team. Working from the full inventory of potential metrics, the team voted on and ranked what they most needed to do their jobs. This session converted a long list of possibilities into a structured, agreed-upon specification — with clear rationale for each metric included.

**Phase 3 — Architecture and design.** Working from the workshop output, I planned the dashboard architecture across **5 metric categories**: 

- Application (App Store and Play Store ratings, downloads, ranking evolution), 
- Demographics (gender, age, city distribution), 
- Usage (active users, sessions, session duration, screen depth), 
- Platforms (device types, OS versions, app version adoption), and 
- Content (most accessed screens, service availability and failure rates). 

The architecture also defined filter logic — by time period and by each of the **9 insurance product lines** (Auto, Life, Health, Dental, Residential, Pension, Card, Capitalization, and consolidated group view). A Google Data Studio chart reference was embedded in the plan to guide implementation decisions for each metric type.

I briefed one of our UI designers on the architecture, who translated it into a prototype through multiple rounds of review with the team and managers. Once approved, the final specification was handed off to the analytics team for production build in Google Data Studio.

![Mobile app analytics dashboard — v1.4 prototype](assets/insurance-mobile-analytics-dashboard-2019.png)

## What changed

The dashboard gave product managers direct, self-service access to the app metrics they needed to make decisions — eliminating the bottleneck of analytics requests that previously took months to fulfill. The metric scope was validated by the team before a single line of implementation work began, reducing the risk of building a dashboard that didn't reflect actual product management needs.

The review analysis that informed the metric selection identified that **82.4% of app store complaints** concentrated in a small set of recurring topics — data that shaped both the dashboard content and the broader product improvement roadmap.

*Note: I left the company in January 2020 before the production dashboard was completed, so long-term adoption outcomes are unavailable. The methodology — research-led metric definition, team workshop for prioritization, and architecture handoff — is the transferable value here.*
