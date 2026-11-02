# KUSU PayLens Pro — Independent CBA Estimator

**Version 2.0 (2 November 2026)**

Independent GitHub Pages web app for KUSU Grades 5–15, 12 notches each, using the Return-to-Work Formula dated 30 October 2026. The salary tables originate from the uploaded schedule, not from public APIs.

## Publish on GitHub Pages

1. Create a public repository (for example `kusu-paylens`).
2. Upload **all** files from this folder to the repository root, including `index.html`, `.nojekyll`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `icon-192.png`, and `icon-512.png`.
3. GitHub **Settings → Pages → Deploy from a branch → main → /(root)**.
4. Publish the URL in `https://USERNAME.github.io/kusu-paylens/` format.
5. Existing deployment: replace all old files, then hard-refresh or clear the site's offline cache if an old version persists.

## Features

- Grade/starting-notch, increment-month diagonal salary movement and effective CBA-year rates.
- Optional promotions/exit date and a selected-month scenario.
- Responsive gross pay dashboard, commuter/leave allowances and optional statutory deduction scenario.
- Payslip-vs-schedule reconciliation using an optional actual basic-paid input.
- Month-by-month actual basic-paid editing for historical reconciliation.
- Arrears payment tracker for three 2025/26 instalments and Jan 2027 settlement; payment amounts are **user-entered only**.
- Accurate **accrued-to-current-month** basic differences separate from future projections.
- Calculation explanations, print-to-PDF report, CSV timeline export.
- Privacy-safe WhatsApp sharing. The salary figures are excluded by default; the user can opt in. Opening WhatsApp intentionally sends the message to WhatsApp.
- Installable/offline-capable after the first visit. No backend or remote scripts.

## Important limitations

This site is a **DEMO / UNOFFICIAL ESTIMATE**. It is not endorsed by KUSU, IPUCCF, the Ministry, KRA or any other body. It does not establish legal entitlement, grades or salary payment dates. The commuter allowance is a target of KSh 18,000/month with allowed phased transition. Allowance arrears, tax on arrears, personnel exceptions and all employer-specific interpretations are excluded. Optional 2026 net-pay assumptions are not a certified tax computation.

The app does **not automatically transmit form data**. Values are held in memory while the page stays open, not persisted. Clicking WhatsApp sends the message you approve to that external service. Clicking external sources opens those external sites.

Prepared by **Eng Dan Otieno | ICT Expert**.
