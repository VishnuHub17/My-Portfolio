# Mentor Connects Screenshot Checklist

Screenshots are needed in two places: the case-study page (`mentor-connects.html`) and the homepage card (`index.html`). All slots are currently in HTML comments and invisible to visitors.

Do not publish staged, fabricated, or non-live screenshots.

---

## Case study page — gallery (Section 08)

The gallery block in `mentor-connects.html` Section 08 is commented out entirely. Uncomment it and add real `<img>` tags when at least 3 screenshots are ready.

| # | Slot | Image path | Spec | Status |
|---|------|-----------|------|--------|
| 1 | Mentor onboarding or profile preview | `assets/images/mentor-connects/onboarding-profile-preview.png` | 16:9 · ProfilePreview step showing rendered mentor card | Pending |
| 2 | Mentor dashboard | `assets/images/mentor-connects/mentor-dashboard.png` | 16:9 · upcoming webinars, profile summary | Pending |
| 3 | Webinar list | `assets/images/mentor-connects/webinar-list.png` | 16:9 · upcoming, held and not-held statuses visible | Pending |
| 4 | Create-webinar modal | `assets/images/mentor-connects/create-webinar-modal.png` | 4:3 · modal open with form fields | Pending |
| 5 | Webinar details and registrations | `assets/images/mentor-connects/webinar-details.png` | 16:9 · registration list visible | Pending |
| 6 | Admin mentor management | `assets/images/mentor-connects/admin-mentors.png` | 16:9 · mentor list with search and onboarding status | Pending |
| 7 | Mentor detail page | `assets/images/mentor-connects/mentor-detail.png` | 16:9 · mentor profile with webinar history | Pending |
| 8 | Global admin calendar | `assets/images/mentor-connects/admin-calendar.png` | 16:9 · FullCalendar with per-mentor colour blocks | Pending |

Use 6 to 8 screenshots maximum. Do not show all 8 if quality varies — choose the strongest.

---

## Homepage card — inline screenshots (`index.html`)

Three commented-out `<img>` tags in the Mentor Connects card. Uncomment and set the `src` when assets are available.

| # | Slot | Image path | Status |
|---|------|-----------|--------|
| 1 | Mentor dashboard | `assets/images/mentor-connects/mentor-dashboard.png` | Pending |
| 2 | Create webinar modal | `assets/images/mentor-connects/create-webinar-modal.png` | Pending |
| 3 | Admin calendar | `assets/images/mentor-connects/admin-calendar.png` | Pending |

When adding inline card screenshots, add `.wc-screenshot` styles (border-radius: 8px, margin-top: 12px, max-height: 140px, object-fit: cover) to keep the card compact.

---

## Image directory

Place all Mentor Connects screenshots in:

```
assets/images/mentor-connects/
```

Create this directory before adding files.

---

## Notes

- Static mockups exist in `VishnuHub17/Mentor-Connects` at `V1 MC/static_mockups/`. Use them only if they accurately represent the live product state.
- Do not show private mentor names, emails, or personal data without explicit permission.
- Do not stage screenshots for features that are not implemented.
- Tag each published screenshot file with a capture date in the filename or a comment so staleness is visible.
- To replace a placeholder: uncomment the `<img>` tag, set `src`, verify `alt` text is descriptive.
