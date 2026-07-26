# Portfolio Changelog

## [Unreleased] — 2026-07-26

### Added
- `pathwisse.html` — complete rebuild as a full 19-section product case study for the Pathwisse Student Success Platform (previously a stub "coming soon" page about Practice Labs only)
- `PATHWISSE_SCREENSHOT_CHECKLIST.md` — 12 screenshot placeholders with purpose, section location, and recommended ratio
- `PORTFOLIO_CHANGELOG.md` — this file
- `CONTENT_NEEDED.md` — outstanding real content Vishnu needs to provide
- `PORTFOLIO_QA.md` — QA checklist for the full portfolio

### Changed — `index.html`

**Navigation**
- Merged "Case Studies" and "Products" nav items into a single "Work" link pointing to `#work`

**Hero section**
- Removed photo placeholder div and developer instructions
- Removed non-functional "Download Resume" button (no URL existed)

**Capabilities section**
- Removed `[X] workflows` and `[X] modules` placeholder metrics from CRM & SaaS Workflows capability text

**PM Toolkit section**
- Removed `[X] workflows` placeholder metric from Requirements & user stories toolkit item

**Work section (new)**
- Replaced separate "Case Studies" (`#case-studies`) and "Products & Shipped Work" (`#products`) sections with a single "Selected Product Work" (`#work`) section
- Pathwisse: redesigned as a full-width featured card with verified stats (160+ stakeholders, 4 colleges onboarded, 4 portals, 5 colleges discovered) — updated description to reflect full platform, not Practice Labs only
- Agoda: updated description, added inline disclaimer ("Independent concept case study — not affiliated with Agoda. All metrics are proposed")
- Mentor Connect: updated description to reflect product ownership accurately; replaced dead `href="#"` with `#connect` CTA; removed `[Add Mentor Connect URL]` todo flag; case study marked as "in preparation" instead of "coming soon"
- Removed Shaquantum Labs Website card entirely

**Testimonials**
- Removed both placeholder testimonial bands

**Connect section**
- LinkedIn and Resume links converted from dead `href="#"` anchor tags with todo flags to non-clickable informational rows (`pointer-events: none`) with honest placeholder text

### Changed — `pathwisse.html`

Full replacement. Previous content: 3-section stub with "coming soon" messaging, a short paragraph, and a single CTA.

New content: 19 sections covering:
1. Hero with stat strip (5 colleges, 160+ stakeholders, 4 portals, 4 onboarded)
2. Product overview with four-portal card grid
3. The fragmented student-success problem (role-by-role table)
4. Discovery across five colleges
5. Research insights (six insight cards)
6. Product decision and roadmap prioritisation (shared-team note, five-row table)
7. Product architecture with screenshot placeholder
8. Student portal (six feature cards, two screenshot placeholders)
9. Faculty portal (four feature cards, two screenshot placeholders)
10. HOD portal (three feature cards, one screenshot placeholder)
11. Management portal (two feature cards, one screenshot placeholder)
12. My ownership (three-column ownership grid: Vishnu owned / Shared / Engineering)
13. Deep dive: tracking and intervention (four cards, one screenshot placeholder)
14. Deep dive: career roadmaps and personalised learning (flow list, two screenshot placeholders)
15. Deep dive: Practice Labs and AI mock interviews (four cards, two screenshot placeholders)
16. Validation and onboarding of four colleges (four cards)
17. Current limitations (four honest limitation cards)
18. Metrics to measure next (five-row table, clearly labelled "proposed — not yet measured")
19. Product learnings (four insight cards + closing callout)

### Removed
- Shaquantum Labs Website card (from homepage and all references)
- Both placeholder testimonial bands from `index.html`
- All `[X]` placeholder metrics
- All `href="#"` dead links (Download Resume, View live app, LinkedIn, Resume)
- All `todo-flag` spans with placeholder instructions
- "Coming soon" and "Full case study with artifacts coming soon" messaging from `pathwisse.html`
- Photo placeholder and developer replacement instructions from hero
- Duplicate section headings (case-studies and products merged)
