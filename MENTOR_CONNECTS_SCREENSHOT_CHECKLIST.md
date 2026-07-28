# Mentor Connects Screenshot Checklist

All slots below are commented-out placeholders in `index.html`. Uncomment and replace each `<div class="screenshot-slot">` with a real `<img>` when assets are ready.

Do not publish staged, fabricated, or non-live screens.

---

## Homepage Card — 3 priority slots

| # | Slot | Screen | Spec | Status |
|---|------|--------|------|--------|
| 1 | Mentor dashboard | `/dashboard` | 16:9 · readiness score, recent activity, upcoming webinars | Placeholder — commented out |
| 2 | Webinar creation modal | `AddWebinarModal` | 4:3 · modal open with form fields visible | Placeholder — commented out |
| 3 | Admin calendar | `/admin/calendar` | 16:9 · FullCalendar month or week view with events | Placeholder — commented out |

---

## Additional screens (future case study or extended card)

| # | Screen | Route | Notes |
|---|--------|-------|-------|
| 4 | Login page | `/login` | Static mockup exists at `V1 MC/static_mockups/login/` |
| 5 | Signup page | `/signup` | Static mockup exists at `V1 MC/static_mockups/signup/` |
| 6 | Welcome / onboarding start | `/welcome` | Static mockup exists at `V1 MC/static_mockups/welcome/` |
| 7 | OnboardingResume | `/setup/resume` | Shows resume-upload or LinkedIn-resume step |
| 8 | CompleteProfile | `/setup/onboard` | Multi-step profile form |
| 9 | ProfilePreview | `/setup/preview` | Rendered mentor card before publishing |
| 10 | ComposioSuccess | `/setup/composio-success` | LinkedIn import confirmation screen |
| 11 | Admin mentor list | `/admin/mentors` | Static mockup exists at `V1 MC/static_mockups/list/` |
| 12 | Admin dashboard | `/admin/dashboard` | Static mockup exists at `V1 MC/static_mockups/admin/` |

---

## Notes

- Do not show private mentor names, emails, or personal data in any screenshot without explicit permission
- Static mockups in `V1 MC/static_mockups/` can be used only if they accurately represent the live product state
- To publish a screenshot: swap the commented-out `<div class="screenshot-slot">` for `<img src="..." alt="..." loading="lazy">` with a descriptive alt attribute
- Tag each published screenshot with the date captured so staleness is visible
