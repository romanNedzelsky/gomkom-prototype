# AI Use Case Register — clickable prototype

Validation-sprint prototype for an **operational evidence layer for employment AI**
(Paperclip issue GOM-19, parent GOM-12). Shown in the last ~12 minutes of a discovery call,
after the sample evidence pack.

**Open `index.html`.** It is a single self-contained file — no build, no backend, no tracking.

Mirrors rule pack `EU-EMPL-2026.10` and the sample evidence pack as corrected on 2026-10-07.

## What it is

Seven screens in one click-through path:

1. **Register** — every AI system touching an employment decision, with owner, entity, decision role, indicative risk, evidence completeness, next review.
2. **Use case detail** — the structured register entry, with *decision role* as the spine of the record.
3. **Triage** — six plain-language questions; each answer shows the provision it relies on, when that duty binds, and an **indicative** result that only a named human can confirm.
4. **Evidence checklist** — 13 controls: evidenced / partial / missing, with owner, document, last verified, next review, and the date each duty applies.
5. **Gap dashboard** — gaps across all use cases by severity, with named owners and target dates, separating gaps that are live today from readiness gaps against a future application date.
6. **Export** — generate the evidence pack: what is included, gaps flagged, timestamp, rule-pack version, dated applicability block.
7. **Activity history** — the append-only chain of who decided what, and when.

## Four obligation tracks, four dates

The register deliberately does not collapse these into one status. A `Partial` or `Missing` row on a
duty that is not yet in force is a **readiness gap**, not a duty contravened today, and the interface
says so on every row rather than leaving the viewer to infer it.

| Track | Applies |
|---|---|
| GDPR (Art. 5, 13, 22, 35) — controls C11, C12 | now |
| National works-council co-determination — BetrVG §87(1) No. 6 (DE), WOR Art. 27(1) (NL) — control C10 | now |
| AI Act Art. 5 prohibited practices, and the AI-literacy provisions — triage question 3 | now, since 2 February 2025 |
| AI Act Art. 50 transparency obligations | now, since 2 August 2026 |
| AI Act Art. 26 deployer duties for Annex III high-risk systems, and Art. 86(1) — controls C1–C9, C13 | **from 2 December 2027** |

The Digital Omnibus entered into force on 27 July 2026 and extended the Annex III high-risk
application date to 2 December 2027 (AI embedded in Annex I products: 2 August 2028). Sources are
cited in the interface itself, in the boundary strip under "Which duties bind today, and which do not".

## What it is not

- Not production UI and not a design system.
- Not legal advice, not a conformity assessment, no legal sign-off. That boundary is in the
  interface itself, not in a footer.
- No ATS/HCM integration, no bias-testing screens, no employee-level data, no billing.

## Fictional data

**Every organisation, person, system name and vendor in this prototype is invented.**
Names were checked against public company registries and web search to avoid collision with
real companies. The data mirrors the sample evidence pack produced in the same validation
sprint, so the two artefacts tell one consistent story.

Desktop-first; designed at 1280px or wider.
