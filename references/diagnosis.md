# How to diagnose a marketing problem

The order of questions that turns a vague complaint into the right framework, for a marketer or founder at a seed to Series B B2B software company.

**Owns:** intake questions, finding the growth constraint, mapping a founder's complaint to its likely real cause, the prerequisite rules that decide whether a build is worth starting, the order of work for a company starting from nothing, and when to say this skill does not cover something.
**Does not own:** the build steps, benchmarks, and tier ladders for any single topic. Once this file names a framework, the topic file for that framework answers the question. This file never gives the fix. It points.

## The rule that governs this file

Answer the question behind the question, in this order:

1. **Intake.** Get the five facts that change every answer (below). Without them, any recommendation is a guess dressed up as advice.
2. **Constraint.** Find where growth is actually blocked (FW-FOUND-009's constraint diagnostic). The complaint is a symptom reported from wherever the person sits. It is rarely the constraint.
3. **Prerequisite check.** Confirm the thing upstream of the proposed fix exists. Most failed marketing programs were started before their prerequisite was true.
4. **Then** name the owning framework and hand off.

Skipping step 2 produces the single most common bad answer: doing more of the thing the person already named. Skipping step 3 produces the second most common: building the right thing on top of nothing.

## 1. Intake questions

Ask these before answering anything. Each one changes the answer, so none of them is small talk. The field names in brackets are the ones the library's decision rules key off.

| Ask | Why it changes the answer |
|---|---|
| What stage and roughly what revenue? [COMPANY_STAGE: pre-seed, seed, Series A, Series B, Series C or later] | Almost every "deprioritize this" rule in the library is stage-gated. Pre-seed and seed companies get told to defer work that a Series A company should start this month. |
| How many paying customers, and how many closed-lost deals can you list? | The hard floor for an Ideal Customer Profile (ICP) is 5 paying customers, or 20 substantive sales conversations. Below that, only a hypothesis is possible (FW-FOUND-001). Below 5 customers, most analysis work produces a wish list. |
| Who does marketing? [TEAM_STRUCTURE: founder with no marketer, solo marketer, small team, full function] and how many marketing people? [MARKETING_HEADCOUNT] | A solo marketer cannot run the Tier 3 version of anything. Sales and marketing alignment is premature below 3 combined sales and marketing people (FW-SALES-007). |
| What is the go-to-market motion? [GTM_MOTION: self-serve product-led, sales-led inbound, sales-led outbound, partner-led, community-led, founder-led] and what is the average contract value? [ACV_RANGE] | Motion and deal size decide which channel advice applies at all. Library guidance on viable motion by deal size: self-serve under about $1K, low-touch $1K to $5K, inbound-to-sales from about $5K and clearly above $10K, inside sales $10K to $50K, enterprise from about $50K, field sales above $100K. |
| What have you already tried, for how long, and what happened? | This separates "never built" from "built and abandoned" from "built and not adopted," which have different fixes. Demand creation programs cannot be judged on pipeline at under 12 months (FW-DEMANDGEN-009), so "we tried content and it did not work" after 4 months is not evidence. |

Four more worth asking when the question is bigger than a single tactic:

- **What is in the stack?** [TOOL_STACK] Specifically: is there a customer relationship management system (CRM), is a marketing-qualified lead (MQL) defined in it, and is source attribution recorded? Several builds require at least 60 days of attribution data before they are worth starting.
- **Is the person asking a trained marketer or not?** [OPERATOR_BACKGROUND: marketing-trained or non-marketer] Non-marketers need the vocabulary defined inline and need the first step sized to a few hours, not a quarter.
- **Are you hiring for this?** [HIRING_INTENT] If a marketing leader is about to be hired, build the ICP before they start. It makes the hire effective sooner and gives the founder a way to judge the hire's work.
- **What do you think the problem is?** Record the answer, then treat it as a hypothesis to test, not as the brief. The standing misdiagnosis list below exists because the founder's own diagnosis is wrong in predictable ways.

**Proceed without an answer only when the missing fact cannot change the recommendation.** If it can, ask one short question rather than guessing. If the person will not or cannot answer, say which answer you assumed and that the recommendation changes if the assumption is wrong.

## 2. Find the constraint before you answer (FW-FOUND-009)

Five constraint categories. Score each 1 (no real issue), 2 (moderate), or 3 (primary blocker). The highest score is what the strategy should address first. Everything below the primary constraint waits.

| Constraint | What it means | Signals |
|---|---|---|
| Awareness gap | ICP-fit companies do not know the product exists | Inbound volume very low against ICP market size, minimal branded search, cold outbound conversion to "interested in learning more" below 2%, reps have to explain the category before the product |
| Consideration gap | They know, and they still do not put you on the list | Traffic exists but trial or demo conversion is below 1% of traffic, weak review-site presence, competitors hold much higher share of voice on category searches, reps report buyers evaluating two or three named competitors without you |
| Conversion gap | They evaluate and do not buy | Pipeline to closed-won below 15%, sales cycle well above the benchmark for the deal size, loss reasons concentrated in two or three categories (price, feature gaps, trust, switching cost), MQL to sales-qualified lead healthy but sales-qualified to close is not |
| Retention gap | They buy and leave | Gross revenue churn above 10% a year, net revenue retention (NRR) below 95%, churn concentrated in one cohort, marketing absent from the post-sale experience |
| Expansion gap | They stay and do not grow | NRR between 95% and 105%, no tier upgrades or seat growth, no defined customer marketing program |

Two rules that come out of this:

- **A complaint about pipeline is not automatically an awareness problem.** Thin pipeline with a small team is usually a targeting problem, and the efficient fix is the ICP, not more activity. Adding budget or headcount to a misdirected motion produces more waste, not more pipeline.
- **When pipeline is acutely short of the near-term revenue target, long-payback work waits.** Brand campaigns, demand creation, and category work all have longer time-to-return than demand capture. They are the right answer at the wrong moment.

## 3. Symptom to cause

For each complaint: the real causes in rough order of likelihood, and the framework that owns the answer. Framework IDs are authoritative; the topic file that holds each one is named by the router in `SKILL.md`.

### "Pipeline dried up" / "demo requests fell off a cliff"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | Demand did not change, the measurement broke. A form, a UTM convention, a routing rule, or a lifecycle field. Check raw form fills before believing the drop | FW-REVOPS-002, with FW-REVOPS-004 for the sourced definition |
| 2 | A paid channel is under-pacing its budget, the landing page conversion rate dropped, or the audience is exhausted and frequency is too high. Those are the three standard causes of a volume miss | FW-DEMANDGEN-001, then the paid framework (FW-DEMANDGEN-005 through 008) |
| 3 | Email placement collapsed, so nurture and outbound stopped arriving at all. Volume spikes and list quality both trigger it | FW-MAIL-001, FW-MAIL-002 |
| 4 | The program is all demand capture, and the buyers already searching have been harvested. Capture cannot create new in-market buyers | FW-DEMANDGEN-009 |
| 5 | Publishing stopped two or three months ago. Content and search pipeline lag the work, so the gap surfaces now | FW-CONTENT-001 |
| 6 | Volume held and quality fell, so the same leads produce fewer opportunities. That is a different problem: see "Our leads are bad" below | FW-SALES-007 |
| 7 | Follow-up slowed. Routing, speed to first touch, or a rep who left. Same leads, worse conversion | FW-SALES-007 |
| 8 | Buyers get the answer from an AI assistant and never click, so informational and branded traffic fell while demand held | FW-SEO-007, then FW-SEO-008 |

First probe: put raw form submissions next to MQLs for the same two months. If raw fills held and MQLs fell, it is a definition, routing, or tracking problem, not a demand problem. Second probe: is it one channel or every channel at once. One channel is execution. Every channel at once is usually tracking, seasonality, or a measurement change.

**Unit warning.** The volume rules in this library are written in MQLs. Founders usually report demo requests. Treat the two as the same number only when the demo form is what triggers the MQL, and say which one you are using. If they are different events, the library gives no conversion rate between them, so ask for both counts instead of guessing.

### "Our leads are bad" / "sales says the leads are garbage"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | No written MQL definition that sales signed off on. Both sides are working from private definitions | FW-SALES-007 |
| 2 | The ICP is too broad, or is a persona wearing an ICP label, so demand gen is correctly executing a wrong target | FW-FOUND-001 |
| 3 | The ICP is aspirational. It names the customer leadership wants, not the one the data shows you win | FW-FOUND-001 |
| 4 | Paid targeting is built on job title and industry with no firmographic ICP filter, so reach is far wider than the ICP | FW-FOUND-001, then the paid framework (FW-DEMANDGEN-005 through 008) |
| 5 | Routing and follow-up, not quality. High-intent leads sit for days, so they convert like cold leads | FW-SALES-007 |
| 6 | The feedback loop does not close. Nobody records why leads were disqualified, so marketing cannot correct | FW-SALES-007, FW-PM-006 for the interview version |
| 7 | A gated asset is attracting the wrong audience, so the lead magnet is doing its job for the wrong people | FW-CONTENT-003 |

First probe: ask three salespeople to state the ICP criteria without looking at the document. If they cannot, the problem is adoption, not criteria.

### "Nobody knows who we are"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | A messaging problem wearing a brand costume. The market does not understand what you do. Sharper language fixes this; awareness spend does not | FW-FOUND-004, with FW-FOUND-003 if the position itself is weak |
| 2 | A positioning problem. You are trying to be compelling to everyone, so you are compelling to no one | FW-FOUND-003 |
| 3 | A genuine awareness gap. Buyers understand you and still do not think of you. Confirm with unaided awareness below 15% in the target ICP before spending | FW-BRAND-004 to measure, then FW-BRAND-005 to act |
| 4 | You run only demand capture and call it a content program. Capture reaches buyers already searching. If nobody is searching, capture cannot find them | FW-DEMANDGEN-009 |
| 5 | A content program with volume and no strategic clarity. More posts at the same clarity produce more undifferentiated posts | FW-CONTENT-001 |
| 6 | No earned media or third-party presence at all, in a category where buyers check | FW-PR-001 |

Order of operations: do not start a brand campaign before the brand strategy is stable, the visual identity and voice exist, and a pre-campaign baseline is measured. A campaign with no baseline cannot be evaluated.

### "Sales says marketing is useless"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | No written MQL definition, no service-level agreement in either direction, so every miss becomes an argument with no standard to check against | FW-SALES-007 |
| 2 | A definition problem presented as an attribution problem. The two sides never agreed what "marketing sourced" means, so every report produces a different number | FW-REVOPS-004, with FW-FOUND-006 for the underlying definitions |
| 3 | Misaligned incentives. Each function hits its own number while the business misses revenue | FW-SALES-007 |
| 4 | Alignment exists at the top and not at the working level. Leaders agree; the sales development reps and content marketers never got the translation | FW-SALES-007 |
| 5 | Sales has nothing to sell with. No battlecards, no objection handling, no collateral tied to the real objections | FW-PM-005 for collateral, FW-PM-004 for battlecards |
| 6 | Campaign volume outruns sales capacity, so the best leads age out and reinforce the story that marketing leads are weak | FW-SALES-007 |

Deprioritize this whole area if sales and marketing are the same person, or if combined headcount is under 3, or if no source has yet produced repeatable pipeline. Alignment without pipeline is a premature problem.

### "Our pricing page does not convert"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | Demand, not the page. Under roughly 500 pricing-page visits a month, conversion work moves a handful of deals and cannot be measured. Go back to the constraint diagnostic | FW-FOUND-009, then the demand framework |
| 2 | Tier boundaries drawn around feature inventory instead of buyer type. Structural, not visual. Cleaner design will not fix it | FW-EMERGING-013 |
| 3 | The pricing model is wrong, not the price. Charging per seat when buyers value outcomes will underperform at every price point | FW-GROWTH-005 |
| 4 | Mechanical conversion problems: page speed, form length, or a headline that does not match the ad or query that sent the visitor | FW-DEMANDGEN-004 |
| 5 | The page does not say who each tier is for, so buyers land in the wrong tier. Watch for more than 10% to 15% of new customers changing tier within 90 days | FW-EMERGING-013 |
| 6 | Discounting, not packaging. If discounts vary by rep or no approval rule exists, it is a deal-desk problem | FW-SALES-006 |

The split to apply: discounts that are high and similar across reps inside one tier point to packaging or tier price (FW-EMERGING-013). Discounts that vary by rep point to the deal desk (FW-SALES-006). Pricing model and overall price level belong to FW-GROWTH-005.

### "We are invisible to AI assistants"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | Nobody has checked. Run the test before theorizing: ask ChatGPT, Claude, Gemini, and Perplexity "What is [Company]?", "What does [Company] do?", and "Who are [Company]'s competitors?" and write down the answers | FW-SEO-008 |
| 2 | Not enough content to be sourced from. Under about 30 indexed pages of substantive content, there is nothing to optimize | FW-CONTENT-001 first, then FW-SEO-007 |
| 3 | The content answers the question, badly. The direct answer is buried in paragraph three after 200 words of preamble, so extraction skips it | FW-SEO-007 |
| 4 | Technical foundation. AI systems source from technically healthy, indexed pages. Optimizing broken pages returns nothing | FW-SEO-001 |
| 5 | Entity confusion. The company is described differently across Wikidata, Crunchbase, LinkedIn, and its own About page, so the model has no consistent fact to learn | FW-SEO-008 |
| 6 | No underlying authority. AI systems favor established sources, so citation work without authority work is premature | FW-SEO-004, FW-PR-001 |

Hard ordering rule: answer engine optimization (AEO, FW-SEO-007) comes before generative engine optimization (GEO, FW-SEO-008). If AEO is below Tier 2 Building, GEO investment adds little. Also confirm rather than assume that the buyers use AI assistants at work. Some segments do not.

### "Our budget just got cut and the number did not"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | Nothing is cut yet, because nobody has ranked spend by cost per opportunity. Rank first, cut second | FW-REVOPS-004 for channel CAC, then FW-FOUND-008 for the share that remains |
| 2 | The cut lands on the channels with the longest lag, so pipeline looks fine for a quarter and then falls off a cliff | FW-FOUND-009 for the awareness lag, FW-DEMANDGEN-009 for what capture cannot replace |
| 3 | Tools, not programs, are the fast cut. The stack is usually the only line that can fall quickly without touching pipeline | FW-OPS-003 |
| 4 | The plan was never reforecast, so the old pipeline number is still being defended against a smaller budget | FW-FOUND-009 |

First move: do not cut evenly. Rank every line by cost per opportunity over the last two quarters, protect the top two, and take the cut from the bottom and from tools. Say out loud which number moves if the full cut has to land. This library does not have a mid-year reforecasting procedure, so that part is judgement.

### "The sales team wants ammo for one competitor they keep losing to"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | No battlecard that a rep can use mid-call. Owner of the card and its contents | FW-PM-004 |
| 2 | No loss evidence, so the card is built on opinion. Interview the losses first | FW-PM-006 |
| 3 | No standing competitor monitoring, so the card is stale within a quarter. This is the research program, not the card | FW-DATA-008 |
| 4 | The gap is price or product, not ammunition. Ask what the last ten losses actually said before building anything | FW-PM-006 |

### "My CEO keeps forwarding me competitor posts"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | No written plan with a fixed number of initiatives, so every new idea looks like it fits | FW-FOUND-009, which holds the initiative cap and the authority to say no |
| 2 | No competitor monitoring the CEO can see, so they are doing it manually and routing it to you | FW-DATA-008 |
| 3 | A real gap you have not priced. Run the request through the dependency table before dismissing it | Section 5 below |

This library has no play for managing an executive relationship, which is usually the actual problem. It can give you the plan authority and the monitoring cadence that take the heat out of it.

### "Churn is too high"

| Order | Likely real cause | Open |
|---|---|---|
| 1 | The wrong companies were admitted. No negative ICP screening for the characteristics that predict failure | FW-FOUND-001 |
| 2 | Onboarding never reached a value moment, so the customer never had a reason to stay | FW-CUSTMKT-002 |
| 3 | One cause is being treated as all causes. Sponsor departure, budget change, competitive loss, and disengagement each need a different response. A re-engagement email is right for exactly one of them | FW-CUSTMKT-004 |
| 4 | No feedback instrument, so churn is a surprise every time | FW-CX-004 for scoring and detractor saves, FW-DATA-009 for the company-wide system |

## 4. Standing misdiagnosis list

These are the library's recorded patterns of founders diagnosing themselves wrong. Check the complaint against this list before accepting it.

| They say | It is usually | Open |
|---|---|---|
| "Pipeline quality is poor, fix demand gen" | The ICP is too broad and demand gen is faithfully generating low-fit volume | FW-FOUND-001 |
| "Sales is not closing, train them" | The ICP is aspirational and reps are being asked to close accounts that will not buy | FW-FOUND-001 |
| "Churn is high, fix the product or add customer success headcount" | The ICP does not screen for the traits that predict product success | FW-FOUND-001 |
| "Paid media is not performing, change the creative" | Targeting has no firmographic ICP filter | FW-FOUND-001 |
| "We need a better copywriter" | There is no messaging architecture for a copywriter to work from | FW-FOUND-004 |
| "We have a brand problem" | The market does not understand what you do, which is a messaging problem | FW-FOUND-004 |
| "We have a positioning problem" or "we have a messaging problem" | Decide first whether the issue is strategic (wrong position) or executional (right position, wrong words) | FW-FOUND-003 for strategic, FW-FOUND-004 for executional |
| "We need a better attribution tool" | Marketing and sales never agreed what "marketing sourced" means | FW-REVOPS-004 |
| "We have a measurement problem" | You have a definition problem. Define lead, MQL, sales-qualified lead, and influenced pipeline before buying infrastructure | FW-FOUND-006 |
| "We need to publish more" | You need a content brief and a pillar architecture, not a faster cadence | FW-CONTENT-001 |
| "We have a demand gen strategy, we run ads and sequences" | Running tactics is not a strategy. There is no connecting logic between channel, segment, and stage | FW-DEMANDGEN-001 |
| "We do product-led growth, we have a free tier" | A free plan with no activation moment, instrumentation, or conversion trigger is not product-led growth | FW-EMERGING-002 |
| "We do win/loss analysis, the CRM has loss reasons" | That is win/loss reporting. Analysis is buyer interviews, and the gap between the two is the finding | FW-PM-006 |
| "We have an ICP" | If it cannot decide whether a named company is in or out in under 60 seconds, it is a market category, not an ICP | FW-FOUND-001 |
| "We have alignment, we share a Slack channel" | Alignment is a written MQL definition sales agreed to, a loop that closes within 30 days, and shared accountability | FW-SALES-007 |
| "Content does not work for our category" | No creation program has been sustained for 12 continuous months, which is the minimum before pipeline judgment | FW-DEMANDGEN-009 |
| "Our audience is not interested" | A 20% newsletter open rate is a content relevance problem, not an audience problem | FW-DEMANDGEN-009 |
| "Activation is low because the product is complex" | Onboarding is not designed around the activation moment, or activation is defined as account setup instead of value delivered | FW-EMERGING-002 |
| "Our annual plan is the channel roadmap" | A channel list is an execution plan with no reason. The plan skipped the constraint diagnosis | FW-FOUND-009 |
| "Our pricing is wrong" | The pricing model is wrong, and model comes before price point | FW-GROWTH-005 |

## 5. Dependency rules

Before recommending a build, confirm the prerequisite. For each row: what must be true, the smallest version that counts, and what breaks if you start anyway.

| Build | Must be true first | Minimum version that counts | What breaks without it |
|---|---|---|---|
| ICP (FW-FOUND-001) | 5 paying customers or 20 substantive sales conversations, and a product that solves a specific identifiable problem | A list of 10 won deals with company name and deal size, plus 5 lost deals with the loss reason | Nothing to validate against, so the output is a wish list |
| Buyer persona (FW-FOUND-002) | A written first-version ICP | Three company-level criteria | Personas describe buyers at companies you should stop selling to |
| Competitive positioning (FW-FOUND-003) | ICP written and validated by sales | A sales-confirmed ICP, not a hypothesis | Generic positioning that tries to appeal to everyone |
| Messaging architecture (FW-FOUND-004) | ICP at Tier 1 Reactive or better with three sales-confirmed criteria, plus the champion persona and the positioning | Persona with the buyer's priority and objections captured | Proof points written in product language buyers do not recognize |
| GTM motion design (FW-FOUND-005) | ICP at Tier 1 minimum, champion persona at Tier 1 minimum, positioning in place | Written target company type validated by sales | The motion targets a vague buyer, producing volume and no conversion |
| Measurement foundation (FW-FOUND-006) | ICP at Tier 1, GTM motion at Tier 1 with a one-page write-up | ICP plus documented motion stages | Funnel stages measure the wrong steps |
| Tech stack and CRM schema (FW-FOUND-007) | ICP firmographic criteria exist, primary persona defined | One-page ICP with size range, top two industries, and the buyer's job title | The schema gets built field by field as needs arise, then has to be redone |
| Budget framework (FW-FOUND-008) | ICP documented with size, industry, deal size, and primary pain; measurement with MQL defined and 60 days of source attribution | A source field in the CRM, even if maintained by hand | The budget becomes a spending plan with no feedback loop |
| Annual plan (FW-FOUND-009) | ICP, measurement with 60 days of data, a budget framework, and an agreed primary motion | A documented ICP with size and industry, plus rough attribution data | Growth hypotheses float free of evidence and resources |
| Demand generation (FW-DEMANDGEN-001) | A validated ICP and a chosen motion. Measurement should reach Tier 2 Building before significant spend | ICP validated and documented | Broadcasting to an undefined audience with no basis for the next decision |
| Outbound (FW-DEMANDGEN-003) | ICP first version, no validation required for a prospecting test | A written first-version ICP | Sequences go to random lists and produce no learning signal |
| **Starting outbound at all (the "what do we set up first" question)** | The first build step is not a tool and not a sequence: it is the written ICP and the qualification criteria that define a meeting worth having. Those come before any hire or any sequence | A written ICP plus qualification criteria both sides signed | A rep spends their first 90 days building the playbook instead of running it, which is an expensive way to write a document. Owned by FW-DEMANDGEN-003 for the sequence and FW-SALES-002 for the rep and the criteria |
| Paid media (FW-DEMANDGEN-005 to 008) | ICP validated | Firmographic criteria that map to platform targeting | High impressions, low conversion, leads sales does not recognize |
| Account-based marketing (FW-EMERGING-003) | Validated ICP, sales leadership co-ownership, differentiated messaging, account-level CRM configuration. Deal size above about $20K | Validated ICP with Tier 1 accounts operationally defined | Low engagement from "target" accounts. Below $5K deal size the economics do not work at all, and between $5K and $20K the only defensible version is list-level advertising with no per-account personalization |
| Pricing page work (FW-EMERGING-013) | Product-market fit, roughly 500+ pricing-page visits a month, and some willingness-to-pay evidence | Five customer interviews about the pricing decision, plus conversion tracking on the page | You redesign a page that demand, not design, was limiting |
| Sales and marketing alignment (FW-SALES-007) | Product-market fit, repeatable pipeline from some source, 3 or more combined sales and marketing people | A jointly written MQL definition both leaders signed | Alignment theater with no change in the daily handoff |
| Brand campaign (FW-BRAND-005) | Stable brand strategy, visual identity and voice established, brand health baseline measured, pipeline not acutely short | A brand health pulse survey taken before the campaign | The campaign cannot be evaluated, and it may communicate an identity about to change |
| AEO (FW-SEO-007) | Technical SEO foundation in place, about 30 or more indexed pages of substantive content | 10 to 15 target queries tested by hand and documented | Optimizing pages that are not indexed or sourced |
| GEO (FW-SEO-008) | AEO at Tier 2 Building or above, existing brand and press signals, product-market fit | Documented AI answers for your own brand questions | Amplifying an unstable identity, which produces confusion |

Three dependency failures worth naming out loud because they recur: starting account-based marketing before the ICP is validated, running paid media before the ICP is defined, and building a CRM scoring model on unvalidated criteria. All three encode a wrong assumption at scale, which is more expensive than having no system.

## 6. Order of work from nothing

For a company with no marketing function. Gates matter more than dates.

**Stage 0, before any of this.** If there are fewer than 5 paying customers, the product is still changing significantly, or the founder has had fewer than 10 sales conversations, formal marketing work is premature. Run more sales conversations. Deferring here is cheap. Deferring forever on the grounds of "we do not have product-market fit yet" is a way of avoiding targeting decisions permanently, so set a date to revisit.

1. **ICP (FW-FOUND-001).** Pull the last 10 closed-won deals and name the three traits they share that the losses do not. 4 to 6 hours for a first version, one person, spreadsheet only. Gate: sales can use it to call a named company in or out in under 60 seconds.
2. **Buyer persona (FW-FOUND-002).** Can start the moment the first ICP version is written. Does not wait for validation.
3. **Competitive positioning (FW-FOUND-003).** Starts after sales has validated the ICP.
4. **Messaging architecture (FW-FOUND-004).** After persona and positioning. This is what a copywriter or agency works from.
5. **GTM motion (FW-FOUND-005).** After the ICP is validated. Check the choice against deal size before anything else.
6. **Measurement foundation (FW-FOUND-006).** Define lead, MQL, and sales-qualified lead jointly with sales, then put a source field in the CRM. Definitions first, infrastructure second.
7. **Tech stack (FW-FOUND-007).** Configure the CRM against the ICP criteria and the measurement requirements, not the other way around. Martech sits at roughly 15% to 25% of the marketing budget at every stage; review above about 25%.
8. **Budget framework (FW-FOUND-008).** Needs the ICP plus about 60 days of attribution data.
9. **Annual plan (FW-FOUND-009).** Run the constraint diagnostic, then pick what to build. Tier 1 Reactive version is a one-page brief: revenue target, primary motion, the one or two channels being tested, and the output metric for 90 days.
10. **Then, and only then, the first channel build**, chosen by the primary constraint from step 9 rather than by preference or by what the last company did.

Two steps that can run earlier if the situation demands it: an MQL definition agreed with sales (step 6's first half) can happen as soon as there are two people, and outbound can start on an unvalidated first-version ICP as a prospecting test.

## 7. Who owns a question when two frameworks touch it

When two frameworks both cover a topic, the owner answers and the other points to it.

| Topic | Owner split |
|---|---|
| Tech stack | FW-FOUND-007 designs it, FW-OPS-003 buys and governs each tool, FW-REVOPS-002 runs it day to day |
| Pricing | FW-GROWTH-005 sets model, value metric, and price level. FW-EMERGING-013 owns tiers and the pricing page. FW-SALES-006 owns individual deals and discount approval |
| Feedback | FW-CX-004 runs scoring and detractor saves for current customers. FW-DATA-009 runs the company-wide voice-of-customer system. **Where the feedback goes next is a third question:** the roadmap routing loop sits with FW-PM-001 in `product-marketing.md`, so "we collect it and nothing changes" needs both the synthesis layer and that loop |
| Competitive intelligence | FW-DATA-008 runs the research program, FW-PM-004 turns it into battlecards and enablement |
| GTM motion | FW-FOUND-005 chooses and designs the motion, FW-SALES-001 runs sales strategy inside it |
| Launches | FW-EMERGING-012 decides and validates entering a new market, FW-PM-003 runs the launch |
| Category and analysts | FW-EMERGING-005 picks the category path, FW-PM-007 runs a category-creation program, FW-INFLUENCE-001 runs each analyst interaction |
| Comms | FW-PR-001 owns earned media, FW-COMMS-001 owns crises, FW-COMMS-002 owns investor comms, FW-COMMS-003 owns employer brand and layoff communication |
| Positioning and messaging | FW-FOUND-003 owns the competitive positioning choice, FW-FOUND-004 owns the messaging architecture, FW-PM-002 applies both at product level, FW-BRAND-001 owns brand-level identity and associations |

## 8. When to say this skill does not cover it

Say so plainly in these cases, and do not stretch a nearby framework to fit. Word it as "this skill does not cover it", not "there is nothing on it": these files are a condensed version of a larger library, so a gap here is a gap in the condensation.

1. **The question is not B2B software marketing.** The library is built for seed to Series B business-to-business software companies. Consumer marketing, physical products, retail, and regulated-industry compliance detail are out of scope.
2. **The question is another function's.** Financial modelling, accounting, tax, legal advice, employment law, product development, engineering, and fundraising mechanics are not here. Employer brand (FW-COMMS-003) is the only people-adjacent topic covered, and only the marketing half.
3. **No framework owns it.** Known gaps: website design and site information architecture (the SEO frameworks cover technical health and on-page optimization, not design or navigation), channel and reseller program economics beyond co-marketing (FW-EMERGING-004 covers partner co-marketing only), and review-site programs, which appear inside customer marketing and advocacy without a framework of their own.
4. **The answer depends on a number the library does not have.** Current ad platform costs, current tool prices, current platform policies, and anything that changes quarterly. Say the method is here and the number needs checking today.
5. **The question is about one specific company's data.** Nothing here can tell you your own win rate, churn, or conversion. It can tell you what to measure and what range is normal.

What to say instead, in this shape:

> This is outside what the library covers. [One sentence on why.] The closest thing it does cover is [framework and what it answers], which gets you [the part of the question it handles]. For the rest, you need [the specific input, person, or current source].

Never fill a gap by generating a plausible-sounding framework. The value of this skill is that every answer traces to a written source. An invented answer that sounds like the others is worse than no answer, because the reader cannot tell them apart.

## Dropped

- **"21 to 30 cents of every lead-handling dollar" wasted on unqualified follow-up** (FW-SALES-007, Failure Mode 1). The library hedges it as "typically estimated," with no traceable source. The failure mode and the fix stand without the number.
- **"Response within 5 minutes increases contact rates by 100x versus a 30-minute delay"** (FW-SALES-007, Failure Mode 3). Widely repeated, not verifiable from the library. Replaced with the actionable part: the service-level agreement of 1 hour for demo and pricing-page leads, 24 hours for content downloads.
- **Constraint-diagnostic resemblance to the Theory of Constraints.** The structure echoes Eliyahu Goldratt's work, but the library does not credit him, so no credit is claimed or implied here.
- **The "rings" vocabulary in FW-FOUND-002** (priority initiative, perceived barriers, decision criteria). It is close to Adele Revella's Buyer Persona Institute model and the library does not credit her, so the ring names were paraphrased into plain words rather than reused.
- **Specific tool and vendor names** that appeared in the source budget sections. They date quickly and naming them reads as endorsement.
- **Section 25 tier labels from the source** (TIER_1_AD_HOC, TIER_3_DEFINED, TIER_4_OPTIMIZED). Mapped to Tier 1 Reactive, Tier 3 Operating, and Tier 4 Compounding.
- **FW-INFLUENCE-002.** The ID is absent from the library. Flagged, not filled.

## Credit

| Model named here | Originator |
|---|---|
| Positioning as a deliberate strategic choice (used in FW-FOUND-003) | April Dunford |
| Price Sensitivity Meter survey (referenced in the pricing-page prerequisite) | Peter van Westendorp |
| Net Promoter Score, the basis of the feedback scoring in FW-CX-004 | Fred Reichheld |
