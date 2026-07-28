# Mentor Connects Portfolio Changelog

---

## Added — Jul 2026

### Summary

Added the Mentor Connects project card to the portfolio homepage (`index.html`). No case-study page was created. All copy is based on verified source code in `VishnuHub17/Mentor-Connects`.

---

### Repository inspection

Files read before writing any copy:

| File | Purpose | Finding |
|------|---------|---------|
| `V1 MC/src/App.jsx` | Route structure | Confirms all pages: Login, Signup, Welcome, OnboardingResume, CompleteProfile, ProfileSetup, ProfilePreview, ComposioSuccess, Dashboard, Webinars, WebinarDetails, MentorSettings, AdminDashboard, AdminCalendar, AdminWebinars, MentorsList, MentorDetails, AdminApiKeys, AdminSettings |
| `V1 MC/src/components/AddWebinarModal.jsx` | Webinar creation | Confirms webinar creation form (title, description, date, time, target audience, meet link) with sessionStorage draft persistence; inserts to Supabase `webinars` table |
| `V1 MC/src/pages/admin/AdminCalendar.jsx` | Calendar view | Confirms `import FullCalendar from '@fullcalendar/react'` with `dayGridPlugin` and `timeGridPlugin`; per-mentor colour coding via deterministic hash |
| `V1 MC/supabase/functions/composio-linkedin-v3/index.ts` | LinkedIn import | Confirmed via file tree — Composio LinkedIn OAuth integration |
| `V1 MC/src/pages/ComposioSuccess.jsx` | LinkedIn import | Confirmed via file tree — success state after Composio flow |

---

### Verified capabilities (4)

1. LinkedIn profile import via Composio OAuth (`composio-linkedin-v3` + `ComposioSuccess.jsx`)
2. Multi-step mentor onboarding with profile preview (`OnboardingResume`, `CompleteProfile`, `ProfileSetup`, `ProfilePreview` pages)
3. Webinar creation and scheduling with draft persistence (`AddWebinarModal.jsx` — sessionStorage across fields)
4. Admin calendar with per-mentor colour coding (`AdminCalendar.jsx` — FullCalendar with deterministic hash colouring)

---

### Verified tech stack (5)

React · Supabase · Tailwind CSS · Composio · FullCalendar

All five confirmed by direct source file inspection.

---

### Files modified

- `index.html` — Mentor Connects card replaced (line ~1505)

### Files created

- `MENTOR_CONNECTS_SCREENSHOT_CHECKLIST.md` — 12 screenshot slots with specs
- `MENTOR_CONNECTS_PORTFOLIO_CHANGELOG.md` — this file

---

### Claims excluded

| Excluded claim | Reason |
|---------------|--------|
| Active mentor count | Not verifiable from source code |
| Webinars delivered | Not verifiable from source code |
| Students reached | Not verifiable from source code |
| Time saved | Not verifiable from source code |
| Adoption or retention metrics | Not verifiable from source code |
| Revenue or commercial metrics | Not verifiable from source code |

---

### CTA behaviour

The card CTA ("View Product Overview →") links to `#mentor-connects-overview`, which is the `id` on the card element itself. It does not link to an external page or a non-existent case study. No `href="#"` or empty href used.

---

### Screenshot placeholders

Three screenshot slots are present in `index.html` as HTML comments. They are invisible to visitors and require no action until real screenshots are available. See `MENTOR_CONNECTS_SCREENSHOT_CHECKLIST.md` for specs.
