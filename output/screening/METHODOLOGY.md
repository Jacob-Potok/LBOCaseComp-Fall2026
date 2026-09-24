# Capital IQ FCF Conversion Screen — UConn Fall 2026

This document defines the reproducible screen for the UConn Fall 2026 LBO Case Competition.

## Universe

- Public operating companies with current enterprise value of **$500 million through $10 billion inclusive**.
- Exclude utilities, commodities companies, REITs, healthcare, telecommunications, other highly regulated sectors, and the prior competition targets listed in the Build Guide (page 23).
- Resolve duplicate listings to one Capital IQ company ID and retain the primary listing.
- Record industry taxonomy, country, exchange, ticker, EV date, extraction timestamp, and every exclusion reason.

## Metric convention

Use Capital IQ historical actuals and the standardized LTM EBITDA field. Use matched-period cash-flow components:

`FCF = cash flow from operations - capital expenditure paid`

Capital expenditure is treated as a positive cash outflow. The ranked metric is:

`FCF Conversion = FCF / EBITDA`

Use USD millions and one FX basis for all flow metrics. Do not substitute adjusted EBITDA, estimates, EBIT, or EBITA. Missing values remain missing; EBITDA at or below zero is retained in the audit table but excluded from the ranked conversion list.

## Period policy

Use the most recent completed LTM period available at extraction, with identical period dates for EBITDA, CFO, and CapEx. Record the exact Capital IQ field labels, period dates, reporting currency, FX setting, and source filing date. If standardized LTM data is unavailable, show a separately labeled FY fallback; do not blend LTM and FY observations.

## Review and audit

Apply industry and prior-target exclusions at company level after the Capital IQ EV/public-company prefilter. Keep an audit row for every exported company, including excluded, incomplete, and unresolved cases. Review unusually high conversions for small EBITDA denominators, working-capital releases, cash-tax effects, unusual CapEx, acquisitions, discontinued operations, and lease classification.

Sort eligible matched-LTM rows by FCF Conversion descending, then company name and Capital IQ company ID for deterministic ties. Report row counts before and after each filter.

## Data handling

Capital IQ exports are licensed vendor data. The connected GitHub repository is public, so raw exports and derived company-level rankings remain local unless repository visibility is changed or publication is otherwise authorized. This repository change contains methodology and status only.
