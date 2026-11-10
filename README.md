# IRICH — reviewable local alpha

Open index.html in a modern browser. Or serve this folder with Python: `python3 -m http.server 4173 --bind 127.0.0.1`. The local preview previously started in this chat uses http://127.0.0.1:4173/index.html#circles while its server is running. No build or dependency installation is required. Photographs load from Unsplash and require internet access.

## Review the updated journey

1. The opening shows the woven mark and a brief colour reveal once per browser session; Skip intro and reduced-motion preferences bypass it.
2. Open My circles. The ten-person Dublin group is an example, not an app-wide membership limit.
3. Create another group with 2–30 fictional members and a chosen whole-euro monthly contribution. This creates an independent draft without changing existing circles. The fixed demo due day is the 5th, beginning January 2027. A group of thirty has thirty monthly turns, ending June 2029.
4. Each fictional member privately ranks every payout turn and explicitly accepts that group's terms and simulated payment authorizations. Generate the disclosed deterministic demo draw, have each member accept the final schedule, then start.
5. For a quick review, load the clearly marked running demo fixture in Payout turns. This supplies invented consent records; it is not real consent.
6. Explore full-pot, pending, failed, under-review and post-grace late-payment scenarios. Only the scheduled recipient can choose an available short pot after grace. The missing contribution remains owed; a provider-style confirmation enables the remainder to settle to the same recipient.
7. Switch circles using the desktop selector or My circles link. The portfolio shows separate circles and a combined monthly commitment across active circles. This assumes one demo person participates in each active circle. Local invite codes open only circles already stored in that browser; no remote invitations are sent.
8. Inspect private reminder, simulated connection, authorization revocation and member-specific exit request in My space. These are simulated identity views, not secure accounts.

## Included now

Multiple independent circles; configurable membership 2–30; configurable initial contribution €1–€10,000 in whole euros; recalculated target and schedule; per-circle full rankings, terms/schedule consent and ledger; first-turn payment simulation; aggregate commitments; two illustrative people photographs; woven I + RICH wordmark; once-per-session intro; matching landing page.

## Explicit limits

This is an alpha prototype, not a finished financial service. No real money moves. Identities, authorizations, bank connections and transactions are simulated. No banking credentials are collected. IRICH does not claim to hold funds. Provider support and Irish regulatory status remain unconfirmed; no approval, partnership, protection guarantee or traction is claimed.

Only turn one executes payments. Later turns are schedule previews. Editing accepted terms, revised group membership, replacement approval, pause/resume and real provider discrepancy escalation are not interactive. Recurring debits are not executed; revocation records a simulated stop only. Production needs secure accounts/access controls, durable consent/audit records, independently auditable randomness, provider integration and appropriate regulatory/security/data-protection work.

Data is stored only in browser localStorage, using irich-circles-v2. Earlier single-circle demo state is migrated if available. Reset demo resets only the selected circle. Storage is not tamper-resistant or private between people using the same browser. The 30-member cap is a provisional prototype product choice. No fixed limit on number of groups is asserted; browser storage remains finite.

## Verification

Functional harness checks passed for cap validation, two-/thirty-member group creation, dynamic amounts and end dates, full rankings and individual consent, unique turn allocation, payout isolation during group switching, partial payment and remainder, per-circle persistence and all five generated app views. HTML local assets and SVG validate. This does not verify actual browser rendering, image delivery, clicks, touch, animation timing, mobile overflow or screen-reader behavior. Browser-control connection has been unavailable. Nothing is publicly published.

See RELEASE-REVIEW.md for the latest implementation status. Earlier review notes document prior revisions and are superseded where this release adds multiple groups or configurable amounts.
