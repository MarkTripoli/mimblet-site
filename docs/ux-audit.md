# UX Audit — Mimblet site

## User goals
- Parents/caregivers understand what Mimblet is (offline story library) and that no store links are available yet.
- Find support answers (offline use, sound/timer, reading, preferences).
- Verify privacy guarantees.

## Flows
- Home → The library section → availability note.
- Home → Support → topic TOC → answer sections.
- Footer → Privacy / Support / Report a problem.

## Friction points
- App lifecycle/status unclear: "Preparing for store release" only in hero; unclear what to do next.
- Support has no explicit escalation path beyond "Report a problem"; users with unlisted issues may stall.
- Skip link target focus handling should be verified across browsers.

## Recommendations
- Keep copy concise and aligned with privacy (no forms/tracking).
- Add escalation copy on Support footer pointing to GitHub issues/mailto.
- Document skip-link focus verification.

## Prioritized fixes
1. (P1) Add "Need something else?" escalation copy + mailto/issues link on Support footer.
2. (P2) Clarify release status messaging on Home.
3. (P3) Verify skip link focus behavior across multi-device checks.
