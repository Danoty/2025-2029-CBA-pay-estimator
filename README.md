# KUSU PayLens 4.1 — A simpler way to explore CBA pay

**Prepared by Eng Dan Otieno | ICT Expert**  
**DEMO · UNOFFICIAL ESTIMATE** — Not certified or endorsed by KUSU, IPUCCF, the Ministry, KRA or another body.

A modern, standalone, mobile-friendly website for Grades 5–15 under the 30 October 2026 Return-to-Work Formula. Use the **three-step guided calculator** in Simple View or switch to **Expert View** for payslip reconciliation, promotions, salary timelines, net-pay illustrations and arrears tracking.

## Publish on GitHub Pages
1. Extract the ZIP. Upload `index.html`, `.nojekyll`, `manifest.webmanifest`, `sw.js`, icons, and the `sources` folder directly to your repository root.
2. GitHub repository → **Settings → Pages** → Deploy from a branch → `main` → `/(root)`.
3. Visit `https://YOUR-USERNAME.github.io/YOUR-REPO/` once deployed.
4. When replacing an old version, commit all changed files together. Refresh the page if your browser has the previous offline version cached.

## Understanding the numbers
- Salary figures: Schedule I, PDF pp. 9–14, 2024/25 reference and revised annual basic salaries, Grades 5–15, notches 1–12.
- Leave allowance: Schedule II, PDF p. 8. Shown **annually**, not added to the regular monthly gross.
- Commuter allowance: target KSh 18,000 per month for Grades 5–15. Some universities may phase increases. Default is an **assumption**, not the member's verified allowance.
- Diagonal movement: annual increment advances a notch (up to 12), and each July moves to the next CBA salary column. Promotions require checking appointment letters.
- Arrears: calculated month by month using the salary schedule and entered/assumed actual basic paid; actual payments reduce the balance. **No future months are included in accrued arrears**. Payment schedule is indicative and allowance arrears are not included.
- Optional net-pay calculations illustrate 2026-era statutory rules; these may change and must be verified against current official guidance and payroll.

## Privacy and limitations
The app is a static client-side page with **no account, analytics, or server-based salary processing**. Entered details are used in the active browser session and are not automatically sent to a server. WhatsApp sharing happens only if clicked; salary details are excluded by default. Members should not upload payslips or personal identifiers.

The site includes a copy of the signed agreement in `sources/` so members can cross-check. Remove that file if you do not wish to republish it publicly, and update source links in `index.html` accordingly.

## Files
- `index.html`: single-file webpage and calculator (no external libraries).
- `sw.js`, `manifest.webmanifest`, `icon.svg`, `icon-192.png`, `icon-512.png`: optional install/offline support.
- `.nojekyll`: GitHub Pages compatibility.
- `sources/Return-to-Work-Formula-30-Oct-2026.pdf`: reference source document, not evidence of endorsement.

For a quick local preview, open `index.html` in a browser. For service-worker/offline testing, serve via HTTPS or localhost.


## v4.1 notch selection correction

Quick mode (default): enter the grade and notch for the selected pay month. The calculator uses that notch exactly. It does not calculate historical arrears. Historical mode: enter the grade and notch at 30 June 2025, plus the increment month; the model advances notches in each subsequent increment month for the monthly CBA and arrears scenario. Example: starting notch 3 in June 2025, October increments result in notch 4 in October 2025 and notch 5 in October 2026. Do not confuse the resulting projected notch with the notch originally entered.
