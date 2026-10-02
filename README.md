# AI Use Case Register — clickable prototype

Validation-sprint prototype for an **operational evidence layer for employment AI**
(Paperclip issue GOM-19, parent GOM-12). Shown in the last ~12 minutes of a discovery call,
after the sample evidence pack.

**Open `index.html`.** It is a single self-contained file — no build, no backend, no tracking.

## What it is

Seven screens in one click-through path:

1. **Register** — every AI system touching an employment decision, with owner, entity, decision role, indicative risk, evidence completeness, next review.
2. **Use case detail** — the structured register entry, with *decision role* as the spine of the record.
3. **Triage** — six plain-language questions; each answer shows the provision it relies on and an **indicative** result that only a named human can confirm.
4. **Evidence checklist** — 12 controls: evidenced / partial / missing, with owner, document, last verified, next review.
5. **Gap dashboard** — gaps across all use cases by severity, with named owners and target dates.
6. **Export** — generate the evidence pack: what is included, gaps flagged, timestamp, rule-pack version.
7. **Activity history** — the append-only chain of who decided what, and when.

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
