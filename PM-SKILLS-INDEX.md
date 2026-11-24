# PM skills index: The Complete Claude Guide for Product Managers

All 42 skills from 90n's pack, in the order the product job runs. Folder names are the exact directory names under `skills/` in the upstream pack. The skills are 90n's work, not mine; this repo holds no copies of the skill files.

Install in Claude Code:

```
/plugin marketplace add polar-bear-org/claude-skills
/plugin install complete-claude-guide-for-product-managers-pack@90n-skills
```

Guide: https://90n.ai/resources/complete-claude-guide-for-product-managers-pack — Source: https://github.com/polar-bear-org/claude-skills

## 1. Set direction

| Skill | Folder | What it produces |
| --- | --- | --- |
| Write the Product Vision | pmg-write-product-vision | Vision statement options, Product Vision Board (target group, needs, product, business goals) |
| Write the Product Strategy | pmg-write-product-strategy | Diagnosis, guiding policy, coherent actions, "we will not" list |
| Map the Impact | pmg-map-the-impact | Goal, actors, impacts, deliverables, deliverables no impact needs marked to cut |
| Size the Market (TAM, SAM, SOM) | pmg-size-the-market | Top-down and bottom-up estimates, sourced assumptions, a range, sanity checks |
| Fill the Lean Canvas | pmg-fill-lean-canvas | One-page business logic, riskiest assumptions marked untested |
| Pick the North Star Metric | pmg-pick-north-star-metric | North star, three to five named inputs with definitions, counter-metrics |
| Build the Product Roadmap | pmg-build-product-roadmap | Now-next-later board, confidence notes, "not on the roadmap" list, one-page executive version |

## 2. Discover

| Skill | Folder | What it produces |
| --- | --- | --- |
| Prepare the Customer Interview Guide | pmg-prepare-interview-guide | Screener lines, story-based questions, probes, consent note, notes template |
| Synthesise the Interviews | pmg-synthesise-interviews | Affinity clusters, need statements with sources, contradictions, open questions |
| Build the Personas | pmg-build-personas | Composite personas from interview evidence, each claim linked to its source |
| Map the Customer Journey | pmg-map-customer-journey | Stages, actions, thoughts and feelings, pain points, opportunities, evidence per cell |
| Map the Jobs to Be Done | pmg-map-jobs-to-be-done | Job statements, circumstances, forces for and against switching, alternatives |
| Fill the Value Proposition Canvas | pmg-fill-value-proposition-canvas | Customer profile, value map, fit notes, one positioning line every team uses |
| Build the Opportunity Solution Tree | pmg-build-opportunity-tree | Outcome, opportunities, target opportunity, three ideas, riskiest assumption per idea |

## 3. Decide

| Skill | Folder | What it produces |
| --- | --- | --- |
| Triage the Feature Requests | pmg-triage-feature-requests | Request log, the job behind each request, build / later / no sort, reply drafts |
| Score the Backlog with RICE | pmg-score-with-rice | Scored backlog, confidence notes, out-of-order exceptions, cut list |
| Score with ICE | pmg-score-with-ice | Impact, confidence and ease scores, evidence behind each confidence score, top ten to test |
| Rank with WSJF | pmg-rank-with-wsjf | Cost of delay parts divided by job size, ranked list, sensitivity check |
| Cost the Delay | pmg-cost-the-delay | Urgency profiles, CD3 order, "yes, if" options, reply to the asker |
| Make the Business Case | pmg-make-business-case | One-page case in five parts, assumptions table with ranges and owners, what would change the answer |
| Set Up the DACI Decision | pmg-set-up-daci-decision | Driver, approver, contributors, informed, inputs, decision date |
| Keep the Decision Log | pmg-keep-decision-log | Dated records (context, decision, status, consequences), reopening rule |

## 4. Define

| Skill | Folder | What it produces |
| --- | --- | --- |
| Write the One-Pager | pmg-write-one-pager | Problem, who it is for, why now, the bet, success, what we will not do, the ask |
| Write the PR/FAQ | pmg-write-pr-faq | One-page press release, customer FAQ, internal FAQ |
| Write the Prototype Brief | pmg-write-prototype-brief | The belief it tests, pass line set in advance, what it does not prove, gap-to-production list |
| Write the PRD | pmg-write-the-prd | Problem and evidence, goals, non-goals, numbered testable requirements, open questions, success measures |
| Spec the AI Feature | pmg-spec-the-ai-feature | Task, measurable success criteria, acceptable error rate, eval set plan, human fallback, launch bar |

## 5. Deliver

| Skill | Folder | What it produces |
| --- | --- | --- |
| Build the Story Map | pmg-build-story-map | User activity backbone, walking skeleton, release slices |
| Write the User Stories | pmg-write-user-stories | Stories, Given / When / Then criteria, INVEST check, refinement questions |
| Plan the Sprint | pmg-plan-the-sprint | Sprint goal as an outcome, capacity by role, items the team selected, definition of done check |
| Run the Sprint Review | pmg-run-sprint-review | Increment against the sprint goal, feedback, backlog changes, short key-updates deck |
| Cut Scope with MoSCoW | pmg-cut-scope-with-moscow | Must / Should / Could / Won't list, Must budget check, Won't-this-time list |

## 6. Launch

| Skill | Folder | What it produces |
| --- | --- | --- |
| Write the Competitive Analysis | pmg-write-competitive-analysis | Landscape table with sources, win / loss themes, where you differ, what not to copy |
| Plan the Go-to-Market | pmg-plan-go-to-market | Launch tier, audiences, positioning line, readiness by team, enablement brief |
| Run the Pre-Mortem | pmg-run-pre-mortem | Failure story, reasons list, top risks with owners and signals, go / adjust / stop |
| Write the Release Notes | pmg-write-release-notes | Customer notes by change type, internal version for support, who is affected |

## 7. Prove

| Skill | Folder | What it produces |
| --- | --- | --- |
| Set the Success Metrics | pmg-set-success-metrics | HEART table (goals, signals, metrics), baseline, target, guardrail |
| Design the Experiment | pmg-design-the-experiment | Hypothesis, variants, primary metric, guardrails, sample and duration check, decision rule |
| Run the Post-Launch Review | pmg-run-post-launch-review | Intended versus actual, why, keep / change list, keep, fix or remove call |

## 8. Run the product

| Skill | Folder | What it produces |
| --- | --- | --- |
| Write the Weekly Update | pmg-write-weekly-update | News-first subject line, bottom line and asks, shipped, at risk, decisions by date, one cut per audience |
| Run the Retro | pmg-run-the-retro | Last action checked, a format for this cycle, themes, one owned change with a check date |
| Plan the Quarter | pmg-plan-the-quarter | Objectives and key results, capacity split, bets, what is out, check-in dates |

## Using the skills

In Claude Code, after installing, call a skill by name in a new chat, for example:

```
Run pmg-write-product-vision for [product]. What we have so far: [paste it here]
```

```
Run pmg-synthesise-interviews on these interview transcripts: [paste them here]
```

```
Run pmg-score-with-rice on these requests: [paste them here]
```

On Claude.ai or Claude Desktop instead: download the skill zips from the `install/` folder in the upstream pack and upload each one under Customize, then Skills. Turn on code execution and file creation under Settings, then Capabilities first.

Credit: all 42 skills are by 90n (https://90n.ai), Copyright (c) 2025 90n. Free to use inside your company and in client work, not for resale. Full terms: `LICENSE.md` in the source repo.
