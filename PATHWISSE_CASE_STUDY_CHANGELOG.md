# Pathwisse Case Study Changelog

---

## Refactor — Jul 2026

### Summary

Restructured the existing 19-section case study into a 14-section narrative-led format focused on the product decision story rather than a feature catalogue.

---

### Sections merged or removed

| Original section | Action | Destination |
|-----------------|--------|-------------|
| 01 Context | Merged | 01 Product Context |
| 02 Product Overview (portal cards) | Merged | 06 How the Four-Role Platform Works |
| 07 Product Architecture | Merged | 06 How the Four-Role Platform Works |
| 08 Student Portal (standalone section) | Merged | 06 How the Four-Role Platform Works |
| 09 Faculty Portal (standalone section) | Merged | 06 How the Four-Role Platform Works |
| 10 HOD Portal (standalone section) | Merged | 06 How the Four-Role Platform Works |
| 11 Management Portal (standalone section) | Merged | 06 How the Four-Role Platform Works |
| Research insight 5 (readiness is a process) | Removed | Absorbed into product context copy |
| Research insight 6 (communication skills) | Relocated | Supporting insight note in Section 10 |
| Learning 4 (honesty about metrics) | Removed | Per spec: three learnings only |

---

### Final section structure

01. Product context  
02. The fragmented student-success problem  
03. Discovery across five colleges  
04. Key research insights  
05. The product decision  
06. How the four-role platform works  
07. My ownership  
08. Deep dive: tracking and intervention  
09. Deep dive: career roadmaps  
10. Deep dive: Practice Labs and AI mock interviews  
11. Validation and onboarding  
12. Current limitations  
13. Metrics to measure next  
14. Product learnings  

---

### Existing claims retained

- 5 colleges researched
- 160+ stakeholders engaged
- 20+ HODs, 40 faculty, 100+ students
- 4 role-based portals
- 4 colleges onboarded
- All four portal descriptions (student, faculty, HOD, management)
- All three-column ownership split (Vishnu owned / shared / engineering)
- All four current limitations
- All faculty tracking and intervention signals
- Career roadmap flow (5 steps)
- AI interview rationale (voice over text)
- All validation and demonstration ownership statements

---

### Claims softened or clarified

| Original | Updated |
|----------|---------|
| "Colleges Discovered" (stat label) | "Colleges Researched" |
| "The roadmap adapts based on progress" | "Current personalisation is structured and rule-based, not dynamically adaptive" |
| No explicit scope caveat on discovery | Added: "Discovery was a shared team effort. My ownership was synthesis, problem definition and requirements." |

---

### Visual evidence still required

All items are in PATHWISSE_SCREENSHOT_CHECKLIST.md. In summary:

- Research artefact (Section 03) — highest priority; demonstrates the discovery claim
- Faculty tracking view (Section 06) — validates the intervention-signal claim
- Student dashboard (Section 06) — validates the roadmap and practice claims
- HOD and Management dashboards (Section 06) — validates institutional visibility claims
- Acceptance criteria artefact (Section 08) — validates the UAT ownership claim
- Career roadmap and roadmap-progress screens (Section 09)
- Practice Labs and AI interview screens (Section 10)

---

### Files modified

- `pathwisse.html` — full restructure
- `index.html` — Pathwisse card description, key-decision line, stat order, CTA text
- `PATHWISSE_SCREENSHOT_CHECKLIST.md` — updated to match new section numbers
- `PATHWISSE_CASE_STUDY_CHANGELOG.md` — created (this file)

---

### Unresolved content questions

1. **Research artefact**: A sanitised stakeholder map, interview guide or insight board would significantly strengthen the discovery claim. Does any shareable artefact exist?
2. **AI interview evaluation stage**: The case study says "early-stage." If evaluation quality has improved significantly since writing, the limitation wording may need updating.
3. **Opportunities layer status**: The case study says "not fully mature." If the layer has launched or expanded since writing, this limitation should be updated.
