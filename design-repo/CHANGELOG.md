# Changelog

## 0.2.0 — 2026-10-07 (review punch list)
- **Asset roles:** third-party marks (Notion, Salesforce, Harvard, HubSpot, McKinsey and the app tiles Gmail, Slack, Linear, Granola, Photoshop, Google Meet, Zoom, Finder, DoorDash, Ashby, Qatar) were filed under `logo` (must-reuse-exact). 16 assets and the sections that show them now use `customer-logo` (must-not-fabricate); `logo` (2 assets) is Merlin's own mark only. `verify_all.py` now rejects a `logo` outside the own-brand sections.
- **Templates:** `template.blog-2` -> `template.blog-post` (lists all 20 routes; `routesTruncated` removed), `template.group` -> `template.legal`. `verify_all.py` checks each template's routes equal the ledger's routes for it (1:1, checkable from design-repo/ alone).
- **Sections:** `content.site-container` was a catch-all (24 inner-page header containers plus the whole pricing body). It is now `shell.page-nav` (nav + brand mark), and pricing has `commerce.pricing-plans`, `features.pricing-included`, `support.pricing-faq`. 22 sections.
- **Purposes:** every section purpose is authored from its measured copy (`purposeIsInferred: false`, `purposeBasis` says how). Categories corrected (PROOF, COMMERCE, FEATURES, SHELL); ids keep their original prefixes.
- **Examples:** a real-copy PageSpec for every template in `schema/examples/` (all validated by the real semantic validator in `verify_all.py`). The skip-link now carries its label and anchor.
- **Responsive:** 7 sections that had `changes: []` now list the `@media` rules found in the stylesheets.
- **Motion:** the source does use `prefers-reduced-motion` (13 of 17 stylesheets). Each section's `motion.reducedMotionEvidence` says measured / site-wide / contract-default; hero and manifesto fallbacks are `instant-state` (measured). No Rive/Lottie/canvas exists in the source.
- **Ids:** section ids now carry their category prefix (`shell.skip-link`, `proof.used-by-professionals-at`, `features.routines|browser|meetings|companion|privacy|merlin-in-your-everyday`, `commerce.pricing-plans`).
- **IA:** `ia.json`, `IA.md` and `matrix.csv` are reconciled with the design-repo (22 sections, new categories, all 20 blog-post routes).
- **Drift proofs:** `prove_drift.py` now covers 21 injections (logo role, dropped route, missing/invalid example added).

## 0.1.0 — 2026-10-07T11:14:27Z
- Initial extraction from https://www.merlin.computer//: 19 sections, 7 templates, 27 routes.
