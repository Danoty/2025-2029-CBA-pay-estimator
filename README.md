# KUSU PayLens v3 — Easy CBA Pay Estimator (Unofficial Demo)

**Prepared by Eng Dan Otieno | ICT Expert**

A static, responsive CBA pay estimator for KUSU Grades 5–15. Easy 4-field calculator, result card, visual dashboard, payslip comparisons, payment tracker, promotions/departures, optional net-pay illustrations, printable report and CSV export. Salary and allowance figures are derived from the signed 30 October 2026 Return-to-Work Formula, which is included in `sources/` for reference.

## Publish on GitHub Pages

1. Create a repository or open your existing GitHub Pages repository.
2. Upload all files and the `sources` folder **without nesting them in another folder**. Keep `index.html` at the repository root.
3. Under **Settings → Pages**, select **Deploy from a branch**, **main**, and **/(root)**; save.
4. Visit `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/` after GitHub completes deployment.
5. When updating an existing site, upload all changed files (including `sw.js`) together; refresh or reinstall if the browser shows an old cached version.

## Important limitations

**DEMO · UNOFFICIAL ESTIMATE**. Not certified or endorsed by KUSU, IPUCCF, the Ministry, KRA, or any other body. Entries stay on the device; sharing through WhatsApp is initiated only by the user. Validate with employer payslips and the signed CBA. Salary arrears depend on actual monthly payments; allowance arrears are excluded. Full commuter of KSh 18,000 may be phased. Illustrative statutory net calculations are not authoritative and may need updating when legislation changes.

## Files
- `index.html`: Entire calculator, styling and scripts; no external libraries.
- `sw.js`, `manifest.webmanifest`, icons: optional install and offline-friendly app behaviour.
- `.nojekyll`: GitHub Pages convenience.
- `sources/Return-to-Work-Formula-30-Oct-2026.pdf`: reference signed agreement; not a sign of endorsement.

There is no backend, account, automatic storage or analytics. No salary inputs are transmitted automatically. The only outbound navigation is user-initiated links or sharing.
