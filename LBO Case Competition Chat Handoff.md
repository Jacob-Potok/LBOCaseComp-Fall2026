# LBO Case Competition — Chat Handoff

This file carries the useful information and decisions from the Codex task [Support LBO case competition](thread://01a0cb5a-818c-70a2-b434-c20fed9e864f?hostId=local) into this project. It consolidates the discussion and links the original case materials stored alongside it.

## Case materials in this project

- [Fall 2026 LBO Build Guide.pdf](Fall%202026%20LBO%20Build%20Guide.pdf)
- [Fall 2026 LBO Kickoff Presentation.pdf](Fall%202026%20LBO%20Kickoff%20Presentation.pdf)
- [Fall 2026 LBO Model Template.xlsx](Fall%202026%20LBO%20Model%20Template.xlsx)
- [Fall 2026 LBO Flash Memo Template.pptx](Fall%202026%20LBO%20Flash%20Memo%20Template.pptx)
- The earlier task also referenced `/Users/jpotok34/Downloads/stream.html`, a saved SharePoint player page for the kickoff video. It is not present in this project. Its saved HTML contained player metadata and a transcript endpoint, but not transcript text; the kickoff presentation PDF was judged to capture the substantive presentation content.

## Competition requirements and timeline

The prior review of the kickoff presentation and build guide identified these requirements:

- Select a public target with enterprise value between **$500 million and $10 billion**.
- Excluded industries: **utilities, commodities, REITs, healthcare, and telecommunications**; previously used competition targets are also excluded.
- Build **three historical years** and **five forecast years**.
- Support growth, margins, capital expenditures, working capital, valuation, and financing assumptions with evidence.
- Include a coherent downside case and sensitivity analysis.
- If leverage exceeds **5.0x EBITDA**, complete five additional tests specified in the build guide.

Milestones shown in the kickoff materials:

| Date | Deliverable |
|---|---|
| October 2, 2026 | Proposed company due |
| October 23, 2026 | Flash Memo due |
| November 6, 2026 | Semifinal; 8–10 slides |
| November 9, 2026 | Final Four announcement |
| November 13, 2026 | Final in New York City |

## Model template review

The workbook has `Read Me First` and `LBO Model` tabs. The previous review found 809 formulas, no cached formula errors, all built-in calculation integrity checks passing, and `Decision Readiness` still at `NEEDS INPUT` because illustrative company data remains.

Template conventions and mechanics:

- Editable inputs use blue text and yellow fill; gray cells contain fixed SOFR assumptions.
- First-lien loan: seven-year maturity at SOFR + 375 bps.
- Mandatory amortization: 1% annually based on original principal.
- Optional senior notes; no interim sponsor distributions.
- Retained cash is added to exit proceeds.
- Simplified cash-tax treatment; no NOL carryforwards.
- Iterative calculation handles interest and debt balances.

Illustrative outputs (not a target-company case):

- Entry enterprise value: **$1.2 billion**; entry multiple: **10.0x**.
- Gross debt: **$835 million**; sponsor equity: **$412.5 million**.
- MOIC: **2.17x**; IRR: **16.7%**.

The Flash Memo template has four suggested sections: (1) company overview, financial summary, thesis, and transaction rationale; (2) segments, customers, and geographic revenue; (3) short-form LBO and returns; (4) optional technology/value-creation slide. Its charts and tables are not linked to Excel, so figures need manual updating and reconciliation.

## Company screening and recommendations from the chat

The screening criteria were eligibility, EV, recurring or resilient revenue, cash generation, debt capacity, operational improvement, and a credible five-year exit. The conversation encouraged creative ideas as well as conventional LBO targets.

### Initial ranked shortlist

| Rank | Candidate | Ticker | Approx. EV cited in chat | Angle / caveat |
|---:|---|---|---:|---|
| 1 | Alarm.com | ALRM | $2.7B | Recurring software and licensing; valuation and growth runway require scrutiny. |
| 2 | Brady Corporation | BRC | $3.8B–$4.2B | Strong cash conversion and traditional LBO profile; recently completed a sizable acquisition. |
| 3 | Vontier | VNT | $6.2B | Deleveraging and operational improvement; industrial cyclicality and slightly declining Q2 sales cited as risks. |
| 4 | H&R Block | HRB | $6.4B | Low valuation and cash generation; tax-season working-capital and debt timing make modeling harder. |
| 5 | Dolby Laboratories | DLB | $4.9B | High-margin licensing and cash balance; growth/expense-reduction thesis needs evidence. |
| 6 | StepStone Group | STEP | ~$6.5B | Fee-related growth; financial-services eligibility is a major open issue. |

Other names considered during broad screening included Mister Car Wash, Bright Horizons, and ePlus; the available discussion did not establish them as final recommendations.

### Candidate detail preserved from the discussion

**Alarm.com — strongest blend of recurring revenue and growth in the initial screen.** It sells a B2B2C platform through professional service providers, rather than competing as a direct-to-consumer hardware brand like Ring, Nest, or SimpliSafe. Provider-installed systems create a service-provider relationship and recurring SaaS/licensing economics. The prior answer cited SaaS and licensing at about 68% of 2025 revenue, three-to-five-year provider/customer contracts, and Q2 2026 SaaS/license growth of 11.1%. Growth avenues mentioned: commercial access control/video/intrusion, multifamily, energy, gunshot and water management, fleet/vehicle management, international expansion, and commercial fire. A July 2026 commercial fire communicator launch was cited. Thesis: cross-sell products and verticals, expand commercial/international, improve sales productivity, and use recurring cash flow to repay debt. Main concern: at roughly $2.7B EV and ~16x EBITDA, it is not a bargain; avoid pitching it as a consumer camera share-taker. In the later answer, the recommendation was downgraded: strong business, but not necessarily the best target unless the team can defend the differentiated commercial/platform runway.

**Brady Corporation — best traditional LBO candidate in the initial screen; later ranked #1.** Sells identification, safety, connectivity, and productivity products embedded in customers' processes. The chat cited FY2026 sales of $1.66B (+9.8%), operating cash flow of $244M (nearly +35%), and management FY2027 adjusted EPS growth guidance of about 23% at midpoint. The thesis: integrate the Intelligent Productivity Solutions acquisition, improve procurement/manufacturing and margins, cross-sell, pursue bolt-ons, and direct free cash flow to debt paydown. Caveat: recent major acquisition makes historical results less representative and requires pro forma work. Later relative ranking called Brady the strongest conventional LBO and cash-flow case.

**Vontier — strongest operational improvement/deleveraging case.** A provider of fueling, payment, mobility, and convenience-retail technology. The chat cited Q2 2026 adjusted FCF of $97.6M, 79% FCF conversion, LTM adjusted EBITDA of $714M, 2.3x net leverage, and ~$1.64B net debt. Thesis: portfolio rationalization/restructuring, margin improvement, shift toward software/payments/services, and debt reduction (the prior answer suggested moving below 1.0x). Risks: industrial cyclicality, Q2 sales decline, and reliance on execution rather than organic growth alone.

**H&R Block — creative cash-flow/undervaluation case.** The chat cited FY2026 revenue growth of 5%, operating cash flow growth of 23%, and $714M returned to shareholders. Growth drivers cited were higher average fees, company-owned tax-preparation volume, international revenue, and Wave subscriptions. Thesis: grow Wave subscriptions/payments and year-round services, cross-sell financial products, trim low-return spending, and use seasonal cash to pay down debt. Key modeling risk: cash generation is concentrated in tax season; debt and interest mechanics need careful timing.

**Dolby Laboratories — creative high-margin licensing case.** The discussion described over 90% of revenue as licensing, FY2025 licensing revenue around $1.25B, operating cash flow of $472M, Q3 FY2026 gross margin around 88%, and minimal debt with a substantial cash balance. Thesis: moderate leverage, expand Atmos/Vision in automotive, gaming, music, and mobile, and pursue licensing partnerships. The chat identified possible risk around market maturity and the need to establish credible operating improvements. Verify the exact case for leverage and growth before choosing it.

**StepStone Group — conditional candidate.** Attractive growth and recurring fee economics were noted, but financial services may be excluded by the rules. Resolve eligibility with the competition rules before spending time on it.

### Later relative ranking

After the user challenged Alarm.com’s growth story versus Ring, SimpliSafe, and Nest, the chat revised the relative ranking to:

1. **Brady Corporation** — strongest traditional LBO and cash-flow case.
2. **Vontier** — strongest deleveraging and operational-improvement case.
3. **H&R Block** — strongest undervaluation case.
4. **Alarm.com** — strongest recurring-revenue case, but less obvious growth runway.
5. **StepStone** — attractive only if financial services are allowed.

The chat's bottom-line recommendation was to keep Alarm.com on the list but not choose it without a convincing case for commercial/platform differentiation. Brady emerged as the leading conventional recommendation, subject to acquisition pro forma analysis.

## Source links cited in the previous research

These are the sources referenced in the screening discussion; refresh them and verify all figures/as-of dates before using them in a submission.

- [Alarm.com 2025 10-K](https://www.sec.gov/Archives/edgar/data/1459200/000145920026000005/alrm-20251231.htm)
- [Alarm.com Q2 2026 results](https://investors.alarm.com/news-releases/press-release-details/2026/Alarm-com-Reports-Second-Quarter-2026-Results/default.aspx)
- [Alarm.com commercial fire announcement](https://investors.alarm.com/news-releases/press-release-details/2026/Alarm-com-Expands-into-Commercial-Fire-with-New-Fire-Communicator/default.aspx)
- [Brady FY2026 results](https://investors.bradycorp.com/news-releases/news-details/brady-corporation-reports-2026-fourth-quarter-and-record-full)
- [Vontier Q2 2026 results](https://investors.vontier.com/press-releases/press-releases-details/2026/Vontier-Reports-Strong-Second-Quarter-Results-and-Raises-Full-Year-Adjusted-EPS-Guidance/default.aspx)
- [H&R Block FY2026 results](https://investors.hrblock.com/news-releases/news-release-details/hr-block-reports-fiscal-2026-results-and-enters-fiscal-2027)
- [H&R Block financial ratios](https://stockanalysis.com/stocks/hrb/financials/ratios/)
- [Dolby FY2025 results](https://investor.dolby.com/news-events/financial-news/news-details/2025/Dolby-Laboratories-Reports-Fourth-Quarter-and-Fiscal-Year-2025-Financial-Results/default.aspx)
- [Dolby Q3 FY2026 results](https://investor.dolby.com/news-events/financial-news/news-details/2026/Dolby-Laboratories-Reports-Third-Quarter-2026-Financial-Results/default.aspx)
- [Dolby valuation statistics](https://stockanalysis.com/stocks/dlb/statistics/)

## Open work / next decisions

1. Confirm target eligibility, including prior competition targets and any interpretation of financial services.
2. Choose the target (Brady was the latest leading conventional pick; Alarm.com remained conditional; Vontier and H&R Block offered distinct alternatives).
3. Refresh public-market EV, debt, cash, EBITDA, and trading multiples as of the actual proposal date.
4. Build an evidence-backed three-year historical/five-year forecast and downside case; replace all illustrative workbook data.
5. Reconcile the Excel model and manually update the Flash Memo figures from the final model.

## Context and limits

This handoff captures the substantive findings, recommendations, and cited sources visible in the referenced task. Figures were reported as research snapshots from that conversation and should not be treated as current or independently re-verified here. The original task also included exploratory searches and workbook/template inspection; this file consolidates the useful outcomes rather than reproducing internal tool traces or hidden reasoning.
