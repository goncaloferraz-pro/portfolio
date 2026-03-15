---
title: "Website Navigation Redesign Research — Enterprise Web Services Platform"
year: 2023
domain: Web Hosting / SaaS
duration: 2 months (April–June 2023)
primary_role: Senior UX Researcher
secondary_roles:
  - UX Strategist
methods:
  - Desk research and competitive benchmarking
  - User interviews
  - Card sorting
  - Moderated usability testing
impact: Research defined and validated the navigation architecture — 4 groupings, mega menu, and labeling strategy — before any design or engineering investment
---

# Enterprise Web Services Platform — Navigation Architecture From First Principles

An enterprise web services platform was redesigning its global marketing site navigation. Before any design decisions were made, I answered **5 specific research questions** about naming, groupings, overview pages, menu type, and conversion focus — using a four-method study that ran from brief to published report in **2 months**.

| | |
|---|---|
| **4 research methods** combined in a single study | **5 research questions** fully answered |
| **4 nav groupings** validated through card sorting | Mega menu recommended based on Fitts' Law analysis |
| **2-month study** from brief to published report | Naming inconsistency confirmed as a structural barrier across the full site |

---

## 1. Context

An enterprise web services platform was overhauling its global marketing site navigation — top and footer menus across every page, serving visitors ranging from first-time website builders to experienced web professionals managing multiple client sites.

The existing navigation had accumulated over time: inconsistently labeled, structured around internal product categories rather than visitor mental models, and not optimized for conversion. A redesign was planned, but the team needed to know what the new structure should actually be — not based on internal assumptions, but based on how real visitors thought about and searched for what the platform offered.

Five research questions were defined upfront: What naming do users respond to? What groupings make sense? What should overview pages do? What menu type is most effective? How does navigation affect conversion?

---

## 2. My Role

**Primary: Senior UX Researcher**
I designed and led the full four-method study, synthesizing findings across methods into a single structured recommendation set that answered all five research questions.

**Secondary roles:**
- **UX Strategist**: Applied Fitts' Law analysis to make the menu-type recommendation; identified conversion-focused placements for pricing tables that emerged from behavioral patterns in usability testing.

---

## 3. Method

**Desk research (baseline)**
Reviewed existing documentation: internal slide decks, listening posts, homepage heatmaps, sitemap, and content inventory. Benchmarked navigation patterns across competitor and reference sites, analyzing linear menus, mega menus, and touch-target sizing implications (Fitts' Law). Established what was known before any user contact.

**User interviews**
Explored how visitors mentally categorized the platform's products and services — what terms they used, what they expected to find where, and where terminology created confusion. Focused on the language gap between internal product naming and user-facing mental models.

**Card sorting**
Tested which groupings made structural sense to users. Produced four top-level navigation categories validated as the clearest organizing structure for the platform's full product range.

**Usability testing (moderated)**
Validated the proposed navigation structure, surfaced interaction-level issues, and confirmed conversion-influencing behaviors — including scroll position expectations when navigating between sections.

---

## 4. Analysis and Insights

**Finding 1 — Naming: The platform used title-style labels that omitted descriptive terms.**
Navigation relied on labels that were structurally ambiguous — visitors with lower web-technology familiarity could not locate what they were looking for. The labels were internally coherent but externally opaque. SEO also emerged as a constraint: navigation labels needed coordination with the marketing team to serve both user clarity and search indexing simultaneously.

**Finding 2 — Groupings: Two visitor profiles coexist, and both respond to the same four-category structure.**
"Explorers" (browsing broadly) and "seekers" (looking for known terms) both oriented to the same four categories: **Business** (establishing an online presence), **eCommerce** (building online stores), **Products** (specific feature exploration), and **Pricing** (consistently navigated to after an initial page scan). The four-category structure matched how visitors described their own needs.

**Finding 3 — Overview pages: One "Overview" per category is not enough.**
Users expected overview pages to function as high-level landing pages — not as intermediate navigational steps. Product details should live on dedicated product pages with clear CTAs, preventing the deeper nav nesting that caused confusion when visitors tried to learn about specific products from a top-level overview.

**Finding 4 — Menu type: Mega menu over linear dropdown.**
Given the volume of items within each category, a mega menu was the right choice. Fitts' Law analysis drove the recommendation: increased click-target size per item (particularly important for mobile/touch), visual contrast to signal interactive areas, and spatial grouping to reduce scan time. The research also found that pages should reset to the top of scroll position when navigating via the main menu — a behavior users expected but the current implementation did not provide.

**Finding 5 — Conversion: Showing pricing at the end of category pages was well-received.**
Once visitors encountered interesting content in a category, they expected to be able to act on it immediately — suggesting feature-level links and pricing tables at the bottom of Business and eCommerce category pages. Pricing was the most consistently sought destination after an initial site scan, confirming it should be prominent in the primary navigation.

---

## 5. Deliverables and Outcomes

Full research report with specific, actionable recommendations for product and design teams:

- Rewrite navigation labels to include key descriptive terms users recognize
- Restructure primary nav into four validated groupings: Business, eCommerce, Products, Pricing
- Implement a mega menu to accommodate item volume and improve target sizing on all devices
- Limit support content to the Help Center channel only — remove broader Resources list from primary nav
- Relocate Blog, Case Studies, and Whois Lookup to the footer (indexable by search engines without competing for nav real estate)
- Reset scroll position to top when navigating between pages via main menu
- Surface pricing tables at the end of Business and eCommerce category pages

**Impact:** The study preceded any design or engineering investment, ensuring that navigation architecture decisions were grounded in observed visitor behavior rather than internal assumptions. The four-method approach answered all five research questions within a single two-month engagement.

---

## 6. Recommendations and Next Steps

Top recommendations delivered (in order of navigation hierarchy importance):

1. **Fix the label language first** — four correct groupings with wrong labels will still fail; the right terms are the prerequisite
2. **Implement the four-category structure** (Business, eCommerce, Products, Pricing) as the primary nav spine
3. **Adopt the mega menu** — item volume alone justifies it; Fitts' Law benefits on mobile are a secondary win
4. **Remove Resources, Blog, and Case Studies from primary nav** — footer placement serves SEO without competing for navigation attention
5. **Surface pricing tables inline on category pages** — visitors expect to be able to act from within the category, not only from the Pricing nav item

Follow-up research recommended:
- Quantitative A/B test of the new navigation structure vs. the current to validate conversion impact
- Post-launch click-heatmap analysis to confirm the four-category groupings hold under real-world traffic patterns

---

## 7. Reflection

**What worked:** The four-method sequence was well-designed for the questions at hand. Desk research and interviews established the conceptual baseline before asking participants to evaluate specific structures — which made the card-sort more valid and the usability testing more diagnostic. Participants weren't being asked to evaluate a structure they had no mental model for; they'd already expressed how they thought about the platform's products.

The Fitts' Law analysis was a useful bridge between qualitative user preferences and a quantitative design rationale. Recommending a mega menu based purely on "users liked it" would have been a weaker argument than grounding the recommendation in target-size and touch-accuracy principles.

**Challenges:** The research was conducted with a self-selected sample of current users and potential visitors. Navigation confusion disproportionately affects first-time visitors who have no existing mental model of the platform — and those are the hardest participants to recruit for a study. The card-sort in particular may underrepresent how confused newcomers are with the platform's terminology.

**What I'd do differently:** Run a separate first-click test with participants who have zero prior exposure to the platform, specifically to validate the label choices. Card sorting captures grouping preferences from people who are already somewhat familiar with the product range; it doesn't fully simulate the first-time visitor experience where labels alone determine whether someone continues or bounces.
