# Mentor Connects Case Study Changelog

---

## Created — Jul 2026

### Summary

Created `mentor-connects.html` as a concise, recruiter-readable 8-section case study for the independently built Mentor Connects product. Updated the homepage card in `index.html` and applied shared icon-size corrections across the homepage.

---

### Files created

- `mentor-connects.html` — full case study (8 sections)
- `MENTOR_CONNECTS_CASE_STUDY_CHANGELOG.md` — this file

### Files updated

- `index.html` — Mentor Connects card, icon-size corrections
- `MENTOR_CONNECTS_SCREENSHOT_CHECKLIST.md` — extended with case-study gallery and homepage card slots

---

### Repository inspected

`VishnuHub17/Mentor-Connects` — read before writing any copy.

| File | Finding used in copy |
|------|---------------------|
| `V1 MC/src/App.jsx` | Route structure: 19 routes confirmed across mentor and admin portals |
| `V1 MC/src/components/AddWebinarModal.jsx` | Webinar creation form, session-storage draft persistence |
| `V1 MC/src/pages/admin/AdminCalendar.jsx` | FullCalendar with dayGrid + timeGrid; per-mentor deterministic hash colouring |
| `V1 MC/supabase/functions/composio-linkedin-v3/index.ts` | Composio LinkedIn import function |
| `V1 MC/src/pages/ComposioSuccess.jsx` | LinkedIn import success state |

---

### Case study structure (8 sections)

| # | Section | Approx. words |
|---|---------|--------------|
| 01 | The problem | ~110 |
| 02 | Product goal | ~65 |
| 03 | How the product works | ~30 (workflow labels) |
| 04 | What I designed and built | ~200 |
| 05 | Key product decisions | ~100 |
| 06 | My ownership | ~60 |
| 07 | Current status and limitations | ~120 |
| 08 | Learnings and product gallery | ~130 |
| **Total** | | **~815 prose words** |

Estimated reading time including visual elements: 4–5 minutes.

---

### Design decisions

- CSS copied from pathwisse.html baseline and adapted — same variables, same `.case-section` grid layout, same `.project-snapshot` component
- New components: `.problem-stack`, `.workflow-row`, `.decision-card`, `.ownership-col`, `.limit-list`, `.metrics-list`, `.learning-card`, `.gallery-grid`
- Icon containers: `.role-badge` at 32px × 32px (card-icon spec); no oversized icon containers added
- Gallery section is entirely commented out — no screenshots published until real assets are available

---

### Claims excluded

| Excluded claim | Reason |
|---------------|--------|
| Active mentor count | Not verifiable from source code |
| Webinars delivered | Not verifiable from source code |
| Students reached | Not verifiable from source code |
| Adoption, retention, efficiency percentages | Not verifiable from source code |
| Revenue or commercial metrics | Not verifiable from source code |
| AI features | Not present in verified source |
| Mentor marketplace / matching | Not present in verified source |

---

### Homepage card changes (index.html)

| Element | Before | After |
|---------|--------|-------|
| Title | "Mentor Connect" | "Mentor Connects" |
| Tags | "Live Product" | "Independently Built Product" |
| Meta label | (not present) | "Mentor Onboarding and Webinar Operations Platform" |
| Description | Short one-liner | Updated per spec |
| Ownership line | (not present) | "Designed and built end-to-end" |
| Highlights | 4 technical capabilities | 3 highlights per spec |
| Flow line | Signup → … → Calendar | Removed (card simplified per spec) |
| Tech tags | React, Supabase, … (inline) | Removed from card |
| Primary CTA | "View Product Overview →" (self-anchor) | "Read Case Study" → mentor-connects.html |
| Secondary CTA | (not present) | "View Repository" → GitHub |

---

### Icon-size corrections (index.html)

| Element | Before | After |
|---------|--------|-------|
| `.work-card-icon` container | 46px × 46px | 32px × 32px |
| `.work-card-icon` font-size | 18px | 15px |
| `.work-card-icon` border-radius | 12px | 8px |
| `.cap-icon` container | 44px × 44px | 36px × 36px |
| `.cap-icon` border-radius | 12px | 9px |

Pathwisse and Agoda case-study pages: no oversized icon containers found — no changes required.

---

### Screenshots still required

See `MENTOR_CONNECTS_SCREENSHOT_CHECKLIST.md`. 8 slots identified; gallery hidden until at least 3 real screenshots are available.

---

### What was not changed

- Pathwisse case study content — unchanged
- Agoda case study content — unchanged
- Shared nav, footer, or font loading — unchanged
- Any content in `VishnuHub17/Mentor-Connects` — not modified
