# Portfolio QA Checklist

Run through this checklist before pushing to GitHub Pages.
Test in a real browser via the local server (`python -m http.server 8000`).

---

## Global

- [ ] All three pages load without console errors
- [ ] Nav is visible and fixed on scroll on all pages
- [ ] Scroll-reveal animations trigger correctly on all sections
- [ ] No `[X]`, `[Add …]`, or `todo-flag` text visible anywhere
- [ ] No dead `href="#"` links remain (except `#connect` intentional anchors)
- [ ] Footer text is correct on all three pages

---

## index.html

### Navigation
- [ ] "Work" link scrolls to the Selected Product Work section
- [ ] "Capabilities" link scrolls to the Capabilities section
- [ ] "Craft" link scrolls to the Craft section
- [ ] "Approach" link scrolls to the Approach section
- [ ] "Let's Connect" link scrolls to the Connect section
- [ ] Mobile burger menu opens and closes correctly

### Hero
- [ ] Name, headline and credential text display correctly
- [ ] "View My Work" button scrolls to `#work`
- [ ] "Let's Connect" text link scrolls to `#connect`
- [ ] No photo placeholder div visible

### Capabilities
- [ ] No `[X]` placeholder metrics visible in any capability description
- [ ] All four capability cards display correctly

### Selected Product Work
- [ ] Pathwisse featured card is visually larger and more prominent than the two cards below
- [ ] Pathwisse stats strip shows: 160+, 4, 4, 5
- [ ] "Read full case study →" links to `pathwisse.html`
- [ ] Agoda card shows the disclaimer in the grey pill
- [ ] Agoda "Read Case Study" links to `agoda.html`
- [ ] Agoda "View Deck" opens the Google Drive link in a new tab
- [ ] Mentor Connect card says "Case study in preparation" (not "coming soon")
- [ ] Mentor Connect "Ask me about it →" scrolls to `#connect`
- [ ] No Shaquantum Labs Website card visible

### Connect section
- [ ] Email link (`mailto:`) works correctly
- [ ] LinkedIn row is visible but not clickable (greyed out)
- [ ] Resume row says "Available on request — email above" and is not clickable

---

## pathwisse.html

### Navigation
- [ ] "All Work" links to `index.html#work`
- [ ] "Let's Connect" links to `index.html#connect`
- [ ] Back link in hero links to `index.html#work`

### Hero
- [ ] Stat strip shows: 5 / 160+ / 4 / 4
- [ ] Tags display correctly (B2B EdTech, Student Success, Role-based Portals, Product Discovery, Pathwisse)

### Sections
- [ ] All 19 section numbers display in order (01–19)
- [ ] Sticky section kickers work on desktop (scroll down within a section and kicker stays visible)
- [ ] Ownership grid shows three columns: Vishnu owned / Shared with core team / Engineering owned
- [ ] "Proposed metrics — not yet measured" tag is visible in Section 18
- [ ] Current Limitations section (17) is clearly separated from Metrics (18)

### Screenshot placeholders
- [ ] All 12 screenshot placeholder boxes display correctly (dashed border, orange label, title, hint)
- [ ] No broken image tags

### Final CTA
- [ ] "Ask me about this work" links to `index.html#connect`
- [ ] "← Back to all work" links to `index.html#work`

---

## agoda.html

### Navigation
- [ ] "All Work" links to `index.html#work`
- [ ] Back link links to `index.html#work`

### Content
- [ ] Disclaimer (yellow pill) visible in hero section
- [ ] Scope & Disclaimer section (02) lists all six scope points clearly
- [ ] "View Full Deck (PDF)" button in final CTA links to the correct Google Drive file URL
- [ ] Drive link opens in a new tab
- [ ] All 17 section numbers display in order (01–17)
- [ ] "Proposed plan — No experiment was run" tags visible in Section 13 (Validation Plan)
- [ ] "Proposed metrics — Not actual results" tags visible in Section 14
- [ ] Current User Journey (07) shows numbered journey diagram with friction/critical colour coding
- [ ] Journey analysis note visible below the diagram
- [ ] Concept disclaimer (amber) visible above wireframe screens in Section 11
- [ ] Normal flow shows 4 screens in a 4-column grid
- [ ] Exception flow shows 2 screens in a 2-column grid
- [ ] All 6 wireframe images load (not broken) or placeholders display correctly if images not yet added
- [ ] Clicking any wf-img opens the lightbox
- [ ] Lightbox shows full image, caption, and close button
- [ ] Pressing Escape closes the lightbox
- [ ] Clicking outside the image in the lightbox closes it

---

## Responsive / mobile

- [ ] `index.html` — all sections stack correctly below 768px
- [ ] `pathwisse.html` — case-section grid collapses to single column below 980px
- [ ] `pathwisse.html` — ownership grid collapses to single column below 640px
- [ ] `pathwisse.html` — stat strip stacks vertically on mobile
- [ ] `agoda.html` — case-section grid collapses correctly
- [ ] Nav burger works on all three pages (mobile only)

---

## Before deploying to GitHub Pages

- [ ] `PATHWISSE_SCREENSHOT_CHECKLIST.md` reviewed — screenshots either added or placeholders accepted as-is
- [ ] `CONTENT_NEEDED.md` reviewed — decision made on what stays placeholder vs. what blocks deploy
- [ ] No sensitive personal information in any file (no phone numbers, private email addresses, unpublished URLs)
- [ ] Run `git status` to confirm only intended files are staged
- [ ] Commit with a clear message describing what changed
- [ ] Push to `main` branch — GitHub Pages will rebuild automatically
