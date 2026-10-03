# Customer marketing and feedback

How a B2B software company with paying customers listens to them, keeps them, grows them, and turns the happy ones into references. For a marketer or founder at seed to Series B who needs the next specific move.

**Owns:** the customer survey program and follow-up rules (the 48-hour rule and the scripts); churn interviews and journey research; advocacy, references, reviews, and case studies; churn-risk signals marketing can see and the at-risk response; expansion signals and campaigns; customer communication cadence (onboarding, monthly email, renewal support, review rhythm).
**Does not own:** combining feedback from many sources into messaging, ICP, or roadmap decisions (FW-DATA-009); the revenue data layer and CRM sync (FW-REVOPS-001, FW-REVOPS-002); attribution models (FW-REVOPS-004); community launch and operations (FW-COMMUNITY-001 to 003, FW-EMERGING-006); win-back of churned customers and competitive displacement (FW-EMERGING-011); email deliverability and lifecycle automation mechanics (FW-MAIL-002, FW-MAIL-003); pricing and packaging (FW-EMERGING-013, FW-SALES-006); sales and marketing handoffs (FW-SALES-007).

Retention math: NRR is (starting ARR plus expansion, minus contraction, minus churned ARR) divided by starting ARR. GRR is the same without expansion.

## Customer feedback program and follow-up rules  (FW-CX-004, with FW-CX-001 for the health gate)

The scoring question is the Net Promoter Score (NPS) question (Fred Reichheld, with Bain and Satmetrix): "How likely are you to recommend us, 0 to 10?" Scores of 9-10 are promoters, 7-8 passives, 0-6 detractors. The score is the headline. The follow-up is the program.

**When this matters:** 30+ paying customers and decisions are made without structured customer input. Churn surprises the team. NRR fell two or more quarters and nobody can say why. A fundraise is coming and investors will ask for trend data and proof you follow up.
**Skip it when:** Under 30 paying customers. The sample is too small, so talk to every customer each quarter (at 10 to 20 customers, a 30-minute founder call each beats any survey). Also skip it when there is no health or escalation field in the CRM (you cannot suppress surveys), or the product changes weekly during a product-market-fit search (interview users instead).

**Where you are** (self-score 0-100 across five areas of 20 points: survey design, follow-up, reading comments, churn interviews, how far feedback reaches product and leadership)
- Tier 1 Reactive (0-25): No structured program. Detractors are known only when they complain.
- Tier 2 Building (26-50): A post-onboarding survey and a quarterly relationship survey run. Every detractor gets follow-up within 48 hours. Promoters get one ask. Top three themes go to leadership each quarter.
- Tier 3 Operating (51-70): Surveys at two or more lifecycle moments, scores split by segment and stage, a monthly multi-source summary, churn interviews for 80%+ of lost accounts above your ACV line.
- Tier 4 Compounding (71-100): Feedback is tied to roadmap choices in writing, a customer advisory board advises, and the program's own metrics are reviewed yearly.

**First build, in order**
1. Pick one survey: post-onboarding, sent 30 days after contract signature, two questions only (the 0-10 score and "What is the main reason for your score?", open text for every score). Send to the primary contact. For accounts above about $20K to $30K ACV, also survey the executive sponsor in a separate send. 1 to 2 hours.
2. Write the suppression rule before launch: no survey to a customer with a critical open ticket, a red health score in the last 30 days, or a billing dispute. 1 hour.
3. Configure the tool (2 to 3 hours): sender is a named person, never a no-reply address; scale is 0-10 (a 1-10 scale breaks the math); never anonymous in B2B; a detractor alert reaches the account owner within 4 hours.
4. Write the follow-up protocol before the first send (1 hour). Detractor: first message within 24 hours (48 at most), call within 48 hours, outcome logged in the CRM within 24 hours of the call. Passive: if the comment names a specific problem, treat as a detractor; otherwise send a note within a week asking "What would make this a 9 or 10 for you?" Promoter: personal thank-you within a week and one specific ask.
   - Detractor first message: "Hi [first name], thank you for the score and for being direct about [their comment, in their words]. I read it myself and I want to get this right. What does that look like day to day for your team? If a call is easier, I have 20 minutes on [two times]. [Name]." Quote the comment, ask one open question, offer a call without requiring it. No discount or credit (it teaches customers a low score pays), no review ask, no defending the product.
   - Close-the-loop message, from the same person when the fix ships or the decision is made, even if the answer is no: "In [month] you told us about [issue]. Here is what we did: [change, with the date]. If not fixing: We are not building this now because [reason]. In the meantime, [workaround]. Thank you for raising it."
5. Send wave one. With no history, also send one survey to the whole base for a baseline, staged over two to three weeks above 100 accounts. Wait for 30 to 50 responses before you calculate a score.
6. First quarterly read (60 to 90 minutes): tag every comment (product, experience, support, pricing, CSM, competitive, other), count, and write two paragraphs on the top three themes with specifics ("eight customers cited slow reports on dashboards over 5,000 records, mostly enterprise"). Score goes on the last line.
7. Then add, in order: a quarterly relationship survey; a post-QBR survey 24 to 48 hours after each review; a post-renewal survey within a week; scores split by segment and stage; a quarterly pass on promoter comments for messaging language.

**Decision rules**
- If churn is above 15% a year and you cannot name reasons with quotes, then interview churned customers before building surveys (the library flags 12%+ as a priority signal). Interviews find causes faster.
- If day-30 surveys keep returning detractors from customers still mid-onboarding, then send 5 days after the first value milestone instead.
- If a customer is in an active escalation, then suppress the survey. A bad-week score poisons the trend.
- If an executive sponsor scores 0-6 while the daily user scores 9-10, then escalate to the CS manager or VP for an executive-to-executive call. The sponsor decides renewal.
- If a detractor threatens a bad review unless an issue is fixed, then fix the issue and promise nothing about the review.
- If the same competitor is named by three or more customers in one month, then escalate to the CEO and head of sales that week with the quotes. If a theme persists three months with no roadmap response, then put it in front of the CEO.
- If a customer would get a second survey within six weeks of the last, then hold it. Keep one calendar of every survey customers receive.
- With 100 customers and a 35% response rate, expect about 35 responses and 5 to 7 detractors a quarter, roughly 3 hours of calls. Staff for that.
- If a fundraise is coming, then have four quarters of trend, response above 25%, and detractor follow-up above 85%.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Typical B2B software score | 30-40; 40-49 good; 50-65 strong; above 65 exceptional; below 20 investigate | Lintel guidance. Sources differ by about 10 points. Trend and competitor set matter more |
| Response rate | 25-35% relationship by email; 35-50% transactional; 10-20% in-product | Below 20%: check sender, frequency, length |
| Detractor follow-up within 48 hours | 90%+; below 75% means the loop is broken | Lintel guidance |
| Detractor moved to 7+ within 90 days | 30-50%; below 20% means calls miss root causes | Lintel guidance |
| Promoter ask completed within 60 days | 25-40%; below 15% means vague or badly timed | Lintel guidance |
| Churn interview completion | 70-80% of lost accounts above ACV line | Below 50% is a process gap |
| Score gap between segments | Over 15 points hides a problem segment | Lintel guidance |

**Where it goes wrong:** The scorecard program (a number on a dashboard, no follow-up, and response rates sag as customers learn nobody reads comments). The promoter harvest (review, case study, reference, advisory seat, and webinar in one email; ask for one thing). Surveying only the power user, so enterprise shows 8-9 and still churns because the buyer was never asked. Surveys from several teams stacking up in one quarter.

## Churn interviews and customer journey research  (FW-CX-004, FW-CX-002, with FW-CX-001)

**When this matters:** Churn reasons are guesses. You lose more than two accounts a month above your ACV line with no exit interviews. Customers drop at a particular stage and nobody knows why.
**Skip it when:** Formal journey mapping under 50 customers (just call five). No definition yet of customer success per segment (FW-CX-001 first). Core product rewritten weekly.

**Where you are**
- Tier 1 Reactive: Churn reasons guessed. The journey is described by the teams that run it.
- Tier 2 Building: A written interview guide, 50%+ of lost accounts above your ACV line interviewed, one map built from 5 to 8 customer interviews.
- Tier 3 Operating: 80%+ interviewed within 30 days, reasons tagged monthly, a map per main segment, an improvement list with owners.
- Tier 4 Compounding: 90%+ interviewed, a reason database reviewed quarterly, maps refreshed quarterly, changes tied to retention results.

**First build, in order**
1. Set the ACV line above which every lost account gets an interview, within 30 days of churn.
2. Have the CS lead or a CX owner run it, never the account's CSM (who has a renewal to protect). 30 minutes. Open: "We are not trying to change your decision. We respect it. We want to learn so we improve for others."
3. Ask five things: when you first felt unsure about staying; the main factor; what we could have done differently; which competitor you chose and why it appealed; what you will miss. The last answer shows your real strengths.
4. Tag each loss: adoption failure, satisfaction failure, organizational change (sponsor left, restructuring, acquisition), competitive displacement, or budget and outside pressure. Compute the share of churned ARR in each. The biggest bucket is the first program to build.
5. For journey research, pick the segment with the most ARR or churn risk. Interview 8 to 12 customers across tenures (0-6, 6-18, 18+ months) plus two or three churned ones (minimum 5 to 8 for a small base). Ask "walk me through what happened when..." and "how did you feel then?" Rating questions do not produce a journey.
6. Map it in a shared sheet your team already edits: a column per stage; rows for customer actions, feelings, touchpoints, internal owner, friction, opportunity. Use quotes. Score friction by impact and effort, fix the top three, and present to sales, CS, product, and support.

**Decision rules**
- If churn clusters in first-year customers, then fix onboarding. If it clusters in one segment, then look at ICP or product fit. If it spreads everywhere, then it is product or experience quality.
- If over 40% of churned ARR is competitive displacement, then build the competitive kit (churn-risk block). If over 50% is organizational change, then build the new-stakeholder program first.
- If a fix needs both CS and product, then give it one owner with authority over both, or escalate to the CEO. If the friction sits inside the product, then hand product the ARR at stake and give customers a workaround meanwhile.
- If sales-to-CS handoff is a top-three friction, then build a handoff sub-map first. It sets the tone for the whole relationship.
- If accounts are above $50K ACV, then map buyer and user separately. A sponsor who cannot explain the value at renewal is the classic enterprise churn trigger.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Onboarding to active adoption | 85%+ within 60 days | Lintel guidance |
| Adoption to value realized | 75%+ within 90 days | Lintel guidance |
| Handoff smoothness (1-5, asked a week after) | 4.0+; below 3.5 is a real problem | Lintel guidance |

**Where it goes wrong:** Running the interview as a retention pitch with roadmap and discounts, so the customer stops being candid. Journey interviews run as satisfaction surveys. A map in a tool only one person can edit. Fifteen frictions listed and none fixed.

## Advocacy, references, reviews, and case studies  (FW-CUSTMKT-001, FW-CX-001, with FW-CX-004 for the ask)

**When this matters:** Sales asks for references and you have no process. Customer-referred pipeline is under 10% of new pipeline though customers have been active 12+ months. Enterprise deals stall for lack of third-party proof.
**Skip it when:** Under 20 paying customers (founders ask in person). No health tracking yet (you will recruit unhappy customers and collect bad reviews). Product-market fit is unproven or the product is about to change enough to date every asset.

**Where you are**
- Tier 1 Reactive: Case studies happen through someone's personal relationship, with no filter on who is asked.
- Tier 2 Building: A repeatable process produces three or more case studies or testimonials a year, and a gate is applied before any ask.
- Tier 3 Operating: 15 to 30 willing references tagged by industry and use case, four advocacy tracks, advocacy pipeline tracked in the CRM.
- Tier 4 Compounding: Advocacy is a measured pipeline channel and public advocates produce referrals.

**First build, in order**
1. Set the gate and apply it to every list: health green, no open escalation, 6+ months as a customer, survey score 8+ for case studies and reviews (9+ for community or speaking), a measurable outcome for case studies. Five minutes of filtering prevents the worst harms.
2. Pick five candidates with CS. CS confirms health, raises the idea in a normal conversation, and hands off to marketing only after the customer shows interest. Then a personal email from the CS lead or marketing owner. Expect about half to say yes: two or three studies or references from five asks.
3. Produce case studies with one process: a 30-minute interview by marketing, a draft, written customer approval of the text and every number, CS on the relationship throughout. Target 30 days from yes to published; budget 20 to 40 hours each.
4. Write the distribution plan at the same time: which sales sequences use it (match industry, size, use case), the newsletter slot, social and sales sharing, any paid push. The study is done when the plan has run.
5. Build a reference pool of 15 to 30, matched to prospects by industry and size. Log every use so nobody is over-asked.
6. Reviews (G2, Capterra, and similar): a quarterly note from the CS lead to gated customers who have not reviewed in 12 months, asking for their honest experience. Keep to one ask per promoter per survey cycle. If the promoter has under 6 months of tenure, thank them now and hold the ask.
7. At Series B, with 8 to 10 customers who are 12+ months in, successful, scoring 8+, and interested: start a customer advisory board of 6 to 12, meeting twice a year. Agenda: your roadmap direction, their market view, two or three specific questions, then what you heard and will do. For commercial value, add a duty of one reference call a quarter and one content piece a year.
8. Community: validate demand first. Proceed only if 80%+ of at least 20 named customers say they would take part and you have 100+ active customers on a shared use case. Run it per FW-COMMUNITY-001.

**Decision rules**
- If you have 30+ advocates and few referrals, then add public tracks (reviews, social endorsement, speaking, community content). Reference calls only answer prospects. Referrals come from visible endorsement.
- If ask completion is under 15%, then name a specific prospect or link, and cut steps.
- If a case study customer later has a bad experience, then CS leads recovery, marketing stops using them as a reference, a public dispute means archiving the study, and you ask for consent again before restoring it.
- If a customer churns, then pull their testimonials and case studies and do not respond publicly to competitor claims.
- If you thank references with gifts, then never tie the gift to what they say. The FTC rule on reviews (16 CFR Part 465, in force since October 21, 2024) bars incentives conditioned on positive sentiment and some review suppression. Added outside the library. It may reach B2B reviews, so get legal advice.
- If you are a seed-stage founder, then ask directly ("if you know anyone dealing with [problem], I'd like to meet them") and check in with anyone gone quiet.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Customers with one advocacy act in 12 months | 15-25% at Tier 3+; under 10% means not activated | Lintel guidance |
| Pipeline from advocacy (referrals, reviews, community, case-study inbound) | 10-25% of new pipeline at Tier 3+ | Lintel guidance. Needs a CRM source field |
| Case study effort | 30 days, 20-40 hours | Lintel guidance |
| Reference pool | 15-30 | Matched by industry and size |

**Where it goes wrong:** Starting with advocacy before health. Blasting every customer with a review request (one negative review can outweigh ten positives). Case studies with no distribution plan, so no one can name a deal one helped close. An advisory board with no commercial output.

## Churn-risk signals marketing can see, and the at-risk response  (FW-CX-001, FW-CUSTMKT-001, FW-CUSTMKT-004)

**When this matters:** Surprise churn from accounts thought healthy. At-risk accounts found within 30 days of renewal instead of 90 to 120. GRR below 90%. Detractor share up two or more quarters with no matching recovery calls. More than 20% of accounts red.
**Skip it when:** Under 20 customers. Product-market fit is unproven. Churn comes from outside forces (category consolidation, budget cuts, acquisitions). GRR above 95% with flat expansion (use the expansion block). GRR below 85%: a product or delivery emergency, so diagnose first. Marketing emails cannot fix it.

**Where you are**
- Tier 1 Reactive: Health lives in CSM heads. Renewals are raised 30 to 45 days out.
- Tier 2 Building: A two-to-three-input score updated weekly; red triggers CSM outreach within 48 hours; renewals start 60 to 90 days out.
- Tier 3 Operating: A multi-input score back-tested against past renewals, playbooks for common risks, marketing acts within 48 hours of a threshold crossing.
- Tier 4 Compounding: The score flags churn 90 days ahead with 70%+ accuracy and starts playbooks automatically.

**First build, in order**
1. Run the churn cohort analysis (3 to 4 hours): everyone lost in 12 months, with ACV, tenure, stage at churn, and reason (five buckets in the interview block). Cut also by acquisition month, ACV tier, industry, month-3 usage, onboarding completion. The biggest cluster tells you what to build.
2. Stand up a two-input health score (2 to 3 hours, then 30 minutes a week): logins in 14 days, and days since the last real conversation. Green: 3+ logins and a conversation within 21 days. Yellow: 1-2 logins, or a conversation 22-45 days ago. Red: no logins in 14 days, or no conversation in over 45. Red means CSM outreach within 48 hours. Without usage data, a monthly Healthy, At-Risk, Churning tag per CSM works.
3. Put renewal dates on every account with a 90-day alert, and share the health field with marketing in the CRM and an alert channel.
4. With 12 to 18 months of history, grow to five parts weighted by what predicted renewals. Starting weights without history: product engagement 30%, outcome progress 25%, relationship 20%, support 15%, business risk 10%. FW-CUSTMKT-001 offers a different set. Both are placeholders for your own back-test.
5. With a 0-100 score (above 75 healthy, 50-75 moderate, 25-50 high risk, below 25 churning), set the response. Moderate: three emails over 30 days (a useful guide, a peer story, a soft invitation) and a CSM check-in within 10 business days. High: two emails over 14 days, the second from the CS lead, offering concrete help, and CS outreach within 5 business days by phone or personal email, logged. Churning: stop all marketing; the CS lead calls within 24 to 48 hours; marketing builds the account's value summary.
6. Match the response to the cause. Adoption failure (at-risk plus feature use under 40% two months running): a free product health check and a use-case guide. Satisfaction failure (at-risk plus a low score or an escalation open over 14 days): hold marketing until it is resolved, then a note from the CS lead naming what changed. Sponsor change: personal intro from the CSM within 48 hours and a one-page overview for the new executive. Budget pressure: the cost of cutting, a peer story, and a contract shape that fits.
7. Competitive flag: CSMs mark the account in the CRM within 24 hours of hearing of an evaluation. Marketing delivers a package within 48 hours: a factual comparison, a one-page switching-cost sheet, and two or three 200-300 word "why customers stayed" stories from peers who evaluated that competitor and renewed.
8. Word outreach as "we wanted to check in" instead of "we noticed you have not logged in." Same trigger, less surveillance.

**Decision rules**
- If a customer has an open escalation, then suppress marketing sequences and send only the CS alert.
- If an account is within 60 days of renewal, then run the at-risk sequence beside the renewal sequence. Do not re-trigger within 60 days unless the score drops a tier.
- If a customer asks marketing to stop, then honor it at once, tell the CS manager, and have CS reach out personally within 48 hours. Treat them as high risk whatever the score says.
- If a CSM says an account is fine but the score fell, then log the CSM's view, pause 14 days, and restart if the score keeps falling.
- If green accounts churn, then recalibrate the score using signals you missed in lost accounts.
- If CS misses high-risk alerts for 5 business days, then escalate to the CS lead with the ARR at risk and add a pre-written message. Treat it as a capacity or alert-format problem.
- If over 20% of renewal ARR is at-risk at the 90-day mark, then the early warning is late (the library's action line is 25%). Turn on every at-risk program for those accounts.
- Renewal timeline, human side: at 90 days review health and book a value review for yellow or red; at 60 days start the talk if healthy; at 30 days conversation for all; at 15 days paperwork. Green at 90 days should close in one conversation. Yellow gets value recovery first, with no commercial talk. Red goes to the CS manager or VP at once, and executive-to-executive above your ACV line.
- If an outage or major incident hits, then run the satisfaction program for every account that opened a ticket. If a key CSM leaves, then audit their accounts. If GRR drops 3 points in a month, then run an emergency churn analysis within 48 hours.
- If you hire: first CS hire at 30 to 50 customers or when CS eats 30% of founder time. If customers churn because nobody contacts them, hire CS. If they churn despite contact because risk is found late, build this program first. Win-back after churn belongs to FW-EMERGING-011.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| GRR | Above 90% healthy; above 95% strong; below 85% serious | Lintel guidance |
| NRR | Below 90% serious; 100-110% healthy; 110-120% strong; above 120% exceptional | Lintel guidance |
| Logo churn per year | Under 5% enterprise; under 10% mid-market; over 15% anywhere is systemic | Lintel guidance |
| Red share of accounts (Tier 3+) | Under 10%; yellow 15-25% | Over 20% red points to product or onboarding |
| Recovery from at-risk in 60 days | 35%+ moderate; 20%+ high-risk | Lintel guidance |
| CS response to high-risk alerts in 5 business days | 85%+; below 70% critical | Lintel guidance |
| Renewal rate | Enterprise 90%+, mid-market 85%+, SMB 75%+ | Lintel guidance |
| Competitive retention win rate | 60%+ strong; below 40% weak, often flagged too late | Lintel guidance |

**Where it goes wrong:** Retention work that starts at renewal when the damage came in months 3 to 9. Retention mail from a brand address instead of the CS manager's name. Sequences still running on an account that asked to cancel because nobody updated the health field. Building before the churn cohort analysis and solving the wrong problem.

## Expansion signals and campaigns  (FW-CUSTMKT-003, with FW-CX-001)

**When this matters:** GRR above 90% but NRR near 100%. Expansion under 20% of new ARR at Series B or later and the product has seats, modules, or tiers to expand into. A new module shipped and customers were not told. Accounts are nearing their ceiling and nobody reaches out.
**Skip it when:** GRR below 90% (you expand a draining base; fix retention first). One price tier with nothing to expand into. Under 20 accounts (CS conversations suffice). CS will not coordinate, because uncoordinated campaigns damage live relationships.

**Where you are**
- Tier 1 Reactive: Expansion is whatever CS stumbles into. List the top ten accounts nearest a limit and hand them to CS as warm leads.
- Tier 2 Building: A quarterly campaign to healthy customers with a specific offer, coordinated with CS.
- Tier 3 Operating: A signal model flags ready accounts from usage and routes them to CS within 24 hours.
- Tier 4 Compounding: Product messages, email, and CS work as one account-level motion.

**First build, in order**
1. Confirm trailing 12-month GRR is above 90% (15 minutes). If not, stop and use the retention block.
2. With the CS lead (90 minutes), define each expansion type (seats, tier, module), the usage signal that means ready (for example seat use above 80%, or usage above 85% of a tier limit), the account signal beside it (headcount growth, funding, a new business unit), and the words CS uses.
3. Add a CRM field on expansion opportunities: "Marketing campaign touchpoint? Yes / No / Unknown." CS marks Yes if an opportunity opened within 60 days of a campaign open, click, or pricing-page visit. Tell CS it exists to credit marketing, not to audit them.
4. Run a monthly manual signal review (1 hour): a sheet of seat use, usage against limit, last expansion flag, last CS note, and health tier. Send the top ten to the owning CS managers with the flagging signal.
5. Write a one-page CS protocol (1 hour) and get the CS lead's sign-off before any send: audience list goes to CS first; CS has three business days to pull accounts; any pricing-page visit or reply goes to the CSM within 24 hours; CS can pause any account; CS sees the campaign five business days ahead.
6. After two months of manual review, send the first quarterly campaign, filtered to health green and signal above 50. Fill every email with real data about that account. Do not invent peer statistics.
7. Later, replace the sheet with a signal model. Starting weights: seat use 30%, tier-limit proximity 25%, feature depth 20%, customer headcount growth 15%, budget timing 10%. Above 70: immediate CS alert. 50-70: next campaign. Below 50: monitor. Recalibrate quarterly.
8. For enterprise, build a review pack five business days before each executive review: a one-page ROI summary, a one-page usage comparison with similar accounts, and an internal-only page with the readiness score and suggested next conversation.
9. Calendar: Q1 (January, fresh budgets) is the biggest campaign; Q2 follows up non-converters; Q3 targets customers with 6+ months of use; Q4 goes to small accounts only, since enterprise budgets are locked. Usage-threshold triggers run between and convert best.

**Decision rules**
- If conversion is under 5% for every campaign type, then fix targeting. Require health green and signal above 50. A campaign to 30 ready accounts converting at 20% beats one to 300 generic accounts at 2%.
- If under 15% of flagged accounts reach an opportunity in 60 days, then raise the alert line from 70 to 80 and require product use in the last 14 days.
- If accounts are above $50K ACV, then CS leads. Marketing supplies the review pack. No campaign reaches an enterprise account without that account's CS approval. Automation serves the CSM.
- If you are PLG with usage pricing, then put messages in the product at usage thresholds and email the economic buyer as usage nears the limit.
- If you shipped a new module, then pilot first with 5 to 10 best-fit customers (20-30% of the base typically fits): 30 days, a check-in at day 15, a conversion conversation at day 25. Pilots without a CS cadence cannibalize the sale.
- If marketing-influenced share exceeds 50%, then test for over-crediting: hold out a random 20% of eligible accounts. If the holdout expands at 70%+ of the campaign group's rate, the campaigns add less than attribution says.
- If GRR drops below 90%, then pause campaigns and move the budget to retention.
- If you hire: a dedicated expansion marketer when expansion is under 20% of new ARR at Series B+ and GRR is above 90%.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Expansion share of new ARR | Series B 20-30%; Series C+ 30-50%; best above 40% | Lintel guidance. Under 20% at Series B is the trigger |
| CS-sourced expansion share of new ARR | 20-35% at Tier 3+; under 10% means no working motion | Lintel guidance |
| Campaign conversion in 60 days | Seats 8-15%; tier 5-10%; cross-sell 3-8%; usage-triggered 15-25% | Lintel guidance |
| Alert to opportunity in 60 days | 25%+; under 15% means slow CS or false alerts | Lintel guidance |
| Marketing-influenced share of expansion ARR | 30%+ at Tier 3+ | Verify with a holdout |
| Pilot to paid in 60 days | 40%+ strong; under 25% weak | Lintel guidance |

**Where it goes wrong:** One campaign to every healthy customer. Pushing expansion at 84% GRR so new dollars cover a leak. A campaign that lands while CS negotiates a sensitive renewal with the same account. Marketing crediting itself for deals CS would have closed anyway.

## Customer communication cadence  (FW-CUSTMKT-001, FW-CUSTMKT-002, FW-CUSTMKT-004, FW-CX-003, with FW-CX-001 for QBRs)

**When this matters:** 50+ customers with nothing beyond product updates and renewal notices. Early churn in the first 90 to 180 days. Customers use under half of what they bought. Customer emails get opened less each quarter because everyone gets the same message.
**Skip it when:** Under 20 customers (personal founder emails). Segmented, behavior-triggered messaging under about 100 accounts (relationships beat automation and the data is thin). No usage data in any form. Core product changing so fast that onboarding content goes stale in weeks.

**Where you are**
- Tier 1 Reactive: One list, product announcements when something ships, renewal notice 30 days out.
- Tier 2 Building: A monthly customer email, a welcome sequence, lifecycle stage and health fields on every account, messages that differ by stage.
- Tier 3 Operating: Messages triggered by behavior and health, onboarding tracks by segment, product data flowing into the CRM.
- Tier 4 Compounding: Product, CS platform, and marketing tool share one customer view, and programs act before the customer asks.

**First build, in order**
1. Add three fields to each account: lifecycle stage (onboarding, adopted, mature, at-risk), health tier, contract tier. CS fills them by hand (2 to 3 hours). Start with two or three segments (ACV tier or industry). Every extra segment multiplies content work.
2. Build the suppression rule before any campaign: an "active escalation" flag set by CS, excluded from every promotional or sequence send.
3. Define the first value milestone in one sentence: "A customer has reached first value when they have [specific action] and [specific result], within [N] days of signature." Instrument it in product analytics, or have CS mark it by hand. If two candidates compete, track both for a quarter and compare retention.
4. Write the welcome sequence: five emails on days 1, 3, 7, 14, 30. Each is 150 to 250 words, names the outcome in the subject line (not "Welcome!"), gives one next action and one link, and comes from the CS lead's name. Organize around the customer's goal, not a feature tour.
5. Put marketing sends and CS touches on one calendar. No same-day messages on the same topic.
6. Launch the monthly customer email before segmenting: one product update, one genuinely useful item, one customer result, from a named person. Aim for 30-45% opens and 5-10% clicks; flag unsubscribes above 2%. Opens run high where mail apps pre-load images, so trust clicks and replies more (added outside the library).
7. With usage data, add triggers. First value not reached by 80% of its window: send help and alert CS (the top-priority trigger; CS follows up within 48 hours). Usage drop: no login for 14 days to start, 7 once data is fresh, never in an account's first 14 days or with an open ticket. First value reached: congratulate within 4 hours (route to CS for enterprise).
8. Months 2 to 6: feature education on the two or three least-adopted features, a use-case spotlight, a peer invite, then a month-6 value check of three to five questions (8+ out of 10 is an advocacy candidate; under 6 gets a CS check-in within a week).
9. Renewal support, from the CS manager's name: day -90 usage-based value summary to the primary contact; day -60 renewal notice and a one-page business value summary to the buyer; day -45 internal alert if neither was opened; day -30 team year-in-review; day -14 package to the CSM. Enterprise starts at day -120, and marketing sends the buyer no automated email after day -60 without the CSM.
10. Review rhythm by ACV: above $50K, a quarterly review with the executive sponsor; $10K-$50K, twice a year plus monthly health check-ins; under $10K, an annual review at most plus a quarterly automated check-in. A review runs about 60 minutes: 5 on context, 15 on value delivered (real numbers; about 2 hours of prep), 10 on open issues, 10 on roadmap, 10 on next-quarter targets, 10 open.

**Decision rules**
- If you are PLG, then guide inside the product and keep email to three welcome messages that support it.
- If first value is reached under 70% of the time while opens exceed 40%, then the product step is the problem. Find the biggest drop-off step and give product the data.
- If first value is reached over 80% of the time but early churn stays high, then the milestone marks setup. Move it to a real result.
- If the primary contact changes mid-onboarding, then pause automation, have the CSM re-kick-off, and restart at the right point.
- If accounts are above $50K ACV, then triggers alert the CSM instead of sending. Accounts under $10K can be fully automated.
- If a customer asks to leave all marketing, then honor it fully. CS may still contact them for the relationship but must not relabel marketing as CS mail.
- If you want triggers, then send last login, 14-day login count, active users, and key-feature flags from the product to the CRM nightly (2 to 4 days of engineering).
- Who owns it: at seed, the founder (a personal monthly email, the five-email onboarding in an afternoon). At Series A, 20-25% of an existing marketer. A dedicated customer marketing manager at Series B with 100+ customers, once the work tops 15 hours a week or 30% of one person's time. Before hiring, have health tracked, two months of customer emails, one case study, and a weekly CS-marketing meeting.
- Under 100 customers, hire a CS manager. At 100-200, build onboarding automation alongside. Above 200, automate onboarding communication before adding CS headcount.

**Numbers that matter**
| Metric | Benchmark | Note |
|---|---|---|
| Customer email opens and clicks | 30-45% opens, 5-10% clicks | Lintel guidance. Under 25% opens: check sender and relevance |
| First value reached in target window | 80%+; 90%+ best; under 60-70% is systemic | Lintel guidance |
| Time to first value | 30-45 days for most B2B; simple tools under 7 days, mid 14-21, complex 30-60 | Over 60 days is a first-year churn risk |
| Feature adoption at day 90 | 60%+ healthy; under 40% raises churn risk | Used in the last 30 days |
| CS response to first-value alerts | 85%+ within 48 hours; under 70% critical | Lintel guidance |
| Welcome tracks | Enterprise 8-10 emails over 60-90 days; mid-market 6-8 over 45-60; SMB 5-7 over 21-30 | First value targets: 30-60, 21-45, and 7-21 days |
| Renewal sequence opens and clicks | 45%+ opens, 12%+ clicks | From a CS manager's name |
| Re-engagement recovery in 30 days | 15-30%; under 10% means the message misses the barrier | Lintel guidance |

**Where it goes wrong:** A feature tour in place of an outcome path. The same sequence still sending to someone who is churning or already an expert. A marketing email and a CSM email on the same day about the same topic. Personalizing name and company while the content stays identical.

## Dropped

Analyst and research firm names removed from the source's model references (two CX maturity models, a VoC maturity model, a capability assessment, and a customer marketing maturity note), and the survey vendors cited for score benchmarks. The 30 to 40 typical score stays as Lintel guidance.

About 19 numbers or number groups dropped:
- No source: "25-40% higher response" for a named sender; a "15-25 point" open-rate gain from a CS sender; a "3-8%" response drop from an open-text question; "20-50x more time" to recover churn; "5-7x" cost of winning vs keeping a customer; "10-15 points of NRR" from an expansion hire. Kept the rules, dropped the claims.
- Survey tool prices and annual tool budgets (prices change). ROI multiples in the budget sections (6.7:1, 4-7x, 3-4x, 6-9x, 9-13x, 2,400%), which are worked examples on invented customer counts.
- Onboarding-to-retention gaps: the library gives four conflicting figures. Kept only the test: compare on-time and late first-value cohorts, and read a small gap as a wrong milestone.
- Personalization lifts (2-5 NRR points, 8-15 point first-value gain, 20-40 point nudge lift, 5-15 point score gain) and "15-25% of lapsing customers recovered."
- Conflicts resolved toward the owning file: personalized open rates of 35-55% (used 30-45%); FW-CX-001's score bands (FW-CX-004 owns the metric); FW-CX-001's "15-25% of new ARR" for customer-sourced pipeline (used 10-25% of pipeline); "48 business hours" for detractor contact (used 48 hours); a 90-day first-value ceiling for complex products (used 30-60).
- CS staffing ratios and salary ranges, and win-back reactivation rates (FW-EMERGING-011).
- Two conflicting health score weight sets: kept both as unvalidated starting points.

Reconciled, not dropped: FW-CUSTMKT-001 sends passives a targeted content sequence while FW-CX-004 sends a short check-in within a week. FW-CX-004 owns follow-up, so the check-in goes first and content can follow if the comment shows an adoption gap. FW-CX-004 asks promoters within a week while FW-CUSTMKT-001 gates asks at 6+ months of tenure. Rule used: thank now, hold the ask until the gate is met.

Added outside the library: the FTC review rule note and the note on inflated open rates.

## Credit

- Net Promoter Score (the 0-10 recommend question and promoter, passive, and detractor bands): Fred Reichheld, with Bain & Company and Satmetrix (Reichheld, The Ultimate Question, 2006). Net Promoter, NPS, and Net Promoter Score are trademarks or service marks of Bain & Company, NICE Systems, and Fred Reichheld. Lintel is not affiliated with or endorsed by them.
- Closed-loop follow-up, health scores, quarterly and executive business reviews, the first value milestone, customer advisory boards, and journey maps are common practice with no single originator. The scripts, thresholds, and sequences are Lintel's own descriptions.
