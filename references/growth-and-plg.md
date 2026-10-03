# Growth and Product-Led Motion

How to set the growth model, run experiments, price the product, design trials and activation, build referral, and fix the retention levers marketing owns, for a marketer or founder at a seed to Series B B2B software company.

**Owns:** The growth model and North Star metric. Stage-by-stage diagnosis (acquisition, activation, retention, referral, revenue). The experiment program and its statistics rules. Pricing model, value metric, willingness-to-pay research, and price changes. Free trial versus freemium. Activation measurement from the growth side. Referral, reviews, and word of mouth. Retention levers marketing owns. Network-effect screening. Mobile app growth. Who owns the growth number.

**Does not own:**
- Product-led versus sales-led versus hybrid motion: FW-FOUND-005. ICP: FW-FOUND-001. Attribution setup: FW-FOUND-006 and FW-REVOPS-004. Budget totals and unit economics: FW-FOUND-008.
- Landing page, form, and ad-creative conversion tactics: FW-DEMANDGEN-004.
- Tier count, packaging, published tier prices, pricing page design: FW-EMERGING-013. Discount approval and floor prices: FW-SALES-006.
- Onboarding content: FW-CUSTMKT-002. Renewal marketing: FW-CUSTMKT-004. Expansion marketing: FW-CUSTMKT-003. Case studies and advocates: FW-CUSTMKT-001. Lifecycle email: FW-MAIL-002. NPS programs: FW-CX-004. Community: FW-COMMUNITY-001 to 003.

---

## Growth model, North Star metric, and where to focus  (FW-GROWTH-001)

**When this matters:** Customers arrive but nobody can say which action caused them. Marketing, sales, and product report different success numbers. Growth has flattened despite spend on several channels. A raise is coming. A new growth leader needs a shared definition.
**Skip it when:** Fewer than 40% of surveyed users would be "very disappointed" to lose the product (no fit yet). Fewer than 25 paying customers or no retention evidence past 3 months. A working strategy exists and the problem is execution. A product or churn crisis is eating leadership time.

**Where you are**
- Tier 1 Reactive: Growth comes from founder sales, referrals, and outreach. No North Star. No stage measured as a rate.
- Tier 2 Building: A North Star passes the five tests. At least 3 of 5 stages are measured as rates. One owner reports weekly. Retention is tracked by cohort.
- Tier 3 Operating: One growth loop has a measurable positive coefficient. Experiments follow a protocol. The growth model drives budget.
- Tier 4 Compounding: Two or more loops compound. The model forecasts the North Star within 10% over 90 days. Loops bring 30-50% of new ARR.

**First build, in order**
1. Build a cohort retention table for the first 25-50 customers: acquisition date, channel, size, status, and revenue at months 1, 3, 6, and 12. Group by acquisition month and compute percent active at 3 and 6 months. About 4-6 hours in a spreadsheet. Growth spend without this is a guess.
2. Run the fit survey (Sean Ellis). One question to customers active 30+ days: "How would you feel if you could no longer use this?" Get 25+ responses and split by segment. 40%+ "very disappointed" in one coherent segment is the go signal, and that segment is your growth ICP.
3. Settle the motion in FW-FOUND-005 before choosing channels or loops.
4. Pick the North Star. Score 5-8 candidates 1-5 on five tests: reflects customer value, leads revenue, splits into inputs a team controls, is hard to inflate, and anyone can explain it. Revenue and ARR fail the first two. Examples: weekly active teams, repeat-buyer GMV, reports shared outside the product. Use a 90-minute workshop with up to 6 leaders.
5. Split it into breadth x depth x frequency (Sean Ellis and Amplitude's model). Breadth is acquisition plus activation (marketing and sales). Depth is how fully accounts use the product (product and customer success). Frequency is how often (product, lifecycle marketing, customer success). Name one owner per lever.
6. Hold a weekly 30-minute meeting (North Star versus last week, what changed, one thing to test). Keep a 5-8 row growth model: lever, baseline, target, effect on North Star and ARR, owner, cost. Run every spend request through it.
7. Audit loops. Viral: K = invitations per user x invite-to-active conversion (above 0.1 means a passive loop exists). Content: organic signups divided by all signups (above 15% means a loop). Sales: deals citing a referral, case study, or reference divided by closed deals. Put at least 30% of growth budget behind the strongest loop.

**Decision rules**
- If fit is unconfirmed (under 40%), then stop growth architecture and fix the product. Growth before fit speeds up churn.
- If the motion is product-led at seed or Series A, then activation is the first lever. Do not scale paid acquisition until 7-day activation is above 30%.
- If NRR is under 90%, then pause acquisition scaling and run a churn review of the last 20 churned accounts.
- If you are a solo marketer, then work in order: North Star and weekly cadence, the weakest stage, then the primary loop. One stage at a time.
- If the primary loop sits under 0.10 after 12+ months of spend, then audit it (a product change broke the mechanic, the ICP shifted, or the network is saturated). Do not add money to a stalled loop. Start a second loop only when the first holds above 0.15 for two quarters.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Fit score | 40%+ "very disappointed" in one segment. 30-39% marginal. Under 30% not yet. 55%+ strong | Sean Ellis survey |
| 6-month cohort retention | Under 50% structural. 50-65% fixable. 65-80% healthy. Over 80% excellent | Lintel guidance |
| Net revenue retention | Under 90% critical. 90-100% functional. 100-110% healthy. Over 110% strong | Lintel guidance |
| 7-day activation, product-led | Under 25% problem. 25-40% typical. 40-60% good. Over 60% excellent | Lintel guidance |
| 30-day milestone, sales-assisted | Under 60% problem. 60-80% typical. Over 80% strong | Lintel guidance |
| Loop share of new ARR | Under 15% all bought. 15-25% emerging. 25-40% functioning | Lintel guidance |
| Series A budget split, product-led | 35% activation and product, 30% acquisition, 20% retention, 15% loops | Lintel guidance. Sales-led: 40% acquisition, 25% activation, 20% retention, 15% loops. Totals: FW-FOUND-008 |

**Where it goes wrong:** Scaling before fit. A North Star that counts activity, or one picked because it is easy to pull. Treating the five stages as a build list when they are a diagnosis. Spending 70-80% of growth budget on acquisition while activation sits under 30%.

---

## Experiments and conversion rate work  (FW-GROWTH-002)

Page, form, and ad-creative tactics live in FW-DEMANDGEN-004. This block is the protocol those tests must follow.

**When this matters:** Spend follows seniority or the loudest voice. CAC is rising or conversion is falling and nobody can say which change would fix it. Several changes shipped with no hypothesis, control, or recorded result. The team ships fast and learns slowly.
**Skip it when:** Fit is unconfirmed. The surface has under 500 monthly visitors, trial starts, or active users. No North Star exists to rank tests. A crisis is open. With under 200 monthly conversion events, most tests take 3-6 months, so interview first (see rules).

**Where you are**
- Tier 1 Reactive: Changes ship with no hypothesis, control, or sample size. "Seemed to perform better" counts as a result.
- Tier 2 Building: A hypothesis format is required. A backlog of 15-20+ ideas is scored with ICE. One test always runs. Results are logged, and 90% confidence is the bar.
- Tier 3 Operating: 3-5 tests run at once with a shared calendar. A learning library sits apart from the log. RICE scoring. Win rate 20-30%.
- Tier 4 Compounding: 8-12 tests run at once with feature flags and a growth analyst. The learning library holds 30+ mechanisms and feeds the model each quarter.

**First build, in order**
1. Make a shared sheet (2-3 hours, free) with one row per test: ID, surface (acquisition, activation, retention, referral, revenue), North Star lever, hypothesis with mechanism, primary metric, guardrail metric, minimum detectable effect (MDE), sample size, duration, result, mechanism outcome (confirmed, refuted, inconclusive), one-line learning. Rule: no growth change goes live without a completed row. Hypothesis form: "If we change X, lever Y moves by Z because of W."
2. Compute sample size before launch with a free calculator (Evan Miller's). Inputs: baseline rate, MDE, significance. Set MDE at 10-20% relative for conversion tests and 5-10% for email. Write the number down and do not read results until both arms reach it.
3. Run the first test on a strategic lever, not the easiest one. 50/50 split. At least 2 full business weeks for behavioral tests (a one-time email can finish in 24-48 hours).
4. While it runs, write 15 hypotheses across all five surfaces, score each on ICE (impact, confidence, ease; Sean Ellis), and tie each to a lever.
5. Set standards: 90% confidence by default, 95% for pricing and anything slow to reverse, 80% only as a labeled exploratory signal that gets a confirming test. Each test names a guardrail metric and stops early only if that metric breaks.
6. After 5 finished tests, add a second test only on a different surface and different users (an ad test beside an in-app test is fine; a landing page test beside trial onboarding is not). Add a 15-minute bi-weekly check and a monthly review. Keep a learning library once wins repeat.
7. Use native tools first (ad platform, email split tests, landing page variants). Buy a platform only when you run 3+ concurrent tests a month and need in-product feature flags. Set your confidence standard before configuring any tool.

**Decision rules**
- If you have under 200 monthly conversion events, then interview 5 churned and 5 retained customers to build hypotheses, and test only the busiest surface.
- If someone wants to stop a test early because "we have a winner", then keep running. Early leads appear by chance in nearly every test.
- If win rate is over 40%, then the team is testing safe ideas. Make at least 30% of the backlog low-confidence (ICE confidence under 5). If it is under 15% for two quarters, require behavioral data behind each idea.
- If 60%+ of tests sit on acquisition but activation or retention is the weak stage, then move at least 40% of test cycles there.
- If a surface has 4+ straight nulls, then call it optimized and move on. Never run more than 2 tests in a row on one surface without a win between.
- If a test wins but the variant lacked the intended change, then log it "mechanism unknown" and run a follow-up before scaling.
- If the motion is product-led, then assign by account, not user. If it is sales-led, test the high-volume top of funnel, because demo-stage tests at 100 demos a month take 6-12 months.
- If the outcome lags (retention, expansion, anything pricing), then use a holdout group that never gets the change.
- If you want many variants at once, then don't. With 10 variants at 90% confidence the chance of at least one false positive passes 65%.
- If you are a solo marketer, then run one test at a time and finish one every 3-4 weeks. An agency builds variants against your hypotheses and never writes them.
- For email tests, judge on clicks or a later step, not opens.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Win rate | 20-30% healthy. Under 15% weak ideas or underpowered tests. Over 40% safe-test bias | Lintel guidance |
| Average lift of winners | Tier 2: 10-15% relative. Tier 3: 15-20%. Tier 4: 18-25% | Lintel guidance. Report every win with its size |
| Tests finished per quarter | Seed 2-3. Tier 2 4-6. Tier 3 8-12. Tier 4 15-25 | Lintel guidance |
| Tests run to planned sample | 100% | Early stops other than guardrail breaks are process failures |
| Sample per arm | Roughly 1,000-5,000 for most B2B conversion metrics at a 10% MDE | Depends on baseline. Compute it |

**Where it goes wrong:** Testing where it is easy (ads, headlines) while a 45% drop-off at a setup step sits untouched. Judging an email on open rate. Calling a test at "good enough" sample size. Letting the tool's default confidence level set your standard. Reporting "four wins" with no effect sizes. Running changes and calling them experiments.

---

## Pricing model, willingness to pay, and price changes  (FW-GROWTH-005)

Tier count, packaging, and pricing page design are in FW-EMERGING-013. Discount approval is in FW-SALES-006. Settle model, value metric, and price level here first.

**When this matters:** Pricing is unchanged since launch and came from competitor research or gut feel. Trial-to-paid is under benchmark and price may be a cause. NRR is above 100% and expansion is climbing. A big product investment shipped and price did not move.
**Skip it when:** Fit is unconfirmed (set a price that covers cost and converts, then confirm fit). Growth is above 100% YoY and pipeline, not conversion, is the limit. A major product change is underway. The sales team is under 90 days old. You have fewer than 40 paying customers to survey.

**Where you are**
- Tier 1 Reactive: Price set at launch. No willingness-to-pay data. Discount rate unknown.
- Tier 2 Building: A 30+ response price survey is done. The value metric is named. One price change was made on evidence. A yearly review exists.
- Tier 3 Operating: Model, metric, and prices rest on research. Discounts are tracked. Page tests run quarterly. NRR is tracked by tier. Tier upgrade rate is above 8% a year.
- Tier 4 Compounding: Pricing is a formal lever in the growth model. NRR is above 110%. Upgrade rate is above 12%. Average discount is under 15%.

**First build, in order** (6-8 hours of leadership time over 4-6 weeks)
1. Pull four baselines in 2-4 hours: revenue per customer by tier, trial-to-paid by tier, 12-month tier upgrade rate, average discount.
2. Find the value metric (Patrick Campbell's framing): the unit that rises when customers get more value. List candidates (users, records, API calls, outcomes, projects). Check each: does it rise with value, do buyers understand it, can you measure it. Correlate each with 6-month retention. If your model does not scale on the winner, a model change is the top finding. Fix the model before the price point.
3. Run the Van Westendorp survey (Peter van Westendorp, 1976). Four questions: the price so low you doubt quality, the bargain price, the price that starts to feel expensive, the price too high to consider. Send to 40+ customers active 90+ days, from the account owner, not automation. Wait for 30+ responses (50+ before a large move). Plot the four curves for the acceptable range and best price. About 2 hours.
4. Make one change: raise the price for new customers only, keep current ones where they are. Write down the old price, new price, survey basis, and expected effect. Watch trial-to-paid for 60 days. If it holds within 10% of baseline, the price is inside the acceptable range. Track revenue per customer too, since a 5% conversion dip with 15% higher revenue per customer is a gain.
5. Schedule a 2-hour pricing review 90 days after the survey (survey, NRR by tier, upgrade rate, discount trend, customer ROI evidence). Output a decision, dates, and an existing-customer plan.
6. If you move to usage-based or hybrid pricing, ship the billing view the same day: in-product usage, a spend forecast, and alerts at 70%, 80%, and 90% of the allotment.

**Decision rules**
- If product-led trial-to-paid is under 15%, then diagnose the stage first. Under 30% activation means price is not the main cause. Over 40% activation with conversion still under 15% points to price, so run the survey.
- If tier upgrade rate is under 5% a year, then interview 10 customers who sat on the entry tier 12+ months. If they want nothing more, the tier is too strong. If they name a feature, that is your upgrade trigger and it belongs one tier up.
- If average discount is over 25%, then fix approval rules first (FW-SALES-006).
- If you consider usage-based pricing, then it fits only when value tracks usage, usage varies about 10x across customers, you can meter events, and you will ship the billing view with it.
- If your model is wrong at Series A, then change it now. At 30-100 customers the move is manageable. At 500 it takes about 18 months.
- If you raise prices for existing customers, then lead with value delivered, give 90+ days' notice (6 months for large enterprise), hold customers within 60 days of renewal at today's price for another year, have account owners call larger accounts, and script answers to "too expensive", "our budget is fixed", and "what is new?". For a long-term customer far below market, step up 15-20% at first renewal. A 40% jump drives large-account churn.
- If a competitor cuts price, then do not match. Arm sales with retention and ROI evidence and wait.
- If a new-customer promotion undercuts what loyal customers pay, then stop. Never price a promotion below the lowest price any existing customer pays.
- If churners say "too expensive", then check usage. Active, engaged churners are price-sensitive. Low-usage churners mostly failed to activate.
- If you sell annual plans, then offer 10-12 months' cost at a natural moment, and only to activated customers. Unactivated annual customers hide churn until one renewal date.
- If you test price, then use new customers only, a 60-day window, and 95% confidence under FW-GROWTH-002. If your survey is over 18 months old, rerun it first.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Trial-to-paid, product-led | Under 15% concerning. 15-25% typical. Over 25% strong | Lintel guidance |
| Trial-to-paid, sales-assisted | Under 25% low. 25-40% typical. Over 40% strong | Lintel guidance |
| Pricing page conversion | 5-12% typical for B2B software. Under 5% means friction | Lintel guidance. Design: FW-EMERGING-013 |
| Tier upgrade rate, 12 months | Under 5% weak. 5-10% functional. Over 10% healthy | Lintel guidance |
| Average discount | Under 10% strong. 10-20% acceptable. Over 20% discount culture. Over 30% governance failure | Lintel guidance. Rules: FW-SALES-006 |
| NRR by tier | Each tier over 100%. A tier under 90% has a price, packaging, or fit problem | Lintel guidance |
| Survey size | 30+ responses minimum. 50+ before a large move | Lintel guidance |

**Where it goes wrong:** Tuning the price on the wrong model (per-seat for a product whose value is outcomes). Leaving the launch price alone for fear of upsetting customers. Pricing to competitors, not to value. A discount habit that erases the design. A price-rise notice that cites costs or investors. Usage billing with no usage view, so the first invoice is a shock.

---

## Free trial, freemium, activation, and onboarding (growth side)  (FW-GROWTH-001, -002, -005, -007)

Onboarding content and emails are in FW-CUSTMKT-002 and FW-MAIL-002. This block covers the decisions and numbers above them.

**When this matters:** Trials start but few reach value. Product-led trial-to-paid is under 15%. Median time to activation is over 7 days. Leads rise while activation falls. You are choosing between a trial and a free tier.
**Skip it when:** Fit is unconfirmed. Value needs human setup (use the sales-assisted milestone). Trial starts are under about 200 a month, so tests will be slow (interview instead).

**Where you are**
- Tier 1 Reactive: Activation is not measured. You know signups, not who got value.
- Tier 2 Building: A 7-day activation rate exists and you know the step where most users quit.
- Tier 3 Operating: Activation is tracked per account with workflows around it.
- Tier 4 Compounding: Activation tests feed the growth model and onboarding varies by segment.

**First build, in order**
1. Define the activation event by evidence: the action that best predicts retention and paid conversion in a cohort check. "Viewed the dashboard" is easy to hit and often predicts nothing. High activation beside low trial-to-paid means the event is wrong.
2. Baseline 7-day activation, median time to activation, and trial-to-paid by tier. For B2B, count activation per account.
3. Find the step with the biggest drop and shorten the path to first value. Cut steps. Feature tours are the usual wrong fix.
4. Choose trial or free tier (rules below). The library gives no benchmark for trial length or card-up-front, so test both under the FW-GROWTH-002 protocol.
5. Test one change at a time, assign by account, and use a holdout for onboarding changes since retention lags. Keep self-serve and sales-assisted upgrades in separate cohorts, and give high-fit users who stall a sales touch rather than more email.

**Decision rules**
- If the motion is product-led at seed or Series A, then activation moves first. A point of activation is worth more ARR than a point of trial volume. Fix it before scaling paid acquisition (7-day activation above 30%).
- If activation is under 30%, then price is not the main cause. If it is over 40% and trial-to-paid is under 15%, then price is a likely cause.
- Choose freemium only if all three hold: free users create value for paid users or the brand (viral or network effect), serving a free user costs very little, and there is a clear upgrade trigger. Otherwise use a time-limited trial.
- If free-to-paid is under 2%, then the free tier is too generous or the limit is not worth paying to lift. Redesign limits around the upgrade trigger.
- If leads grow while activation falls, then the gap is audience quality. Write down what a "qualified trial" is.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| 7-day activation, product-led | See growth model block. Simple self-serve: 40-60% at 14 days. Complex: 20-35% at 30 days | Lintel guidance. Watch trend |
| Median time to activation | Under 3 days target. Over 7 days friction | Lintel guidance |
| Free-to-paid, 90 days | 2-5% typical. Over 5% strong | Lintel guidance |

**Where it goes wrong:** Defining activation as an easy event, so the number looks healthy while paid conversion sags. A free tier with no upgrade design (a cost center). Feature tours instead of fewer steps. Pushing annual plans on unactivated users.

---

## Referral, reviews, and word of mouth  (FW-GROWTH-003)

**When this matters:** Customers refer informally and you do not measure it. NPS is above 40 or the fit survey shows 50%+ "very disappointed". Paid CAC is rising. The product has a sharing or invite mechanic. Your ICP lives in a tight community.
**Skip it when:** Fit is unconfirmed. 6-month retention is under 60% (aim for 65%+ before investing). NPS is under 30. Fewer than 20 paying customers. No sharing mechanic and buyers decide alone or through procurement.

**Where you are**
- Tier 1 Reactive: Referrals happen but are not tracked. K is unknown (roughly 0.01-0.05). Under 20 reviews.
- Tier 2 Building: K is calculated monthly (0.05-0.15). A referral request fires on a behavioral event. Reviews arrive at 2-4 a month. Referral source is captured for 70%+ of new customers.
- Tier 3 Operating: Direct referral, product sharing, social proof, and community all run. K is above 0.15 and is a model lever. Incentives have been tested.
- Tier 4 Compounding: K is above 0.25. Viral sources bring 25-40% of new ARR. An advocate group of 25-50 customers is active.

**First build, in order**
1. Add one question at trial start, demo request, or onboarding: "How did you first hear about us?" (colleague, search, review site, social, event, other). Add a CRM "referral source" field. 2-4 hours. Run 30 days for a baseline. Rough K: customers who said "a colleague recommended it" divided by the active base.
2. Send a first review batch. Pick the platform where your ICP researches (G2 reaches the broadest B2B audience, Capterra leans small business, TrustRadius leans enterprise). Send a short personal note from the account owner to customers who have used the product 90+ days. Do not filter the list by how happy you expect them to be, do not pay for reviews, and do not tie rewards to ratings. Check each platform's current rules and the FTC's review rules first.
3. Find the peak value moment. Ask 5 customers who referred and 5 who did not: "When did you first feel it was really working?" Build one email that fires when an account hits that event, names the specific result, and asks for an intro. No incentive yet. Keep referral and review asks in separate emails.
4. Measure NPS (Fred Reichheld) quarterly. Only promoters (9-10) enter the referral flow. Detractors go to customer success. Track three weekly numbers: referral-sourced trials or demos, new reviews, referral emails sent and replies.
5. Move to the full build when 10%+ of new customers come via referral for 4 straight weeks, K is above 0.05, reviews arrive monthly, and 20+ customers got the referral email. Then add a tracked link per referrer, a landing page for warm peer traffic, and three touches (at the trigger, 7 days later, and a 30-day account-review ask for top accounts).
6. Test incentives: 90 days with none, then 90 days with one. Compare referral conversion and referred-account quality (ICP fit, 6-month retention). Pay only when the referred account reaches activation or 90 days active. Experience rewards suit under 200 customers. Cash or credit suits 500+. Disclose rewards wherever a referrer posts publicly.
7. If the product has sharing or invites: give recipients a branded landing page with a clear signup path, brand exports and shared links, and measure share-to-signup.

**Decision rules**
- If 6-month retention is under 60%, then stop. A referral program on a churning base spreads the churn.
- If passive referral is already 10%+, then measure before adding a reward. It may only add cost. If it is 15%+ with no program, this is your top priority.
- If referral conversion is under 3%, then check timing first. A request tied to an outcome beats one tied to the calendar.
- If NPS is 55+ and referral is under 3%, then the gap is missing infrastructure, not product.
- If referred accounts churn faster than direct ones, then the reward attracts the wrong referrals. Gate it on activation and add an ICP-fit filter.
- If the motion is product-led at Tier 1-2, then build in-product sharing before an email program. If the product has no sharing mechanic, do not build one just to raise K.
- If you sell enterprise, then use reference calls, verified public reviews, and speaking or advisory roles. Referring a vendor puts the customer's career at risk.
- If you are a solo marketer, then do three things: the attribution question (about 2 hours), a personal review batch (about 3), a behavioral referral email (about 4). At seed, add founder referral asks after wins and stop there until you have 50+ customers.
- Keep reviews steady. Four a month beats 40 every six months.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Viral coefficient K | Under 0.05 none. 0.05-0.10 passive. 0.10-0.20 working. 0.20-0.40 strong. Over 0.40 exceptional for B2B | Andrew Chen's model. Bands: Lintel guidance |
| Referral conversion | Under 3% timing or framing. 3-7% functional. 7-12% good. Over 12% excellent | Lintel guidance |
| Referred account 90-day retention | At or above non-referred | Below means incentive or fit problem |
| Review velocity | Tier 2: 2-4 a month. Tier 3: 4-8. Tier 4: 8-15 | Lintel guidance |
| Case study coverage of major verticals | 80%+ at Tier 3. Under 50% means deals without proof | Lintel guidance |

**Where it goes wrong:** Launching a cash reward before measuring the base rate. Mass review emails instead of personal notes. A one-time review push followed by silence. Counting referral volume while ignoring referred-account retention. Mistaking a happy renewal for willingness to refer.

---

## Retention and expansion levers marketing owns  (FW-GROWTH-001, -003, -005)

Renewal programs: FW-CUSTMKT-004. Expansion marketing: FW-CUSTMKT-003. Lifecycle email: FW-MAIL-002. This block says when to fix retention before buying growth and how to find the cause.

**When this matters:** 6-month retention is under 65%. NRR is under 100%. New ARR grows but NRR does not. Churn clusters in the first 90-180 days. Exit notes say "too expensive".
**Skip it when:** You have fewer than 25-50 customers across 3+ acquisition months (cohorts too thin). Retention and NRR already beat benchmark and top-of-funnel volume is the limit.

**Where you are**
- Tier 1 Reactive: No cohort data.
- Tier 2 Building: Retention is tracked by cohort. Activation and retention are measured as rates.
- Tier 3 Operating: All five stages are benchmarked. Expansion and referral have owners and programs.
- Tier 4 Compounding: CAC as a share of LTV has fallen four quarters in a row.

**First build, in order**
1. Build the cohort table from the growth model block, split by channel and ICP segment.
2. Read the cause from usage in the first 30 days. High then dropped: product gap. Never high: activation failure. Wrong company type: ICP drift. If NRR is under 90%, review the last 20 churned accounts first, and check "too expensive" exits against usage (pricing rules above).
3. Find the event that predicts seat or tier expansion and build a customer-success workflow around it. Tighten the ICP filter in acquisition. Test lifecycle changes with a holdout group.

**Decision rules**
- If new ARR grows but NRR is under 100%, then pause acquisition scaling and fix the leak.
- If NRR is 100-110%, then find the expansion trigger. If over 110%, scale the expansion motion. If retention beats benchmark, invest in referral, since retained customers are your most credible referrers.
- If a pricing tier has NRR under 100%, then pull that tier's cohorts to find whether price, packaging, or fit is the cause.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| 6-month retention and NRR | See the growth model block | Lintel guidance |
| Expansion share of new ARR | Under 10% not a lever. 10-20% emerging. 20-35% healthy | Lintel guidance |

**Where it goes wrong:** Buying acquisition on a leaking base. Taking "too expensive" at face value. Shipping a lifecycle change with no control and crediting it for a trend already under way.

---

## Who owns growth: charter and cadence  (FW-GROWTH-007)

**When this matters:** Marketing, product, and sales each claim growth and nothing gets prioritized. Tests run but nobody acts on results. Headcount grows with no shared view of who owns what. The exec team is debating a VP of Growth, VP of Marketing, or CPO.
**Skip it when:** Under 5 people. Fit is unconfirmed. No North Star exists (build that first). One person already owns and executes growth and the limit is budget.

**Where you are**
- Tier 1 Reactive: Founder-led and informal. No backlog or tracking.
- Tier 2 Building: One named owner, a written charter, hypotheses written first, a weekly review, engineering time promised.
- Tier 3 Operating: A dedicated or reliably committed team, a test sprint cycle, monthly exec updates.
- Tier 4 Compounding: Squads own parts of the loop with shared goals across growth, product, and marketing.

**First build, in order** (2-4 weeks, no spend)
1. Settle the North Star (growth model block). Name one growth owner in a paragraph. If the real answer is a future hire, write "TBH" and name who covers it.
2. Write a one-page mandate: North Star, owner, 2-3 weekly sub-metrics, budget the owner can spend without asking, and how tests get approved. 2 hours to draft, one meeting to agree.
3. Start a backlog of 10 hypotheses, each scored 1-10 on impact, confidence, and ease. Hold a 30-minute weekly CEO check-in: three metrics, one test running, one finished with its learning, one decision needed.
4. At Tier 2, grow the mandate into a 2-3 page charter with decision rights and committed engineering, design, and analyst time. Get CEO sign-off and put engineering time in writing.

**Decision rules**
- If you are at seed with no marketing hire, then do not build a team. Name the founder as owner and hold the weekly check-in.
- If you are Series A with one marketer, then make that person lead, write the charter, and secure written engineering access. Hire an analyst before a second marketer. If sales-led, embed one growth-minded person in marketing and let revenue operations own pipeline tests.
- If engineering is the block, then escalate for a written allocation before more growth hiring. Lintel guidance: 10-20% of one engineer at Series A. Under 10% tends to yield fewer than 2 tests a month.
- If you are weighing squads, then confirm four things first: a North Star with sub-metrics, engineers to staff squads, a strong growth head, and attribution per squad. Do not copy another company's structure.
- If the mandate is "build growth from scratch" at Series A, then hire at VP or senior director level. An individual-contributor hire tends to fail within 12 months.
- If "nothing is moving", then check mandate, resources, and test process first. Fight with another function is either a mandate fight (fix the charter) or a process fight (write an interface agreement). Reporting-line changes rarely fix it.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Approved brief to launch | Under 7 days for marketing tests. Under 14 for product. Over 21 is a structural block | Lintel guidance |
| Backlog depth | 4-8 weeks of work. Under 2 weeks too few ideas | Lintel guidance |
| Metrics a growth team owns | 3-5 maximum | Lintel guidance |

**Where it goes wrong:** A growth team that advises but owns no number. Copying a famous company's structure. A backlog that never launches. Nobody owning the handoffs between marketing, growth, and product.

---

## Network effects and platform growth  (FW-GROWTH-004)

**When this matters:** Each new user makes the product measurably better for existing users (shared data, a marketplace, messaging, collaboration, benchmarks built from pooled data). Growth is all direct acquisition. A rival is building a platform in your category.
**Skip it when:** Value is the same at 10 users or 10,000. Fit and retention are unconfirmed (a network on churning users is empty). The product is a point solution with no platform plan. No engineering for a multi-sided product.

**The test:** If user 1,001 joins today, does the product get more useful for users 1 to 1,000? If you cannot name the mechanism, you have referral or community, not a network effect.

**Where you are**
- Tier 1 Reactive: Potential exists but was never audited.
- Tier 2 Building: Type identified, critical-mass target set, cold-start plan live, a network value metric measured.
- Tier 3 Operating: The effect works in at least one segment. Mature segments retain better than immature ones.
- Tier 4 Compounding: Active in 3+ segments with high switching cost.

**First build, in order** (3-4 weeks, no spend)
1. Audit five types (NFX's taxonomy): direct, indirect (cross-side), data, social, marketplace. For each, write the mechanism in one sentence or write why not.
2. Decide build or no-build. Build if critical mass in one segment looks reachable in 12-18 months and engineering can cover it. Defer if it is over 24 months away.
3. Pick one network value metric (benchmark coverage, match rate in a time window, interaction value per user, or share of your ICP present) and write the cold-start offer: what a lone user gets before the network exists.

**Decision rules**
- If all five types are absent, then use the viral, content, and sales loops (FW-GROWTH-001 and -003).
- If you run a marketplace, then seed one side to minimum density in one segment before opening the other. If match rate is under 40%, rebalance now and focus acquisition on the short side until it passes 65%.
- If critical mass is reached and the retention gain is under 5 points, then the value is not visible to users or standalone features drive retention. If cold-start retention is under 50% at 90 days, strengthen standalone value or narrow the ICP.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Network readiness score (0-20) | 0-5 Tier 1. 6-10 Tier 2. 11-15 Tier 3. 16-20 Tier 4 | Five dimensions scored 0-4. Lintel guidance |
| Retention gap, mature vs immature segments | Tier 4 bar: 15+ points. Under 5 means no visible effect | Lintel guidance |

**Where it goes wrong:** Calling referral or a community feature a network effect. Growing both marketplace sides at once. Growing wide before any segment is dense. Declaring critical mass too early.

---

## Mobile app growth  (FW-GROWTH-006)

**When this matters:** A native app with 1,000+ monthly installs and an untouched store listing. Mobile is a main surface for your ICP (field teams, executives approving on the go). Day-1 retention is under 25%. Push opt-in is low or unknown. Installs cannot be tied to channels.
**Skip it when:** There is no native app (mobile web belongs to FW-DEMANDGEN-004). Under 500 monthly active app users. The app is read-only or only sends alerts. Fit is unproven for the mobile use case.

**Where you are**
- Tier 1 Reactive: Listing untouched since launch, no mobile analytics, generic push broadcasts.
- Tier 2 Building: Listing tuned, install attribution in place, retention cohorts read, rating prompt live.
- Tier 3 Operating: Segmented push, in-app messages, deep links on paid campaigns, tests under FW-GROWTH-002.
- Tier 4 Compounding: Tests across listing, onboarding, push, and paid installs feed the growth model.

**First build, in order**
1. Audit the store listing (4-8 hours, free): compare title, subtitle, keyword field, and screenshots with the top 3 competitors, then update the keyword field, subtitle, and first two screenshots. Gains show in 2-4 weeks.
2. Install mobile analytics (baseline day-1, day-7, day-30 retention) and an install-attribution tool before any paid installs.
3. Measure push opt-in and add a screen that explains the value before the system prompt. Add an in-app rating prompt and get the rating above 4.0.

**Decision rules**
- If attribution is not installed, then do not buy installs. If day-7 retention is under category benchmark, then do not scale paid installs.
- If most installs come from searches of your brand name, then the listing is not working on category keywords. Aim for keyword search above 30% of organic installs.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Day-1 retention | Under 25% problem for a B2B app. Under 40% for a consumer-facing B2B app | Lintel guidance |
| Day-7 retention | 35-40% for B2B utility apps | Lintel guidance |
| Push opt-in, iOS | Under 40% means the main retention channel is missing | Lintel guidance |

**Where it goes wrong:** Treating the listing as a one-time launch task. Paying for installs with no attribution. Assuming web fit means mobile fit.

---

## Dropped

**Numbers left out as unsupported:**
- Pricing: "Tier 1 companies are underpriced by 30-50%" (credited to a vendor study), "surveys typically show prices 25-40% below optimal", "pricing to the optimal point lifts new-customer ACV 20-40%", "Series A can raise 15-25%", "a recommended badge moves 20-30% of buyers to annual", "annual plans lift ACV 10-20%", and a value capture rate of 10-20%.
- Referral and mobile: review request conversion of 15-30% personal versus 2-5% mass, "5x worse" subject lines, dark social "2-3x tracked referrals", and "store tuning adds 20-40% installs".
- Growth and testing: "over-weighting acquisition raises CAC 30-50%", test program return ratios (5:1, 10:1, 20:1), and "10 points of activation is worth $200K-$500K". These are illustrations. Also all salary ranges, tool and agency prices, and per-lead channel costs, which age fast.

**Conflicts inside the library, and what I used:**
- Test velocity and win rate: FW-GROWTH-002 says 4-6 tests a quarter at Tier 2 and a 20-30% win rate. FW-GROWTH-007 says 2-5 a month and 10-20%. I used 002 because it owns experiments. For concurrent tests, 002's quick-reference (2-3 and 5-8) differs from its tier text (3-5 and 8-12). I used the tier text.
- Traffic floor: 002 gives 500 monthly visitors and 200 monthly events. I used both.
- Retention bar for a fit signal: 001 uses 70% once and 60% in its tier checklist. 003 and 005 use 65%. I used 50, 60, and 65, each tied to its owner. Fit survey sample: 001 says under 20 is unreliable and also says at least 25. I used 25.
- K bands: 001 calls over 0.25 strong. 003 calls 0.20-0.40 strong. I used 003. Review velocity differs inside 003. I used its metrics section.
- Trial-to-paid: 005's quick-reference says under 20% and 40% is weak. Its metrics section says 15% and 25%. I used the metrics section. Tier upgrade rate: metric bands (5% and 10%) differ from tier exit bars (8% and 12%). I kept both, labeled.

**Added by me, not in the library:** the review guidance (do not filter by expected sentiment, do not pay for reviews, check FTC and platform rules). The library says to send review requests to your happiest customers, which can collide with review-gating rules. Treat this as a compliance prompt, not legal advice.

**Not covered (library gap):** Trial length, card-up-front at trial start, and price research below 40 paying customers. Test the first two and research the third.

**Scope removed:** analyst-firm names in the enterprise referral guidance, discount ceilings (FW-SALES-006), tier count and packaging design (FW-EMERGING-013), regional price bands, and the four-factor motion test (FW-FOUND-005).

## Credit

- **Pirate metrics (AARRR):** Dave McClure, 2007.
- **North Star Metric framework, fit survey, and ICE scoring:** Sean Ellis (survey about 2010). The North Star framework was later systematized by Amplitude. **RICE scoring:** Intercom.
- **Growth loops:** synthesized from Reforge, Brian Balfour, and Casey Winters.
- **Experimentation maturity stages (tiers adapted):** CXL Institute. **Sample size calculator:** Evan Miller.
- **Value metric framework:** Patrick Campbell (Price Intelligently, later ProfitWell). **Price Sensitivity Meter:** Peter van Westendorp, 1976.
- **Viral coefficient model and the cold start problem:** Andrew Chen. **Net Promoter Score:** Fred Reichheld, 2003.
- **Network effects taxonomy:** NFX (James Currier).
