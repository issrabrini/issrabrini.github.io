# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Existing static site: a single `index.html` (inline CSS and JS) served from GitHub Pages at issrabrini.github.io. Real WebGL 3D via three.js loaded from a CDN, kept as a static page with no build step. Confirmed by the user.

## Users

Recruiters and engineering hiring managers, mainly in Paris, screening candidates for a 6-month end-of-studies AI/ML engineering internship starting January or February 2027. They skim quickly, often on a laptop between other candidates, sometimes on a phone from a LinkedIn or email link. Their job in the first seconds: see what this person has built and open one project to judge it.

## Product Purpose

Personal portfolio of Isra Brini, software-engineering student at INSAT Tunis specializing in AI. It exists to win an internship interview. Success: a recruiter sees the projects immediately, opens at least one case study, and then downloads the CV or emails.

## Positioning

A student who has shipped agent systems in industry (Neoxam: a deployed AI skill that migrates test suites; a RAG assistant with citations) and who explains each project as a problem, a build and a measured result. The proof is in the metrics and case studies, not in claims.

## Operating Context

Visitors arrive through tracked links (`?ref=...`) sent to specific companies; light analytics post to a Google Apps Script URL (currently empty). Each project opens in a full case-study dialog (problem, what was built, replayable pipeline flow, metrics, stack, GitHub/demo links, prev/next).

## Capabilities and Constraints

- Six projects: Juriq (featured), Respiratory sound classification, Plant disease detection, SmartSight, Social media trend analyzer, Mentora.
- Existing behavior to preserve: project dialog with deep-link hashes (`#juriq`), replay of the flow, prev/next, LINKS / IMAGES / TRACK_URL configuration blocks, `data-track` events, CV download at `cv/Isra_Brini_CV.pdf`.
- All copy, metrics, links and facts stay as written (user-confirmed). Nothing may be invented: no new metrics, employers, testimonials or demos.
- Contact: isra.brini@gmail.com, LinkedIn IsraBrini, GitHub issrabrini, +216 27 077 002.
- Languages shown: Arabic native, English C2, French B2, Korean A2.
- Screenshots (`IMAGES`) are empty today; the user has not supplied project imagery.

## Evidence on Hand

Real metrics for Juriq (4.59 → 2.63 workload spread, 60 → 72.7% expertise match, 5 → 1 overloaded professors), Respiratory sounds (0.68 → 0.75 sensitivity, 0.6610 composite), one live demo (SmartSight on Vercel), GitHub repos for all six, and a CV PDF. No project screenshots or videos exist; do not fabricate any.

## Product Principles

1. Projects before biography: the work is visible on arrival, not behind a scroll or a click.
2. Show the result, then the story: every project leads with its measurable outcome.
3. Only true claims: demonstration visuals may be illustrative, but facts and numbers are the user's own.
4. One clear path: open a project, then CV or email.

## Accessibility & Inclusion

Keyboard and screen-reader operable (cards are buttons, the dialog traps focus and restores it), respects `prefers-reduced-motion`, readable contrast on a light ground, 3D scene is decorative (`aria-hidden`) and the page must remain fully usable without WebGL.
