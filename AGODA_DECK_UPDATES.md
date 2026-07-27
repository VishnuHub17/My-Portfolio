# Agoda Deck Updates

Slides to add to the PDF deck before the next share or publish.

---

## Slides to add

### 1. My Role and Study Boundaries

Clarify the scope of the case study explicitly on the slide:

- What is included: problem framing, user journey mapping, proposed solution design, wireframe concepts, product hypothesis, proposed validation plan, proposed success metrics
- What is not included: primary user research, internal Agoda data, shipped code, measured outcomes
- Role: Independent concept case study. Not affiliated with Agoda.

### 2. Scope and Disclaimer (second slide)

Add a clear disclaimer slide early in the deck:

> "This is an independent product case study based on personal experience and public product analysis. All research, design framing and analysis is original and independent. The proposed concept was not tested or validated with real users. Concept screens are not existing, implemented or tested Agoda interfaces. Metrics and outcomes are proposed hypotheses, not actual results. This case study is not affiliated with Agoda or Booking Holdings."

### 3. Constraints, Risks and Dependencies

Currently covered in the portfolio (section 15) but absent from the deck. Add a slide covering:

- Hotel system integration (real-time data not guaranteed)
- Data mismatch handling workflow
- Operational ownership of the issue tracker
- False-confidence risk (never show "verified" unless truly matched)
- Support escalation for cases that need human intervention

### 4. Validation and Experiment Plan

New slide covering the proposed A/B test:

- Control: current post-booking confirmation flow
- Treatment: Booking Assurance Layer visible after payment
- Primary metric: pre-trip confirmation support ticket volume
- Secondary metrics: post-booking confidence score, hotel acknowledgment rate, detail match rate
- Proposed success threshold: ≥10% reduction in confirmation tickets, ≥0.3 improvement in confidence score
- Note: No experiment was conducted

### 5. Learnings and Expected Product Impact

Currently the deck ends on the hypothesis. Add a closing slide covering:

- Key learning: platform confirmation must evolve into booking assurance
- Expected impact: improved post-booking confidence, reduced anxiety-driven support contacts
- Validation needed: A/B tests on support ticket volume, post-booking confidence survey, hotel acknowledgment completion rate

---

## Required disclaimer on concept screens

Add this caption below every wireframe screen in the deck:

> "Concept wireframes: created for this independent product case study. Not existing, implemented or tested Agoda interfaces."

---

## Image file names for portfolio (assets/images/agoda/)

Save each uploaded screenshot with the correct filename. The HTML references these exact paths.

| Section | Screen title | File name |
|---------|-------------|-----------|
| Normal flow — Screen 1 | Booking created and verification started | `wf-normal-01-booking-created.png` |
| Normal flow — Screen 2 | Hotel acknowledgment and verification pending | `wf-normal-02-ack-pending.png` |
| Normal flow — Screen 3 | Verification timeline | `wf-normal-03-timeline.png` |
| Normal flow — Screen 4 | Verified and ready for check-in | `wf-normal-04-ready-check-in.png` |
| Exception flow — Screen 5 | Booking-detail mismatch detected | `wf-exception-01-detail-mismatch.png` |
| Exception flow — Screen 6 | Hotel acknowledgment delayed | `wf-exception-02-ack-delayed.png` |

### Image-to-file mapping (from the uploaded screenshots)

- Uploaded Image 1 (Booking Confirmed, green checkmark, verification in progress) → `wf-normal-01-booking-created.png`
- Uploaded Image 2 (Booking Assurance, awaiting acknowledgment, assurance checklist) → `wf-normal-02-ack-pending.png`
- Uploaded Image 5 (Verification timeline, pending acknowledgment) → `wf-normal-03-timeline.png`
- Uploaded Image 3 (Ready for check-in, all matched, hotel reference number) → `wf-normal-04-ready-check-in.png`
- Uploaded Image 4 (Booking details issue, mismatch detected, resolution options) → `wf-exception-01-detail-mismatch.png`
- Uploaded Image 6 (Booking attention needed, acknowledgment delayed, Agoda follow-up) → `wf-exception-02-ack-delayed.png`

Save all files to: `assets/images/agoda/`
