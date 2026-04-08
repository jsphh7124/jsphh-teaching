# PPT Creator - Pre-Flight Checklist

Use this checklist before running the quality rubric scoring. All items should be checked before delivery.

## Content Quality

- [ ] Goal and audience clearly defined
- [ ] Pyramid structure (conclusion → reasons → evidence) is complete
- [ ] Each slide has exactly one core idea
- [ ] All headings are assertion sentences (not topic labels)
- [ ] Evidence supports each assertion
- [ ] No slide exceeds 70 words (excluding captions)
- [ ] Transitions between slides are natural and logical

## Data & Visualizations

- [ ] Charts match the Chart Selection Dictionary recommendations
- [ ] All charts have complete labels (axes, units, sources)
- [ ] Data sources are cited in refs.md
- [ ] Placeholder charts clearly list required data fields
- [ ] No hard-coded random numbers in generated data

## Visual & Accessibility

- [ ] Text contrast ratio ≥ 4.5:1 (WCAG AA)
- [ ] UI element contrast ≥ 3:1
- [ ] Font sizes meet minimums (heading 34+, body 18+, footer 14+)
- [ ] Safe margins ≥ 48px maintained
- [ ] Images have alt descriptions
- [ ] Color palette is AA compliant
- [ ] Line spacing appropriate (heading 1.1, body 1.3)

## Speaker Notes

- [ ] Every slide has 45-60 second speaker notes
- [ ] Notes follow structure: opening → assertion → evidence → transition
- [ ] Language is natural and speakable
- [ ] Notes explain charts and data points
- [ ] Assumptions and defaults are documented

## Deliverables

- [ ] `/output/slides.md` exists and is properly formatted
- [ ] `/output/notes.md` contains complete speaker notes
- [ ] `/output/refs.md` lists all sources and citations
- [ ] `/output/assets/` contains generated charts (if applicable)
- [ ] PPTX export attempted (if python-pptx available)
- [ ] Reuse instructions appended to notes.md

## Technical Quality

- [ ] File paths are stable and consistent
- [ ] No external web scraping without permission
- [ ] Scripts only run when user provides data
- [ ] Fallback plans documented for missing dependencies
- [ ] All gaps and limitations explicitly marked

## Final Check

- [ ] Total word count appropriate for duration
- [ ] Slide count matches target (12-15 typical)
- [ ] No spelling or grammar errors
- [ ] Consistent terminology throughout
- [ ] Ready for RUBRIC scoring
