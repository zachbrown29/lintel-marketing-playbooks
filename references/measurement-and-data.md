# Measurement and data

How a seed to Series B B2B software company decides what to instrument first, how far to trust attribution, what to show a founder, which metrics to run at each stage, how to hear customers, and how to keep data clean. For a marketer or founder who wants a specific next step.

**Owns:** data definitions and governance, tracking validation, data hygiene, dashboards for founders and boards, the limits of attribution and when to run a mix model, LTV and CAC payback math, cohort retention, first-party data and server-side tracking, when to buy a CDP, customer feedback systems, and the competitor and market research program.
**Does not own:** which marketing metrics and funnel to track (FW-FOUND-006). The CRM attribution model, such as sourced vs influenced pipeline and multi-touch weighting (FW-REVOPS-004). How UTM capture, MAP-CRM sync, lead scoring, and routing are configured, and why a number in a tool is wrong (FW-REVOPS-002). Which stack layers to have (FW-FOUND-007) and which vendor to buy (FW-OPS-003). NPS timing, detractor follow-up, and reading scores (FW-CX-004). Running win/loss interviews (FW-PM-006). Battlecards and live-deal responses (FW-PM-004). Competitive positioning (FW-FOUND-003). Pricing (FW-GROWTH-005). Legal review of consent and privacy (FW-OPS-002, and a lawyer).

**Benchmarks:** every number in the tables below is Lintel guidance unless a source is named in the Note column. Treat them as starting thresholds, not industry statistics.

## Data foundation: definitions, tracking, hygiene  (FW-DATA-001)

**When this matters:** Marketing and sales disagree on pipeline, lead counts, or attribution. Two reports give different answers for one metric. You plan to spend $50,000 or more on paid media with no validated event tracking. A CDP or warehouse evaluation is running and nobody can say what data goes in or who owns it. A big GTM change (new ICP, channel, or pricing) is coming.
**Skip it when:** Fewer than five programs run and one person holds all the data in their head. There is no budget and no paid programs. Sales and marketing are one person with one CRM. A CRM or MAP migration is underway. You are still finding product-market fit and strategy changes weekly.

**Where you are**
- Tier 1 Reactive: Data lives in whichever tool collected it. No dictionary, no canonical customer ID, inconsistent UTMs, and reports differ by who pulled them.
- Tier 2 Building: Core metrics have written definitions, UTMs are standardized by process, the CRM is the source for contacts and accounts, and quality is checked monthly by hand.
- Tier 3 Operating: A named owner with a charter, a full object taxonomy, automated quality alerts on critical fields, and a warehouse or BI layer that locks metric definitions.
- Tier 4 Compounding: CDP, warehouse, and reverse ETL, real-time quality monitoring, automated compliance, and the owned audience reported to the board.

**First build, in order**
1. Run a disagreement audit (3 to 5 hours). Pull the same metric from every system that reports it. Ask the marketing lead, head of sales, and top revenue person which number they use and why. The result is your list of what to define first.
2. Define the five highest-conflict metrics (4 to 6 hours). One 90-minute session with marketing, sales, and whoever runs the CRM. For each metric agree on what counts, which one system is the source of truth, and who owns it. Write it in a shared doc. That is dictionary v1. Five agreed definitions beat 50 nobody signed off on. At Tier 1 the usual five are pipeline, MQL count, conversion rate, CAC, and customer count.
3. Write a UTM naming rule (2 to 3 hours): lowercase, hyphens between words, no spaces, the same source and medium values everywhere. Build a Google Sheets builder that checks entries. Apply to new campaigns only, because fixing history costs more than it returns. (Capture and sync setup is FW-REVOPS-002.)
4. Name one data owner. About 20% of a marketing ops role. Not a committee.
5. Validate core tracking (2 to 4 hours). Confirm demo request, trial signup, and contact form events fire in every ad platform, web analytics, and the CRM, and that UTMs reach the CRM on every form submit. Fix before paid campaigns run. Repeat before every major launch and monthly, because tags break quietly.
6. Then: a tool inventory, the full dictionary, a written spec for every sync that says which system wins on a field conflict (the step most teams skip), a monthly quality audit, and a consent record on every contact (timestamp, source, type, scope) built before a law forces it.

**Decision rules**
- If marketing and sales cite different numbers, then ask five questions before touching tools. Which system does each come from? When did both teams last review the definition? Is the field free text or a picklist? Is the date filter the same? Do duplicates inflate one count? Definitions come before tools.
- If a Series B company has weak attribution, then check UTM coverage and attribution coverage before changing the model. If coverage is fine, check the window against the real sales cycle.
- If someone proposes a CDP or warehouse and there is no dictionary, then stop and write definitions. A warehouse on undefined data is an expensive database of bad records.
- If senior time on report reconciliation tops 4 hours a week despite working Tier 2 governance, then scope a warehouse and BI tool. Not before.
- If you sell product-led and track no product events, then wire them in first. If you do, define the product-qualified lead jointly with product and sales.
- If the attribution method changes every 6 to 12 months, then freeze it. Treat the method as a governance choice that marketing and sales agree on. Frequent swaps make sales distrust every number.
- If you enter the EU within 90 days, or you are a Series B or later health, fintech, or legal-tech company, then settle consent and data residency with counsel first.
- If you are hiring marketing ops or RevOps, then first have dictionary v1, a UTM rule in use, and a CRM named as the pipeline source, or their first 60 to 90 days go to definitions. Scope by tier: Tier 1 CRM admin and dictionary skills, Tier 2 warehouse, BI, and modeling, Tier 3 CDP and first-party activation.
- Staffing: fractional (10 to 20 hours a month) at Seed or early Series A. Full-time at Series A once paid media passes $500K a year and reconciliation eats senior time weekly. Consultants for one-offs only (dictionary v1 at 20 to 40 hours, a cleanup sprint, a warehouse build), never ongoing ownership.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Completeness of critical fields (lead source, lifecycle stage, company, size, industry) | 90%+ | Under 85% on lead source is high priority |
| UTM coverage on paid clicks | 95%+ | 90%+ for email. Misses show up as "Direct." |
| Closed-won deals with one or more marketing touches | 70%+ at Series A, 85%+ at Series B | Under 50% is a major tracking gap |
| Duplicate records | Under 2% good, over 5% systemic | Fix the source form or import |
| Consent record rate | 100% EU, 95%+ elsewhere | |
| Fix time for high-impact data issues | Under 5 business days | |
| Cost | Seed 4 to 8 hours a month, no tools. Series A 0.25 to 0.5 ops FTE and $1,500 to $4,000 a month. Series B 1 ops FTE plus 0.25 to 0.5 data engineering and $8,000 to $20,000 a month | |

**Where it goes wrong:** Declaring the CRM the source of truth while three people still pull pipeline from three places. Patching bad tracking with a hand-built spreadsheet. Marketing writing definitions alone, so sales never adopts them. Reading compliance advice from blog posts when a 30-minute legal review costs less than a mistake.

## Reporting a founder will actually read  (FW-DATA-006)

**When this matters:** Senior people spend over 4 hours a week assembling reports by hand. Leaders wait 24 to 48 hours for channel performance, pipeline contribution, or CAC to LTV. Stakeholders use reports that disagree. A board meeting or diligence round is close. A BI tool is installed and marketing ignores it.
**Skip it when:** The data foundation is not in place (a polished dashboard on undefined data breeds false confidence). You have under 3 active campaigns, 50 customers, or 6 months of history (a BI tool wants 3+ paid channels, 50+ customers, 12 months). The real gap is not knowing what to measure. A tool migration will change the sources.

**Where you are**
- Tier 1 Reactive: Manual exports pasted into spreadsheets, and everyone has a different number.
- Tier 2 Building: Five shared live reports (one source, one definition, one owner each), then three audience dashboards.
- Tier 3 Operating: A semantic layer that locks definitions, self-serve for marketing, sales, and CS, anomaly alerts, and a weekly digest.
- Tier 4 Compounding: Proactive alerts, written context next to numbers, and forecasts checked against actuals.

**First build, in order**
1. List the five metrics that cause the most disputes or ad hoc requests (2 to 3 hours). Ask which number causes confusion in meetings.
2. Write one paragraph per metric (2 to 4 hours): what it is, how it is calculated, the source system, the date filter. Get sign-off from the person who disputes it.
3. Build one live report per metric inside its source tool (4 to 8 hours). No BI tool and no multi-metric dashboards yet.
4. Send the five links to the CMO, finance lead, and sales head with the definition, update frequency, and a contact (1 hour). Sharing makes it the official source.
5. Judge BI only now. Buy one when all three hold: more than 3 sources feed one report, analysts spend over 4 hours a week assembling reports, and non-technical people need self-serve. Library picks: Metabase (lowest friction), Looker (best definitions layer, higher cost), Tableau (best visuals, higher cost), Looker Studio (free, thin definitions layer), Power BI (if you run on Microsoft). Check current prices. A solo marketer should use native CRM and MAP reports for 12 months and cap BI setup at 20 hours.
6. Build three dashboards, one per audience:
   - Marketing performance (the team): MQLs by channel against target, CPL by channel over 30 days, spend pace, MQL to SQL by channel, SQL to opportunity, opportunity to close by source. Spend and MQLs daily, conversion weekly.
   - Pipeline contribution (CMO, CRO, sales): marketing-sourced pipeline by month over 12 months, influenced share, pipeline by channel and stage, MQL-to-close by channel. Label every attribution chart with its method (for example "time-decay, 90-day window") or executives read it as proof of cause.
   - Unit economics (finance, board), five metrics only: LTV:CAC by segment with a 3:1 line, CAC by channel over 90 days, payback trend with an 18-month line, NRR trend with 100% and 110% lines, spend as a share of pipeline.
7. Build the board page last, with no more than 7 metrics. Four KPIs with red, amber, green status (green at or above target, amber 5 to 15% below, red more than 15% below): pipeline contribution, CAC against target, NRR against target, spend against budget. Add a 6-month trend of marketing-sourced pipeline and a 2 to 3 sentence note, written by a person, on the main pattern and what you are doing about it.
8. Add alerts when dashboards are stable. Start at plus or minus 20% from the trailing average, then tighten.

**Decision rules**
- If someone at Seed or Series A asks for a dashboard, then redirect to steps 1 through 4. The goal is ending the most frequent reporting fights.
- If marketing and sales cite different numbers, then it is a definition fight. Find whether the gap is a definition (what counts as an MQL), a source (HubSpot vs Salesforce), or a date filter (created vs closed).
- If the BI tool exists but marketing ignores it, then redesign around decisions. Ask the CMO for the three questions they ask most and make those answerable in 30 seconds.
- If a board or diligence round is coming, then show six items: marketing-sourced pipeline over 8 quarters, LTV:CAC by segment, CAC by channel over 12 months, NRR trend, cohort retention curves, and marketing spend as a share of revenue. Have the CFO confirm every number first.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Monthly adoption by intended audience | Over 70% operational, over 50% analytical, over 80% board summary | |
| Analyst time on recurring reports | Under 4 hours a week at Tier 2, under 2 at Tier 3, over 8 means failing | |
| Data freshness | Under 4 hours operational, under 24 hours analytical, under 7 days strategic | |
| Time for an executive to find the key number | Under 15 seconds | Over 30 means redesign |

**Where it goes wrong:** The everything dashboard (47 metrics sorted by data source, built for the person who collects data, not the one who decides). An attribution chart with no method label. A dashboard with no maintainer that goes stale. Alerts so sensitive that people ignore them.

## Attribution limits and when to model it  (FW-DATA-003)

Which attribution model to run inside the CRM belongs to FW-REVOPS-004. This block covers what attribution cannot tell you and when a mix model pays off.

**When this matters:** Spend is over $1M a year and allocation rests on first-touch or last-touch alone (single-touch credit overstates some channels and understates others). Privacy changes degraded tracking and you cannot trust ad platform dashboards. Leadership wants business-level proof and campaign reports cannot give it. You have 18+ months of steady spend and revenue data and a raise or board review is near.
**Skip it when:** Annual spend is under $500K (too little statistical power). You have under 12 months of consistent data. The real problem is broken tracking (a model on bad data gives confident wrong answers). The channel mix changes every quarter. You are at Seed or Series A with no analyst.

**Where you are**
- Tier 1 Reactive: Spend and clicks tracked by channel, first or last touch credit, and "we think LinkedIn works" as evidence.
- Tier 2 Building: Multi-touch credit (time-decay or linear), 18+ months of weekly data collected, and awareness the model has gaps.
- Tier 3 Operating: A mix model built, tested on held-out data, and used for at least one real budget move, plus incrementality tests on top channels.
- Tier 4 Compounding: Quarterly refresh on an automated data feed, incrementality tests twice a year, and results used at every budget cycle.

**First build, in order**
1. Build the weekly dataset (8 to 12 hours once, then weekly upkeep by one named owner). One row per week, 24 months if you can (18 minimum). Columns: spend by channel, the outcome (weekly closed revenue, or new pipeline if revenue history is short, and say so), and 1/0 flags for launches, pricing changes, and sales headcount moves over 10%. Investigate every missing week. This needs no modeling and is the most valuable artifact in the program.
2. Check readiness (4 to 6 hours). Divide each channel's weekly spend standard deviation by its mean. Under 0.2 means too little variation to estimate a response curve. Plot spend against outcome with 2-week and 4-week lags. At least two channels should have moved 25% or more, and three or more should each spend over $5,000 a quarter.
3. Pick the approach (2 to 4 hours). Open source first: Robyn (Meta, R-based) or Meridian (Google, Python-based). If nobody can run either, a managed service costs $30,000 to $100,000 for the first engagement.
4. Write the business questions with the CMO (2 hours), such as "Should we shift budget from display to LinkedIn?" Without them the model gets built and ignored.
5. Build and validate (40 to 80 analyst hours) with the event flags and a seasonality term. Hold out a recent period.
6. Apply gently. Act only on channels with narrow uncertainty ranges. Move 10 to 15% of budget from the lowest-ROI, most certain channels to the highest-ROI, most certain. Write down the prediction and check in 8 to 12 weeks. No sharp cuts in the first cycle.

**Decision rules**
- If you are at Seed or Series A, then do not build a mix model. Start the weekly dataset today.
- If spend is under $500K, then use correlation checks and incrementality tests on single channels.
- If spend is $500K to $1M, then build the dataset and run incrementality tests. Build the model above $1M with 24 months of data, or sooner with an analyst on staff. (Lintel guidance names $750K with 4+ channels as the readiness line.)
- If privacy loss is the cause of weak attribution, then add a mix model as a complement. It uses aggregate data, so tracking loss does not break it.
- If the question is which campaigns to tune, then use multi-touch credit. If it is how to allocate or defend the total budget, then use a mix model. Most companies need both by Series C.
- If you sell product-led, then add organic product growth (trial starts, active users) as a variable. Otherwise the model credits marketing for revenue the product produced.
- If a CFO wants ROI proof, then do not promise it next quarter. A proper model takes 12 to 16 weeks from a data-ready start. Offer a directional view, how many months of clean data exist, and a date.
- If a platform says 4x and the model says 2x, then expect that gap. Each platform claims credit for every conversion it touched, including ones that would have happened anyway. Settle it with an incrementality test.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Error on held-out period (MAPE) | Under 10% excellent, 10 to 15% fine for a first build, over 15% very uncertain | |
| Width of a channel's ROI range (80% interval) | Under 1.5x usable, over 3.0x too uncertain for big moves | |
| Convergence (R-hat, Bayesian models) | All under 1.05 | |
| In-sample fit (R-squared) | Over 0.85 typical for a well-built model, under 0.70 means missing drivers | Read with MAPE |
| Cost | Open-source build $15,000 to $25,000 in year 1 (mostly internal time), $2,500 to $4,000 per refresh. Managed service $65,000 to $130,000 in year 1 | Proprietary platforms ($100K to $500K a year) rarely pay off early |
| Refresh cadence | Quarterly or twice a year | A one-time model goes stale |

**Where it goes wrong:** Defending the platform number so the model never gets used. Presenting "shift $47,500" as if the estimate had no error bar. Telling the board the model "proved" a return when it is observational (an experiment is the proof). Buying one engagement with no refresh budget, then steering by an 18-month-old model.

## LTV, payback, and cohorts  (FW-DATA-004, FW-DATA-005)

Pricing choices live in FW-GROWTH-005. NPS scores live in FW-CX-004.

**When this matters:** CAC targets are set from first-year revenue only. LTV:CAC has never been split by segment. Churn is above 15% a year with no picture of who leaves. NRR fell more than 5 points over two quarters with no isolated cause. You report one blended retention number. Series B or C diligence is near (investors ask for cohort curves early).
**Skip it when:** Seed with under 50 paying customers (samples too small, so put the energy into product-market fit). Under 12 months of revenue history (LTV) or under 6 completed monthly cohorts with 3 months each (cohorts). Churn above 40% a year (fix the product). Revenue is lumpy one-time payments or irregular usage billing. Churn is under 5% and steady.

**Where you are**
- Tier 1 Reactive: One blended retention number, and LTV from a simple formula or none.
- Tier 2 Building: Margin-adjusted LTV:CAC and payback tracked monthly, a cohort retention heatmap, and cohort LTV curves reviewed quarterly.
- Tier 3 Operating: LTV and retention split by channel, ICP fit, and size, behavior-based cohorts, and activation milestones tied to retention.
- Tier 4 Compounding: Survival analysis (Kaplan-Meier, Cox) and forecasts checked against actuals, with customer-level risk scores steering CS effort.

**First build, in order** (the cohort program is 12 to 20 hours total, no special tooling)
1. Fix one churn definition (2 to 3 hours). Use revenue churn for LTV. With mostly annual contracts, measure annually because cancellations cluster at renewal. Decide how downgrades count and write it down.
2. Calculate the baseline (3 to 4 hours). LTV = (average MRR per customer x gross margin %) / monthly churn rate. CAC = trailing 12 months of sales and marketing spend / new logos in that period. Payback = CAC / (average MRR x gross margin %). Ratio = LTV / CAC. Use gross margin, not revenue. Flag a ratio under 2:1 or payback over 24 months.
3. Tag every customer in the CRM (2 to 4 hours): acquisition month, acquisition channel, size tier, in-ICP or out. Write "Unknown" instead of guessing. Do this even at Seed so analysis works in 12 months.
4. Build the revenue matrix (4 to 8 hours, then 30 to 60 minutes a month). One row per customer, one column per calendar month, MRR in each cell. Zero before start and after churn, blank for future months. Pull MRR from billing, not the CRM.
5. Make the cohort heatmap (2 to 4 hours). Group by acquisition month and show the share still active at months 1, 3, 6, 9, and 12, shaded red to green. Read down a column for trend, across a row for decay. Combine cohorts under 15 customers into quarterly cohorts.
6. Chart churn events by tenure month (1 to 2 hours). Annual-contract spikes usually sit at months 11 to 13. Monthly contracts spike at months 1 to 3 and at renewal. Time CS outreach to the chart.
7. Split LTV:CAC by channel (4 to 6 hours), the most actionable output. Under 2:1, cut or add no money. 2:1 to 3:1, hold. Above 3:1, fund it. Above 4:1, consider more.
8. Run one behavioral split (4 to 8 hours). Pick the one product action that means "got real value" (finished the main setup, produced the first output, invited a second user). Compare month-12 retention for customers who did it in their first 14 days against those who did not. The gap is your intervention target.
9. Present to the CMO, CFO, and head of CS and assign owners: head of CS owns activation completion, CMO owns channel cohorts, CFO owns the monthly refresh. Without owners it stays a one-off.

**Decision rules**
- If you are at Seed or have under 50 customers, then compute the blended formula and tag customers. Nothing more.
- If LTV:CAC is under 2:1, then it is a business model problem, not a modeling problem. Diagnose churn, CAC, and gross margin separately, because each has a different fix. Take it to the CFO.
- If LTV:CAC is above 5:1, then you may be under-investing. First check that gross margin and the right churn rate were used and that one strong channel is not hiding weak ones.
- If NRR is above 100%, then the churn-based formula understates value. Use cohort revenue curves. (The library says 100% in one path and 120% in another. Use 100%.)
- If month-12 retention is down for three cohorts in a row, then diagnose in order: channel mix shift (most common), selling outside the ICP, falling activation completion, a competitor or product change.
- If you want a churn-prediction model, then you need product behavior linked to CRM records, 200+ past churn events, and an analyst. With fewer than 200 events use Kaplan-Meier survival estimates.
- If you want predictive LTV, then you need 150+ paying customers, 24+ months of history, customer-level product data, and an analyst. Do cohort and segment work first.
- If you sell product-led, then separate pure self-serve, self-serve later upsold by sales, and top-down enterprise. For free-to-paid cohorts, start the clock at trial start.
- If a raise is coming, then bring cohort curves for 6 to 8 quarters with logo and revenue retention, the LTV:CAC formula with inputs, payback by cohort, NRR trend, and the best and worst segment. Know what the curves show before the investor does.
- Never quote "lifetime" LTV without a horizon. A monthly churn of 1.8% implies a 55-month lifetime, which no customer of a 22-month-old company has proved. State what the data covers (24 months is a safe frame).
- Look past month 12 for annual contracts, and tag every cancellation with a reason. One churn number sends retention money to the wrong places.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| LTV:CAC (margin-adjusted) | Under 2:1 structural problem, 2 to 3 watch, 3 to 5 healthy, over 5 may be under-investing | Per segment too |
| CAC payback | Under 12 months excellent, 12 to 18 typical, 18 to 24 watch cash, over 24 cash risk | |
| NRR | Under 90% serious, 90 to 100 stable, 100 to 110 healthy, over 110 strong | |
| Annual logo churn | Under 5% excellent, 5 to 10 fine, 10 to 15 watch, over 15 act | Read with NRR |
| Month-12 cohort retention | Under 70% serious, 70 to 80 fine for SMB, 80 to 90 good, over 90 excellent for mid-market | |
| Stage targets (annual logo retention, NRR, month-12, month-24) | Series A over 85%, 100%, 75%. Series B over 88%, 105%, 80%, 70%. Series C and later over 90%, 110%, 85%, 75% | Targets, not guarantees |
| Primary activation milestone | 60%+ finish it in its window, under 40% is an onboarding problem | |
| Median time to activation | Under 7 days excellent for self-serve, 7 to 14 fine, over 21 friction | |

**Where it goes wrong:** Revenue-based LTV (it ignores delivery cost). One blended ratio hiding a 7:1 channel and a 1.6:1 channel (investors find this in the data room). Cohort charts that describe decline and never name an intervention. Stopping at month 12. A churn definition that drifts.

## Metrics stack by stage  (FW-DATA-001, 004, 005, 006)

What to run as the company grows. What to measure in the funnel is FW-FOUND-006. This is the data layer under it. Each rung depends on the one before: definitions, then tracking, then reporting, then modeling.

| Stage | Instrument and report | Do not build yet |
|---|---|---|
| Seed, founder-led | Five defined metrics, a UTM rule, tracking checked on lead forms (8 to 12 hours total). Acquisition month and channel on every customer. Consent timestamp, source, and scope on new contacts. Five customer interviews. Blended LTV:CAC at 50+ customers and 12+ months of revenue | CDP, warehouse, BI, mix model, cohorts under 50 customers |
| Early Series A | Dictionary v1 and a named owner. Five shared live reports in the CRM or MAP. Revenue matrix and heatmap at 60 to 200 customers. Start the weekly spend and revenue dataset. Server-side tracking if paid media passes about $200K | BI tool, warehouse with no use case, CDP, mix model |
| Late Series A to early B | Monthly quality audit, sync specs, three dashboards, channel LTV:CAC, post-onboarding and post-churn surveys, competitor monitoring | Board dashboard before a quarter of dashboard use, predictive models |
| Series B | Warehouse once reconciliation passes 4 hours a week, a semantic layer, automated quality alerts, behavior-based cohorts, predictive models if readiness checks pass, incrementality tests, a mix model above $1M spend, a win/loss program | CDP before three written use cases |
| Series C and later | CDP with a use case roadmap, reverse ETL, the owned audience reported to the board, a mix model refreshed quarterly, a unified feedback layer | Enterprise platforms before manual work proves the need |

If a stage says "wait" on a tool, ask what question it answers that a spreadsheet cannot. If you sit between stages, use the triggers (customer count, months of history, paid spend, hours lost to manual work), not the label.

## First-party data, server-side tracking, and when to buy a CDP  (FW-DATA-007, FW-DATA-002)

**When this matters:** CPL rose over 20% in a year with no change in competition. Paid targeting depends on platform audiences that are shrinking. Paid media is over $500K a year with no server-side tracking. For a CDP: one customer sits as separate records in three or more systems and programs misfire, personalization needs real-time product signals, or someone spends over 10 hours a week building segments by hand.
**Skip it when:** Paid media is under $200K a year. Organic is the main channel (paid under 20% of pipeline). Consent and governance are not in place. Seed (the audience is too small, so wait for about 5,000 contacts). For a CDP: fewer than three customer-touching systems with real signal, under 10,000 monthly active contacts at Seed or Series A, nobody can name three specific uses, or a CRM or MAP migration is underway.

**Where you are**
- Tier 1 Reactive: Opt-in, unsubscribe, and a cookie banner exist. Browser pixels only. Consent is a yes/no field.
- Tier 2 Building: Consent with source and scope per record, server-side tracking on the top two paid channels, and CRM audiences uploaded weekly.
- Tier 3 Operating: The owned audience seeds all lookalikes, the CPL gap against interest targeting is measured, and a CDP is live or deliberately deferred in writing.
- Tier 4 Compounding: Owned audience size, growth, engagement, and revenue contribution reported to the board quarterly.

**First build, in order**
1. Run a consent scope audit (3 to 4 hours). For every contact: is there a consent record, a timestamp, and consent that covers sharing with ad platforms? The output is one percentage, and only that share can go into ad activation. EU contacts need specific informed consent for this purpose. US contacts usually need a clear opt-in and a privacy policy naming third-party advertising, but have counsel review.
2. Change consent capture on every form (4 to 8 hours of MAP setup). Wording must cover targeted advertising. Add fields for consent date, source, and scope.
3. Send your top conversion event server-side to Meta's Conversions API (20 to 40 engineering hours). One event first, usually demo request or trial signup, with hashed identifiers. Match browser and server events with a shared event ID, or conversions double count and the algorithm chases duplicates. Check Meta's match quality score. Google's equivalent is Enhanced Conversions (hashed email from the conversion page). Send only data with advertising consent.
4. Upload your first CRM audience to Meta (2 to 4 hours), compliant segment only. Build a suppression audience of current customers and apply it to new-business campaigns at once. It is the fastest measurable win.
5. Record baselines first (2 hours): attribution coverage, CPL for first-party vs interest audiences, match rate, opted-in size. Set 90-day targets.

For a CDP decision:
1. Size the gap (4 to 6 hours). Match product users to CRM contacts by email. What share of active users has a CRM record, and what share of CRM contacts has usage data?
2. Build a plain product-to-CRM sync before shopping (20 to 40 engineering hours), via reverse ETL or a nightly script. Push the product user ID, activation milestone flags, logins in the last 30 days, and last active date.
3. Write the use case list (3 to 4 hours) with marketing, sales, and product. Each needs a segment, a destination tool, an owner, a success metric, and a go-live date.
4. Score readiness out of 25 across governance, use cases, identity matching, technical readiness, and ownership. 0 to 8 not ready, 9 to 14 fix gaps first, 15 to 20 start vendor evaluation with the use cases as the scorecard, 21 to 25 well prepared.

**Decision rules**
- If someone wants to upload the CRM to Meta or LinkedIn and consent never came up, then stop and run the audit. A generic "send me updates" checkbox does not cover sharing with ad platforms.
- If you are at Seed or Series A and ask about a CDP, then skip vendor evaluation. Reverse ETL or a nightly sync fits, at roughly $500 to $2,000 a month and 20 to 40 engineering hours. A CDP runs roughly $3,000 to $7,000 a month and 200 to 600 hours.
- If you have a warehouse and are weighing a CDP against reverse ETL, then a CDP wins only if you need sub-hour activation, anonymous visitor data in segments, or identity across more than three systems.
- If you sell product-led, then put server-side tracking on the free-to-paid event first (it happens in the product) and connect product behavior to the CRM.
- If paid CPL rose, then separate the cause. Falling impression share with rising CPL points to competition. Stable impression share with a falling click-to-conversion rate points to lost conversion signal, and server-side tracking is the fix.
- If you are Series B and want a CDP, then wait for a readiness score of 15 or more.
- Do not build lookalikes from a tiny seed. Under 5,000 opted-in contacts is too thin.
- A list is not a strategy. A 50,000-person email list with no paid seeding or suppression, no server-side tracking, and no measured revenue is an email program.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Opted-in audience with paid-media consent | Under 5,000 too small for lookalikes, 5,000 to 25,000 suppression and basic targeting, 25,000 to 100,000 strong | |
| Contacts cleared for ad use (consent scope coverage) | Over 70% strong, 40 to 70 typical mid-transition, under 40 too low for scale | |
| Meta event match quality (0 to 10 scale) | Under 5 poor, 5 to 6 acceptable, 6 to 7.5 good, over 7.5 excellent | |
| Paid conversions attributed to a source | Under 50% severe gap, 50 to 70 priority, over 85 strong | |
| CDP cost at Series B | $2,500 to $7,000 a month licensing, $40,000 to $100,000 to implement | Check current vendor prices |

**Where it goes wrong:** Buying a CDP from a demo with no use cases. Over-building identity matching when email matching covers most profiles. Uploading contacts to ad platforms on generic consent. Server-side tracking with no event deduplication. Launching personalization before the data behind it is clean.

## Customer feedback systems  (FW-DATA-009)

NPS timing, detractor follow-up, and score reading belong to FW-CX-004. Win/loss program design belongs to FW-PM-006. This block is the company-wide system: interviews, tagging, storage, and turning many sources into messaging, ICP, and roadmap decisions.

**When this matters:** Product choices come from opinion and sales anecdotes. Churn is rising and nobody can say why with quotes and patterns. Customers describe your value differently than your messaging does. Win/loss lives in reps' heads. Satisfaction is measured once a year or never.
**Skip it when:** Fewer than 10 paying customers (founder interviews are enough). Product-market fit is not validated (structured feedback then tunes the wrong product). Nobody owns acting on feedback (asking and ignoring annoys customers more than not asking). No CRM or marketing automation yet.

**Where you are**
- Tier 1 Reactive: Feedback arrives by chance, nobody owns it, and answers come from memory.
- Tier 2 Building: Two or more collection channels, a shared taxonomy, a monthly synthesis brief, post-churn interviews, and a survey with a written loop for unhappy customers.
- Tier 3 Operating: Feedback tied to CRM accounts, surveys triggered by product milestones, call transcripts and support themes feeding the brief, and detractors followed up within 48 hours.
- Tier 4 Compounding: One data layer for interviews, surveys, tickets, reviews, and calls, with predictive churn flags and every change tracked to its outcome.

**First build, in order** (about a week of part-time work)
1. Write 8 to 10 interview questions and run 5 interviews (4 to 5 hours). Core set: What were you doing before you found us? What made you decide to buy? What surprised you, good or bad? What do you wish we did that we do not? How would you describe us to a colleague? That last answer is the rawest messaging input you will get. Write answers down verbatim.
2. Make a repository (30 minutes) in a Sheet or Notion: date, customer, segment, category, summary, verbatim quote, recommended action. Start with 5 or 6 broad categories.
3. Hold a 60-minute synthesis with whoever owns product and marketing. Pull the 3 to 5 most repeated themes and, for each, what customers say, what it means for product and for messaging, and the action. That is your first brief.
4. Send a 2-question micro-survey after onboarding (2 hours): ease of getting started from 1 to 7, then open text for "what would have made it easier."
5. Put a recurring 60-minute monthly synthesis on the calendar with one owner. This is the most important step. Without a standing slot, collection outruns synthesis.
6. At 10+ interviews, 30+ entries across channels, and 3 monthly briefs, move to the standard build: apply an eight-category taxonomy to every channel (product, onboarding, support, pricing, competitive, messaging, integration, sales experience).

Three interview types:
- Customer interviews: active customers at 60 to 90 days after activation and at 6 months, 4 to 6 a quarter, 30 to 45 minutes. Run by CS, product, or a researcher, never sales.
- Churn interviews: every churned customer within 48 to 72 hours, 15 to 20 minutes. Use someone with no prior relationship to the account (the CSM who owned it tends to understate CS-related causes). Even a 20% contact rate gives the densest signal you will get.
- Win/loss interviews: 2 to 4 a month, lost deals within 30 days of close, by someone who was not on the deal (FW-PM-006).

**Decision rules**
- If you are at Seed with under 20 customers, then run 5 interviews and a monthly synthesis. No survey tools.
- If retention is the main constraint, then start with churn interviews before any NPS or CSAT. For 90 days contact every churned customer within 72 hours, record the reason by category, and synthesize at 20 interviews.
- If you are at Series A and no NPS runs, then complete at least 15 qualitative interviews first, or you cannot read open-text answers. If the board demands NPS, send a simple monthly one but do not treat the score as the main signal.
- If you collect a lot and synthesize little, then stop adding channels. Ship a monthly brief within 2 weeks even from messy data, with an owner and a template.
- If positioning is weak, then take the last 10 to 20 answers to "how would you describe us to a colleague" and use them to rewrite the homepage headline and the first paragraph of the sales deck (about 2 hours).
- If you sell product-led, then ask inside the product and keep free and paying users in separate pools.
- If you have a CRM and product analytics, then trigger by behavior. Engagement under 50% of baseline for 7+ days gets a CS check-in, not a survey. A finished activation milestone gets the ease-of-use survey within 24 hours. 90 days before renewal gets NPS plus open text.
- If manual synthesis passes 20 hours a month and you run more than 4 collection channels, then evaluate a unified platform. Not before.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Churned customers contacted within 7 days | Over 40% strong, under 20% means most reasons are invisible | |
| Actions taken from each brief | 1 to 2 a month at Tier 2, 3 to 5 at Tier 3 | |
| Survey response rate | 25 to 35% with a working closed loop, under 15% signals fatigue or lost trust | |
| Post-support satisfaction (CSAT) | Over 85%, under 75% is a support process failure | |
| Cost by stage | Seed $0 to $100 a month and 5 to 10% of one person. Series A $100 to $500 a month and 20 to 30% of one person. Series B $500 to $2,000 a month and 30 to 50% of one person under 150 customers, 50 to 100% above | |

**Where it goes wrong:** A score dashboard reviewed quarterly with no owner and no action. Interviewing only happy customers, so churn drivers stay hidden. Five surveys launched at once, each under 10% response. A repository with no tags that nobody can search. One 30-question annual survey standing in for a program.

## Competitive and market research program  (FW-DATA-008)

Battlecards and live-deal responses belong to FW-PM-004. Positioning belongs to FW-FOUND-003. This block is the research process that feeds them: what to watch, where, how often, and how it reaches leaders.

**When this matters:** Sales keeps losing to one or two competitors and cannot say why. A big decision is coming (new market, pricing change, roadmap shift, raise) and your read on the market is over 6 months old. A competitor changed price, shipped a major product, or raised a large round and you have no process to catch it. Your ICP or messaging is over 12 months old and untested.
**Skip it when:** Seed with under 20 customers and the open question is product-market fit. The market has no real competition (rare). Nobody is named to own it or distribute it. The sales team has fewer than 5 people and is not yet losing revenue to named competitors.

**Where you are**
- Tier 1 Reactive: Competitor knowledge sits in reps' heads, and any profiles are 12+ months old.
- Tier 2 Building: Top 3 profiles, monitoring on the top 5 competitors, and a monthly digest to sales and product.
- Tier 3 Operating: Win rate by competitor on a dashboard, win/loss interviews feeding profiles, a quarterly market brief, and breaking news reaching leaders within 24 hours.
- Tier 4 Compounding: A market layer above competitors (category trends, buyer shifts, adjacent moves 12 to 24 months out) and the program's return tracked yearly.

**First build, in order** (about 15 to 20 hours)
1. Ask 5 to 10 reps three questions (2 to 3 hours). Which competitors came up in your last 10 deals? What are the top 2 or 3 objections from each? Where do you feel least confident?
2. Build three one-page profiles (8 to 12 hours): what they sell and at what price, their three strongest claims, the three most common objections they create, your one-sentence answer to each, and their go-to-market motion. Design for a rep with 3 minutes before a call. Three competitors only.
3. Walk sales through them live (1 hour). Reps will correct errors on the spot. Then name the profiles the official source.
4. Set up cheap monitoring (2 to 3 hours): alerts on each competitor's brand, product, and CEO names, page-change watches on pricing and homepage, and a monthly look at review-site profiles.
5. Start a one-page monthly digest (1 hour): major developments, new objections from sales, and one actionable insight for next month's deals.

**Decision rules**
- If you are at Seed, then write down what you already know: one page on each of the top 3 competitors. Everything else waits for a sales team.
- If profiles are older than 6 months at Series B, then do a one-day refresh sprint (pricing page, homepage, last 5 reviews) before expanding.
- If you lose more and more to one competitor, then pull the last 10 lost deals, interview at least 3 of those buyers, and talk to the reps. Find what claim they make that you are not countering and what buyers believe about them that you have not addressed.
- If you sell product-led, then lean on review-site analysis: "switched from" and "switched to" stories, and where your activation is weaker.
- If win rate by competitor is not tracked, then add a "primary competitor" field to opportunities (30 minutes). It is the feedback loop for the whole program.
- If you are thinking of buying a competitive intelligence platform, then first confirm you already have a monthly digest sales reads and current profiles. A platform on top of no process adds alerts nobody reads.
- Collect from the field as well as the web. What competitors tell buyers in live deals is the most useful intelligence, and public monitoring never sees it.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Win rate against a named competitor | Over 50% strong, 35 to 50 improvable, under 35 needs a response | Three straight months of decline means investigate |
| Profile age | Under 90 days target, over 180 likely wrong, over 365 unreliable | |
| Time to brief on breaking events | Within 24 hours | Over 48 means reps meet the news in a deal |
| Cost by stage | Seed 4 to 8 hours of founder time. Series A 15 to 20% of a product marketer's time. Series B 25 to 30%, plus $20,000 to $40,000 a year if you add a platform | |

**Where it goes wrong:** A polished competitor deck built for each board meeting and then filed. A feature checkmark matrix that lists what products have, not what buyers value. A platform bought before any manual process worked. Monitoring only, with no field intelligence.

## Dropped

Left out because the library gives no way to trace them:
- Outcome promises that read as measured results: "reduces reconciliation time 50 to 70%," "improves paid efficiency 10 to 25%," "CDP projects fail 60 to 70% of the time," "server-side tracking recovers 20 to 45% of conversions," "first-party audiences cut CPL 15 to 40%," "CDP cuts paid CAC 15 to 25%," "mix-model reallocation lifts revenue 5 to 15%," "VoC-informed messaging lifts win rate 5 to 15 points," "customers who activate retain at 80%+ vs 40 to 60%," and the ROI paragraphs in each Section 18.
- Typical-value claims with no source: "contacts not enriched in 24 months have 30 to 40% job title error," "marketing is 20 to 40% of revenue in a mix model," "fully loaded LTV:CAC runs 0.3 to 0.8 lower," "expansion is 20 to 40% of new-logo revenue," "months 11 to 13 hold 35 to 55% of churn," "B2B CRM audience match rates run 25 to 50%," and "80%+ of report disputes are definition problems."
- Vendor prices that are likely stale (a monthly BI price, a minimum lookalike seed size attributed to one ad platform) and named competitive intelligence and survey platforms. Check current prices before relying on any tool cost.
- Adstock decay ranges by channel. The library gives two slightly different tables, so I omitted both.
- The stage retention targets are credited in the library to three named venture and research firms. I removed the names and kept the numbers as Lintel targets. I could not verify them, so treat them as directional.
- Section 19 revenue figures inside pitch scripts (the library marks these as illustrations).

Conflicts in the library and how I settled them:
- Mix model spend floor: $500K (skip below), $750K with 4+ channels (readiness), $1M (Series B build). I gave all three as a ladder.
- Skip data governance below five programs (Section 0) or three (Section 25). I used five.
- Slow activation: over 30 days in one framework, over 21 in another. I used 21.
- NRR break point for the churn-based LTV formula: 100% in one path, 120% in another. I used 100%.
- Churn interview timing: 48 to 72 hours, 7 days, and 48 hours in different places. I used 48 to 72 hours as the target and 7 days as the measure.
- Churn interviewer: one section says CS or a senior person, another warns against the account's own CSM. I used "someone with no prior relationship."
- Older tier labels in the sources (Ad Hoc, Defined, Developing, Integrated, Systematic, Optimized) are replaced by Reactive, Building, Operating, and Compounding.
- ARR bands per stage differ by file. I used stage names and avoided ARR bands.

## Credit

- Marketing mix modeling tools: Robyn (Meta) and Meridian (Google), both open source.
- Net Promoter Score: Fred Reichheld (with Bain and Company). Named only to point to FW-CX-004.
- Customer Effort Score: Matthew Dixon and colleagues (Corporate Executive Board).
- Kaplan-Meier survival estimates: Edward Kaplan and Paul Meier. Cox proportional hazards: David Cox.
- Meta Conversions API, Meta event match quality, and Google Enhanced Conversions are product features of those companies.
- Everything else (data dictionary, cohort heatmap, LTV:CAC, CAC payback, dashboard tiers, the interview taxonomy) is described in Lintel's own words from FW-DATA-001 through FW-DATA-009.
