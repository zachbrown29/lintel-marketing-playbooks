# Demand generation and email

How to build a B2B demand program from zero, run paid media and outbound support, capture and score leads, nurture them by email, and keep that email in the inbox. For a marketer or founder at a seed to Series B software company.

**Owns:** building a demand program (pipeline model, first channel, MQL definition, closed loop with sales); the capture versus creation split; paid search, paid social, retargeting, and display; outbound mechanics; landing page conversion and a starting lead scoring model; inbound as a pipeline channel; the email program, lifecycle sequences, deliverability, and email metrics.
**Does not own:** ICP and buyer persona work (FW-FOUND-001, FW-FOUND-002); positioning and messaging (FW-FOUND-003, FW-FOUND-004); content and SEO strategy (FW-CONTENT-001); BDR team structure, pay, and coaching (FW-SALES-002); account-based marketing (FW-EMERGING-003); attribution models, CRM, and tool stack (FW-FOUND-006, FW-REVOPS-002, FW-REVOPS-004); the first value milestone and post-sale lifecycle email (FW-CUSTMKT-001 to 004).

**Order of operations for "where do I start":** ICP, then MQL definition with sales, then attribution, then one channel for 60-90 days. Every block below assumes it. If any of the four is missing, send the reader back before spending.

---

## Building a demand program from zero  (FW-DEMANDGEN-001)

**When this matters:** pipeline runs dry every 60-90 days while close rates are fine. Product-market fit is validated (10+ customers who renewed unprompted) and growth must reach beyond founder networks. Inbound is near zero and outbound has no channel logic. Reps spend over 40% of their time prospecting.
**Skip it when:** PMF is not confirmed (demand gen before PMF fills the pipeline with customers the product cannot keep). The ICP is undocumented. Sales cannot work the pipeline it already has. A product problem is dragging close rates.

**Where you are**
- Tier 1 Reactive: leads come from referrals and founder outreach. No MQL definition, pipeline model, or attribution. Pipeline is unpredictable past 30 days.
- Tier 2 Building: documented channel rationale, an MQL agreed with sales, a spreadsheet pipeline model, monthly cost per MQL, attribution for the main channel.
- Tier 3 Operating: two or more channels allocated on efficiency data, calibrated lead scoring, intent data feeding outbound, the model driving the annual plan.
- Tier 4 Compounding: threshold-triggered reallocation, capture and creation at scale, multi-touch attribution, marketing sourcing 40-60% of pipeline (a Series C+ pattern).

**First build, in order**
1. **Document the ICP** (4-8 hours) from the 10 best customers: size, industry, use case, buyer. It describes who already bought and stayed (detail in FW-FOUND-001).
2. **Define the MQL with sales** (1-2 hours). Review 10 recent leads in a 60-minute session: worth a call, and why. Combine company fit with an intent action. Get the sales lead's written confirmation.
3. **Set up attribution before spending** (2-4 hours): UTMs on every link (source, medium, campaign as quarter-segment-offer, content), a required CRM source field, and a tracking sheet. Data from before this is lost for good.
4. **Run one channel for 60-90 days** at $3,000-5,000 a month, or 20 hours a week of outbound. State beforehand how many MQLs justify scaling. Starting pairings: mid-market VPs on LinkedIn, developers in communities and technical content, SMB owners on Google search and review sites, enterprise C-suite at events.
5. **Evaluate:** spend, leads, MQLs, cost per MQL, MQL-to-SQL. Above target, scale. At target, continue. Below, diagnose targeting, creative, and landing page before cutting.
6. **Build the pipeline model** once one channel has 10+ MQLs with conversion data and the MQL has survived two sales cycles. Revenue target, times coverage (3-4x), divided by deal size for opportunities, then back through SQL and MQL conversion rates, divided by 12. Check with the library's inputs: $3M new ARR, $40K ACV, 25% win rate, 20% MQL-to-opportunity gives 75 wins, 300 opportunities, 1,500 MQLs a year (125 a month).
7. **Design channel architecture** with at least one capture and one creation channel, each with target, offer, spend, MQL goal, and scale trigger.
8. **Close the loop with sales.** Sales dispositions every MQL within 48 hours (accepted, or rejected with a reason code). A monthly 30-minute review flags sources under 50% accepted and scales those over 75%.
9. **Review quarterly.** Two quarters under threshold means cut or restructure, applied next quarter.

**Decision rules**
- If the ICP is undocumented or attribution is missing, then hold program spend to $2,000 a month. Spend without either buys noise and guesses.
- If Seed with weak retention (NRR under 90%), then keep demand gen at test level and talk to the 10 best customers. The problem is fit.
- If one channel beat target for two quarters, then add a second of a different type (creation if the first is capture).
- If pipeline is short and budget tight, then add no channels. Move money to the lowest cost per SQL, cut creation before capture, and cut channels rather than thinning all.
- If cost per MQL rises over 30% for two months, then check pacing, frequency, click-through, and landing page conversion before cutting.
- If MQL-to-SQL is under 15% and sales complains, then review the last 20 rejected leads with them, fix the top two patterns, and recalibrate quarterly until the rate passes 20%.
- If PLG, then measure trial sign-ups and activation, not MQLs. If SMB under $5K ACV, then cost per MQL must stay under $100, which rules out most LinkedIn. If enterprise, then events, executive programs, and ABM (FW-EMERGING-003).
- If hiring the first demand gen person, then ICP, MQL, and 60 days of attribution come first. Full time above $15K a month of programs. Fractional at $5-15K (15-20 hours a month). A consultant (4-8 weeks) to set the foundation.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Pipeline coverage | 3-4x SaaS, 5-6x enterprise, 2-3x high-velocity SMB | Under 2.5x is urgent. Lintel guidance |
| MQL-to-SQL | 20-30% | Under 15% is low-quality volume. Over 40% may be over-filtering |
| Lead-to-MQL | 10-25% | Under 10% is broad targeting or loose criteria |
| Cost per SQL | $500-2,000 SMB and mid-market, $1,000-5,000 enterprise | Lintel guidance |
| Cost per marketing-sourced opportunity | $800-2,500 mid-market, $2,000-8,000 enterprise | Rough |
| Marketing share of pipeline | 30-50% balanced, 60-80% inbound-led, 15-30% outbound-led | Verify attribution first |
| MQL response time | Under 4 hours for demo requests, under 24 standard | A sales process issue |
| Demand gen headcount | 1 per $1-2M ARR at Series A, 1 per $2-4M at Series B | Lintel guidance |

**Where it goes wrong:** running tactics with no connecting logic. A 30-day test then a cut. Three channels on $5,000 (about $1,667 each, under any paid channel's minimum). Attribution added two months late. Leading with brand and content when the need is pipeline this quarter.

---

## Capture versus creation  (FW-DEMANDGEN-009)

Only about 3-5% of a market is in market at any time (the 95-5 rule, John Dawes, Ehrenberg-Bass Institute), so capture alone runs out of audience in 12-24 months.

**When this matters:** pipeline swings between strong and dry months. More capture spend returns less. Prospects say "I hadn't heard of you until I searched." Capture costs keep rising. You are entering a new category.
**Skip it when:** capture channels do not convert yet. ARR is under roughly $1-2M and founders do the marketing (capture plus founder LinkedIn only). Budget forces a choice (pick capture).

**Where you are**
- Tier 1 Reactive: every channel is capture and nobody has labeled it.
- Tier 2 Building: separate baselines for capture and creation.
- Tier 3 Operating: a target split reviewed quarterly.
- Tier 4 Compounding: measurement links creation touches to later capture conversions.

**First build, in order**
1. **Audit** (2-3 hours). Paid search, bottom-funnel SEO, retargeting, LinkedIn conversion campaigns, most blog content, and gated content are capture. Write the split as "X% capture, Y% creation."
2. **Check the capture ceiling:** the 10 core keywords total under 1,000 monthly searches, share of voice already above 50%, or cost per acquisition up two quarters with no new competition.
3. **Choose one creation entry point and commit 12 months.** Default: a newsletter on a topic one level above the product. Alternatives: founder LinkedIn (cheapest), podcast (costlier, slower), community (slowest).
4. **Seed 500 ICP-fit subscribers in 30-60 days:** customers, CRM contacts, team, a LinkedIn announcement, paid promotion by job title. Publish at least biweekly.
5. **Measure creation on its own terms:** subscribers, growth, opens, clicks, unsubscribes. Add "How did you first hear about us?" to demo forms, onboarding, and win/loss calls. Do not judge on MQLs for 12 months.
6. **Add channels in sequence:** newsletter, founder LinkedIn (3+ opinion-forward posts a week), owned event or community, then research and podcast. Review the split quarterly.

**Decision rules**
- If Seed and capture-only, then founder LinkedIn (3-4 posts a week, one topic) and nothing paid. Formalize a newsletter at about $1-2M ARR or Series A.
- If Series A with stable capture cost and no creation, then launch the newsletter and move to 15-20% creation over six months.
- If capture cost has risen two quarters and the capture audit passes, then move 20% of budget to creation for at least 12 months.
- If pipeline is volatile, then add the first-awareness question this week and start newsletter planning within 30 days.
- If no pipeline is attributed to creation after 18 months, then check subscriber titles and company size against the economic buyer.
- If newsletter opens stay under 25% after six months, then re-engage the low segment (three issues, then remove) and check topic drift.
- If the newsletter is company news, it is retention. If all content is bottom-funnel SEO, it is capture.
- If the category is new, then run about 70% creation until branded searches for core terms pass 1,000 a month.
- If leadership wants to cut creation in a pipeline trough, then fix capture execution separately. The cut leaves a gap 12-18 months out.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Long-run B2B split | About 46% creation, 54% capture | Binet and Field, adapted by the B2B Institute at LinkedIn |
| Creation share by stage | Seed 0-5%, A 10-20%, B 25-40%, C+ 40-55% | Lintel guidance |
| By category stage | Nascent 60-70% creation, growing 40-50%, mature 55-65% | Review yearly |
| Newsletter click rate | 3-8% | Opens: see email metrics. Want 35%+ before scaling |
| Newsletter cost, Series A-B | $1,500-6,500 a month | Platform, writing, paid growth |
| Research report | $13,000-53,000 | One a year, Series B+ |
| Podcast | $2,500-7,500 a month | Needs a 12-month commitment and 20-episode plan |

**Where it goes wrong:** judging creation by 90-day MQLs. A launch spike then irregular publishing. Starting with a podcast. Five programs at once. Producing content before any distribution exists.

---

## Paid search  (FW-DEMANDGEN-005)

**When this matters:** buyers search for your category. Pipeline is behind and you need faster capture than SEO gives. A competitor bids on your brand. Tracking is live (or can be within a week) and a landing page can take traffic.
**Skip it when:** core category terms get under 500 searches a month. Conversion tracking is absent. ACV is under $1,500 and cost per click is over $15. You are pre-PMF (paid search amplifies conversion problems).

**Where you are**
- Tier 1 Reactive: no tracking, negatives, or cadence. First move: a brand campaign (under two hours).
- Tier 2 Building: clean the search terms report (these accounts often waste 20-35% of spend on irrelevant queries).
- Tier 3 Operating: offline conversion import, so bidding optimizes pipeline, not form fills.
- Tier 4 Compounding: full-funnel attribution sets budget by campaign type.

**First build, in order** (at least $2,000 a month)
1. **Conversion tracking** (3-4 hours) through Tag Manager, firing on the thank-you page. Nothing launches before it.
2. **Seed negative list:** 50+ terms in five groups (jobs, free tools, educational, definitional, competitor names).
3. **Brand campaign:** exact match on company, product, misspellings. Manual CPC $2-4, $500-1,500 a month, its own landing page.
4. **One non-brand campaign** on the most direct category term. Phrase and exact match only, 2-3 tight ad groups, a dedicated landing page, $1,500-3,000 a month. Broad match off for 30 days.
5. **Done when** tracking fires, brand has run two weeks, non-brand has 20-30 conversions, and the search terms report was reviewed twice.
6. **Then:** auto-tagging on and audience lists uploaded early (500+ members to activate). Offline conversion import with the click ID stored in the CRM (30 imported events before switching bidding to it). Responsive ads with 10+ distinct headlines. Landing pages with message match, four fields, mobile PageSpeed over 80. Competitor campaigns for the top 3-5 rivals, each with a comparison page.
7. **Cadence.** Weekly (30-45 minutes): search terms, pacing, cost per conversion, impression share. Monthly (2-3 hours): CRM pipeline, weakest Quality Scores, pages under 2%. Quarterly: keyword expansion and reallocation.

**Decision rules**
- If Seed and category volume is thin or tracking is missing, then skip search until the core term passes 500 searches a month.
- If Seed SMB with cost per click over $15, then run a 30-day, $2,000 test. Pause if cost per MQL exceeds 15% of ACV.
- If the account has no structure, tracking, or negatives, then rebuild it. Do not optimize it.
- If Tier 2 and no offline import (HubSpot or Salesforce), then do it first. It is a 2-4 hour job and the biggest gain at this tier.
- If brand impression share is under 80%, then fund brand before non-brand. Over 90% and tight budget, move 15-20% of brand spend to the best non-brand campaign.
- If monthly conversions are under 50, then phrase and exact only. At 100+ non-brand conversions, test broad match capped at 15-20% of non-brand spend, never over 25% without 500+ negatives.
- If a campaign has under 30 conversions a month, then manual CPC. Above 30 with 60+ days of data, move to target CPA at 120% of current manual CPA and allow 4-6 weeks.
- If category cost per click is high, then try niche phrases. Lintel guidance: 60-80% cheaper with 20-40% higher conversion.
- If a non-marketer runs it, then warn about three Google defaults: broad match everywhere, Display Network on search campaigns, and auto-applied recommendations.
- If an agency runs it, then hold it to cost per MQL and per opportunity, not cost per lead.
- If leads sit unworked for days, then fix response before touching the account.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Cost per click | SMB $3-12, mid-market $10-35, enterprise $25-80, brand $0.50-4 | Lintel guidance |
| Click-through | Brand 10-25%, non-brand 3-7%, competitor 2-5% | |
| Conversion rate | Brand 15-35%, non-brand dedicated page 3-6%, homepage 1-2% | |
| Cost per demo request | SMB $50-200, mid-market $150-500, enterprise $400-1,200 | |
| Cost per MQL | SMB $100-400, mid-market $300-900, enterprise $800-2,500 | Keep under 10% of ACV |
| Cost per opportunity | 20-30% of ACV | Judge at 90 days |
| Impression share | Brand over 90%, priority non-brand over 60% | |
| Return | Pipeline over 5x spend at 180 days, closed-won over 3x at 12 months | With offline import live |

**Where it goes wrong:** broad match before tracking. Eight campaigns with thin data instead of two clean ones. Sending paid traffic to the homepage. Mistaking a running account for a working system.

---

## Paid social  (FW-DEMANDGEN-006)

**When this matters:** inbound is too small or lumpy. Your ICP can be described by title, seniority, size, and industry. Sales cycles run over 30 days. You have an offer worth clicking. ACV is over $10K (under $3K the math is hard).
**Skip it when:** the ICP is undefined or you are pre-PMF. The landing page does not convert. Sales cannot close the leads you have. Budget is under $2,000 a month.

**Where you are**
- Tier 1 Reactive: one LinkedIn campaign, one audience, one creative, to learn the cost of reaching an ICP buyer.
- Tier 2 Building: a second campaign, Meta retargeting, cost per SQL tracked.
- Tier 3 Operating: separate awareness, consideration, and conversion campaigns with CRM attribution.
- Tier 4 Compounding: ABM against named accounts, with a creative test log.

**First build, in order**
1. **Turn the ICP into targeting** (2-3 hours) from 10-20 closed-won deals: top 2-3 titles, size range, industries. No closed deals means skip paid social.
2. **Build one offer worth clicking** (1-2 weeks): a benchmark report, framework, or original data study about the problem, not the product. Cold audiences will not book a demo.
3. **Build a dedicated landing page** (3-5 hours): headline matches the ad, four fields, under 3 seconds on mobile, one proof element.
4. **Launch one LinkedIn campaign:** website conversion objective, audience 50,000-200,000, at least $100 a day, maximum delivery bidding, 2-3 image ads with one image and different headlines (under 150 characters), UTMs.
5. **Hands off for 30 days.** Weekly check only. Changes reset learning.
6. **Expand when** you have a 30-day baseline, 20 leads reviewed with sales, working UTMs, and a page converting 5%+. If under 30% of leads are ICP-fit, narrow targeting first.
7. **Then:** CRM attribution before scaling. Meta retargeting after 60-90 days, once the site audience passes 1,000. An offer ladder (research, then webinar or case studies, then demo or trial). New creative every 4-6 weeks, 3+ variants live, one variable per test. A follow-up SLA with sales.

**Decision rules**
- If Seed and SMB ACV, then do not start. Outreach validates the ICP faster.
- If Seed with mid-market or enterprise ACV, then a narrow $2,000-3,000 LinkedIn test is ICP research, not a pipeline plan.
- If Series A or B with a volume gap, then start now at $3,000 a month minimum.
- If Series A SMB, then test 60 days at $3,000. Cost per customer over 30% of ACV means shift to Meta and Google search.
- If the operator is a non-marketer, then apply your close rate to LinkedIn's $100-400 per lead. Cost per customer under 25% of ACV works. Over 40% does not.
- If targeting cold, then the gated offer. Demo requests are for warm retargeting.
- If sales says leads are poor, then measure ICP fit on 30-50 leads before changing targeting. Under 35% fit, narrow titles. Over 50% fit with lead-to-SQL under 10%, check follow-up speed first.
- If cost per lead rises over 40% unchanged, then check frequency (rotate above 4), competitor CPM, and season, in that order.
- If sales wants a cut on last-touch data, then build first-touch and pipeline-influence reports first.
- If healthtech or fintech, then check Meta's special ad category limits and expect cost per lead 30-50% higher.
- If spend is under $15K a month, then manage in-house. The company keeps ICP, offers, allocation, and attribution even with an agency.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Cost per lead | LinkedIn $80-300, Meta retargeting $40-120, Meta cold $60-200 | Lintel guidance |
| Cost per SQL | Mid-market $300-900, enterprise $800-3,000 | |
| Landing page conversion | Gated content 8-18%, cold demo 2-6%, warm demo 8-15%, webinar 15-30% | |
| Click-through | LinkedIn 0.4-0.8%, Meta 0.8-1.5% | |
| Frequency | LinkedIn 2-4 a month, Meta 3-6 | Rotate creative past it |
| Lead-to-SQL | Well-targeted 20-35%, broad 5-15%, lead gen forms 5-15% | |
| Pipeline per dollar | $4-10 within 90 days at maturity | |
| Budget mix | Tier 1 all LinkedIn; Tier 2 65/35 LinkedIn/Meta; Tier 3 about 50/30, plus 15% ABM and 5% thought leader ads | |

**Where it goes wrong:** LinkedIn and Meta at once on a small budget. A demo request as the only cold offer. Weekly targeting changes. Judging at two weeks. Optimizing cost per lead over ICP fit. An agency owning attribution reporting.

---

## Retargeting and display  (FW-DEMANDGEN-008 owns retargeting, FW-DEMANDGEN-007 owns display and programmatic)

**When this matters:** 1,000+ monthly unique visitors (or a contact list over 500) and nobody is re-engaged. Traffic is fine but conversion is flat. Trials pile up unconverted. High-ACV prospects go quiet between calls. Search and social audiences are saturating (display).
**Skip it when:** traffic is under 500 monthly visitors (install the pixel, spend nothing). No ICP, no landing page, or pre-PMF. Search and social are not yet profitable. Programmatic budget is under $5,000 a month.

**Where you are**
- Tier 1 Reactive: pixel installed and three audiences built (all visitors, high-intent pages, customer exclusion).
- Tier 2 Building: audiences split by funnel stage, sequential messaging, customers suppressed. A DSP comes only after audiences are validated.
- Tier 3 Operating: CRM lists beside pixel audiences, separate trial and MQL non-converter programs, private marketplace deals.
- Tier 4 Compounding: dynamic creative by page viewed and view-through in attribution.

**First build, in order**
1. **Pick one platform** (1-2 hours): LinkedIn for sales-led, Google or Meta for PLG.
2. **Install the pixel on every page** (2-4 hours) and confirm it fires on home, pricing, demo, and thank-you. If tracked visitors divided by analytics visitors is under 0.4, do server-side tracking first.
3. **Build three audiences before spending:** all visitors (30 days), pricing, demo, and contact visitors (14 days), and a customer exclusion list. No campaign launches without the exclusion.
4. **Give each audience one goal and a matching landing page,** one ad each, a cap of 5 impressions per user per week. High-intent gets a direct ask. Broad gets a resource or proof.
5. **Expand** after 30 days once the high-intent audience tops 200 users and converts 3%+. Start at $500-2,000 a month.
6. **Full build:** at least five audiences (add content engagers and form abandoners), CRM uploads, view-through windows set to 0-1 day (platform defaults overcount), a three-ad sequence (problem, differentiation, direct ask), weekly suppression sync. Minimum audience to launch: 300 on Meta and Google, 1,000 on LinkedIn.
7. **Display:** conversion tags first, three creative sizes (300x250, 728x90, 160x600), Google's network at $1,000-2,000 a month. Non-marketers should pick an ABM platform with managed service over a self-serve DSP. Add viewability and invalid-traffic verification. CTV is a Tier 3 test.

**Decision rules**
- If PLG with 200+ unconverted trials a month, then run trial-to-paid retargeting from a CRM list at $500-1,000 a month, with a holdout cohort to measure lift.
- If pixel match is under 40%, then fix server-side tracking before scaling and lean on CRM audiences meanwhile.
- If sales-led with ACV over $25K, then measure pipeline influence, not direct conversions. At ACV under $10K, push direct asks.
- If retargeting cost nears cold cost with healthy frequency, then the broad audience is diluting the high-intent one. If it costs 3-5x high-intent, cut it.
- If budget is under $500 a month, then one audience (pricing and demo visitors, 14 days), capped at 4 a week.
- If retargeting influences over 15% of pipeline at Series C+, then hold out 15-20% of the audience for 30-60 days to test incrementality.
- If budgets are cut, then protect retargeting and cut prospecting first.
- If programmatic shows zero influenced pipeline after six months, then check measurement, reach, creative stage, attribution window, and invalid traffic before killing it.
- If EU audiences lack a consent platform, then pause cookie-based retargeting for them.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Retargeting click-through | Google 0.3-0.8%, LinkedIn 0.4-1.0%, Meta 0.8-2.0% | High-intent runs 50-100% higher |
| Conversion after click | High-intent to demo 5-15%, mid-funnel to download 10-25%, broad 1-5% | |
| Cost per acquisition | 30-60% below cold paid social | Parity means exhaustion |
| Frequency | 3-5 a week healthy, 5-8 with sequences, over 8 is exhaustion | Programmatic prospecting runs 2-4 a month |
| Pixel match | Over 60% healthy, 40-60% normal, under 40% fix | |
| CRM match rate | LinkedIn 40-55%, Meta 50-70%, Google 40-65% | Under 25% is a data problem |
| Retargeting budget split | High-intent 40-50%, CRM re-engagement 20-30%, trial non-converts 30-40% (PLG), broad 10-20% | |
| Display CPM | Google retargeting $6-15, DSP $15-40, CTV $25-60 | B2B display click-through is 0.05-0.12%. Value shows as view-through |

**Where it goes wrong:** pixel on the homepage only. No customer exclusion list. Daily budget set before checking audience size ($50 a day on 300 people is 12+ impressions each a week). Default view-through windows that inflate results. Display with no conversion pixel.

---

## Outbound support  (FW-DEMANDGEN-003)

Covers the mechanics marketing supports. BDR team structure and management belong to FW-SALES-002.

**When this matters:** PMF and ICP are validated but inbound will not hit the target. The ICP is narrow enough for a finite account list. ACV is over $10,000. Reps spend 40%+ of their time sourcing pipeline.
**Skip it when:** the ICP is undefined or you are pre-PMF. ACV is under $5,000 (use short automated sequences to a list under 500, or paid capture). The category is so new that prospects do not know the problem.

**Where you are**
- Tier 1 Reactive: no list logic. First move: 20 personalized messages to top-fit accounts.
- Tier 2 Building: sequences run in a tool with reply and meeting benchmarks and subject tests.
- Tier 3 Operating: intent data prioritizes accounts, high-value accounts are multi-threaded.
- Tier 4 Compounding: signals enroll accounts in sequences automatically.

**First build, in order**
1. **Build a 100-account list** (3-5 hours) from ICP criteria, one verified business-email contact in the buyer role each.
2. **Write five emails plus one LinkedIn touch** (3-5 hours). Day 1 (100-130 words): one specific observation, one line on what you do, a soft ask. Day 3: LinkedIn. Day 5 (75-100): content or data. Day 8 (50-75): a question. Day 12 (75-100): a relevant result. Day 17 (40-50): a short break-up note.
3. **Track every contact** in a sheet: step, reply type, meeting booked.
4. **Send 5-10 a day over 30 days.** Use a separate sending domain or subdomain with SPF, DKIM, and DMARC in place, and validate every address (see the deliverability block).
5. **Decide at day 60.** Positive reply rate over 1%: scale. Under 1%: check the list, then the message. Move on after 200 contacts, 1%+, and 5+ meetings.
6. **Full build:** a tiered account list, one sequence per persona, trigger sequences (funding, executive hire, job posting, launch) of 3-4 steps, and a re-engagement sequence with a new angle. Apollo suits Seed and Series A. Outreach or Salesloft only with 3+ BDRs and a manager. Share the account list with the paid team.

**Decision rules**
- If reply rate is under 2% for 30 days, then pull the last 50-100 contacts. Under 70% ICP match means fix the list. At 70%+ rewrite the opening line and test on the next 100. Change one thing at a time.
- If bounces or complaints spike, then pause the domain and follow the deliverability incident steps.
- If Seed, then the founder owns outbound. Credibility beats volume and the aim is learning.
- If reply rate falls 0.5+ points a month for three months, then refresh sequences, then expand the list, then change channel.
- If BDRs are measured on activity, then move to meetings held and opportunities, keeping activity as a floor.
- If outbound is the only pipeline source, then start inbound at $3,000-5,000 a month.
- If contacts are in the EU, UK, or Canada, then get a legal review for GDPR and CASL first.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Reply rate | 3-8% | Under 3% is list or message |
| Positive reply rate | 1-3% | Need 100+ contacts for a first read |
| Reply-to-meeting | 40-60% | Under 40% is response handling |
| Meeting held | 70-85% | Add reminders below 70% |
| Meeting-to-opportunity | 30-50% | Under 30% points at list or discovery |
| Cost per outbound opportunity | $800-3,000 mid-market, $2,000-8,000 enterprise | Under 10% of ACV. Lintel guidance |
| Contacts per BDR a day | 40-80 personalized, 80-150 templated | |
| Unsubscribes per step | Under 0.5% | |

**Where it goes wrong:** 100 emails in one day. An opening line about the sender. Quitting after 30 contacts (at 2% that is 0.6 replies). Using the primary domain. One sequence for every persona.

---

## Inbound as a pipeline channel  (FW-DEMANDGEN-002)

Covers inbound as a pipeline source. Content and SEO strategy is FW-CONTENT-001.

**When this matters:** the ICP is validated and there is no organic traffic. Paid cost per MQL is rising. Referred prospects close at higher rates than outbound ones.
**Skip it when:** the ICP is unvalidated. You need pipeline inside 6-12 months. The category has under 1,000 monthly searches across relevant queries (distribute through LinkedIn and communities instead).

**Where you are**
- Tier 1 Reactive: a blog, under 500 organic visits a month, no inbound MQL tracking.
- Tier 2 Building: briefs, a keyword plan by funnel stage, offers per stage, organic MQLs tracked.
- Tier 3 Operating: all stages covered, nurture running, organic 20-30% of MQLs.
- Tier 4 Compounding: organic 30-40%+ of MQLs, older content paying at near-zero marginal cost.

**First build, in order**
1. **Find five ICP queries** (3-5 hours): ask 3-5 customers what they typed into Google and what they asked before they knew the category existed.
2. **Write one definitive piece** (8-16 hours), 2,000-3,000 words, answer in the first 200 words.
3. **Add a conversion mechanism** (1-2 hours): a download for early-stage readers, a demo request for late-stage.
4. **Publish and distribute,** then measure at 60-90 days. Move on when three pieces get traffic, one organic lead is ICP-fit, and the form works.

**Decision rules**
- If pipeline is short, then run paid and outbound now and build inbound alongside. Never cut inbound to fund a short-term fix.
- If adding inbound to a paid program, then start with comparison, alternative, and pricing pages. Early-stage content takes 12-18 months.
- If traffic is over 5,000 sessions but MQLs are under 20 a month, then fix conversion on the top 10 pages before writing more.
- If 50+ pieces yield under 5 page-one rankings, then move 30-40% of effort to earning links.
- If cutting budget, then cut new production before refreshing top performers.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Organic traffic growth | 5-10% a month | Under 2% means no traction |
| Inbound share of MQLs | Series A 15-25%, B 25-35%, C+ 35-45% | |
| Cost per inbound MQL | Series A $80-150, B $50-100 | Fully loaded |
| Nurture-to-MQL in 90 days | 3-8% | Under 2% means triggers miss intent |
| Time per piece | 7-13 hours | |

**Where it goes wrong:** a 500-word first piece. Publishing with no conversion path. Judging at 30 days. Writing about the product. Calling a blog a program with no intent targeting or MQL tracking.

---

## Lead capture, conversion, and scoring  (FW-DEMANDGEN-004, with scoring from FW-DEMANDGEN-001, FW-DEMANDGEN-002, FW-MAIL-001)

**When this matters:** traffic and leads exist but conversion is under benchmark. Cost per MQL is rising. Pages have run untouched for six months. MQL-to-SQL is under 20%. You are about to scale paid spend.
**Skip it when:** a page gets under 500 visits a month (fix obvious problems and grow traffic). The ICP is unvalidated or you are pre-PMF.

**Where you are**
- Tier 1 Reactive: fix basics on the top five pages.
- Tier 2 Building: A/B test the top page, headline first.
- Tier 3 Operating: a prioritized test backlog with heatmaps.
- Tier 4 Compounding: weekly tests and personalization.

**First build, in order**
1. **Install measurement** (2-4 hours): GA4 conversion events and Microsoft Clarity (free) on the top five pages.
2. **Baseline 30 days** with no changes. Watch 10-20 recordings per page.
3. **Fix the obvious** (1-2 weeks): mobile speed, forms across browsers, broken links. New 30-day baseline.
4. **Run the first A/B test** (30-60 days): one hypothesis, headline first, sample size set up front, at least 14 days, no other changes, results checked weekly at most.
5. **Map the conversion chain:** rate, benchmark, and pipeline gain from a 20% lift at each stage. Often the biggest hole is MQL-to-SQL, which page tests cannot fix.
6. **Score and queue.** Score pages on the LIFT model (WiderFunnel): benefit headline, ad-to-page match, form length, proof, one call to action. Rank 10-20 hypotheses with PIE (potential, importance, ease).
7. **Write the MQL criteria down** as fit, behavior, and disqualifiers. Scoring automates it. Basic scoring in HubSpot or Marketo is enough through Tier 2. No AI scoring before 6+ months of conversion data.
8. **Start with these weights, as hypotheses to calibrate.** Pricing, demo, or trial page visit, tour completion, or 3+ case study views in a session: +20-30. A mid-funnel download or webinar signup: +5-15. Blog visit, generic download, email open: +1-5. Lose 5-10 a week after 30 silent days. Email: open +2, click +5, click to pricing or demo +15, sequence finish +5, unsubscribe -10. Subtract for competitor domains, student emails, and irrelevant functions. Set the MQL line where history shows 20%+ MQL-to-SQL and recalibrate quarterly after 3-6 months. Routing and model design: FW-REVOPS-002.
9. **Route by intent.** Demo requests and trial sign-ups qualify automatically and reach an account executive in minutes, with a CRM task and alert. Downloads and newsletter sign-ups go to nurture. Give reps a template that cites the page that produced the lead.
10. **Forms:** first name, last name, work email, company, labels above fields. Enrich instead of adding fields.

**Decision rules**
- If there is no baseline, then no testing.
- If a demo page converts under 3% against 8-15%, then audit with LIFT and fix the largest problem before any test.
- If MQL-to-SQL is under 15% and pages meet benchmark, then work the handoff (criteria, routing, first touch), not the site.
- If a paid page converts 40% below the site average, then fix message mismatch: match the headline to the ad or keyword.
- If conversion rose but pipeline did not, then compare the MQL-to-form-fill ratio before and after.
- If five or more tests were inconclusive, then check traffic per variant, test bigger variables, and stop ending early.
- If enterprise demo conversion is under 3%, then test a direct meeting request, an expert chat route, or gated research.
- If email tests are planned, then 500 recipients per variant for subject lines, 200 per variant for outbound steps.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Visitor-to-lead | Demo request 8-15%, content download 5-12%, free trial 5-10%, newsletter 2-5% | Well-optimized B2B pages |
| Lead-to-MQL | 10-25% | |
| MQL-to-SQL | 20-30% | Under 15% is critical |
| Demo-to-opportunity | 30-50% | Under 25%: pre-qualification or the demo |
| Form abandonment | 20-35% fine, over 50% a barrier | |
| Page speed | Main content under 2.5 seconds, layout shift under 0.1 | Fix before testing |
| A/B win rate | 30-40% | Under 20% over 5+ tests: hypotheses lack evidence |

**Where it goes wrong:** testing before a baseline. Testing low-traffic pages. Starting with button color. Forms not wired to the CRM. Ending tests early. Treating form fills as pipeline.

---

## Email program strategy and list health  (FW-MAIL-001)

**When this matters:** 500+ contacts and no systematic program. Open, click, and conversion rates were never measured. Sales runs outbound but nothing nurtures inbound leads, trials, or subscribers. Warm-list opens fell under 20%.
**Skip it when:** under 200 contacts and no lead capture. The motion is purely outbound (an SDR topic). You are pre-PMF (send simple manual emails). SPF, DKIM, and DMARC are missing and bounces exceed 5%.

**Where you are**
- Tier 1 Reactive: ad hoc sends. First move: audit the list by source and take a bounce, complaint, and unsubscribe baseline.
- Tier 2 Building: each segment has a program type and cadence, and the first full program runs.
- Tier 3 Operating: behavioral segments by product use, engagement, and lifecycle stage.
- Tier 4 Compounding: email tied to pipeline and revenue instead of opens and clicks.

**First build, in order**
1. **Audit and segment** (2-3 hours) into prospects, customers, and everyone else.
2. **Verify SPF, DKIM, and DMARC** (see the deliverability block).
3. **Tag every link:** source is always email, medium is the program type (newsletter, nurture, lifecycle, product, transactional), campaign is the program, content is the email number. One shared builder sheet.
4. **Create a master suppression list** (30 minutes): unsubscribes, competitors and internal addresses, contacts sales is actively working. Exclude it from every send.
5. **Build one program** for the highest-value segment (3-5 hours), usually a 4-5 email nurture at days 0, 3, 7, 14, and 21. Move on after three segments, passing authentication, UTMs in use, and 30 days of results.
6. **Full build:** a health audit (volume, hygiene, 90-day engagement); four fields (lifecycle stage, lead source, last engagement date, opt-in status) with enrollment and exclusion rules; a program map (audience, trigger, objective, cadence, exits, suppression, success metric); and four triggers (pricing or demo visit escalates to sales, 3+ opens or 2+ clicks adds a sales task, trial sign-up moves to onboarding, 90 days inactive starts a two-email re-engagement).

**Decision rules**
- If Seed and founder-led, then the founder emails personally in plain text monthly. No marketing platform until the list passes 200-300.
- If complaints exceed 0.1% or known contacts hit spam, then pause non-critical sends, fix, and resume to the most engaged 20%, expanding over 2-4 weeks.
- If PLG, then trial activation comes first (next block).
- If the reader is a non-marketer, then one program: a prospect nurture or new-customer onboarding, whichever fixes the bigger problem.
- If the list has been silent 90+ days, then validate, segment by last engagement, send to the freshest first, and wait 5-7 days. Continue only if complaints are under 0.05%.
- If newsletter unsubscribes exceed 0.3% a send, then send only to people who opened 2+ prior issues or opted in for it. Expect a 30-40% smaller audience.
- If any contacts were purchased, then remove them and never send. Build by opt-in only.
- If EU contacts lack documented consent, then send one reconfirmation and remove non-confirmers.
- If engagement is high but pipeline near zero, then the audience is not the ICP. Under 30% ICP-fit means rebuild acquisition.
- If solo, then build in this order: prospect nurture, onboarding, newsletter, re-engagement, trial activation, 60 days apart.
- If open rates are poor, then suspect segmentation before subject lines.
- If choosing a platform, then CRM-native email suffices under 2,000 contacts and two programs. Above that, or with 3+ behavioral programs, use a dedicated tool. On a minimal budget, buy content before features.

**Numbers that matter** (the email metrics that matter, in one table)
| Metric | Benchmark | Note |
|---|---|---|
| Open rate | Newsletters 25-45%, nurture 30-50%, customer lifecycle 40-60% | Apple Mail privacy (2021) inflates opens. Compare to your own baseline |
| Click-to-open | 8-20% healthy, under 8% weak call to action, over 25% strong | Other files quote 15-25%. Use this range |
| Click rate | Newsletters 2-5%, nurture 4-10% | |
| Unsubscribe per send | Under 0.2% healthy, over 0.5% audience mismatch | Over 15% of the list a year is a relevance problem |
| Hard bounce | Under 1% healthy, over 2% hygiene, over 5% damages reputation | |
| Spam complaints | Under 0.05% safe, 0.1% is the action line | |
| Inbox placement | Over 90% healthy, under 80% a problem | |
| Net list growth | 5-15% a year | |
| 90-day newsletter engagement | Over 40% healthy, under 25% a problem | |
| Nurture completion | Over 60% through five emails, under 40% a problem | |
| Email-influenced pipeline | 15-30% of new pipeline at Tier 3+ | 30-60 day lookback |

**Where it goes wrong:** blasting the full list. Designing before fixing deliverability. Several programs before one is validated. Adding contacts without permission. A full-list send after a long silence.

---

## Lifecycle automation and nurture  (FW-MAIL-002)

**When this matters:** leads or sign-ups get no automated follow-up. Trial-to-paid is under 20%. People send onboarding emails by hand. First-90-day churn runs high. The automation tool sends only newsletters.
**Skip it when:** the list is under 200 with no steady lead source. The platform is not connected to the CRM or product data. You are pre-PMF or deliverability is broken.

**Where you are**
- Tier 1 Reactive: build the confirmation that sends within five minutes of a form fill.
- Tier 2 Building: a full prospect nurture, with high-intent contacts escalated to sales early.
- Tier 3 Operating: sequences branch on behavior, not a fixed calendar.
- Tier 4 Compounding: a master enrollment model moves contacts between sequences as stage changes.

**First build, in order**
1. **Pick the one sequence that moves revenue most** (30 minutes): sales-led, the immediate response and nurture for the main inbound event. PLG, trial activation. One only.
2. **Map it** (1 hour): trigger, timing (email 0 within 5 minutes, then day 3 and day 7), one specific call to action each, exits (trial, demo request, unsubscribe, purchase), and where completers go.
3. **Write it** (2-4 hours): 150-250 words, one call to action, a helpful colleague's voice, value before product.
4. **Configure and test** (1-2 hours): suppression, exits, UTMs, a test run to yourself.
5. **Add one behavioral exit** (30 minutes): a pricing-page visit removes the contact and creates an SDR task.
6. **Full build.** Write an enrollment document first (per sequence: entry, every exit, destination, conflicts) and update it before every change. Then:
   - Immediate response: email 0 delivers the resource in about three sentences with no pitch. Days 3, 7, 14, and 21 deepen the topic, soften toward an offer, and close.
   - Prospect nurture: problem (emails 1-2, no product), solution exploration (3-4), vendor consideration (5-7). Fast-track branch for 3+ opens in 7 days plus a click. Stalled branch for no opens by day 10.
   - Trial activation (needs the first value milestone, FW-CUSTMKT-002): welcome within five minutes naming one step, day 1 steps, a day 3 split by milestone reached, day 7 peer example, day 14 check-in from a CS lead, day 21 nudge, day 27 expiry.
   - MQL handoff: 2-3 emails from the SDR's name, SDR task, follow-up within 24 hours.
   - Re-engagement at 90 days inactive.

**Decision rules**
- If Seed and founder-led, then one email that sends within five minutes of any sign-up is the whole program.
- If trial-to-paid is under 15% and there is no activation sequence, then build it first (12-20 hours). Lintel guidance: a 5-15 point gain.
- If product events do not reach the email tool, then fix that first. Fallback: a weekly 30-60 minute manual flag by CS.
- If SDR sequences and marketing email hit the same prospect, then share a suppression list (4-8 hours).
- If activation emails are opened (40%+) but first-value achievement is under 50%, then the product is the constraint. Do not tune email.
- If Tier 2 has no branching, then add the pricing-page exit and a day-7 non-opener recovery first.
- If several sequences run with no enrollment document, then stop adding and write it (2-4 hours).
- If there is no re-engagement sequence, then build one. Lintel guidance: opens commonly rise 3-8 points in 60-90 days.
- If engagement is strong but pipeline flat, then check UTMs, whether calls to action reach conversion pages, and ICP fit.
- If someone proposes custom automation, then buy a platform. Custom builds rarely pay below 1,000 employees.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Sequence completion | 40-60% | Over 60% may mean exits never fire |
| Exit mix | 15-25% behavioral, 10-20% conversion, under 5% unsubscribe | |
| Behavioral exit rate | Over 10% good, under 5% check triggers | |
| Opens by position | Over 30% for the first three emails | Under 25% at email 2 or 3 means broken continuity |
| Click-to-open per email | Over 12% | Under 8%: vague call to action |
| Trial-to-paid (PLG) | 15-25% typical, 25-40% well-optimized | |
| First value milestone reached | Over 70% target | Under 50% is critical |
| SDR follow-up within 24 hours | Over 85% | Under 70%: escalate with data |
| Re-engagement recovery | Over 20% (90-180 days inactive), over 10% (180-365) | |

**Where it goes wrong:** a ten-email sequence before a three-email one works. Pitch before value. Going live untested. No conversion exit, so a trial user still gets nurture. Treating trigger logic as a copywriting problem.

---

## Deliverability and email operations  (FW-MAIL-003)

**When this matters:** opens fell 15+ points in six months with no content change. A send drew complaints over 0.1% in 30 days. Known contacts see your email in spam. SPF, DKIM, or DMARC is missing (Google's 2024 bulk sender rules made authentication mandatory). You are changing platforms or mailing a new segment.
**Skip it when:** under 200 contacts and one or two sends a month (still do the SPF, DKIM, and DMARC basics). No program has launched yet (authenticate first, skip heavy monitoring).

**Where you are**
- Tier 1 Reactive: authentication unverified. First move: the free MXToolbox check (15 minutes).
- Tier 2 Building: Google Postmaster Tools and Microsoft SNDS registered.
- Tier 3 Operating: a marketing subdomain and quarterly audits with inbox placement tests.
- Tier 4 Compounding: automated alerts and a written incident playbook.

**First build, in order**
1. **Check authentication** (15 minutes): SPF, DKIM (with your platform's selector), and DMARC on MXToolbox.
2. **Add missing records** (30-60 minutes, plus 24-72 hours to propagate), using your platform's values. Start DMARC at `p=none` with a report address. Only one SPF record per domain, so add senders to the existing one.
3. **Register Google Postmaster Tools** and Microsoft SNDS. Targets: reputation High, spam rate under 0.10%.
4. **Create a marketing subdomain** (for example `email.company.com`), and test it before a live send.
5. **Validate the list** (1-2 hours, about $15-50 per 5,000 addresses). Suppress invalid addresses and send risky ones in small batches.
6. **Full build:**
   - Separate subdomains for marketing, product notifications, and sales outbound.
   - DMARC schedule: month 1 `p=none`, month 2 `p=quarantine; pct=10`, month 3 `pct=50`, month 4 `pct=100`, month 5 `p=reject`. Read reports for two weeks at each step. Alignment over 95% before quarantine.
   - Monthly inbox placement test (GlockApps, about $15-49 a month, or free Mail-Tester), Gmail and Outlook separately.
   - Quarterly hygiene: auto-suppress hard bounces, move 90-day-inactive contacts to re-engagement then suppress non-responders, validate segments unmailed for 60+ days, move role addresses (info@, support@) out of marketing.
   - Dormant lists: validate, then send by tier (90-180 days, 180-365, 365+). Wait 72 hours between tiers and continue only if spam rate is under 0.05%.
   - Pre-send checklist for sends over 500: marketing subdomain, suppression applied, right segment, working links with UTMs, tested unsubscribe link and header, HTML plus plain text, a recognizable sender, test sends in Gmail and Outlook.
   - IP warming (new platform, IP, or segment, or 90+ days dormant): week 1, 200-500 a day to people who opened in 30 days. Week 2, 500-2,000 (60 days). Week 3, 2,000-7,000 (90 days). Week 4, full volume. Halve volume if reputation slips to Medium. Pause if Low.

**Decision rules**
- If opens are falling, then check authentication, Postmaster reputation, complaint rate, the send before the drop, and inbox placement, in that order. Content last.
- If complaints pass 0.1%, then pause the domain, find the send, remove that segment, resume at 500-1,000 a day to engaged contacts, adding 20% daily. Expect 30-60 days to recover.
- If reputation drops to Medium or Low, then send to engaged contacts only and ramp over 30 days. Low takes 45-90 days to recover.
- If authentication fails, then fix DNS (24-72 hours). Reputation may need another 14-30 days.
- If a purchased list was mailed, then remove every address, pause 3-5 days, and plan 60-90 days at 200-500 a day to engaged opt-in contacts.
- If migrating platforms, then plan warming 60 days ahead, authenticate the new subdomain first, avoid the 30 days around a big campaign, and test placement after week two.
- If Gmail primary placement is under 85% and authentication passes, then it is usually the promotions tab. Simplify HTML, add plain text, cut images.
- If contacts come from paid gated-content ads, then double opt-in, a separate segment for 90 days, and monthly validation for six months.
- If DMARC has sat at `p=none` over 90 days with all senders identified, then move to quarantine at 10%. If reports show spoofing, go to reject.
- If you send under 50,000 a month to a clean opt-in list, then free tools are enough.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Domain reputation | High | Medium is developing trouble, Low is heavy filtering |
| Spam complaint rate | Under 0.05% excellent, under 0.10% the line | Over 0.30% triggers domain-level filtering |
| Hard bounce | Under 1% | Over 2% hygiene, over 5% damages reputation in 1-2 sends. Overrides the looser figure in FW-DEMANDGEN-003 |
| Soft bounce | Under 3% | |
| Inbox placement | Over 90% | Under 80% investigate |
| Authentication alignment | 99%+ | Under 95% investigate |
| 90-day engaged share of list | Over 30% healthy, under 20% a problem | Under 15% is mostly cold |
| List validity | Over 95% | Under 90%: poor acquisition sources |
| Platform delivery rate | Over 97% | Delivered is not the same as inbox |

**Where it goes wrong:** duplicate SPF records. DMARC to reject before reading reports. Skipping the subdomain test. Reading a placement drop as a content problem. Treating "delivered" as "in the inbox." A dormant list sent at full volume.

---

## Dropped

About 40 numbers and claims left out.

**Analyst-credited figures.** Removed every credit to named research firms. Kept a range only where useful, labeled Lintel guidance. Cut: a BDR productivity table (8-15 meetings a month, $200K-600K quarterly pipeline per BDR); BDR pay bands and tool price lists (owned by FW-SALES-002 and quickly stale); marketing CAC at 40-70% of blended CAC; "$36-42 per $1" email ROI; "$20-50 pipeline per $1" for lifecycle programs.

**Wrong math.**
- FW-DEMANDGEN-001 says the $3M, $40K ACV, 25%, 20% example needs about 600 MQLs a year. Its own inputs give 1,500 (shown above).
- FW-DEMANDGEN-004 calls a 3-point gain on 5,000 visitors "150 additional MQLs." Those are leads, not MQLs.
- FW-MAIL-001, -002, and -003 ROI worked examples (a seed case that yields $3,000 when its inputs give about $9,000, 70-125x, 40-80x, a $165,000 placement gain) stack assumptions. A "$3-8 a year" subscriber value had no source.

**Response-time claims.** Four files give different multipliers for contacting a lead in five minutes ("drops 80%," "9x," "50-70% lost after 72 hours," a named MIT study). None verified and they disagree. Kept only the SLA targets.

**Conflicts, settled by ownership.**
- Channel cost per MQL in FW-DEMANDGEN-001 conflicts with the channel files. Used the channel blocks.
- Creation share by stage differs between FW-DEMANDGEN-001 (A 20-25%, B 25-35%) and FW-DEMANDGEN-009 (A 10-20%, B 25-40%). Used FW-DEMANDGEN-009.
- FW-DEMANDGEN-009 says capture-only under $500K ARR in one place and no newsletter before $1-2M ARR in another, while its starter path makes the newsletter the default. Used the $1-2M or Series A line.
- Click-to-open is 15-25% in three demand gen files but 8-20% in FW-MAIL-001. Used FW-MAIL-001.
- Bounce and inbox placement limits in FW-DEMANDGEN-003 (3%, 85%) differ from FW-MAIL-003. Used FW-MAIL-003.
- Lead-to-MQL is 10-25% in FW-DEMANDGEN-001 and 15-30% in FW-DEMANDGEN-004. Used 10-25%.
- Retargeting frequency is 7 a week in FW-DEMANDGEN-007's setup and 3-5 in FW-DEMANDGEN-008. Used FW-DEMANDGEN-008.
- Paid minimums are $3,000-5,000 a month per channel (FW-DEMANDGEN-001, -006) versus $2,000 for search (FW-DEMANDGEN-005). Kept both, scoped.

**Unsupported or outdated.**
- FW-MAIL-003 says DMARC at `p=quarantine` or stricter is mandatory above 5,000 daily Gmail sends. I could not verify it. Left out.
- Pre-send spam score "under 3/10" runs opposite to Mail-Tester's scale, and FW-DEMANDGEN-003 says "above 9/10." Dropped both, plus the "under 5 links" rule and the banned-word list.
- FW-DEMANDGEN-004 lists First Input Delay as a Core Web Vital. Google replaced it, so only load and layout thresholds remain. Also dropped "5-20x CRO ROI" and a "15-25% personalization lift."
- FW-DEMANDGEN-006's "30-50% outbound reply lift from coordinated ads" and customer cost of $1,200-4,500 (far below FW-DEMANDGEN-001's $5K-20K). FW-DEMANDGEN-007's viewability and invalid-traffic industry averages. BIMI open lift and cost. "Free tools diagnose 90% of problems."
- FW-DEMANDGEN-002's domain authority targets, click-through by rank, and page benchmarks (SEO belongs to FW-CONTENT-001). FW-DEMANDGEN-009's analyst relations path (it named research firms).

**Worried about:** every cost and conversion range across the paid channels is a broad library figure with no outside source. Treat them as starting points to replace with the company's own data after 60-90 days.

## Credit

- **LIFT model and PIE framework** (conversion audits and test ranking): WiderFunnel (Chris Goward).
- **Long-run brand and activation split:** Les Binet and Peter Field, adapted for B2B by the B2B Institute at LinkedIn.
- **95-5 rule** (about 5% of B2B buyers are in market at a time): John Dawes, Ehrenberg-Bass Institute.
