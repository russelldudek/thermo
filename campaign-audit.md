# Campaign audit

Campaign state: source complete; live exact-head verification pending after clean `main` publication.

Root causes repaired:

1. The previous public `main` branch contained staging placeholders and no `index.html`, so there was no deployable site tree.
2. The prior resume route omitted `brand-tokens.css` while the shared stylesheet depended on those variables.
3. The report routes repeated page-level H1 elements, the entry-plan scorecard overflowed at mobile width, and the scenario reset existed in code but not as a visible control.

Corrections: atomic full-tree publication; all six routes explicitly load both stylesheets; official wordmark above the fold; one semantic H1 on every route; visible resettable smart RAG starting state; keyboard-operable scenarios; complete reduced-motion treatment; responsive document reflow; mobile scorecard recomposition; exact 2/1/3/3/1 PDF package; no fragile secondary image dependency.

QA: 29 rendered states covering six routes across desktop, laptop, tablet, and mobile, a desktop interaction loop, and four reduced-motion states. Checks included stylesheet requests and resolved variables, official identity loading, horizontal overflow, screen-document clipping, runtime errors, scenario click/reset/keyboard behavior, links, and PDF availability. All ten PDF pages were rasterized and visually inspected.

Candidate-facing confidentiality: passed. Forbidden internal-name matches: 0.
