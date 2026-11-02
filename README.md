# KUSU 2025–2029 CBA Pay & Arrears Estimator

**Independent demonstration • GitHub Pages ready • Prepared by Eng Dan Otieno | ICT Expert**

This is a static, single-page salary and arrears **estimator** for KUSU staff in Kenyan public universities using the salary and allowances schedules in the **KUSU Return-to-Work Formula signed 30 October 2026**. It is **not** an official KUSU, government, employer or KRA tool.

## Publish using GitHub Pages

1. Create a GitHub repository, e.g. `kusu-cba-estimator`.
2. Upload `index.html`, `.nojekyll` and this `README.md` to its **root** (not a nested folder).
3. Commit changes to the `main` branch.
4. Repository **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
5. Use `https://YOUR-USERNAME.github.io/kusu-cba-estimator/` after Pages publishes it.

No installation, dependencies, server, database, API keys or build tools are needed. The form's inputs stay in the current browser session and are not uploaded or stored on a server. You can use **Copy estimate**, **Print** and **CSV export** from the page.

## How to use

- Choose the grade (5–15) and notch (1–12) held on **30 June 2025** and the normal increment month. A July increment moves the employee to the next notch when the 2025/26 schedule begins; future increment months move one notch per year, up to Notch 12.
- Pick a month between July 2025 and June 2029 to inspect the scheduled gross pay.
- Set the month your employer **first paid the new basic rate**, or leave it blank to model continued use of the reference basic. This does not alter the official July 2025 schedule effective date.
- Optionally add up to two promotions using the grade/notch stated in the promotion decision, and an employment end month.
- Enter current and assumed commuter amounts, house and other regular allowances. Commuter **KSh 18,000 per month** is a target in the agreement, subject to a three-year progressive transition at universities currently paying less. Annual leave is a separate once-per-year entitlement.
- In the month-by-month table, enter the **actual basic salary received** where known. Overrides take precedence over the first-paid-month and reference-scale assumptions.
- The arrears section shows July 2025–June 2026 and July–December 2026 separately. Any extra post-December-2026 amount is a **future scenario**, not already-accrued arrears. Previously paid basic arrears are deducted from the estimated balance. Leave and commuter arrears are excluded.
- Optional net pay uses an **approximate November 2026 Kenyan statutory-rate scenario**. Pension rate, union dues, NSSF and other payroll deductions are individual choices. These rates are not guaranteed for future years and do not model tax on arrears.

## Independent disclaimer displayed on the page

**Demo · Unofficial estimate.** Not certified or endorsed by KUSU, IPUCCF, the Ministry, the Kenya Revenue Authority (KRA) or any other body. No data is transmitted to a server. Validate your entitlement with your employer, payslip and the signed CBA documents.

## Sources / scope

- Primary KUSU source: *Return-to-Work Formula*, 30 October 2026, Salary Schedule I (pages 9–14 of user-provided scan) and revised allowances (page 8). **KUSU salary and leave rates are transcribed into `index.html`.**
- Comparison reference: [academic-staff CBA estimator](https://kagiricharles2010.github.io/cba-estimator/) (functional comparison only). The KUSU site does **not** assume that UASU-specific academic allowances apply to KUSU.
- Official PAYE rates and relief: [KRA PAYE](https://www.kra.go.ke/individual/filing-paying/types-of-taxes/paye)
- Official Affordable Housing Levy: [KRA](https://www.kra.go.ke/news-center/public-notices/2099-collection-of-the-affordable-housing-levy-by-kenya-revenue-authority)
- NSSF contribution notice: [NSSF Year Four (2026)](https://www.nssf.or.ke/notice-to-employers-year-4-2026-nssf-contribution-rates)
- SHIF: [Social Health Authority](https://sha.go.ke/)

### Important calculation limitations

- The agreement is not an individual payslip or a certified payroll instruction. Grade/notch history, prior increases, pension scheme rules and contractual terms must be verified.
- Reference salary comparisons use each month’s grade/notch at the **2024/25 Schedule I rate**, unless you enter actual salaries. This comparison is particularly limited following **promotion**, where real old payroll may be higher or lower.
- The tool does not predict when treasury funds will arrive, impose a deadline for payroll implementation or automatically calculate allowance arrears.
- PAYE is a simplified individual resident scenario with standard KSh 2,400 monthly relief, KRA banding, and tax allowances for SHIF, Housing Levy and qualifying retirement contributions to a combined KSh 30,000 monthly cap. It excludes personal tax exemptions, mortgage interest, special reliefs and variable payroll adjustments. Pension and NSSF scheme participation must be set correctly by each user.
- NSSF is estimated optionally at 6% of regular gross with a KSh 6,480 employee cap (2026 Year Four). Actual pensionable wages and transition years may vary.
- Data isn't transmitted by the calculator, but GitHub may log normal web traffic to the published page under its own service practices.

## Author credit

**Prepared by Eng Dan Otieno | ICT Expert**
