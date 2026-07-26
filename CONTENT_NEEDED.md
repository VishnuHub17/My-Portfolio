# Content Needed

Real assets and information Vishnu needs to provide before the portfolio is fully complete.
Items are grouped by priority — blockers first, improvements second.

---

## Priority 1 — Blockers (visible gaps in the live site)

### Pathwisse screenshots (12 screens)
The case study has placeholder boxes for 12 screens. See `PATHWISSE_SCREENSHOT_CHECKLIST.md` for the full list, purpose, and ratio for each.

- All 12 screens are currently empty placeholder boxes
- No partial credit — the placeholders are clearly marked so readers know they are coming

### Mentor Connect URL
- The Mentor Connect card links to `#connect` as a temporary CTA
- Provide the live URL to replace it with a direct link
- Once available: add `href="[URL]"` and change button text to "View live app →"

### LinkedIn URL
- The LinkedIn row in the Connect section is currently non-clickable
- Provide the full LinkedIn profile URL
- Once available: change `<div class="connect-link connect-link-pending">` to `<a href="[URL]" class="connect-link" target="_blank" rel="noopener noreferrer">`

### Resume PDF
- The Resume row in the Connect section says "Available on request — email above"
- Upload the resume file and provide the path or URL
- Suggested path: `assets/vishnu-vardhan-resume.pdf`
- Once available: change the resume row to an anchor tag with the correct href

---

## Priority 2 — Quality improvements

### Headshot / profile photo
- The hero section no longer has a placeholder div but the layout was designed for a photo
- If you want to add a photo later: add `<img src="assets/photo.jpg" class="hero-img" alt="S Vishnu Vardhan">` inside `<div class="hero-image-wrap">` and restore the two-column hero layout
- Not a blocker — the single-column hero works without it

### Agoda case study — wireframe slots
- `agoda.html` has `.visual-slot` placeholder boxes in Sections 07 and elsewhere
- If wireframes or flow diagrams are available from the deck, they can be embedded here

### Testimonials
- Both placeholder testimonial sections have been removed
- When real quotes are available (from a collaborator, developer, or institutional contact), they can be added back as a styled blockquote band between the Work and Craft sections

---

## Priority 3 — Nice to have

### Mentor Connect case study
- The Mentor Connect card notes "Case study in preparation"
- When ready, create `mentor-connect.html` following the same structure as `pathwisse.html`
- Update the card CTA from `href="#connect"` to `href="mentor-connect.html"`

### Pathwisse — Opportunities layer details
- This section is scoped in the case study but noted as "planned, not fully live"
- When the layer ships, update Section 08 (Student Portal → Opportunities) and Section 17 (Current Limitations) accordingly

---

## Summary

| Item | Type | Where |
|------|------|--------|
| 12 Pathwisse screenshots | Images | `pathwisse.html` §07–§15 |
| Mentor Connect URL | URL | `index.html` work card |
| LinkedIn URL | URL | `index.html` connect section |
| Resume PDF | File + URL | `index.html` connect section |
| Profile photo | Image | `index.html` hero (optional) |
| Testimonials | Text | Between Work and Craft (optional) |
| Mentor Connect case study | New page | When ready |
