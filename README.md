# B2B marketing playbooks

A Claude skill that answers B2B software marketing questions with a consistent method instead of generic advice: diagnose first, name the one framework that owns the question, give the build steps and the numbers, and say plainly when the answer is not here.

Built for seed to Series B B2B software companies, and deliberately kept there. At Series C and beyond the method and the build sequences still hold, but the benchmarks were written for smaller companies and the skill will say so instead of handing you a number from the wrong stage.

## What it is for

Questions like these, where most answers you can find are either a listicle or a consultant's opener:

- We are at $800k ARR with no marketer. What should we spend, and who should we hire first?
- Our demo requests fell off a cliff. What broke?
- Should we hire an SDR? Our ACV is $18k and we get six inbound demos a month.
- Sales says the leads are garbage, marketing says sales never follows up. How do we settle it?
- Leadership will not let us publish prices. What goes on the pricing page?

It answers with a stage, a build sequence in order, a decision rule with its threshold, and a benchmark, and it names the framework behind each one so you can argue with it.

## Install

Copy this folder into your skills directory:

- **Claude Code:** `~/.claude/skills/b2b-marketing-playbooks/`
- **Claude Desktop:** the skills folder for your install

Then ask a marketing question. The router loads first and pulls in only the topic file it needs.

## How it works

`SKILL.md` is the router: the method, the 13 topic files and what each one owns, the maturity ladder, and the rules that keep answers consistent. `references/diagnosis.md` always gets read first, because a complaint and its cause usually live in different files. Everything else loads on demand, so a question costs one topic file, not 118,000 words.

The four tiers, used the same way in every file: **Reactive** (happens when someone remembers), **Building** (written down, someone owns it), **Operating** (runs on a cadence, measured), **Compounding** (improves itself and survives a person leaving). Work on the next tier, not the last one.

## What it will not do

It does not write the copy, run the campaign, or replace knowing your own customers. It does not cover consumer marketing, ecommerce, or enterprise sales motions above the mid-market. It holds no data about any company, so the quality of an answer depends on what you tell it about yours.

Known gaps it will admit to rather than bluff about: review-site programs, website design and information architecture, app store optimisation, layoff communication, executive compensation, and later-stage benchmarks.

## How honest the numbers are

Every benchmark is either credited to whoever published it or marked as our own judgement from practice. Nothing here is attributed to an analyst firm, because figures we could not trace to a real published report were stripped rather than dressed up with a citation. Models created by other people (MEDDIC, SPIN, NPS, Jobs to Be Done, the Bowtie, and others) are credited in [CREDITS.md](CREDITS.md), with a short list of credits still to verify.

It has been tested. On 25 real questions, scored side by side against the 3.5M-word library it was condensed from, it held up: better on 16 questions, worse on 5, level on 4. The judging was not blind and the margin was close to judge noise, so read that as "the short version does not lose much", not as a win.

## Licence and trademarks

MIT, see [LICENSE](LICENSE). Trademarks belong to their owners and nothing here is endorsed by them, see [NOTICE.md](NOTICE.md). This is general guidance, not professional advice.

Built by Zach Brown (Lintel).
