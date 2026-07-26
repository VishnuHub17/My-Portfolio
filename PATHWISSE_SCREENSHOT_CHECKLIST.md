# Pathwisse Screenshot Checklist

Screens needed to complete the Pathwisse case study in `pathwisse.html`.
Each placeholder shows the purpose and recommended aspect ratio.

---

## Platform / Architecture (Section 07)

| # | Screen | Purpose | Ratio | Status |
|---|--------|---------|-------|--------|
| 1 | Platform or portal navigation overview | Shows the four-portal structure and how they connect | 16:9 | ⬜ Needed |

---

## Student Portal (Section 08)

| # | Screen | Purpose | Ratio | Status |
|---|--------|---------|-------|--------|
| 2 | Student dashboard | Readiness score, activity summary, roadmap progress | 16:9 | ⬜ Needed |
| 3 | Opportunities screen | Filtered opportunity list based on readiness | 16:9 | ⬜ Needed |

---

## Faculty Portal (Section 09)

| # | Screen | Purpose | Ratio | Status |
|---|--------|---------|-------|--------|
| 4 | Faculty assigned-student tracking view | Student list with readiness status and intervention flags | 16:9 | ⬜ Needed |
| 5 | Academic or assignment screen | Academic context shown alongside placement readiness data | 16:9 | ⬜ Needed |

---

## HOD Portal (Section 10)

| # | Screen | Purpose | Ratio | Status |
|---|--------|---------|-------|--------|
| 6 | HOD department dashboard | Department-wide readiness with batch and course breakdown | 16:9 | ⬜ Needed |

---

## Management Portal (Section 11)

| # | Screen | Purpose | Ratio | Status |
|---|--------|---------|-------|--------|
| 7 | Management dashboard | Institutional-level view with cross-department placement readiness | 16:9 | ⬜ Needed |

---

## Tracking and Intervention (Section 13)

| # | Screen | Purpose | Ratio | Status |
|---|--------|---------|-------|--------|
| 8 | Faculty intervention flag view | At-risk student list with engagement and progress indicators | 16:9 | ⬜ Needed |

---

## Career Roadmaps (Section 14)

| # | Screen | Purpose | Ratio | Status |
|---|--------|---------|-------|--------|
| 9 | Career roadmap selection screen | Student choosing a career path | 4:3 | ⬜ Needed |
| 10 | Roadmap progress view | In-progress roadmap with milestones and skill coverage | 4:3 | ⬜ Needed |

---

## Practice Labs and AI Mock Interview (Section 15)

| # | Screen | Purpose | Ratio | Status |
|---|--------|---------|-------|--------|
| 11 | Practice Labs screen | Active practice session — aptitude or communication | 4:3 | ⬜ Needed |
| 12 | AI mock interview session | Voice agent interface during an active interview | 4:3 | ⬜ Needed |

---

## How to add a screenshot

1. Export the screen at 2x resolution (retina-quality)
2. Save to `assets/screenshots/pathwisse/` (create folder if it does not exist)
3. Use descriptive filenames: `student-dashboard.png`, `hod-department.png`, etc.
4. In `pathwisse.html`, replace the `<div class="screenshot-slot ...">` block for that screen with:

```html
<img
  src="assets/screenshots/pathwisse/your-filename.png"
  alt="Brief description of what the screen shows"
  class="case-screenshot"
  loading="lazy"
>
```

5. Add to the CSS in `pathwisse.html` (once, near `.screenshot-slot`):

```css
.case-screenshot {
  width: 100%;
  border-radius: 12px;
  border: 1px solid var(--border);
}
```

---

## Progress

- Total screens needed: **12**
- Completed: **0**
- Remaining: **12**
