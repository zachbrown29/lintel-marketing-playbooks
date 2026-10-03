# Sales handoff and revenue operations

How to pass leads from marketing to sales, qualify them, staff the development function, and build the pipeline data that makes forecasting and attribution possible. For a marketer or founder at a seed to Series B B2B software company.

**Owns:** the MQL and SQL definition, routing and follow-up SLAs, the sales-to-marketing feedback loop, when to hire the first and second SDR or BDR, qualification methodology selection, pipeline stage definitions, forecasting, CRM data hygiene, lead scoring and routing mechanics, marketing-sourced and marketing-influenced attribution, and channel CAC.

**Does not own:**
- Which motion to run at all (product-led, sales-led, outbound, partner, community) and motion-level CAC and payback: FW-FOUND-005.
- Which tool categories the stack needs and the CRM foundation choice: FW-FOUND-007. Which vendor to buy, renew, or cut: FW-OPS-003.
- Pricing model, price level, and the annual pricing review: FW-GROWTH-005. Tier design and pricing page: FW-EMERGING-013.
- The ICP document itself: FW-FOUND-001.
- Conversation intelligence and the full enablement content library: FW-EMERGING-008.
- Demand generation spend and channel programs: the demand generation frameworks.

---

## The marketing-to-sales handoff  (FW-SALES-007)

**When this matters:** Sales and marketing disagree on what a qualified lead is, even informally. Marketing generates leads sales does not work, or works slowly. Pipeline coverage swings while marketing spend stays flat. Each function blames the other. You are about to add headcount to either side and have no shared operating model.

**Skip it when:** Sales and marketing are the same person and no split is planned in the next 6 months. The company has not yet shown repeatable pipeline from any source. Product-market fit is unconfirmed. Combined sales and marketing headcount is under 3.

**Where you are**
- Tier 1 Reactive: MQL and SQL exist as words, not written definitions. Reps pick leads by instinct. Marketing reports lead volume, sales reports pipeline, neither cites the other.
- Tier 2 Building: Both definitions are written and both functions use them. Routing is automated. An SLA exists but compliance is patchy. Joint meeting happens monthly. Disposition data is partly captured, never reviewed.
- Tier 3 Operating: All four parts are present (shared definitions, shared data, feedback loop, accountability). SLA compliance above 80%. Marketing changes targeting based on disposition data. Attribution is agreed and reported the same way every time.
- Tier 4 Compounding: A RevOps layer owns the mechanics. Attribution is multi-touch with agreed weights and feeds budget. Marketing and sales co-own new ARR and co-present one forecast.

**First build, in order**
1. Book a 90-minute joint session. Required: whoever runs marketing, whoever runs sales, and at least one rep who has been on recent discovery calls. One output only, a written MQL definition.
2. Before that session, have each function write its current implicit criteria separately. Compare them. The gaps are the agenda. They are almost always wider than either side expects.
3. Write the definition from the last 10 closed-won deals. For each: company size, industry, job title of the first contact, the action that created the lead, and days to close. The shared characteristics are the criteria. The definition must cover firmographic, persona, behavioral, and timing criteria with specific thresholds ("visited pricing page at least once in the last 30 days or submitted a demo request"), not adjectives like "high engagement". 2 hours. No lead score yet.
4. Confirm CRM routing sends a qualifying lead to the right rep or queue within 15 minutes. Test with 3 to 5 records before going live. 2 to 4 hours of configuration.
5. Write the follow-up SLA as one rule and send it to the sales team: demo requests and pricing page visits get a contact attempt within 1 business hour, everything else within 24 business hours. 30 minutes.
6. Run it for 30 days untouched. Track MQLs created, percentage contacted inside SLA, MQL to SQL, and SQL to opportunity. Then hold a 60-minute review and revise the definition if it is producing the wrong leads.
7. Add MQL disposition reasons as a required CRM picklist that must be filled before the record leaves MQL stage. Use 5 to 7 options: not ICP fit, wrong persona, not in active evaluation, already a customer, no response after 3 attempts, duplicate or invalid, qualified and advancing. Do not include "other". It absorbs everything useful.
8. Put a standing 30-minute biweekly review on the calendar between the marketing lead and the SDR lead. Agenda: disposition by source and segment for the last 2 weeks, any single reason above 20%, the input that caused it, and one assigned action with an owner and a date. Review last meeting's actions first.
9. Write the marketing response protocol in advance: a source above 25% not-ICP-fit in any 30-day window gets paused or requalified; a segment above 30% wrong-persona gets a targeting review; an MQL-to-SQL drop of more than 10 percentage points against the prior 90-day average triggers a joint review inside 5 business days.
10. Only then add shared scorecard metrics, a monthly Demand Review with a fixed agenda, and a written inter-function SLA reviewed every 6 months.

**Decision rules**
- If lead quality is the pipeline gap and there is no agreed written MQL definition, fix the definition before touching targeting, channels, or spend. Quality problems start as definition problems.
- If volume is the pipeline gap and there is no feedback loop, do not increase spend. More volume at the same disqualification rate just produces more waste.
- If the operator describes sales and marketing "not getting along", reframe it as structural. They do not disagree about each other, they disagree about the rules. Write the rule.
- If the company is at Series B and scores low on the alignment diagnostic, run a 90-day fix: definitions in month 1, shared dashboard in month 2, feedback loop in month 3. Hold accountability work until the loop produces steady data.
- If the motion is product-led, the MQL definition must include product-qualified lead criteria, which needs product activation data in the CRM. No integration available? Have sales tag PQLs by hand from a weekly usage report rather than waiting.
- If the motion is hybrid (self-serve plus sales), build separate definitions and separate SLAs for marketing leads and PQLs. One definition applied to both produces inconsistent results.
- If budget is tight, build all of it anyway. The definition is a document, routing is a native CRM workflow, the loop is a meeting plus one field, and the dashboard is a saved report. None of it needs new software.

**Numbers that matter**

| Metric | Benchmark | Note |
|---|---|---|
| MQL to SQL conversion | 20% to 35% | Below 20% means qualification is loose. Consistently above 40% means it is too tight, or sales is cherry-picking. Lintel guidance |
| Follow-up SLA compliance | 85%+ on the 24-hour SLA, 70%+ on the 1-hour SLA | Monitor by rep. A team average can hide two reps who never comply. Lintel guidance |
| Time to first contact | Under 1 hour for demo requests, under 4 hours for high-intent in business hours, under 24 hours for standard | Look at the distribution, not the average. A 2-hour median with a 72-hour tail is a routing problem, not a speed problem |
| Disposition completion rate | 85%+ within 5 business days | Below 70% and the feedback loop is running on a biased sample |
| MQL to opportunity | 10% to 20% for mid-market | If MQL-to-SQL is fine but this is low, the SQL definition is too loose |
| Marketing-sourced pipeline share | 30% to 50% with balanced inbound and outbound | Below 30% is under-contribution. Above 50% is inbound concentration risk |
| Marketing-influenced pipeline | 70% to 90% with a mature content and paid program | Under 60% means marketing reaches a small slice of the accounts that close |
| Marketing-sourced win rate | Within 5 points of overall win rate | A bigger gap means marketing is sourcing from segments the product fits less well |
| Pipeline coverage | 3x to 4x of the period target | Below 2.5x is an emergency needing a joint response. Above 5x usually means loose qualification |

**Where it goes wrong:** The alignment offsite, where a day in a room substitutes for a written rule. The unilateral definition, where marketing writes the MQL criteria alone and presents them as finished, so sales never follows them. The volume trap, where marketing is measured on MQL count, misses target, and quietly relaxes the criteria. The one-way mirror, where sales fills in disposition data and marketing never changes anything, so reps stop filling it in. The executive handshake, where the CMO and CRO get along and the working level still has no process. Treating an SLA breach as a performance issue rather than asking which part of the system broke.

---

## Qualification, the sales process, and the first sales hire  (FW-SALES-001, FW-SALES-003)

**When this matters:** Deals close and nobody can explain why. Some reps hit quota and others miss badly with no explanation beyond talent. Cycle length is growing without deal size growing. You are hiring AE number two, three, or four and have no playbook to onboard them to. Win rate on qualified pipeline is below benchmark and you do not know why. Post-meeting follow-up is inconsistent across reps.

**Skip it when:** Fewer than 3 closed deals with unrelated customers. The founder is the only seller and the process lives in one head. Product-market fit is unconfirmed. There are fewer than 2 reps and no plan for a third inside 2 quarters. The product or ICP is mid-pivot, so anything written will be stale in weeks. ACV is under about $1,000 on a self-serve model, where a human sales motion does not pay for itself.

**Where you are**
- Tier 1 Reactive: Deals close through founder relationships and referrals. Every rep has a different approach. CRM stages are intuitive labels with no criteria.
- Tier 2 Building: Stages are named and roughly described. Criteria exist but are not precise enough for two reps to place the same deal the same way.
- Tier 3 Operating: Entry and exit criteria are precise and applied consistently. Methodology fields live in the CRM and are inspected in deal reviews. Forecasting uses stage-weighted pipeline with defined confidence categories.
- Tier 4 Compounding: Win rate is at or above benchmark for the ACV and motion. Stage conversion rates are tracked and managed. A revenue capacity model drives hiring 6 to 9 months ahead of the pipeline need.

**First build, in order**
1. Interview the one or two people closing the most deals (often the founder) and extract the 5 to 7 steps from first meeting to close. Write it down before anything else. Pull it from 3 or 4 recent closed-won conversations, not from theory.
2. Name stages after buyer commitment, not rep activity. A workable baseline: Prospect (account meets minimum ICP criteria, exits when a real conversation is scheduled or done), Qualify (discovery happened, exits when problem, budget context, decision process, and stakeholders are confirmed), Evaluate (active evaluation, demo or proof of concept, exits when decision criteria are documented and a champion is named), Propose (proposal presented and acknowledged, next step confirmed), Close (legal and procurement in progress, exits at signature or a documented loss reason). SMB motions compress to 3 stages. Enterprise expands to 7 or 8.
3. Configure the CRM with the stage sequence and move every active deal into the right stage. Half a day. Informal CRM habits formed in the first 30 days are very hard to undo.
4. Write a three-question qualification standard for pipeline entry: does this company have the problem we solve, is it the type of company we sell to, and is there someone here who can make or strongly influence the decision. This is not MEDDIC yet.
5. Make a dated, named next step a required CRM field. "Following up" is not a next step. This one requirement kills the biggest class of early-stage stall.
6. Before finalizing stages, interview 3 to 5 recent customers about how they actually decided: who was involved, what they needed, what approvals were required, why they chose you. Map stages to buyer decision milestones. Any stage you cannot map to a buyer milestone is a rep activity log and should not be a stage.
7. Rewrite every criterion as a verifiable yes or no question ("Has the economic buyer been identified by name and title?" "Has the buyer given a decision timeline in writing?"). Test against 5 to 10 real deals. Any criterion where two reviewers disagree is not precise enough.
8. Select one methodology for the ACV and motion, run a calibration session on what "confirmed" means for each element at this company, then build the CRM fields. Fields before training produces fields filled in wrong.
9. Build the deal review template and weekly cadence before the fields go live. Fields nobody inspects get filled in for appearances. The template covers stage criteria confirmation, which methodology fields are complete, the gap, the rep's proposed action, the manager's coaching input, and the agreed next step with a date and owner.
10. Build the forecast model last, from real stage conversion data, with a methodology completeness modifier.

**Decision rules**
- If the company is Series A and at Tier 1, build the stage architecture before any methodology. Introducing MEDDIC first gives reps vocabulary with no idea which stage each element belongs to.
- If ACV is above $50K and 3 or more stakeholders are involved, MEDDIC is the right starting point. If ACV is $20K to $50K and the buyer has not yet named their own problem, SPICED usually fits better because it builds the business case during discovery. Challenger fits only when you have a genuine insight to teach.
- If ACV is below $10K and maturity is Tier 1 or Tier 2, do not use MEDDIC or MEDDPICC. Use three elements: problem confirmed, budget confirmed, decision timeline confirmed. Three or four stages at most. Manage on volume and contact rate, not field completion.
- If the industry is regulated and the company is Series B or later, add dedicated stages for compliance review, security assessment, and procurement, each with its own criteria, and use MEDDPICC so the paper process is mapped.
- If reps went through methodology training and win rate did not move, the methodology was deployed as training, not as a system. Check whether the CRM has the fields. If it does, check completion rate. Below 70% means deal reviews are not enforcing it. Above 70% means audit the content, because placeholder text means reps are gaming it.
- If deals keep slipping out of the committed forecast, the cause is almost always one of three gaps: no confirmed compelling event, the economic buyer was never engaged directly, or the paper process was never mapped. Ask what happened on the last three slips and the pattern names the cause.
- If win rate between the top and bottom rep differs by more than 2x, this is coaching and adherence, not hiring. Review 3 to 5 calls from each and map the behavioral difference to specific methodology elements.
- If a new VP of Sales just joined, hold a process alignment session before they replace anything. New leaders tend to import the methodology from their last company without checking what already works.
- Before the first AE hire, these must exist: a written ICP with firmographic criteria, a one-page playbook (motion, discovery questions, objection responses, competitive positioning), a CRM with stages and written exit criteria, either 500+ ICP-fit prospecting accounts for outbound or evidence of 10+ inbound MQLs per month, and an approved comp model. The full objection library, detailed battlecards, and demo talk track can be built by the hire.

**Numbers that matter**

| Metric | Benchmark | Note |
|---|---|---|
| Win rate on qualified pipeline | 20% to 35% at seed and Series A, 25% to 40% at Series B and C | Below 20% at Series B signals process, positioning, or qualification problems. Lintel guidance |
| Sales cycle length | SMB under $15K ACV 14 to 30 days, mid-market $15K to $100K 30 to 90 days, enterprise $100K+ 90 to 270+ days | Growing cycle length with flat deal size is an early warning on pipeline quality |
| Stage conversion | Qualify to Evaluate 40% to 60%, Evaluate to Propose 55% to 70%, Propose to Close 65% to 80%, Close to Won 80% to 90% | Use your own trailing 12-month averages once you have them |
| Stage close probability for forecasting | Stage 1 to 2 10% to 15%, Stage 3 25% to 35%, Stage 4 50% to 60%, Stage 5 75% to 85% | Starting estimates only. Recalibrate from actuals. If Stage 4 deals close at 45%, weight it 45% |
| Quota attainment spread | 65% to 75% of reps above 75% attainment | Under 50% above 75% means quota is too high or territories are uneven |
| Ramp to first full quota month | SMB 2 to 4 months, mid-market 4 to 6, enterprise 6 to 12 | This sets hiring lead time. Six-month ramp means hiring six months early |
| Forecast accuracy | Within 10% is excellent, 10% to 20% acceptable at Series A and B | A miss above 20% is a qualification or stage definition problem, not a modeling problem |
| MEDDIC pipeline quality score | Above 9 of 12 supports forecast confidence, 7 to 9 needs coaching, below 7 means the pipeline cannot carry the forecast | Lintel guidance |

**Where it goes wrong:** The activity-based stage, where stages describe what the rep did instead of what the buyer committed to. Methodology tourism, training MEDDIC in January, adding Challenger in March, and introducing SPICED in Q3 when a new VP arrives. Methodology as training rather than an operational system, with no CRM fields and no inspection. Hiring the first AE before the founder extracted their process, so the hire has nothing to learn from. Win and loss notes that blame "price" or "timing", which are the two most convenient explanations and almost never the real cause.

---

## SDR and BDR program: when to hire the first and second rep  (FW-SALES-002)

**When this matters:** The founding team closes deals but has no repeatable way to find or qualify new ones, so pipeline depends on referrals and network. Cycle length is rising or close rates falling because unqualified conversations are entering pipeline. AEs are spending more than 30% of their time prospecting instead of closing. Inbound volume is adequate but lead-to-meeting conversion is under 15%. You have a defined ICP and a documented TAM and are ready to work it systematically.

**Skip it when:** Product-market fit is unconfirmed. The ICP is undefined or too broad. ACV is below $5K a year, where a fully loaded development rep costs more than the pipeline they produce. The closing function is not repeatable yet. Fewer than 3 closed-won deals with unrelated customers, so there is no script to hand anyone.

**Where you are**
- Tier 1 Reactive: Prospecting happens on personal judgment and network access. No documented ICP to evaluate targets against, no standard qualification bar.
- Tier 2 Building: A documented ICP and qualification standard exist. One or more development reps are running a sequencing tool against them.
- Tier 3 Operating: A formal function with dedicated management, documented rep development, and a data model connecting development activity to pipeline and revenue. Quota comes from performance data, not from the revenue plan.
- Tier 4 Compounding: The function is a predictable pipeline input. Headcount comes from coverage models. Quota is recalibrated quarterly. Targeting updates from revenue attribution data.

**First build, in order**
1. Write the qualification criteria that define a meeting worth having: minimum ICP fit, the title, the problem signal. Do this before assigning or hiring anyone.
2. Build a sequenced outreach cadence tied to that ICP and those criteria, instrumented to measure reply rate, meeting rate, and show rate by step.
3. Put the four readiness conditions in place before the first hire: at least 5 repeatable closed deals, a written ICP with four dimensions, written qualification criteria, and an AE or closing rep ready to receive meetings. Add 50 to 100 identified Tier 1 accounts, at least one drafted sequence, CRM source tagging, a handoff template, and a rough quota so the rep has a number on day one.
4. Leave for the hire: sequence iteration and testing, account list expansion, and qualification call refinement. Do not leave them the ICP document or the CRM configuration. Reps who spend their first 90 days building infrastructure instead of operating it are an expensive way to write a playbook.
5. Add lead scoring and routing that separates inbound from outbound pipeline and tracks development source through to close, so per-rep productivity can be measured.
6. Add a forecasting model sourced from development activity and a formal rep development program with documented ramp benchmarks, monthly coaching, and written promotion criteria.

**Decision rules**
- First hire type: if inbound MQL volume exceeds 30 per month, hire an inbound-focused SDR. If growth depends on reaching accounts that are not generating inbound interest yet, hire an outbound-focused BDR. Never hire both with the first hire.
- If inbound exists and ACV is above $25K, start with inbound SDR. If inbound is thin and ACV is above $50K, start with outbound BDR.
- Below $25K ACV the answer depends on two things, and the library states both rules without reconciling them, so apply them together. An SDR is only justified when a dedicated closing rep already exists and inbound volume is above 30 MQLs a month. With either missing, hire a full-cycle rep who prospects and closes. With both present at $5K to $25K, build the inbound SDR function before any outbound, because warm inbound converts at 3x to 5x cold outbound at the same cost.
- Below 30 inbound MQLs a month, the constraint is demand, not capacity. An SDR with nothing to qualify is the most expensive way to discover that. Fix demand first.
- **Second and later reps.** Hire when all three capacity signals hold at once. (1) Volume: the current rep has held at or above the per-rep benchmark for 2 to 3 consecutive months (inbound SDR 15 to 25 qualified meetings a month, outbound BDR 12 to 20). For inbound, an MQL load above roughly 200 to 300 per SDR per month is a second volume sign. (2) Strain: speed to first contact on inbound has slipped past 15 minutes, or leads sit uncontacted past 30 minutes in business hours, with real-time alerts already in place so the cause is capacity and not process. For outbound, Tier 1 accounts are going unworked because the rep has no time. (3) Quality: qualification rate is holding at 70% or above.
- Read the signals that do not line up. Quality falling while volume rises means the rep is overloaded or booking loosely, so fix qualification first. Volume and quality holding with no strain means the rep has room, so raise the meeting target or widen the list. Strain with volume below benchmark means the constraint is process or performance, not headcount.
- Timing: hiring takes about 5 to 9 weeks and ramp takes 60 to 90 days for inbound SDRs, 90 to 120 for outbound BDRs. A new rep is productive roughly 3 to 5 months (inbound) or 4 to 6 months (outbound) after the role opens. Open the role as soon as the three signals hold, or earlier if the pipeline plan shows demand passing capacity inside that window.
- If meeting volume is the gap and qualification rate is below 70%, fixing qualification raises effective output without adding cost. Only above 80% qualification rate with volume still short is headcount the right answer.
- If a budget-constrained case is being made for more development headcount, confirm current reps are at or above quota benchmark first. Below quota means the constraint is performance.
- If the first hire is at 3 months with attainment below 60% of target, diagnose the system before taking personnel action. Was the ICP documented before the hire? Was the sequence tested? Is there structured weekly coaching? Was quota set from measured conversion or from the revenue plan? Any "no" makes this a system failure. About 60% of "the SDR was a bad hire" diagnoses are actually this.
- Cost to run the math yourself: a fully loaded development rep is $70K to $100K a year at seed and $80K to $120K at Series A, including compensation, tools, and data. A rep should generate 5x to 10x that in pipeline. At $18K ACV, 5x on an $85K rep means about $425K of sourced pipeline, which is roughly 24 opportunities a year, or two a month. (Outside benchmarks put loaded cost higher, around $120K to $160K. The library's number is the lower bound.)
- At sub-$5K ACV, recommend against the function entirely. Optimize inbound automation, product-led mechanics, or low-touch qualification instead.
- Fractional is appropriate at seed to build the playbook (ICP document, sequence library, CRM configuration) in 4 to 8 weeks before committing to a full-time hire. Require a deliverables specification up front, or the engagement ends and nothing is left behind.

**Numbers that matter**

| Metric | Benchmark | Note |
|---|---|---|
| Speed to first contact, inbound | Under 5 minutes for high-intent in business hours, 5 to 15 minutes acceptable | Above 30 minutes and contact rate drops sharply. Lintel guidance |
| Contact rate, inbound | 35% to 55% when contacted within 5 minutes | Below 25% is structural, in approach or timing. Lintel guidance |
| Outbound reply rate | 8% to 15% for well-targeted personalized sequences | Below 5% is a targeting or messaging problem. Test the same sequence on a tighter ICP subset: if reply rate rises, it was targeting. Lintel guidance |
| Reply to meeting | 30% to 50% inbound, 20% to 35% outbound | Lintel guidance |
| Show rate | 75% to 85% from qualified inbound, 60% to 75% from cold outbound | Below 60% means meetings are being booked without a real qualification conversation |
| Qualification rate (AE confirms the meeting was worth taking) | 70% to 80% is a healthy floor | Below 65% is a rigor problem. Consistently above 85% means useful meetings are being screened out |
| Qualified meetings per fully ramped rep per month | Inbound SDR 15 to 25, outbound BDR 12 to 20. **ACV moves this:** above $75K ACV expect lower volume and higher qualification rigor, below $25K ACV higher volume is achievable | Ramping reps run 8 to 10. Do not hold an outbound BDR to the inbound range. Credited in the source library to The Bridge Group (2023); we have not checked it against their report |
| Sourced pipeline per rep | A BDR at a $50K ACV company should source $1M to $2M annually | Rough guide. Build your own from actual data |
| Ramp to quota run rate | 60 to 90 days inbound SDR, 90 to 120 days outbound BDR | Without a documented ramp program, expect 30% to 50% longer |
| Voluntary attrition | 25% to 35% a year is normal for the role | Above 45% signals unclear career path, unattainable quota, or management quality. Lintel guidance |
| SDR or BDR to AE promotion rate | 20% to 30% a year with a formal progression framework | Lintel guidance |
| Cost per qualified meeting | $600 to $1,200 outbound at Series A, $200 to $500 inbound SDR | Up to $2,000 can be justified above $75K ACV if meeting-to-pipeline conversion is strong |
| Function cost as share of ARR | 8% to 15% at Series A, 5% to 10% at Series B, 3% to 7% at Series C+ | Each rep should generate 5x to 10x their fully loaded cost in sourced pipeline per year |
| Manager-to-rep ratio | 1 manager per 4 to 6 reps | Below 4 reps the VP of Sales can absorb it with a structured coaching cadence |
| Tool budget | $5K to $10K a month for a 2-rep team, $15K to $30K for 5 to 8 reps | Sequencing, enrichment, CRM, and conversation intelligence |

**Where it goes wrong:** Hiring before the playbook exists, then diagnosing the rep instead of the system. Scaling outreach volume on broken targeting, which burns the addressable market and produces no new signal. Working cold outbound while inbound leads decay, the single most common resource allocation mistake in this function. Setting quota from the revenue plan rather than measured conversion rates, which produces attrition inside a year. Treating "we need more meetings" as the answer when the real problem is that 40% or more of the meetings should never have been booked.

---

## Pipeline definitions, forecasting, and CRM hygiene  (FW-REVOPS-001, FW-REVOPS-003)

**When this matters:** Marketing and sales report different pipeline numbers from the same CRM in the same meeting. You cannot forecast 90 days out because the data is disputed. Leads are lost, duplicated, or stalled between functions with no owner. You missed target 2 or more quarters running and could not explain why until after close. Reps advance deals to late stages that do not close. Coverage has been above 3x for several quarters and you still close below target. A fundraise is coming and investors will want a credible 90-day forecast with pipeline behind it.

**Skip it when:** Fewer than 15 employees with one person doing marketing and sales. Product-market fit is unconfirmed. There is no CRM in use at all, which makes tool selection the first job. The cycle is entirely founder-led with no handoff. Fewer than 10 active opportunities at a time, where the founder reviewing each deal beats any model. CRM data quality score below 75%, where a forecast model produces unreliable output that looks credible.

**Where you are**
- Tier 1 Reactive: A CRM exists and is used inconsistently. Stage advancement is at rep discretion. No written stage definitions. The CEO asks for a forecast and gets an estimate.
- Tier 2 Building: Canonical pipeline stages and transition criteria are written, confirmed by both functions, and enforced in the CRM. A stage-weighted forecast runs and gets checked against actuals.
- Tier 3 Operating: One shared revenue dashboard that both the marketing and sales leader present from, with no reconciliation. Deal quality fields at Stage 3 and above feed the forecast.
- Tier 4 Compounding: Quarterly reviews produce investment decisions, not status reports. Statistical or AI-assisted forecasting with human override where the model signal is known to be unreliable.

**First build, in order**
1. Designate a CRM owner today. Not a hire, the most CRM-fluent person you have. Their mandate: data entry standards are their responsibility. 30 minutes. Nothing else changes yet.
2. Run the data quality audit. Pull every deal closed in the past 6 months and check 10 fields: lead source, stage at each key point, close date, deal value, industry, company size, contact job title, lost reason, opportunity type, and campaign attribution. For each, calculate the percentage populated with a meaningful value, counting blank, "other", and "unknown" as empty. Anything below 70% is a gap. 3 to 4 hours.
3. Define and enforce those 10 fields: name, accepted values as a picklist wherever the field will be used in reporting, who enters it, and when. Make all 10 required and test the enforcement by trying to create a record without them. If the CRM cannot require at field level, enforce at the stage transition instead. 2 to 4 hours.
4. Write pipeline stage definitions as one sentence each describing the observable buyer evidence required to enter that stage. Run a 90-minute session. Have the sales leader and the CRM owner confirm each one. Enter them as stage descriptions in the CRM and send the list to every rep in writing.
5. Calculate historical close rates by stage from the past 12 months. If data quality is too poor, start with Stage 1 10%, Stage 2 25%, Stage 3 45%, Stage 4 65%, Stage 5 85%, and refine over 2 quarters. 2 to 4 hours.
6. Build one shared pipeline report and use it in the next pipeline meeting with both leaders present. A single saved CRM report showing open opportunities by stage with value, close date, owner, and source is enough. The first meeting's goal is agreement that this is the only report either side will use.
7. Start a 30-minute weekly pipeline review: forecast against target, coverage ratio, and the top 5 deals by value with a 2-minute update each. Every blocked deal gets an action before the meeting ends.
8. Enforce stage transitions in the CRM with required fields. Stage 1 to 2: contact role (economic buyer or champion named), company size, industry. Stage 2 to 3: business problem confirmed in free text with a minimum length, buyer-provided decision timeline as a date. Stage 3 to 4: executive sponsor named, budget confirmed yes or no, buyer-confirmed close date. Stage 4 to 5: legal review initiated, competitive alternatives named, paper process defined.
9. Set a deal inactivity policy: 21 days SMB, 30 mid-market, 45 enterprise. Flag anything past it. The rep either documents a next buyer action or moves the deal to closed-lost. Exclude stale deals from the coverage calculation.
10. Add the deal quality adjustment layer on top of the stage-weighted model. Starting adjustments, to be recalibrated after 4 quarters: both executive sponsor and budget confirmed +10%, neither confirmed -15%, buyer-confirmed close date within 30 days with both quality fields confirmed +5% more, single-threaded at director level or above -10%, no activity in 21 days -15%.
11. Add rep-submitted forecast categories alongside the model: Commit (the rep is committing, a miss costs them quota on that deal), Best Case (possible with positive developments), Pipeline (in the funnel, not this period). Comparing commit against the model exposes systematic sandbagging and systematic optimism.
12. Run a weekly data quality report on fields populated across records created in the last 7 days. Anything below 90% in a week alerts the CRM owner, who resolves or escalates. Standing weekly task, not an audit.
13. Backfill lead source and close reason for the prior 12 months of closed-won and closed-lost. It does not need to be perfect. Without these two fields the first quarterly review cannot make channel-level recommendations.

**Decision rules**
- If forecast accuracy is poor, fix stage enforcement before building a better model. A more sophisticated model on inconsistently advanced pipeline gives you a more sophisticated version of the same wrong answer.
- Split the review meetings. Weekly Deal Review (30 to 45 minutes, sales leader plus reps, stale deals first, every blocker gets an owner and a date). Weekly Forecast Call (15 to 20 minutes, CEO or CRO, CFO, VP Sales, RevOps, output is one confirmed number). Monthly Pipeline Review (60 minutes, marketing, sales, finance, and RevOps, full funnel from MQL through close, at least one action per function). Merging the deal review into the forecast call puts rep-level noise in front of the CFO.
- If coverage drops below 2.5x, identify whether the shortfall is in pipeline creation or pipeline conversion before acting. They need different interventions. Check stage velocity to find where deals stall.
- If the forecast needs to warn you in time, build the revenue model to flag projected coverage below 2.5x more than 90 days out. A well-structured spreadsheet updated monthly is enough at Tier 3.
- Make close date a buyer-confirmed field distinct from the rep's expected close date. Any close date without buyer confirmation is an estimate and should be treated as one in the model.
- If a company says it "has RevOps" because it has a CRM and an admin, it has a database. RevOps is the operating model: shared stage definitions, cross-functional accountability, and an investment decision framework.
- Build the dashboard in the CRM below 200 MQLs a month or below $5M ARR. Move to a BI tool above that, or when cross-functional data integration is needed.
- Do not buy revenue intelligence tooling before Series C. It needs 12 to 18 months of clean historical data to produce reliable output.
- Before the first dedicated RevOps hire, leadership must be able to name the problem ("our forecast is unreliable because stage definitions are inconsistent"). A hire who has to define the problem spends 90 days in discovery. A Director-level RevOps hire at Series B should inherit a working data foundation and build the reporting and investment layers, not start from zero.

**Numbers that matter**

| Metric | Benchmark | Note |
|---|---|---|
| CRM data quality score | 90%+ of required fields populated on records created in the last 30 days | Below 80% means reporting built on it is unreliable. Historical records can be lower |
| Pipeline coverage | 3x to 4x, excluding stale deals from the numerator | Below 2.5x triggers the watch protocol. Above 5x usually means loose qualification |
| Forecast accuracy | Within plus or minus 15% at Tier 2 and 3, within 10% at Tier 4 | Persistent positive variance is sandbagging, persistent negative is over-optimism in stage weighting |
| Deal quality field completion | 85%+ on Stage 3 and above deals | Below 70% and the quality-adjusted model loses its accuracy advantage |
| Deal slippage rate | Under 15% quarterly for mid-market | Above 25% is systematic over-optimism on close dates |
| Win rate | 20% to 35% overall mid-market, 10% to 20% enterprise, 35% to 50% SMB | Competitive deals typically run 10 to 15 points below uncontested |
| Sales cycle length | Mid-market $15K to $50K ACV 45 to 90 days, enterprise above $100K 90 to 180, SMB below $10K 14 to 30 | |
| Stage conversion, mid-market reference | Stage 1 to 2 60% to 75%, Stage 2 to 3 50% to 65% | Track each stage against your own trailing 12-month average |
| Net revenue retention | Above 100% healthy, above 110% strong, above 120% exceptional, below 90% an emergency | Decompose into logo churn, revenue churn, and expansion before acting |
| RevOps spend | 0.5% to 1.5% of ARR at Series A, 1% to 2% at Series B, 1% to 1.5% at Series C+ | At $3M ARR that is $15K to $45K a year, usually one part-time ops hire plus tools |
| RevOps headcount | 0 dedicated at seed and early Series A, 1 generalist at late Series A (40 to 75 employees), 1 to 2 specialists plus a Director at Series B | |
| Fractional RevOps sprint | $8K to $20K for a 90-day build of the data foundation and process layers | Not appropriate for ongoing operations |
| One-time CRM configuration sprint | $5K to $20K for a foundation and process build | Build internally if anyone has admin skills |

**Where it goes wrong:** Building a forecast before stage definitions exist, which is a guess with a spreadsheet around it. Making the key fields free text instead of picklists, so "LinkedIn", "linkedin", "LI", and "Social" all become separate sources. Writing stage definitions alone and sending them out, which the excluded function then ignores. Running pipeline reviews with no required action output, which turns management into status reporting. Defining SLAs and never monitoring them, which drops them to suggestion status inside 90 days.

---

## Lead data plumbing: tracking, enrichment, scoring, routing  (FW-REVOPS-002)

**When this matters:** Lead source is missing or inconsistent for more than 20% of new leads. Automation exists but every campaign is built by hand with no reusable workflow, no scoring model, and no routing logic. The marketing team spends more than 30% of its time on manual data work. A CRM migration, platform change, or large MQL volume increase is coming. MQL-to-SQL is below 20% and the qualification criteria are already well defined, which points at the implementation rather than the definition.

**Skip it when:** Fewer than 20 MQLs a month, where manual handling beats building automation. Product-market fit is unconfirmed. The MQL and pipeline stage definitions are not written yet, because automation built without them encodes the wrong behavior. Nobody on the team has the technical skill to configure and maintain it.

**Where you are**
- Tier 1 Reactive: The automation platform sends email. UTM tracking is inconsistent. Lead source is missing for 30% or more of leads. No scoring model. Routing is manual.
- Tier 2 Building: UTM tracking is applied across all paid and owned channels and lead source populates correctly for 90% or more of new records.
- Tier 3 Operating: A scoring model calibrated to the validated MQL definition, tested against the last 90 days of closed-won data before going live on the routing workflow.
- Tier 4 Compounding: A review cadence runs: monthly stack audit, quarterly workflow review, annual consolidation evaluation.

**First build, in order**
1. Confirm the automation platform and CRM are integrated and that a contact created in one appears in the other inside 5 minutes. Test with a real record. Fix this before anything else, because every later step depends on it.
2. Write a one-page UTM standard defining accepted values for utm_source, utm_medium, and utm_campaign, and build a dropdown spreadsheet that concatenates them. Share it with everyone who launches campaigns. 2 hours.
3. Audit every active paid, email, and social campaign for UTMs and fix the gaps. Add a UTM check to the campaign launch checklist so nothing goes live without it. 2 to 4 hours, then 15 minutes per campaign.
4. Submit a test form fill through each major channel and confirm the CRM lead source value matches the utm_source. Fix field mappings before moving on.
5. Capture first touch, most recent touch, and total touch count as three persistent fields, with first touch never overwritten. Configure this before any new campaign launches, because first-touch data cannot be recovered retroactively.
6. Build one automated routing workflow for your highest-intent action, usually a demo request: create or match the record, set status to MQL, assign to the right rep or queue, and notify them. Test with a real submission.
7. Add enrichment that runs automatically within 60 minutes of record creation for company size, industry, revenue, geography, and tech stack where available. Configure it not to overwrite contact-provided fields like job title. Enrichment must be in place before scoring, or every unenriched lead scores near zero on fit.
8. Build the scoring model as two separate scores. Fit (example weights to calibrate: company size in ICP range +25, industry in target vertical +20, job title in target persona +20, geography +10, tech stack signal +10) and engagement (demo request +40, pricing page visit +30, high-value content download +20, webinar attendance +15, multiple page visits in a session +10, email click +5, decay -5 per week after 30 days inactive). The MQL threshold is fit above X **and** engagement above Y. Never a combined total, because a poor-fit contact with very high engagement should not qualify.
9. Validate the model against closed-won history before it goes live on routing.
10. Run a monthly source tracking audit showing new leads by source with a count of blank and "direct" values. Any source above 10% blank is a tracking gap to fix before that channel's next campaign.

**Decision rules**
- If the question is how a tool you already own is configured or why its data is wrong, it belongs here. If it is whether the stack needs the tool at all, that is FW-FOUND-007. If it is which vendor to buy or whether to keep paying, that is FW-OPS-003.
- Do not build the scoring model before lead source data is reliable, because a model on unsourced leads cannot be validated.
- Do not buy enrichment before UTM tracking works. You get enriched leads you still cannot attribute.
- Build routing automation before nurture sequences. Nurture is the lower priority.
- Enrichment is always a buy, not a build. Maintaining an internal data set costs 5x to 10x vendor cost at any scale below 1,000 employees.
- If a tool falls below 50% utilization, review it. Cut only if it is still below 30% after a fix attempt and 2 or more consecutive quarters (the FW-OPS-003 rule).

**Numbers that matter**

| Metric | Benchmark | Note |
|---|---|---|
| Lead source coverage | 90%+ of new records with a valid, non-blank, non-direct value | Below 80% makes attribution unreliable for at least a fifth of pipeline |
| Enrichment coverage | 75%+ for company size and industry | Below 60% makes fit scoring unreliable for a large share of leads |
| Scoring model validation | 80%+ of the last 30 closed-won deals would have scored above the MQL threshold at first sales touch | Below 70% means the model is miscalibrated |
| SLA compliance by MQL type | 85%+ for each type, tracked separately | A workflow failure looks identical to a rep compliance failure. Check the workflow first |
| Workflow error rate | Below 1% for any production workflow | Above 2% needs immediate investigation, usually a deleted rep or a broken routing destination |
| Email deliverability | Hard bounce below 2%, spam complaints below 0.1%, open rate above 20% | |
| Tool utilization | Above 60% active users for core stack tools | |

**Where it goes wrong:** Leads flowing through the CRM read as proof the system works, when the records have no source tag, are scored against a definition that has since changed, and land in a queue nobody monitors. That is worse than no marketing operations, because it produces false confidence. Building complex nurture before basic routing. Buying tools without the person to run them.

---

## Attribution: sourced, influenced, and channel CAC  (FW-REVOPS-004)

**When this matters:** Marketing and sales disagree on what share of pipeline came from marketing, and the dispute drives budget. Nobody can answer "which channel produced the most closed-won revenue last quarter" from an existing report. CAC is rising quarter over quarter with no explanation in the data. A Series B or C raise is coming and investors will want efficiency metrics with evidence behind them. Budget decisions go to whoever argues best in the planning meeting.

**Skip it when:** UTM tracking is not applied consistently yet, which biases any model toward the channels that happen to be tracked. Pipeline stage definitions are not enforced, which means closed-won and closed-lost data is unreliable. Fewer than 20 closed-won deals in the trailing 12 months, which is not enough volume for channel-level analysis. Pre-product-market fit, where spend patterns are not stable.

**Where you are**
- Tier 1 Reactive: Channel performance is read inside each ad platform. No CRM report connects a channel to pipeline. CAC is total spend divided by total customers, if it is calculated at all.
- Tier 2 Building: "Marketing sourced" and "marketing influenced" are defined in writing and confirmed by both functions, with one agreed CRM report for each.
- Tier 3 Operating: CAC by channel built from 4 quarters of spend and closed-won data, presented in the quarterly review as the basis for channel investment.
- Tier 4 Compounding: Multi-touch attribution with agreed weighting, validated against closed-won outcomes, feeding the annual budget allocation.

**First build, in order**
1. Run a 60-minute joint session with the head of marketing and the VP of Sales to agree the sourced and influenced definitions. Both confirm in writing. That document is the methodology reference.
2. Audit UTM coverage on leads created in the past 30 days. Below 85%, stop and fix the tracking first.
3. Build two CRM reports. Sourced: open opportunities where the first marketing touch preceded opportunity creation. Influenced: open opportunities where at least one campaign member record exists for any associated contact. Review both with the VP of Sales before publishing. If the numbers do not land anywhere near both leaders' expectations, investigate the data before publishing. 2 to 4 hours.
4. Present both at the next pipeline meeting as the official numbers, with both leaders in the room. That is the adoption moment.
5. Write the full attribution methodology document: the definitions, which model is primary and which are cross-checks, rules for retroactive changes (prospective only, with a transition period), the minimum UTM coverage a new channel needs before inclusion, version history, and a named owner. Every attribution dispute is settled by this document, not by judgment.
6. Select and validate the primary model by maturity. Tier 1 to 2: report first-touch and last-touch in parallel with no single primary. Tier 2 to 3: position-based (U-shaped) as primary, weighted 40% first touch, 40% last touch before opportunity creation, 20% spread across middle touches, with first and last touch as cross-checks. Tier 3 to 4: algorithmic, once closed-won volume exceeds 1,000 events a year, validated by holding out 20% of history as a test set.
7. Build the channel CAC calculation with a lag. Take average sales cycle length as the lag, find each closed-won customer's first-touch date and channel, sum the spend in that channel during the matching window, and divide by customers attributed. Document the lag so the number can be reproduced and audited.
8. Add attribution to the quarterly review as a standing item: share by channel against prior quarter, any channel that moved more than 5 percentage points (investigate whether it is real performance or a tracking change), UTM coverage by channel with anything below 85% flagged, and investment recommendations.

**Decision rules**
- Agree the definitions before building anything technical. Most attribution problems are definitional: nobody ever agreed what "marketing sourced" means, so every report using the term produces a different number.
- Never change the sourced definition retroactively because the first number came in lower than marketing hoped. One retroactive change destroys the model's credibility permanently.
- Pre-validate the attribution report with both the marketing and sales leader before it ever appears in a budget discussion. A report introduced for the first time in a budget meeting gets attacked on methodology instead of used for a decision.
- Do not implement multi-touch before CRM data hygiene is reliable. A multi-touch model on dirty data allocates credit incorrectly, which is worse than a simple model.
- If sales and marketing are fighting over credit, do not resolve it by adding more attribution sophistication. That is an arms race. Resolve it with one agreed definition and one report.
- Report sourced and influenced separately and always together. Claiming influenced pipeline as marketing's contribution is the fastest way to lose the sales team's trust in every number marketing produces.

**Numbers that matter**

| Metric | Benchmark | Note |
|---|---|---|
| UTM coverage required before a channel enters the model | 85% | Below that the channel's contribution is systematically understated |
| Marketing-sourced pipeline share | 30% to 50% with balanced inbound and outbound | Below 25% is under-contribution. Above 60% is concentration risk |
| Marketing-influenced pipeline share | 60% to 85% with an active content, email, and events program | |
| Channel CAC | Below one-third of ACV for each channel | At $25K ACV, channel CAC above $8,300 is a sustainability problem |
| LTV to CAC by channel | 3:1 or above sustainable, 5:1 or above strong, below 2:1 unsustainable | |
| Win rate by source | Within 10 points of the overall win rate | A source 15 or more points below is generating interest, not pipeline |
| Average deal size by source | Compare across channels in your own data | A channel more than 30% below the company average is producing below-average-value customers at the same cost |
| NRR by acquisition source | Above 100% per source cohort at 12 months | A channel can look cheap on CAC and still be a bad channel if its customers churn |

**Where it goes wrong:** Treating attribution as a tooling problem when it is a definitions problem. Building the sourced report before confirming UTM coverage, producing numbers that are not defensible. Crediting marketing for any deal where any marketing touch occurred, which inflates the claim and ends the sales team's willingness to use the report. Late-stage touches (ad impressions after the opportunity already exists) counted as influence, which is correlation dressed as causation.

---

## Deal desk, compensation, and territory: the adjacent decisions  (FW-SALES-004, FW-SALES-005, FW-SALES-006)

These three come up during handoff and RevOps work. Each has its own framework. Here is the minimum needed to route the question correctly.

**When this matters:** Compensation, when the team does something you do not want (small deals, heavy discounting, ignoring a product line) and coaching has not changed it, or when you are hiring AE one or two with no documented structure. Territory, when two reps are contacting the same accounts and credit disputes start, or the team is growing past three reps. Deal desk, when realized ACV is materially below list, the same product sells at $60K and $42K for identical scope and nobody can explain why, or you are moving upmarket into custom pricing and multi-year structures.

**Skip it when:** Compensation, with no quota-carrying reps, or fewer than two with no third planned inside two quarters, or a motion in active revision. Territory, with one quota-carrying rep (they own everything by default), an unstable ICP, or an all-inbound motion where routing rules are enough. Deal desk, when all deals close at list, or below $10K ACV with no custom pricing, or when the VP of Sales is in every deal and therefore already is the deal desk.

**Where you are**
- Tier 1 Reactive: Compensation, define OTE, the base-to-variable split, and the quota multiple before writing a job description. Territory, define the segmentation model (how accounts are categorized by size, segment, or geography) before assigning anyone. Deal desk, write the discount approval matrix.
- Tier 2 Building: Compensation, add accelerators above 100% attainment and a written clawback or draw policy. Territory, document account assignment rules and configure the CRM to match before the next hire. Deal desk, define the standard deal structures you will offer (annual prepaid, monthly, multi-year, volume tiers) with documented pricing and terms.
- Tier 3 Operating: Compensation, segment plans by role and deal type. Territory, instrument coverage metrics per territory and rebalance at least annually. Deal desk, formal review above a defined ACV threshold with a submission template, review team, and turnaround SLA.
- Tier 4 Compounding: Compensation, multi-component plans weighting new business, product mix, customer health, and multi-year value. Territory, a planning model quantifying opportunity per territory from ICP data. Deal desk, analytics on discount rate by rep, segment, and stage, including whether discount level correlates with retention.

**First build, in order**
1. Deal desk first if margin is leaking: a simple table of the maximum discount a rep can approve alone, what needs VP approval, and what needs CEO or CFO approval. Put average discount in every attainment report next to revenue.
2. Compensation next if you are hiring: OTE benchmarked to market data, then the split, then the quota multiple. Those three numbers are the skeleton and everything else follows.
3. Territory last, and only at the second rep or beyond.

**Decision rules**
- If discounts vary widely by rep and there is no approval rule, that is a deal desk problem (FW-SALES-006). If discounts are high and similar across reps inside one tier, that is a packaging problem (FW-EMERGING-013).
- If the behavior is consistent across multiple reps and coaching has not changed it, change the plan, not the people. Reps do what they are paid to do.
- If reps in some territories consistently outperform others, test territory quality before putting anyone on a performance plan. The difference is often market richness, not skill.
- Standard splits: 50/50 for a new business AE, 65/35 or 70/30 for a first SDR or BDR, 60/40 where ramp runs longer than 90 days or pipeline quality during ramp is outside the rep's control.
- Quota multiple: 5x to 7x OTE for sales-led mid-market, 4x to 6x for sales-led enterprise. In the $10K to $75K ACV band, commission 7% to 12% with a 50/50 split is standard.
- A founder selling without a quota does not need a comp plan. They need a documented process (FW-SALES-003) and an ICP (FW-FOUND-001).

**Numbers that matter**

| Metric | Benchmark | Note |
|---|---|---|
| Quota attainment distribution | 60% to 70% of reps at or above 100% in a healthy quarter, centered near 100% | A bimodal spread means quota calibration or territory equity is off |
| Average attainment | 85% to 100% | Below 75% is calibration or performance. Above 110% means quota is too low |
| Sales comp as share of new ARR | 15% to 25% at Series A to B mid-market | Above 30% is usually unsustainable and often a quota calibration problem |
| Commission as share of revenue | 5% to 12% for a sales-led B2B SaaS motion | Should fall as the company scales |
| Top performer retention | Above 85% of reps who hit 110%+ last year still employed | Below 75% usually means capped accelerators or a plan changed after a strong year |
| Commission dispute rate | Below 2% of calculations | Above 5% is an administration accuracy or plan clarity problem |
| Average discount against list | 5% to 15% | Above 20% consistently means list price has lost credibility or discounting is undisciplined. Below 5% sustained may mean you are underpriced |
| Per-rep discount variance | Within 5 to 7 points of the team average | A rep 15 points above needs value-selling coaching, or is working a systematically harder segment |
| Floor price proximity | Under 10% of approved deals within 10% of floor | Above 20% is a leading indicator of gross margin erosion |
| Deal desk SLA compliance | Above 90% | Below 80% and reps route around the deal desk |
| Gross margin | 65% to 80% for a software license business | Below 60% is either discounting or cost-to-serve. Deal desk data tells you which |
| Non-standard term requests | 40% to 60% of enterprise deals above $50K request at least one modification | Below 20% may mean you are not actually selling to enterprise buyers |
| Multi-year deal rate | 15% to 30% for mid-market | Above 40% may mean the multi-year discount is too generous |
| Territory trigger | Ad hoc assignment is manageable at 3 reps and not at 5 | |

**Where it goes wrong:** Diagnosing a compensation problem as a rep performance problem. Diagnosing a pricing problem as a sales problem and coaching reps to hold price when there is no pricing structure or approval rule behind them. Designing territories on an unvalidated ICP, so the whole structure gets rebuilt. Adding a deal desk when the VP of Sales is already in every deal, which adds friction and no value.

---

## Dropped

- **All analyst firm attributions.** The source frameworks credited several benchmarks to named research and analyst firms (a sales benchmarking firm for SDR meeting volume, ramp, and attrition, a lead response study for the 5-minute inbound benchmark, and an analyst firm for the Demand Waterfall funnel model and the Challenger Sale). Numbers kept, firm names removed, marked "Lintel guidance". The Challenger Sale is credited to its authors instead of its publisher.
- **The Demand Waterfall and RevOps maturity models** as named upgrade paths at Tier 3 and Tier 4 in FW-SALES-007 Section 5. Both are attributed to analyst firms in the source, and neither adds anything the four-tier ladder does not already cover.
- **Old tier labels.** FW-SALES-007's scoring interpretation table and several decision paths in FW-SALES-002 and FW-SALES-003 still use Ad Hoc, Defined, Managed, and Optimized, and FW-SALES-003's Tier 2 variable name reads "developing". Translated to Tier 1 Reactive, Tier 2 Building, Tier 3 Operating, and Tier 4 Compounding throughout.
- **Alignment diagnostic 0 to 12 scoring detail** from FW-SALES-007 Section 5. The four dimensions are reflected in the tier descriptions; the point-by-point rubric is too long for a reference file and adds no decision the tiers do not give.
- **Named vendors** where they appeared only as examples of a tool category. Kept where the source names a specific threshold tied to the tool (CRM reporting below 200 MQLs a month, BI tool above it).
- **Specific per-seat tool prices** from FW-REVOPS-001 Section 18 (per-user monthly rates for named CRM, enrichment, BI, conversation intelligence, revenue intelligence, and intent data products). These are time-sensitive vendor pricing and will be wrong fast. Kept the stage-level budget ranges, which are stable.
- **Illustrative numbers inside internal pitch scripts** (FW-SALES-002 and FW-REVOPS-001 Section 19). Both sources flag these as illustrations rather than benchmarks.
- **Intent data lift claim** ("2x to 3x over non-intent-prioritized outreach", FW-SALES-002 Path 11). Attributed to no source, states a large effect, and sits behind a vendor purchase decision. Left out.
- **"Correct diagnosis in 60% of cases" and "40%+ of cases"** precision in FW-SALES-002 Section 23. The direction of the claim is useful and is kept in plain words ("about 60%", "often"); the implied measurement is not supported.
- **Sales enablement content depth.** These 11 frameworks cover the one-page playbook, the objection and battlecard library, and the demo talk track only as hiring prerequisites. The full enablement system belongs to FW-EMERGING-008, which is named as the owner rather than summarized here.

## Credit

| Model | Originator |
|---|---|
| MEDDIC | PTC, 1990s. Developed by Dick Dunkel and Jack Napoli. The Lintel source credits this to Miller Heiman, which is wrong and is corrected here |
| MEDDPICC | Extension of MEDDIC adding Paper Process and Competition |
| SPICED | Winning by Design, 2010s |
| SPIN Selling | Neil Rackham, 1988 |
| The Challenger Sale | Matthew Dixon and Brent Adamson, 2011 |
| Sandler Selling System | David Sandler, 1960s |
| BANT (Budget, Authority, Need, Timing) | IBM. Referenced in the Lintel source for transactional qualification with no credit; credited here |
| Bowtie revenue model | Winning by Design. Used in depth in FW-SALES-001 with no credit in the library; credited here |
| SaaS Magic Number | Scale Venture Partners. Appears in the Lintel keyword set with no credit; credited here for use elsewhere in the library |
| RACI responsibility matrix | Public project management practice from the 1970s and 1980s. No single originator is reliably documented; it is commonly traced to responsibility assignment matrix work at DuPont and to Edmond F. Sheehan. Not a Lintel model. Credited here for use elsewhere in the library |
| Net Promoter Score | Fred Reichheld. Named here only because it appears in adjacent customer frameworks, not used in this file |
